# TikTok 동영상 파서 도구 🎬

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Language](https://img.shields.io/badge/language-한국어-yellow.svg)

## 📋 프로젝트 개요

**TikTok 동영상 파서 도구** 는 교육자, 연구자 및 개인 학습자를 위해 설계된 웹 기반 보조 도구입니다. "공정 이용 (Fair Use)" 원칙에 따라 공개적으로 접근 가능한 TikTok 숏폼 동영상 링크를 기술적으로 분석하고, 교육·연구·개인 학습 목적의 아카이빙을 지원하는 것을 목표로 합니다. 본 도구는 수업 사례 수집, 뉴미디어 연구, 개인 지식 관리 등 비영리 시나리오에서 깔끔하고 효율적인 기술 지원을 제공합니다.

🔗 **온라인 접속**: [https://twittervideodownloaderx.com/tiktok_downloader_ko](https://twittervideodownloaderx.com/tiktok_downloader_ko)

> ⚠️ **중요 안내**: 본 프로젝트는 순수하게 기술 학습 및 연구 목적으로만 개발되었습니다. 이용자는 저작권법 및 관련 플랫폼 이용약관을 준수하고, 원작자의 권리를 존중하며, 본 도구를 저작권 침해 또는 플랫폼 정책 위반 목적으로 절대 사용하지 않아야 합니다.

---

## ✨ 주요 기능

- 🔗 **스마트 링크 인식**: 다양한 TikTok 동영상 URL 형식 자동 파싱 지원
- 📥 **화질 옵션 제공**: 소스 메타데이터 기반 이용 가능한 해상도 표시 (플랫폼 공개 정보 기준)
- 📱 **크로스 디바이스 호환**: 데스크톱 및 모바일 브라우저 모두 최적화된 반응형 디자인
- 🔐 **프라이버시 우선**: 사용자 활동 로그 미저장, 파싱 콘텐츠 서버 보관 안 함
- ⚡ **경량화·고속 처리**: 클라이언트 중심 처리 로직으로 서버 의존도 최소화, 빠른 응답
- 🔄 **지속적 유지보수**: 플랫폼 프론트엔드 변경사항에 정기 대응하여 도구 가용성 유지

---

## 🚀 사용 가이드

### 단계 1: 동영상 링크 복사
1. TikTok 앱 또는 웹사이트 접속
2. 분석하고자 하는 **공개 동영상** 찾기
3. "공유" → "링크 복사" 탭/클릭하여 동영상 URL 복사

### 단계 2: 파싱 요청 제출
1. 도구 페이지 접속: `https://twittervideodownloaderx.com/tiktok_downloader_ko`
2. 제공된 입력란에 복사한 링크 붙여넣기
3. "파싱 시작" 버튼 클릭

### 단계 3: 결과 확인
1. 시스템의 기술적 분석 완료 대기 (보통 수 초 소요)
2. 이용 가능한 동영상 메타데이터 미리보기 확인
3. 안내에 따라 후속 작업 진행 (개인 학습 목적으로만 한정)

---

## 💡 지원 링크 예시

```
✅ 권장 URL 형식:
- https://www.tiktok.com/@username/video/1234567890
- https://vm.tiktok.com/xxxxxx/
- https://vt.tiktok.com/xxxxxx/

❌ 현재 지원되지 않는 경우:
- "비공개" 또는 "친구만 보기"로 설정된 동영상
- 로그인 인증이 필요한 콘텐츠
- 삭제됨, 지역 제한, 연령 제한이 적용된 동영상
- 고급 DRM(디지털 저작권 관리) 으로 보호된 콘텐츠
```

---

## ⚙️ 기술 아키텍처

| 구성 요소 | 구현 기술 | 설명 |
|----------|----------|------|
| **프론트엔드** | HTML5 + CSS3 + Vanilla JS | 프레임워크 미사용으로 빠른 로딩 |
| **요청 처리** | Node.js / Python 백엔드 | 비동기 논블로킹, 고병렬 처리 지원 |
| **콘텐츠 파서** | 정규식 + DOM 분석 | 공개 메타데이터만 추출, 암호화 우회 없음 |
| **보안 계층** | HTTPS + 입력 필터링 + 속도 제한 | 악용 방지 및 서비스 안정성 확보 |
| **배포 환경** | Docker + CDN 가속 | 글로벌 노드 분산으로 저지연 접속 |

---

## ⚠️ 규정 준수 및 책임 있는 이용 안내

본 도구는 **기술적 중립성** 및 **공정 이용** 원칙에 엄격히 기반하여 운영됩니다. 이용 시 다음 가이드라인을 반드시 준수해 주시기 바랍니다:

### ✅ 허용되는 이용 사례
- 📚 교육기관의 숏폼 미디어 학술적 사례 연구 분석
- 🔬 공개 동영상 콘텐츠 샘플링 및 어노테이션을 위한 연구 프로젝트
- 🗂️ 개인 크리에이터의 참고 자료 정리 (출처 명시 전제)
- 🌐 인터넷 접속이 제한된 지역에서의 오프라인 학습 접근

### ❌ 금지되는 행위
- 🚫 파싱 콘텐츠의 영리적 재배포 또는 수익화
- 🚫 워터마크 제거 후 원작인 것처럼 재게시
- 🚫 대량 스크래핑, 자동 데이터 수집, 플랫폼 운영 방해 행위
- 🚫 접근 제어를 우회하여 비공개 콘텐츠에 접근 시도

### 📜 법적 참고 프레임워크
- 각국 저작권법의 공정 이용·인용 규정 (예: 한국 저작권법 제 35 조의 3)
- 플랫폼별 이용약관 및 커뮤니티 가이드라인
- 디지털 콘텐츠 접근 및 지식재산권 관련 현지 법령

> 📌 **면책 조항**: 개발자는 본 도구의 부적절한 사용으로 발생하는 어떠한 결과에 대해서도 책임을 지지 않습니다. 본 소프트웨어를 이용함으로써, 귀하는 위의 이용 조건을 읽고 이해하며 준수하는 것에 동의한 것으로 간주됩니다.

---

## 🤝 기여 가이드

커뮤니티의 기여를 환영합니다. 프로젝트 개선에 함께 참여해 주세요:

```bash
# 1. 저장소 포크 (Fork)
# 2. 기능 브랜치 생성
git checkout -b feature/improvement

# 3. 변경사항 커밋
git commit -m "feat: URL 패턴 매칭 로직 개선"

# 4. 푸시 후 풀 리퀘스트 오픈
git push origin feature/improvement
```

**기여 가이드라인**:
- ESLint / Prettier 코드 스타일 규칙 준수
- 새 기능에는 가능한 경우 단위 테스트 포함
- 커밋 메시지는 명확하고 설명적으로 작성 (한국어 또는 영어)
- 새 기능은 코드 주석 및 README 업데이트를 통해 문서화

---

## 🐛 이슈 보고

버그를 발견하거나 개선 제안이 있으신 경우:

1. 먼저 [Issues](../../issues) 탭에서 중복 보고 여부 확인
2. 새 이슈 작성 시 다음 내용을 포함해 주세요:
   - 브라우저 이름 및 버전
   - 재현 단계 (단계별 설명)
   - 기대 동작과 실제 동작
   - 스크린샷 또는 오류 로그 (해당 시)
3. 팀은 정기적으로 제출물을 검토하며 가능한 한 신속하게 답변드립니다

---

## 📄 라이선스

본 프로젝트는 **MIT 라이선스** 하에 배포됩니다. 원본 저작권 표시 및 라이선스 조항을 유지하는 조건 하에, 본 소프트웨어의 사용, 수정, 배포를 자유롭게 하실 수 있습니다.

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

## 🙏 감사의 말

- 견고한 기술 컴포넌트를 제공하는 오픈소스 커뮤니티에 감사
- 소중한 피드백을 주시는 사용자 및 연구자 분들께 사의 표함
- 디지털 생태계를 풍요롭게 하는 콘텐츠 크리에이터 분들께 경의를 표합니다

---

> 📬 **지원 및 문의**: 기술 협력 문의 또는 규정 준수 관련 질문은 GitHub Issues 를 통해 티켓을 제출해 주세요. 정당한 요청에는 신속하게 대응하겠습니다.

*본 프로젝트는 TikTok Pte. Ltd. 또는 그 계열사와 어떠한 공식적 제휴, 승인, 후원을 받지 않았습니다. 모든 상표, 로고, 브랜드명은 각 소유자에게 귀속됩니다.*