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
> **앱에 관한 정보를 제공하고 스토어 등록 정보 설정 (앱 설정이 완료되면 취소선으로 설정완료 항목이 표시)**
>  - **앱 콘텐츠에 관한 정보입력**
>  - **앱이 분류 및 표시되는 방식관리**

  <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.png" alt="store_3.2" width="60%"/>

#### 3.2.1 앱 액세스 권한
> **게시할 앱이 엑세스가 제한되는 기능을 포함하는 경우 Google 심사에 사용하기 위한 정보를 입력. (ex. 로그인 사용자 인증 정보, 맴버십)**
> - **엑세스정보가 누락된 경우 리젝사유**


 <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.1-1.png" alt="store_3.2.1-1" width="70%"/>

|메뉴명 | 설명  |
|--|--|
| 특수한 엑세스 권한 없이 모든 기능 이용가능:| 별도정보기입불필요|
|전체 또는 일부 기능이 제한됨| 엑세스정보 입력 필요|

#### 3.2.1.1 새안내추가
> **이름, 사용자 이름/전화번호, 비밀번호, 다른 안내사항을 기입**
<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.1.1.png" alt="store_3.2.1.1" width="70%"/>

#### 3.2.2 광고
> **앱에 광고가 포함되어 있는지  설정**

|광고 대시보드 선택화면 | 앱스토어 광고 포함 문구 예시([자세히 보기](https://support.google.com/googleplay/android-developer/answer/9859455?visit_id=637871565108829086-2356309235&rd=1#ads))  |
|--|--|
| <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.2.png" alt="store_3.2.2" width="100%"/>| <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.2-1.png" alt="store_3.2.2-1" width="100%"/>|

앱이 광고를 포함하는 경우 입력하며 기본적으로 Google 의 광고 정책을 따름.
[광고 정책](https://play.google.com/about/monetization-ads/ads/)을 읽고 앱이 정책을 준수하는지 확인하시기 바랍니다.

#### 3.2.3 콘텐츠 등급
>  **콘텐츠 등급 설문지를 완료하여 앱의 공식 콘텐츠 등급을 받으세요. 이 등급은 Google Play에 표시되어 사용자가 앱이 자신에게 적합한지 판단하는 데 도움을 줍니다. ([자세히 보기](https://support.google.com/googleplay/android-developer/answer/9859655?visit_id=637871565108829086-2356309235&rd=1))**

<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.3.png" alt="store_3.2.3" width="70%"/>

입력 완료 시 각 국가별 등급이 결정
등급 부여기관은 Google Play 가 기본이나, 브라질, 북미등 일부 기관의 경우 전문 등급 부여 기관이 별도로 존재

<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.3-1.png" alt="store_3.2.3-1" width="70%"/>

#### 3.2.4 타겟층 및 콘텐츠
> **앱을 사용하는 주 타겟층에 대한 정보를 입력**

<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.4.png" alt="store_3.2.4" width="70%"/>

- 대상연령, 앱 세부정보, 광고, 앱 정보, 요약 순으로 입력. 단 타겟층에 13세 미만 어린이가 포함되는 경우 개인정보처리방침을 추가해야 함.([자세히 보기](https://support.google.com/googleplay/android-developer/answer/9867159?visit_id=637871565108829086-2356309235&rd=1#age-groups))
- 앱 세부정보, 광고 항목은 사전 등록되었으므로 skip 됨'
- 스토어 등록정보가 어린이의 관심을 유도하는지 입력<br/>'아니오' 를 입력하는 경우 Google 심사시 리젝 사유가 될 수 있음. '아니오' 를 입력하면 아래 사유를 충족해야 함<br/>-   스토어 등록정보에 어린이가 좋아할만한 애니메이션, 아동 캐릭터가 포함되지 않아야 함.<br/>-   스토어 등록정보에 어린이의 관심을 끌만한 요소가 없어야 함.<br/><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.4-1.png" alt="store_3.2.4-1" width="70%"/>
- 요약,모든 정보 입력시 요약 화면<br/><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.4-2.png" alt="store_3.2.4-2" width="70%"/>

#### 3.2.5 타겟층 및 콘텐츠
> **앱이 뉴스 앱인지 설정.**

<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.5.png" alt="store_3.2.5" width="70%"/>

뉴스 앱인 경우 Google Play 뉴스 정책을 반드시 준수해야 함 ([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9949730))

#### 3.2.6 코로나19 접촉자 추적 앱 및 이력 앱
> **앱이 코로나19 접촉자 추적 앱 또는 이력 앱인지 파악할 수 있도록 설정.**

<img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.6.png" alt="store_3.2.6" width="70%"/>

공개된 코로나19 이력 앱인 경우  앱이 요건을 충족한다는 증빙 자료를 반드시 제출해야 함([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9889712?hl=ko#app_requirements))

#### 3.2.7 데이터 보안 (선택)
> **필수로 해야되는 항목이 아닙니다.사용자가 엡의 데이터 수집 및 공유 방식을 이해하도록  각 수집 항목에 대해 설명정의를 하도록 합니다.**
- 개요<br/> <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7.png" alt="store_3.2.7" width="70%"/>

- 데이터 수집 및 보안<br/> <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-1.png" alt="store_3.2.7-1" width="70%"/><br/> - 앱에서 필수 사용자 데이터 유형을 수집하거나 공유하나요?<br/>**공개해야 하는 필수 사용자 데이터 유형의 목록에 포함된 데이터**를 수집할 경우 '예' 를 선택해야 합니다. ([자세히 알아보기]((https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#types&zippy=%2C%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%9C%A0%ED%98%95) )) <br/> - 앱에서 수집하는 모든 사용자 데이터를 암호화하여 전송하나요? <br/>**사용자 데이터를 암호화 안하고 평문**으로 전송시에 리젝이 될수 있으니 약관을 참고 해야 합니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#other) )<br/> - 사용자가 데이터 삭제를 요청할 수 있는 방편을 제공하나요?<br/>개인정보는 탈퇴등 방법으로 삭제가 가능해야됩니다..([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#other) )
- 데이터 유형<br/> <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-2.png" alt="store_3.2.7-2" width="70%"/><br/> - 앱에서 필수 사용자 데이터 유형을 수집하거나 공유하나요?<br/>[공개해야 하는 필수 사용자 데이터 유형의 목록에 포함된 데이터](https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#types&zippy=%2C%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%9C%A0%ED%98%95) 에 대해 수집하는것을 선택해줍니다.
- 데이터 사용량 및 처리<br/> <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-3.png" alt="store_3.2.7-3" width="70%"/><br/> 선택된 데이터 수집 항목들이 어떤 용도로 쓰이는지, 외부로 공유되는지 명시하도록 합니다.<br/> <img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-4.png" alt="store_3.2.7-4" width="70%"/> <br/> - 데이터를 수집 또는 공유하나요? 아니면 수집과 공유를 모두 하나요?<br/> 앱내에서 서버전달없이 로컬에서만 사용 할 경우, 수집하여 타사로 전달만 할경우 '**공유됨**'을 선택합니다. <br/>기타 자체서버로 수집하는 경우는 '**수집됨**'을 선택합니다. <br/> - 이 데이터는 임시로 처리되나요?<br/>메모리에 임시로 저장하고 잃어버리는 휘발성 데이터일 경우 '**예, 수집된 데이터가 임시적으로 처리됩니다**'을 선택합니다.<br/>