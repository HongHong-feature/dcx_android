# Google Play Console (Android 앱 배포)
> **Google Play Console 앱 배포(Deployment) 내용을 정리하여 공유**
> 주소: https://play.google.com/console/
## 1. 개발자 등록
> **Google Play Console 을 통해 앱을 서비스 하는 경우 반드시 개발자 등록 필수**
###  1.1 개발자 등록 절차
- Google Play 개발자 계정 생성
  - Google 계정을 사용하여  [개발자 계정을 만듭니다](https://play.google.com/apps/publish/signup).
  - 개발자 계정을 만들면 Play Console을 통해  [앱을 게시하고 관리](https://developer.android.com/distribute/googleplay/developer-console.html)할 수 있습니다.
- 개발자배포계약동의
  - 가입 과정 중에 [Google Play 개발자 배포 계약](https://play.google.com/about/developer-distribution-agreement.html)을 검토하고 이에 동의해야 합니다.
- 등록 수수료 결제 (25$, 2022 년 기준)
  - 등록 수수료(미화 25달러)는 한 번만 청구되며 아래 목록에 있는 신용카드 또는 체크카드로 결제할 수 있습니다.
  - 선불카드는 사용할 수 없습니다. 사용할 수 있는 카드 유형은 지역에 따라 다를 수 있습니다.
- 계정 세부정보 입력
  - 개발자 이름이 Google Play 콘솔에 노출되므로 신중하게 입력
    (**참고:** Play 개발자 계정 요청을 처리하기 위해 본인 법적 이름으로 발급된 유효한 국가 발급 신분증과 신용카드가 모두 필요할 수 있습니다. 잘못된 정보를 제공하는 경우 등록 수수료가 환불되지 않습니다.)
    -계정을 만든 후에도 [계정 정보](https://support.google.com/googleplay/android-developer/answer/139626)를 추가로 입력할 수 있습니다.
## 2. 메뉴 구성
> **Google Play Console 접속시 좌측에 보이는 Main 메뉴 구성에 대한 설명**

<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_2.1.png" alt="store_2.1" width="35%"/>

|메뉴명 | 설명  |
|--|--|
| 모든앱 | 서비스 중인 모든 앱의 개요를 보임 (Dashboard) |
|메시지함 | Google Play 에서 전달하는 모든 메시지를 보임. 정책 변경사항, 앱 위반사항,<br/> 앱 취약점 등에 대한 메시지가 전달 운영 대응을 위해 지속적으로 메시지 확인 및 대응 필수|
|정책상태 | 개발자계정의 문제  및 상태를  확인,별도 문제가 없는 경우 "개발자 계정에서 문제를 찾을 수 없음" 표기|
|사용자및권한| -  개발자 계정에 Access 할 수 있는 사용자를 관리<br/>- 신규초대, 인원별 권한 부여|
|주문관리| - 주문을 확인, 환불 처리, 정기결제 취소<br/> - 앱을 통해 수익 발생사항에 대한 관리|
|보고서 다운로드| - 앱에서 생성되는 보고서 다운로드 (리뷰, 통계, 재무)<br> - 리뷰 : 앱의사용자리뷰 <br/> - 통계 : 앱설치,삭제등앱의전반적인통계 <br/> - 재무 : 앱으로부터 발생한 수익,지출 내역
|계정 세부정보| - 개발자 계정이 개인용인지 아니면 조직이나 비즈니스를 대표하는지 설정 <br/> - 개발자 계정 아이디,이메일,전화번호를 관리|
|개발자 페이지| 구글스토어에 게시할 개발자 소개페이지 편집|
|연결된 개발자 계정| 나와 연결된 다른 개발자 계정이 있는지 Google에서 확인할 수 있도록 [계정 그룹 생성](https://support.google.com/googleplay/android-developer/answer/10627869) 및 관리|
|활동 로그| 계정 소유자는 활동 로그를 사용하여 계정 사용자가 Play Console에서 변경한 사항을 확인할 수 있습니다. <br/>활동 로그에는 전체 기간의 개발자 계정 정보가 기록됩니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/6053184?hl=ko))|
|설정| Google Play Console 설정|
## 3. 앱 등록
>**Google Play Store 에 앱을 등록하는 방법을 정리합니다.**
### 3.1 앱만들기
  <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.1.1.png" alt="store_3.1.1" width="100%"/>

#### 3.1.1 앱 세부정보 입력
  <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.1.1-1.png" alt="store_3.1.1-1" width="70%"/>

|메뉴명 | 설명  |
|--|--|
|앱이름 | GooglePlay에 표시될 앱명을 기입 <br/>(콘솔에서 수정가능)<br/>(성장 -> 앱정보 -> 기본 스토어 등록정보 -> 앱 세부정보)|
|기본언어 |해당앱의기본언어 <br/>(콘솔에서 수정가능)<br/>(성장 -> 앱정보 -> 기본 스토어 등록정보 -> 번역관리)|
|앱또는게임|앱,게임여부설정 <br/>(콘솔에서 수정가능)<br/>(성장 -> 앱정보 -> 스토어 설정 -> 앱 카테고리)|
|유료또는무료|앱,게임여부설정 <br/>(콘솔에서 수정가능)<br/>(수익 창출 -> 제품 -> 앱 가격 -> 가격 설정)<br/>**주의사항 : 앱 생성시에는 변경가능하나, 앱을 게시한 이후 수정 불가 (무료앱을 유료앱으로 변경 불가)**|

#### 3.1.2 선언
  <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.1.2.png" alt="store_3.1.2" width="70%"/>

|메뉴명 | 설명  |
|--|--|
|개발자 프로그램 정책 | 앱이 개발자 프로그램 정책을 준수하는지 약관 동의 ([자세히 알아보기](https://play.google.com/about/developer-content-policy/))|
|Play 앱 서명|Google에서는 Play 앱 서명으로 앱의 서명 키를 관리하고 보호하며, App Bundle에서 생성된 최적화된 배포 APK에 서명하는 데 이 키를 사용합니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9842756?hl=ko&visit_id=637871543737226245-2061671898&rd=1))|
|미국 수출법| 미국 수출법 약관 동의 ([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/113770?hl=ko))|

### 3.2 앱 설정
  <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.png" alt="store_3.2" width="70%"/>
  