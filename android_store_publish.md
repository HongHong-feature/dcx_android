


# Google Play Console (Android 앱 배포)
> **Google Play Console 앱 배포(Deployment) 내용을 정리하여 공유**
> 주소: https://play.google.com/console/

## 목차


 
- 1 [개발자 등록](#1-개발자-등록)
  * 1.1 [개발자 등록 절차](#11-개발자-등록-절차)
- 2 [메뉴 구성](#2-메뉴-구성)
- 3 [앱 등록](#3-앱-등록)
  * 3.1   [앱만들기](#31-앱만들기)
    + 3.1.1 [앱 세부정보 입력](#311-앱-세부정보-입력)
    + 3.1.2 [선언](#312-선언)
  * 3.2 [앱 설정](#32-앱-설정)
    + 3.2.1 [앱 액세스 권한](#321-앱-액세스-권한)
      * 3.2.1.1 [새 안내 추가](3211-새-안내-추가)
    + 3.2.2 [광고](#322-광고)
    + 3.2.3 [콘텐츠 등급](#323-콘텐츠-등급)
    + 3.2.4 [타겟층 및 콘텐츠](#324-타겟층-및-콘텐츠)
    + 3.2.5 [뉴스 앱 설정](#325-뉴스-앱-설정)
    + 3.2.6 [코로나19 접촉자 추적 앱 및 이력 앱](#326-코로나19-접촉자-추적-앱-및-이력-앱)
    + 3.2.7 [개인정보처리방침](#327-개인정보처리방침)
    + 3.2.8 [데이터 보안 (선택)](#328-데이터-보안--선택-)
  * 3.3 [스토어 설정](#33-스토어-설정)
  * 3.4 [기본 스토어 등록정보](#34-기본-스토어-등록정보)
    + 3.4.1 [앱 세부정보](#341-앱-세부정보)
    + 3.4.2 [그래픽](#342-그래픽)
- 4 [테스트](#4-테스트)
  * 4.1 [공개 테스트](#41-공개-테스트)
    + 4.1.1 [국가/지역](#411-국가-지역)
    + 4.1.2 [테스터](#412-테스터)
  * 4.2 [비공개 테스트](#42-비공개-테스트)
    + 4.2.1 [국가/지역](#421-국가-지역)
    + 4.2.2 [테스터](#422-테스터)
  * 4.3 [내부 테스트](#43-내부-테스트)
    + 4.3.1 [테스터](#431-테스트)
  * 4.4 [테스터 이메일 목록 만들기](#44-테스터-이메일-목록-만들기)
  * 4.5 [버전 bundle 혹은 APK 등록 출시](#45-버전-bundle-혹은-APK-등록-출시)
    + 4.5.1 [버전 세부정보 와 App Bundle 등록](#451-버전-세부정보-와-App-Bundle-등록)
    + 4.5.2 [검토 결과 확인 및 출시](#452-검토-결과-확인-및-출시)
  * 4.6 [테스트 참여](#46-테스트-참여)
    + 4.6.1 [내부앱 공유 설정](#461-내부앱-공유-설정)
    + 4.6.2 [초대 수락 혹은 취소](#462-내부앱-공유-설정)
    + 4.6.3 [결과 확인](#463-내부앱-공유-설정)


## 1. 개발자 등록
> **Google Play Console 을 통해 앱을 서비스 하는 경우 반드시 개발자 등록 필수 .**
###  1.1 개발자 등록 절차
- **Google Play 개발자 계정 생성(18세 이상만 가능)**
  - Google 계정을 사용하여  [개발자 계정을 만듭니다](https://play.google.com/apps/publish/signup).
  - 개발자 계정을 만들면 Play Console을 통해  [앱을 게시하고 관리](https://developer.android.com/distribute/googleplay/developer-console.html)할 수 있습니다.
- **개발자 배포계약 동의**
  - 가입 과정 중에 [Google Play 개발자 배포 계약](https://play.google.com/about/developer-distribution-agreement.html)을 검토하고 이에 동의해야 합니다.
- **등록 수수료 결제 (25$, 2022 년 기준)**
  - 등록 수수료(미화 25달러)는 **한 번만 청구**되며 아래 목록에 있는 신용카드 또는 체크카드로 결제할 수 있습니다.  <br/> - Mastercard<br/> - Visa<br/> - American Express<br/> - Discover(미국만 해당)<br/> - Visa Electron(미국 이외의 지역만 해당)
  - **선불카드는 사용할 수 없습**니다. 사용할 수 있는 카드 유형은 지역에 따라 다를 수 있습니다.
- **계정 세부정보 입력**
  - 개발자 이름이 Google Play 콘솔에 노출되므로 신중하게 입력        
    (**참고:** Play 개발자 계정 요청을 처리하기 위해 본인 법적 이름으로 발급된 유효한 국가 발급 신분증과 신용카드가 모두 필요할 수 있습니다. 잘못된 정보를 제공하는 경우 등록 수수료가 환불되지 않습니다.)        
    -계정을 만든 후에도 [계정 정보](https://support.google.com/googleplay/android-developer/answer/139626)를 추가로 입력할 수 있습니다.

[자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/6112435?hl=ko#zippy=%2C%EB%8B%A8%EA%B3%84-%EB%93%B1%EB%A1%9D-%EC%88%98%EC%88%98%EB%A3%8C-%EA%B2%B0%EC%A0%9C%ED%95%98%EA%B8%B0)

## 2. 메뉴 구성
> **Google Play Console 접속시 좌측에 보이는 Main 메뉴 구성에 대한 설명.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_2.1.png" alt="store_2.1" width="35%"/></kbd>

|메뉴명 | 설명  |        
|--|--|        
| 모든앱 | 서비스 중인 모든 앱의 개요를 보임 (Dashboard) |        
|메시지함 | Google Play 에서 전달하는 모든 메시지를 보임. 정책 변경사항, 앱 위반사항,<br/> 앱 취약점 등에 대한 메시지가 전달 운영 대응을 위해 지속적으로 메시지 확인 및 대응 필수|        
|정책상태 | 개발자계정의 문제  및 상태를  확인,별도 문제가 없는 경우 "개발자 계정에서 문제를 찾을 수 없음" 표기|        
|사용자 및 권한| -  개발자 계정에 Access 할 수 있는 사용자를 관리<br/>- 신규초대, 인원별 권한 부여|        
|주문관리| - 주문을 확인, 환불 처리, 정기결제 취소<br/> - 앱을 통해 수익 발생사항에 대한 관리|        
|보고서 다운로드| - 앱에서 생성되는 보고서 다운로드 (리뷰, 통계, 재무)<br> - 리뷰 : 앱의 사용자리뷰 <br/> - 통계 : 앱설치,삭제등앱의전반적인통계 <br/> - 재무 : 앱으로부터 발생한 수익,지출 내역        
|계정 세부정보| - 개발자 계정이 개인용인지 아니면 조직이나 비즈니스를 대표하는지 설정 <br/> - 개발자 계정 아이디,이메일,전화번호를 관리|        
|개발자 페이지| 구글스토어에 게시할 개발자 소개페이지 편집|        
|연결된 개발자 계정| 나와 연결된 다른 개발자 계정이 있는지 Google에서 확인할 수 있도록 [계정 그룹 생성](https://support.google.com/googleplay/android-developer/answer/10627869) 및 관리|        
|활동 로그| 계정 소유자는 활동 로그를 사용하여 계정 사용자가 Play Console에서 변경한 사항을 확인할 수 있습니다. <br/>활동 로그에는 전체 기간의 개발자 계정 정보가 기록됩니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/6053184?hl=ko))|        
|설정| Google Play Console 설정|
## 3. 앱 등록
>**Google Play Store 에 앱을 등록하는 방법을 정리합니다.**
### 3.1 앱만들기
<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.1.1.png" alt="store_3.1.1" width="100%"/></kbd>

#### 3.1.1 앱 세부정보 입력
<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.1.1-1.png" alt="store_3.1.1-1" width="100%"/></kbd>

|메뉴명 | 설명  |        
|--|--|        
|앱이름 | Google Play Store에 표시될 앱명을 기입 <br/>(콘솔에서 수정가능)<br/>(성장 -> 앱정보 -> 기본 스토어 등록정보 -> 앱 세부정보)|        
|기본언어 |해당앱의기본언어 <br/>(콘솔에서 수정가능)<br/>(성장 -> 앱정보 -> 기본 스토어 등록정보 -> 번역관리)|        
|앱또는게임|앱,게임여부설정 <br/>(콘솔에서 수정가능)<br/>(성장 -> 앱정보 -> 스토어 설정 -> 앱 카테고리)|        
|유료또는무료|앱,게임여부설정 <br/>(콘솔에서 수정가능)<br/>(수익 창출 -> 제품 -> 앱 가격 -> 가격 설정)<br/>**주의사항 : 앱 생성시에는 변경가능하나, 앱을 게시한 이후 수정 불가 (무료앱을 유료앱으로 변경 불가)**|

#### 3.1.2 선언
<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.1.2.png" alt="store_3.1.2" width="100%"/></kbd>

|메뉴명 | 설명  |        
|--|--|        
|개발자 프로그램 정책 | 앱이 개발자 프로그램 정책을 준수하는지 약관 동의 ([자세히 알아보기](https://play.google.com/about/developer-content-policy/))|        
|Play 앱 서명|Google에서는 Play 앱 서명으로 앱의 서명 키를 관리하고 보호하며, App Bundle에서 생성된 최적화된 배포 APK에 서명하는 데 이 키를 사용합니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9842756?hl=ko&visit_id=637871543737226245-2061671898&rd=1))|        
|미국 수출법| 미국 수출법 약관 동의 ([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/113770?hl=ko))|

### 3.2 앱 설정
> **앱에 관한 정보를 제공하고 스토어 등록 정보 설정 (앱 설정이 완료되면 취소선으로 설정완료 항목이 표시).**
> - **앱 콘텐츠에 관한 정보입력.**
> - **앱이 분류 및 표시되는 방식관리.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.png" alt="store_3.2" width="60%"/></kbd>


#### 3.2.1 앱 액세스 권한
> **게시할 앱이 엑세스가 제한되는 기능을 포함하는 경우 Google 심사에 사용하기 위한 정보를 입력. (ex. 로그인 사용자 인증 정보, 맴버십).**
> - **엑세스정보가 누락된 경우 리젝사유.**


<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.1-1.png" alt="store_3.2.1-1" width="100%"/></kbd>

|메뉴명 | 설명  |        
|--|--|        
| 특수한 엑세스 권한 없이 모든 기능 이용가능| 별도 정보 기입 불필요|        
|전체 또는 일부 기능이 제한됨| 엑세스정보 입력 필요|

#### 3.2.1.1 새 안내 추가
> **이름, 사용자 이름/전화번호, 비밀번호, 다른 안내사항을 기입.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.1.1.png" alt="store_3.2.1.1" width="100%"/></kbd>

#### 3.2.2 광고
> **앱에 광고가 포함되어 있는지  설정.**

|광고 대시보드 선택화면 | 앱스토어 광고 포함 문구 예시([자세히 보기](https://support.google.com/googleplay/android-developer/answer/9859455?visit_id=637871565108829086-2356309235&rd=1#ads))  |        
|--|--|        
| <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.2.png" alt="store_3.2.2" width="100%"/></kbd>| <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.2-1.png" alt="store_3.2.2-1" width="100%"/></kbd>|

앱이 광고를 포함하는 경우 입력하며 기본적으로 Google 의 광고 정책을 따릅니다.        
[광고 정책](https://play.google.com/about/monetization-ads/ads/)을 읽고 앱이 정책을 준수하는지 확인하시기 바랍니다.

#### 3.2.3 콘텐츠 등급
> **컨텐츠 등급 결정. 설문지 작성을 통해 앱의 공신 콘텐츠 등급이 선정되며, 해당 등급은 Google Play 에 표시되어 사용자가 앱이 자신에게 적합한지 판단. ([자세히 보기](https://support.google.com/googleplay/android-developer/answer/9859655?visit_id=637871565108829086-2356309235&rd=1))**

설문지 시작 클릭시 아래와 같이 상세 입력란이 생성되며 카테고리, 설문지, 요약으로 구성되어 있읍니다.(각 항목별 설문 다수 존재)

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.3.png" alt="store_3.2.3" width="70%"/></kbd>

입력 완료 시 각 국가별 등급이 결정 됩니다.       
등급 부여기관은 Google Play 가 기본이나, 브라질, 북미등 일부 기관의 경우 전문 등급 부여 기관이 별도로 존재 합니다.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.3-1.png" alt="store_3.2.3-1" width="70%"/> </kbd>

#### 3.2.4 타겟층 및 콘텐츠
> **앱을 사용하는 주 타겟층에 대한 정보를 입력.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.4.png" alt="store_3.2.4" width="70%"/></kbd>

- **대상연령**<br/>앱 세부정보, 광고, 앱 정보, 요약 순으로 입력. 단 타겟층에 13세 미만 어린이가 포함되는 경우 개인정보처리방침을 추가해야 합니다.([자세히 보기](https://support.google.com/googleplay/android-developer/answer/9867159?visit_id=637871565108829086-2356309235&rd=1#age-groups))
- **앱 세부정보,광고**<br/>  이 두 항목은 사전 등록되었으므로 skip 됩니다.
- **앱 정보**<br/> 스토어 등록정보가 어린이의 관심을 유도하는지 입력<br/>'**아니오**' 를 입력하는 경우 Google 심사시 리젝 사유가 될 수 있읍니다. '**아니오**' 를 입력하면 아래 사유를 충족해야 합니다.<br/>-   스토어 등록정보에 어린이가 좋아할만한 애니메이션, 아동 캐릭터가 포함되지 않아야 합니다.<br/>-   스토어 등록정보에 어린이의 관심을 끌만한 요소가 없어야 합니다.<br/><br/><kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.4-1.png" alt="store_3.2.4-1" width="70%"/>
- **요약**<br/>모든 정보 입력시 요약 화면,확인 후 완료하면 됩니다.<br/><kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.4-2.png" alt="store_3.2.4-2" width="100%"/></kbd>

#### 3.2.5 뉴스 앱 설정
> **앱이 뉴스 앱인지 설정.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.5.png" alt="store_3.2.5" width="100%"/></kbd>

뉴스 앱인 경우 Google Play 뉴스 정책을 반드시 준수해야 합니다. ([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9949730))

#### 3.2.6 코로나19 접촉자 추적 앱 및 이력 앱
> **앱이 코로나19 접촉자 추적 앱 또는 이력 앱인지 파악할 수 있도록 설정.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.6.png" alt="store_3.2.6" width="100%"/></kbd>

공개된 코로나19 이력 앱인 경우  앱이 요건을 충족한다는 증빙 자료를 반드시 제출해야 합니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9889712?hl=ko#app_requirements))

#### 3.2.7 개인정보처리방침
> **수익 창출 -> 정책 -> 앱 콘텐츠 -> 개인정보처리방침  에서 개인정보 처리방침주소를 추가해야 합니다.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.8.png" alt="store_3.2.8" width="70%"/></kbd>

- 타겟층에 만 13세 미만 어린이가 포함되어 있는 경우 개인정보처리방침을 추가해야 합니다([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9859455?hl=ko#privacy_policy))
- 민감한 사용자 및 기기 데이터를 어떻게 취급하는지 투명하게 알리기 위해 스토어 등록정보에 개인정보처리방침을 추가 합니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/topic/9877467))

#### 3.2.8 데이터 보안 (선택)
> **필수로 해야되는 항목이 아닙니다.사용자가 엡의 데이터 수집 및 공유 방식을 이해하도록  각 수집 항목에 대해 설명정의를 하도록 합니다.**
- **개요**<br/> <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7.png" alt="store_3.2.7" width="70%"/></kbd>

- **데이터 수집 및 보안**<br/> <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-1.png" alt="store_3.2.7-1" width="70%"/></kbd><br/>

| 메뉴 | 설명 |      
|--|--|      
| 앱에서 필수 사용자 데이터 유형을 수집하거나 공유하나요? | **공개해야 하는 필수 사용자 데이터 유형의 목록에 포함된 데이터**를 수집할 경우 '**예**' 를 선택해야 합니다. ([자세히 알아보기]((https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#types&zippy=%2C%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%9C%A0%ED%98%95) ))  |      
|앱에서 수집하는 모든 사용자 데이터를 암호화하여 전송하나요?|**사용자 데이터를 암호화 안하고 평문**으로 전송시에 리젝이 될수 있으니 약관을 참고 해야 합니다. ([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#other) )|      
|사용자가 데이터 삭제를 요청할 수 있는 방편을 제공하나요?|개인정보는 탈퇴 등 방법으로 삭제가 가능해야 됩니다. ([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#other) )  |

- **데이터 유형**<br/> <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-2.png" alt="store_3.2.7-2" width="90%"/></kbd> <br/>[공개해야 하는 필수 사용자 데이터 유형의 목록](https://support.google.com/googleplay/android-developer/answer/10787469?hl=ko#types&zippy=%2C%EB%8D%B0%EC%9D%B4%ED%84%B0-%EC%9C%A0%ED%98%95)에 포함된 데이터에 대해 수집하는것을 선택해 줍니다.

- **데이터 사용량 및 처리**<br/> <kbd width="80%"><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-3.png" alt="store_3.2.7-3" /></kbd><br/> 선택된 데이터 수집 항목들이 어떤 용도로 쓰이는지, 외부로 공유되는지 명시하도록 합니다.<br/> <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.2.7-4.png" alt="store_3.2.7-4" width="70%"/></kbd> <br/>

| 메뉴 | 설명 |      
|--|--|      
| 데이터를 수집 또는 공유하나요? 아니면 수집과 공유를 모두 하나요? | 앱내에서 서버전달없이 로컬에서만 사용 할 경우, 수집하여 타사로 전달만 할경우 '**공유됨**'을 선택, <br/>기타 자체서버로 수집하는 경우는 '**수집됨**'을 선택 합니다. |      
|이 데이터는 임시로 처리되나요?|메모리에 임시로 저장하고 잃어버리는 휘발성 데이터일 경우 '**예, 수집된 데이터가 임시적으로 처리됩니다**'을 선택 합니다.|      
|이 데이터는 앱에 필수인가요? 아니면 사용자가 수집 여부를 선택할 수 있나요?|사용자가 수집여부를 선택할수 있으면 '**사용자가 데이터의 수집 여부를 선택할 수 있습니다**'를 선택|      
|이 사용자 데이터가 수집되는 이유는 무엇인가요? | 수집되는 목적을 다중으로 선택 하면 됩니다.|

### 3.3 스토어 설정
> 성장 -> 앱 정보 -> 스토어 설정 에 있으며 앱의 카테고리, 태그 및 사용자에게 표시되는 개발자 정보를 편집합니다.
>
<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.3.png" alt="store_3.3" width="100%"/></kbd>

|메뉴| 설명  |    
|--|--|    
| 앱 또는 게임 | 게임인지 앱인지 선택 합니다. |    
| 카테고리 | 앱의 서비스 타입에 따라 금융,교육,만화,도구,소셜 등 카테고리에서 하나를 선택|    
| 태그 | 총 5 개의 태그를 선택할 수 있으며 선택된 태그에 따라 Google Play 에서 앱이 표시되는 위치 또는 추천 앱 위치, 사용자 검색등이 달라집니다.([자세히 알아보기](https://support.google.com/googleplay/android-developer/answer/9859673?visit_id=637871810000164338-3206709530&rd=1))|    
| 이메일 주소, 전화번호 ,웹사이트| 스토어에서 사용자에게 표시되는 정보 입니다.|

### 3.4 기본 스토어 등록정보
> 스토어 상세화면에서 보여지는 앱의 이름,소개,이미지 등 정보.

#### 3.4.1 앱 세부정보
> 스토어 상세화면에서 보여지는앱이름, 간략 소개, 상세 소개 입력.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.4.1.png" alt="store_3.4.1" width="100%"/></kbd>

|메뉴|설명  |    
|--|--|    
| 앱 이름 | 플레이스토어 앱 상세화면에 표시될 앱이름 입니다. |    
| 간단한 설명 | 앱 검색시 앱 하단에 간략하게 앱의 기능을 설명함.상세 클릭시 앱정보에서 해당 문구가 표시되며, 상세 보기 클릭시 상세화면의 제일 첫 줄에 표시 됩니다.|    
|자세한 설명| 앱 상세 클릭시 앱 정보의 상세 메시지가 출력 됩니다.|    
입력 내용은  [메타데이터 정책](https://support.google.com/googleplay/android-developer/answer/9898842)을 준수해야 합니다.

#### 3.4.2 그래픽
>스토어 상세화면에서 보여지는 앱 아이콘 ,스크린샷 ,커버이미지.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.4.2-2.png" alt="store_3.4.1" width="100%"/></kbd>    
<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.4.2-1.png" alt="store_3.4.1" width="100%"/></kbd>    
|메뉴|설명  |    
|--|--|    
|앱 아이콘|  앱 검색시 google play store 에 노출되는 아이콘<br/>앱 아이콘은 투명한 PNG 또는 JPEG, 최대 1MB, 512px X 512px이어야 하며 [디자인 사양](https://developer.android.com/google-play/resources/icon-design-specifications) 및 [메타데이터 정책](https://support.google.com/googleplay/android-developer/answer/9898842)을 준수해야 합니다.|    
|그래픽 이미지|Google Play Store 의 앱 소개나, 카카오톡 앱 공유시 썸네일등에 노출될 이미지<br/>그래픽 이미지는 PNG 또는 JPEG, 최대 1MB, 1024px X 500px 입니다.|    
|휴대전화 스크린샷| 전화 업로드된 이미지는 Google Play Store 화면에 설치 버튼 하단에 스냅샷이미지로 노출<br/>휴대전화 스크린샷 2~8장 . 스크린샷은 PNG 또는 JPEG, 장당 최대 8MB, 가로세로 비율 16:9 또는 9:16, 가로세로 길이는 320px X 3840px 사이 입니다.|


|스토어 검색시|스토어 상세 화면  |앱 상세 화면 더보기|    
|--|--|--|    
| <kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.4.1-1.jpeg" alt="store_3.4.1-1" width="100%"/></kbd> |<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.4.1-2.jpeg" alt="store_3.4.1-2" width="100%"/></kbd>|<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_3.4.1-3.jpeg" alt="store_3.4.1-3" width="100%"/></kbd>|

## 4. 테스트
> Google Play Console 테스트 기능을 확인하고 정리합니다.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.png" alt="store_4" width="100%"/></kbd>


|타입 | 설명 |  
|--|--|  
| 공개 테스트 | 대상: <br/> - 실제 유저가 직접 참여 가능 <br/>- 등록한 테스터 그룹 참여 가능<br/>특징:<br/> - 실제 유저 즉 **누구나 Google Play를 통해** 출시 전 버전을 테스트 참여를 가능하게 함<br/>- 앱 등록시 스토어 **심사를 하게 됩니다.**|  
|비공개 테스트| 대상: <br/>- 등록한 테스터 그룹 참여 가능 <br/>특징:<br/>- 트랙을 만들어 **자체 지정 테스터 그룹**에 테스트 참여를 가능하게 함<br/>- 앱 등록시 스토어 **심사를 하게 됩니다.**|  
|내부 테스트| 대상: <br/>- **등록한 테스터 그룹** 참여 가능 <br/>특징:<br/>- 앱 등록시 스토어 **심사를 하지 않습니다.**|

([자세히 알아보기](https://play.google.com/console/about/opentesting/))

###  

### 4.1 공개 테스트
> 공개 테스트 버전은 Google Play 에서 테스터에게 제공(대규모의 그룹). 사용자는 스토어 등록정보를 통해 테스트에 참여.

#### 4.1.1 국가/지역
> 공개 테스트로 배포할 지역을 설정.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.1.1.png" alt="store_4.1.1" width="100%"/></kbd>

프러덕션이 버전과 국가/지역 설정을 동기화 할수 있고 자체로 지정 할 수 있습니다.


#### 4.1.2 테스터
> 공개 테스트에 참여할 테스터 제한과 참여 방법.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.1.2.png" alt="store_4.1.2" width="100%"/></kbd>

|메뉴| 설명  |  
|--|--|  
|테스터  | 참여인원수를 무제한 혹은 제한 할수 있음, 제한 할 경우 최소 1,000명이상 입니다.|  
|의견 URL 또는 이메일 주소| 의견을 받은 사이트 주소나 이메일 주소 입력 합니다.|  
| Android에서 참여| 스토어에서 바로 참여 할 수 있는 링크 복사 합니다. |  
| 웹에서 참여| 웹에서 참여 확인 할 수 있는 링크 복사 합니다. |

- Android에서 참여 할때 **반드시 요청한 이메일이 폰의 Google Playstore 에 로그인 되어 있어야** 테스트모드로 접근 가능 합니다 .
- 웹에서 참여 할때 방문한 페이지에 구글계정은 **반드시 테스트 요청한 이메일로 로그인한 상태**여야 **참여 수락**을 하거나 **참여 취소**할 수 있습니다.



### 4.2 비공개 테스트
> 자체 테스터 그룹을 대상으로 트랙별로 테스트.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.2.png" alt="store_4.2" width="100%"/></kbd>

구분하기 위해 트랙명을 입력하여 트랙을 생성  합니다.

#### 4.2.1 국가/지역

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.2.1.png" alt="store_4.2.1" width="100%"/></kbd>

프러덕션이 버전과 국가/지역 설정을 동기화 할수 있고 자체로 지정 할 수 있습니다.

#### 4.2.2 테스터
> 비공개 테스트에 참여할 테스터 설정과 참여 방법.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.2.2.png" alt="store_4.2.2" width="100%"/></kbd>

|메뉴| 설명  |  
|--|--|  
|테스터  | - 테스터 이메일 목록으로 관리 중인 리스트 선택([목록 만들기 자세히 알아보기](#4.4-테스터-이메일-목록-만들기))<br/>- 내가 지정한 Google 그룹스에 속한 사용자만 테스트에 참여 가능 합니다.<br/>|  
|의견 URL 또는 이메일 주소| 의견을 받은 사이트 주소나 이메일 주소 입력 합니다.|  
| Android에서 참여| 스토어에서 바로 참여 할 수 있는 링크 복사 합니다. |  
| 웹에서 참여| 웹에서 참여 확인 할 수 있는 링크 복사 합니다.|


- Android에서 참여 할때 **반드시 요청한 이메일이 폰의 Google Playstore 에 로그인 되어 있어야** 테스트모드로 접근 가능 합니다.
- 웹에서 참여 할때 방문한 페이지에 구글계정은 **반드시 테스트 요청한 이메일로 로그인한 상태**여야 **참여 수락**을 하거나 **참여 취소**할 수 있습니다.


### 4.3 내부 테스트
> 내부 테스터를 지정하여 심사없이 앱을 테스트.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.3.png" alt="store_4.3" width="100%"/></kbd>

#### 4.3.1 테스터
> 내부 테스트에 참여할 테스터 설정과 참여 방법.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.3.1.png" alt="store_4.3.1" width="100%"/></kbd>

|메뉴| 설명  |  
|--|--|  
|테스터  |  테스터 이메일 목록으로 관리 중인 리스트 선택 합니다.([목록 만들기 자세히 알아보기](#4.4-테스터-이메일-목록-만들기))|  
|의견 URL 또는 이메일 주소| 의견을 받은 사이트 주소나 이메일 주소 입력 합니다.|  
| 웹에서 참여| 웹에서 참여 확인 할 수 있는 링크 복사 합니다.|


-  **반드시 요청한 이메일이 폰의 Google Playstore 에 로그인 되어 있어야** 테스트모드로 접근 가능 합니다 .
- 웹에서 참여 할때 방문한 페이지에 구글계정은 **반드시 테스트 요청한 이메일로 로그인한 상태**여야 **참여 수락**을 하거나 **참여 취소**할 수 있습니다.

### 4.4 테스터 이메일 목록 만들기
> 테스터들의 이메일 목록 추가.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.4.png" alt="store_4.4" width="100%"/></kbd>

|메뉴| 설명 |  
|--|--|  
| 목록 이름 | 이메일 목록 그룹을 구분하기 위한 이름 입니다.|  
| 이메일 주소 추가 | **폰의 PlayStore 나 브라우저에 로그인 되어 있는 이메일주소**를 제공해야 합니다,그래야만 참여요청 할때 Android 혹은 웹으로 초대 할때 해당 이메일로 로그인한 상태에서만 수락이나 거절 등 관리를 할 수 있습니다.|



### 4.5 버전 bundle 혹은 APK 등록 출시
> 테스트로 등록할 버전 bundle등록 .


#### 4.5.1 버전 세부정보 와 App Bundle 등록

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.5.png" alt="store_4.5" width="100%"/></kbd>

|메뉴| 설명 |  
|--|--|  
| App Bundle(혹은 apk) | - 이미 추가 했던 버전이라면 라이브러리에서 추가 합니다.<br/>- 처음으로 등록하는 버전이면 드래그해서 앱파일을 등록 합니다. |  
|출시 노트| 스토어에 게시될 버전 업그레이드 안내 내용 입니다.|

출시 노트를 적은후에 **저장&버전 검토**를 눌러 다음단계로 이동 합니다.

####  4.5.2 검토 결과 확인 및 출시

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.5.1-1.png" alt="store_4.5.1-1" width="100%"/></kbd>

이미지와 같이 **오류** 사항이 없으면 출시 가능한 상태 입니다.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.5.2.png" alt="store_4.5.2" width="100%"/></kbd>

배포타입에 따라 **출시율** 설정이 있고 없으면 안해도 됩니다.
**출시율**은 이미 설치한 유저수 대비 퍼센테지만큼의 유저한테 출시를 할지 정합니다.



<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.5.1.png" alt="store_4.5.1" width="100%"/></kbd>

등록 완료 하면 이미지와 같이 **검토 중**으로 나옴.  
(내부 테스트 외에 모두 심사가 필요하기에 다소 시간이 걸립니다. 심사 시간은 **심사정책에 따라 30분~7일까지 차이**가 있을수 있음)

### 4.6 테스트 참여
> 테스트 참여 방법을 가이드.

#### 4.6.1 내부앱 공유 설정
> 테스트 목록명으로 테스트에 참여가 될때에는 내부앱 공유 설정해야 됩니다.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.6.1.jpeg" alt="store_4.6.1" width="100%"/></kbd>

- PlayStore에서 기존 버전 어플을 다운받은 후, 플레이스토어 설정에 들어가 **PlayStore 버전을 7번 탭**하면 아래의 오른쪽과 같이 내부 앱 공유 버튼이 생성되고, **내부 앱 공유를 활성화**  합니다.

#### 4.6.2 초대 수락 혹은 취소

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.6.1-1.jpeg" alt="store_4.6.1-1" width="100%"/></kbd>


- 그 후, 메일로 전송된 링크 혹은 전달 받은 테스트 링크를 열어 보면  왼쪽 이미지와 같은 페이지로 연결되고, **초대 수락**을 클릭합니다. 그러면 오른쪽과 같은 페이지가 됩니다.
- 혹은 오른쪽 그림처럼 수락후에 프로그램 종료로 테스트 참여 취소를 할수 있습니다.

#### 4.6.3 결과 확인

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw/store_4.6.1-2.jpeg" alt="store_4.6.1-2" width="100%"/></kbd>

- 혹시, 베타버전 테스트를 수락하였는데 플레이 **스토어에서 베타 버전이 검색이 안되는 경우** **플레이 스토어 앱의 캐시를 삭제**하고 실행해 보면 테스트 버전이 잘 검색됩니다.
- 기존 버전을 다운받고 싶으면 메일에 있는 **프로그램 종료**를 클릭하고 다시 플레이 스토어에서 검색을 하면 기존 버전으로 검색이 됩니다.





