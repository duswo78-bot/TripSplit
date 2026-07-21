# ✈️ 트립N빵 (TripNBang)

**스마트하고 세련된 여행 경비 정산기 (Smart Travel Expense Splitter)**

트립N빵은 복잡한 단체 여행 경비 정산을 클릭 몇 번만으로 해결해주는 단일 페이지 웹 애플리케이션(SPA)입니다. 별도의 앱 설치나 서버 연동 없이 브라우저의 저장소(LocalStorage)를 활용하여 빠르고 안전하게 동작합니다.

<p align="center">
  <img src="logo.png" alt="TripNBang Logo" width="120" height="120" />
</p>

## ✨ 주요 기능 (Features)

- 🎨 **프리미엄 UI/UX (Glassmorphism 디자인)**
  - 세련된 반투명 글래스모피즘 기반의 UI
  - **다크 모드 / 라이트 모드** 완벽 지원
  - 부드러운 애니메이션과 마이크로 인터랙션
- 👥 **빠른 멤버 추가 및 관리**
  - 엔터키 하나로 멤버를 빠르게 추가하는 **Quick Add** 기능
- 💸 **복잡한 비용 정산 최적화**
  - N빵, 특정 멤버 제외, 개별 금액 지정 등 다양한 정산 로직 지원
  - '누가 누구에게 얼마를 보내야 하는지' 최소한의 횟수로 송금할 수 있도록 자동 계산 (Settlement Algorithm)
- 📸 **스마트 영수증 스캔 (OCR)**
  - 영수증 사진을 올리면 자동으로 금액을 추출하는 기능 지원 예정 (UI 통합 완료)
- 💙 **토스(Toss) 원클릭 송금 연동**
  - 총무의 계좌번호를 입력해두면 토스 앱으로 즉시 연결되는 딥링크 송금 버튼 생성
- 📂 **로컬 아카이브 (보관함)**
  - 여러 번의 모임이나 여행 일정을 로컬 스토리지에 저장하고 원할 때 다시 불러오기 가능

## 🚀 시작하기 (Getting Started)

이 프로젝트는 바닐라 HTML, CSS, JavaScript로 작성되어 별도의 빌드 과정이 필요 없습니다.

### 설치 및 실행

1. 레포지토리를 클론합니다.
   ```bash
   git clone https://github.com/duswo78-bot/TripSplit.git
   ```
2. 폴더 내의 `index.html` 파일을 크롬, 사파리 등의 웹 브라우저에서 엽니다.
3. 또는 `Live Server` 확장을 사용하거나 간단한 로컬 서버를 띄워 접속합니다.
   ```bash
   npx serve .
   ```

## 🛠️ 기술 스택 (Tech Stack)

- **Frontend**: HTML5, Vanilla JavaScript, Vanilla CSS
- **Storage**: 브라우저 LocalStorage
- **Design**: Glassmorphism UI, Responsive Web, SVG Icons

## 📱 사용 방법 (How to Use)

1. **일정 및 멤버 입력**: 모임 이름과 기간을 적고, 참석한 멤버들을 빠르게 입력합니다.
2. **비용 내역 추가**: 결제한 사람(총무)과 금액, 그리고 해당 비용을 나눌 참석자들을 선택합니다.
3. **정산 결과 확인**: 앱이 알아서 송금해야 할 사람과 금액을 계산해 줍니다. 
4. **송금하기**: 토스 송금 버튼을 눌러 모바일에서 바로 정산을 완료하세요.
5. **보관함에 저장**: 이번 여행이 끝나면 '보관함'에 저장해두고, '새 일정' 버튼을 눌러 다음 모임을 시작하세요.

---
*Developed as a premium expense splitter web application.*
