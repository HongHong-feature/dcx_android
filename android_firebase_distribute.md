

# Firebase Console (Android 앱 테스트 등록)
>  **Frirebase App Distribution 을 통해 앱을 테스트 하는 내용을 정리하여 공유**
> 주소: https://console.firebase.google.com/

## 목차

## 1. App Distribution 메뉴 설명
> **App Distribution의 주요 메뉴에 대해 소개 합니다.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/firebase_1.png" alt="firebase_1" width="35%"/></kbd>


|메뉴명 | 설명  |          
|--|--|          
| 출시버전 | 테스트 예정인 앱 파일(aab 혹은 apk 형태)을 등록할수있는 화면입니다.<br/>혹은 이전에 테스트 출시한 버전의 참여상태등 확인 가능합니다.  |          
|초대링크 |  테스트 그룹에 대한 초대링크를 생성 및 관리를 하는 페이지 입니다.|
|테스터 및 그룹| 테스터를 등록하고 테스터를 그룹별로 생성 및 관리하는 페이지 입니다.|

### 1.1 테스터 등록
> **테스터를 등록하고 테스트 그룹을 만드는 방법을 가이드 합니다.**

#### 1.1.1 그룹 추가
> **그룹은  테스터목록을 그룹별로 관리하기 위함입니다.**

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/fireabse_1.1-1.png" alt="firebase_1.1-1" width="100%"/></kbd>

- **그룹 추가** 버튼을 눌러 **그룹명을 입력**하고 **저장**을 눌러 그룹을 추가합니다.
- 그룹은  테스터목록을 그룹별로 관리하기 위함이고 **그룹명은 테스터리스트 구분가능한 용도로**만 지어주면 됩니다.

#### 1.1.2 테스터 등록
> **테스트를 하기 위한 대상등록하기**

#### 1.1.2.1 직접 입력하여 하나씩 등록
<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/firebase_1.1-3.png" alt="firebase_1.1-3" width="100%"/></kbd>

테스트 추가 를 클릭하여 **테스트하려는 대상의 이메일**을 입력합니다.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/firebase_1.1-2.png" alt="firebase_1.1-2" width="100%"/></kbd>

입력후 **Enter**를 누르면 해당 그룹에 테스터 추가가 완료됩니다.

#### 1.1.2.2 CSV파일형태로 입력된 메일들을 등록

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/firebase_1.1.2-1.png" alt="firebase_1.1.2-1" width="100%"/></kbd>

그룹에 테스터 가져오기를 누릅니다.

<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/firebase_1.1-4.png" alt="firebase_1.1.4" width="100%"/></kbd>


CSV 파일은 **이메일만 입력하여 생성**합니다.


<kbd><img src="https://raw.githubusercontent.com/HongHong-feature/dcx_android/master/raw2/firebase_1.1.2-2.png" alt="firebase_1.1.2-2" width="100%"/></kbd>

**CSV 파일을 드래그** 하여 업로드하여 **가져오기**를 클릭하면 테스트 등록 완료 됩니다.


