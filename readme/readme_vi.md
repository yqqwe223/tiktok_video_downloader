# TikTok Video Parser Tool 🎬

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-Tiếng_Việt-yellow.svg)

## 📋 Tổng Quan Dự Án

**TikTok Video Parser Tool** là công cụ hỗ trợ dựa trên nền web, được thiết kế để hỗ trợ nhà giáo dục, nhà nghiên cứu và người học cá nhân trong việc phân tích kỹ thuật các liên kết video ngắn TikTok có thể truy cập công khai, dưới nguyên tắc "sử dụng hợp lý" (Fair Use). Mục tiêu của công cụ là hỗ trợ lưu trữ nội dung cho mục đích giáo dục, nghiên cứu và học tập cá nhân. Công cụ này tập trung cung cấp hỗ trợ kỹ thuật đơn giản, hiệu quả cho các kịch bản phi thương mại như thu thập trường hợp giảng dạy, nghiên cứu truyền thông mới và quản lý kiến thức cá nhân.

🔗 **Truy Cập Trực Tuyến**: [https://twittervideodownloaderx.com/tiktok_downloader_vi](https://twittervideodownloaderx.com/tiktok_downloader_vi)

> ⚠️ **Thông Báo Quan Trọng**: Dự án này chỉ được phát triển cho mục đích học tập kỹ thuật và nghiên cứu. Người dùng được kỳ vọng sẽ tuân thủ luật bản quyền và điều khoản dịch vụ của nền tảng liên quan, tôn trọng quyền của tác giả gốc, và tuyệt đối không sử dụng công cụ này cho bất kỳ hoạt động nào xâm phạm sở hữu trí tuệ hoặc vi phạm chính sách nền tảng.

---

## ✨ Tính Năng Chính

- 🔗 **Nhận Diện Liên Kết Thông Minh**: Tự động phân tích nhiều định dạng URL video TikTok khác nhau
- 📥 **Hỗ Trợ Tùy Chọn Chất Lượng**: Hiển thị độ phân giải khả dụng dựa trên siêu dữ liệu nguồn (theo thông tin công khai của nền tảng)
- 📱 **Tương Thích Đa Thiết Bị**: Thiết kế phản hồi tối ưu cho cả trình duyệt máy tính để bàn và thiết bị di động
- 🔐 **Ưu Tiên Quyền Riêng Tư**: Không ghi nhật ký hoạt động người dùng, không lưu trữ nội dung đã phân tích trên máy chủ
- ⚡ **Nhẹ Và Nhanh**: Logic xử lý tập trung vào phía client, giảm phụ thuộc máy chủ, phản hồi nhanh chóng
- 🔄 **Bảo Trì Liên Tục**: Cập nhật thường xuyên để thích ứng với thay đổi frontend của nền tảng, duy trì khả năng sử dụng của công cụ

---

## 🚀 Hướng Dẫn Sử Dụng

### Bước 1: Sao Chép Liên Kết Video
1. Mở ứng dụng hoặc trang web TikTok
2. Tìm **video công khai** mà bạn muốn phân tích
3. Nhấn "Chia sẻ" → "Sao chép liên kết" để sao chép URL video

### Bước 2: Gửi Yêu Cầu Phân Tích
1. Truy cập trang công cụ: `https://twittervideodownloaderx.com/tiktok_downloader_vi`
2. Dán liên kết đã sao chép vào trường nhập liệu được cung cấp
3. Nhấp nút "Bắt Đầu Phân Tích"

### Bước 3: Xem Kết Quả
1. Đợi hệ thống hoàn thành phân tích kỹ thuật (thường chỉ vài giây)
2. Xem trước siêu dữ liệu video khả dụng
3. Thực hiện các bước tiếp theo theo hướng dẫn (chỉ dành cho mục đích học tập cá nhân)

---

## 💡 Ví Dụ Liên Kết Được Hỗ Trợ

```
✅ Định dạng URL được khuyến nghị:
- https://www.tiktok.com/@username/video/1234567890
- https://vm.tiktok.com/xxxxxx/
- https://vt.tiktok.com/xxxxxx/

❌ Trường hợp hiện không được hỗ trợ:
- Video được đặt ở chế độ "Riêng tư" hoặc "Chỉ bạn bè"
- Nội dung yêu cầu xác thực đăng nhập để truy cập
- Video đã xóa, bị giới hạn khu vực hoặc giới hạn độ tuổi
- Nội dung được bảo vệ bởi hệ thống quản lý quyền kỹ thuật số (DRM) nâng cao
```

---

## ⚙️ Kiến Trúc Kỹ Thuật

| Thành Phần | Triển Khai | Mô Tả |
|-----------|-----------|-------|
| **Frontend** | HTML5 + CSS3 + Vanilla JS | Không phụ thuộc framework, tải nhanh |
| **Xử Lý Yêu Cầu** | Node.js / Python Backend | Bất đồng bộ không chặn, hỗ trợ xử lý song song cao |
| **Phân Tích Nội Dung** | Biểu Thức Chính Quy + Phân Tích DOM | Chỉ trích xuất siêu dữ liệu công khai, không vượt qua mã hóa |
| **Lớp Bảo Mật** | HTTPS + Lọc Đầu Vào + Giới Hạn Tốc Độ | Ngăn chặn lạm dụng, đảm bảo ổn định dịch vụ |
| **Môi Trường Triển Khai** | Docker + Tăng Tốc CDN | Phân tán node toàn cầu, truy cập độ trễ thấp |

---

## ⚠️ Tuyên Bố Tuân Thủ Và Sử Dụng Có Trách Nhiệm

Công cụ này hoạt động nghiêm ngặt theo nguyên tắc **trung lập kỹ thuật** và **sử dụng hợp lý**. Vui lòng tuân thủ các hướng dẫn sau:

### ✅ Trường Hợp Sử Dụng Được Phép
- 📚 Cơ sở giáo dục phân tích truyền thông dạng ngắn cho nghiên cứu học thuật
- 🔬 Dự án nghiên cứu liên quan đến lấy mẫu và chú thích nội dung video công khai
- 🗂️ Người sáng tạo nội dung cá nhân sắp xếp tài liệu tham khảo để lấy cảm hứng (với ghi nguồn phù hợp)
- 🌐 Truy cập nội dung ngoại tuyến cho mục đích học tập ở khu vực có kết nối internet hạn chế

### ❌ Hành Vi Bị Cấm
- 🚫 Sử dụng nội dung đã phân tích để phân phối thương mại hoặc kiếm tiền
- 🚫 Xóa watermark và đăng lại nội dung như tác phẩm gốc
- 🚫 Thu thập dữ liệu hàng loạt, thu thập dữ liệu tự động hoặc làm gián đoạn hoạt động nền tảng
- 🚫 Cố gắng vượt qua kiểm soát truy cập để xem nội dung không công khai

### 📜 Khung Tham Chiếu Pháp Lý
- Quy định sử dụng hợp lý theo luật bản quyền hiện hành (ví dụ: Luật Sở hữu trí tuệ Việt Nam)
- Điều khoản dịch vụ và hướng dẫn cộng đồng riêng của từng nền tảng
- Luật địa phương điều chỉnh truy cập nội dung số và sở hữu trí tuệ

> 📌 **Tuyên Bố Miễn Trừ Trách Nhiệm**: Nhà phát triển không chịu trách nhiệm cho bất kỳ hậu quả nào do việc sử dụng sai mục đích công cụ này. Bằng cách sử dụng phần mềm này, bạn xác nhận rằng bạn đã đọc, hiểu và đồng ý tuân thủ các điều khoản nêu trên.

---

## 🤝 Hướng Dẫn Đóng Góp

Chúng tôi hoan nghênh sự đóng góp từ cộng đồng để giúp cải thiện dự án này:

```bash
# 1. Fork repository này
# 2. Tạo branch tính năng mới
git checkout -b feature/improvement

# 3. Commit các thay đổi của bạn
git commit -m "feat: cải thiện logic khớp mẫu URL"

# 4. Push và mở Pull Request
git push origin feature/improvement
```

**Hướng Dẫn Đóng Góp**:
- Tuân thủ quy tắc kiểu mã ESLint / Prettier
- Bao gồm kiểm thử đơn vị cho chức năng mới khi có thể
- Sử dụng message commit rõ ràng, mô tả được (tiếng Việt hoặc tiếng Anh)
- Tài liệu hóa tính năng mới cả trong chú thích mã và cập nhật README

---

## 🐛 Báo Cáo Vấn Đề

Nếu phát hiện lỗi hoặc có đề xuất cải tiến:

1. Kiểm tra tab [Issues](../../issues) trước để tránh báo cáo trùng lặp
2. Khi tạo issue mới, vui lòng bao gồm các thông tin sau:
   - Tên và phiên bản trình duyệt
   - Các bước tái hiện vấn đề (theo từng bước)
   - Hành vi mong đợi và hành vi thực tế
   - Ảnh chụp màn hình hoặc log lỗi (nếu có)
3. Nhóm sẽ xem xét các lượt gửi định kỳ và phản hồi sớm nhất có thể

---

## 📄 Giấy Phép

Dự án này được phân phối dưới **Giấy phép MIT**. Bạn có thể tự do sử dụng, sửa đổi và phân phối phần mềm này, với điều kiện phải giữ nguyên thông báo bản quyền gốc và các điều khoản giấy phép.

```
MIT License

Copyright (c) 2024 TikTok Video Parser Project

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Lời Cảm Ơn

- Xin cảm ơn cộng đồng nguồn mở đã cung cấp các thành phần kỹ thuật mạnh mẽ
- Trân trọng cảm ơn người dùng và nhà nghiên cứu đã đóng góp phản hồi giá trị
- Tôn vinh những người sáng tạo nội dung đã làm phong phú hệ sinh thái số

---

> 📬 **Hỗ Trợ Và Liên Hệ**: Đối với các câu hỏi về hợp tác kỹ thuật hoặc vấn đề tuân thủ, vui lòng gửi ticket qua GitHub Issues. Chúng tôi sẽ nỗ lực phản hồi các yêu cầu chính đáng một cách nhanh chóng.

*Dự án này không liên kết, được tài trợ hoặc phê duyệt chính thức bởi TikTok Pte. Ltd. hoặc bất kỳ công ty liên kết nào. Tất cả nhãn hiệu, logo và tên thương hiệu là tài sản của chủ sở hữu tương ứng.*