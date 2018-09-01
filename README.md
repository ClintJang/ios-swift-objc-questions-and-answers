# iOS(Swift, Objc) 자주하는 질문과 답변 모음

## 소개
iOS (swift, objc)개발을 하면서 알게된 질문과 답변 내용을 모아보았습니다. 개발 언어는 공부를 하면 빠르게 익힐 수 있지만, 개발 경험은 물어보고 정보를 얻기가 쉽지 않습니다. 도움이 될 수 있도록 정리를 꼼꼼히 해보겠습니다.

잘못 작성된 정보는 열심히 수정 하겠습니다. 언제든지 문제가 있으면, 편하게 수정해주세요. 

지금은 작성을 시작해서 내용이 적지만, 알차게 계속 업데이트 하겠습니다.

## 주요 목차
- [개발입문](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B0%9C%EB%B0%9C%EC%9E%85%EB%AC%B8)
- [appstore](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#appstore)
- [Xcode](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#xcode)
- [시뮬레이터](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0)
- [reject](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#reject)
- [라이브러리 사용](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9)

## 질문과 답변
### 개발입문
#### Swift 공부할 때 보면 좋은 책은 어떤 것이 있을 까요?
- 개인적으로 바이블과 스토리진행을 따라해보는 2가지가 있을 것 같은데요. 
	- 바이블 쪽이면 : **`스위프트 프로그래밍: Swift4 객체지향, 함수형, 프로토콜 지향 패러다임까지 한 번에! 2판`** 을 검색해보시면 좋은 것 같습니다.
	- 스토리 진행이면 : **`꼼꼼한재은씨의 스위프트 실전편`** 이 좋다는 말은 들었었고, 요즘에는 다양한 책들이 있는 것 같습니다. 알게 되는 책들이 있으면 업데이트 하겠습니다. 

#### Swift 개발을 처음 시작할 때 공부하기 좋은 링크 가 있을 까요?
- 개인적으로 [야곰님의 유투브](https://www.youtube.com/channel/UCkwWWEv3C-3ToeO57r5LCHQ?app=desktop), &nbsp; [야곰님의 동영상 강의](https://www.inflearn.com/course/ios-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D/), &nbsp; [인프런 스탠퍼드 강의](https://www.inflearn.com/course/stanford-ios-%ED%95%9C%EA%B8%80%EC%9E%90%EB%A7%89-%EA%B0%95%EC%9D%98/), &nbsp; [프로그래머스의 iOS swift입문](https://programmers.co.kr/learn/courses/4)이 좋다고 생각합니다.
- [swift 한국어 동영상 강의 링크 모음](https://github.com/ClintJang/awesome-swift-korean-lecture/blob/master/README.md) 은 개인적으로 모아둔 링크입니다.

#### Objective C 공부할 좋은 방법이 있나요?
- **`아론 힐리가스의 오브젝티브-C 프로그래밍`** 책을 검색해 보세요, 국내에서는 이정도가 좋은 것 같습니다.

### AppStore
#### AppStore에 검수 신청하면 얼마나 걸리나요?
- [App review Times](http://appreviewtimes.com/) : 현재 검수 시간이 평균적으로 얼마나 걸리는 지 정보를 제공해줘서 대략적인 판단을 할 수 있게 해주는 사이트 입니다.
- 보통 케바케라서 정확하지 않습니다. 평균적인 시간보다 오래 걸린다면, 검수 진행에 대해 문의를 진행해 해보시면 될 것 같습니다. 

#### 앱스토어를 등록하기 전에 UUID(디바이스) 등록 안된 분들이 테스트 해볼려면 어떻게 해야될 까요?
1. 개인 및 법인 계정이라면 : [Apple TestFlight](https://developer.apple.com/testflight/) 가 있습니다. 
	- 구글에서 "TestFlight 사용법" 으로 검색을 해보셔요.
2. 기업(Enterprice) 계정이라면 : 디바이스 등록없이 기업내 배포가 가능합니다. 단, 자사 외의 다른 목적으로 배포시 계정이 블락 될 수 있습니다. (알고 계시는 분들이 애플에 신고도 가능할 수 있어요~)

### Xcode 
#### Xcode에서 자동완성이 안될 때는?
- Xcode clean, Xcode 재 실행
- 재부팅
- derivedData 를 제거해보기 
	- xcode deriveddata clean 정도로 구글 검색해보셔요. 

### 시뮬레이터
#### 시뮬레이터 재설정 하는 방법은?
1. 시뮬레이터 실행 후 왼쪽 상단 메뉴에서 중에서 

```
Hardware -> Erase All Content and Settings..  
```
2. 팝업에서 Erase 를 선택하시면됩니다.

### Reject
> 1. 기본적인 검수 진행은 진행되는 사항 중 중요한 정보들은 메일로 받아져 있을 것 입니다. 메일함을 우선 확인해 봅시다 😁<br />
2. 검수자에 따라 케바케로 검수결과가 달라질 수 있습니다. 항상 통과되던 앱이 이번에 왜 리젝된거지? 하고 당황하지 말고 리젝 내용을 확인해보세요.<br />
3. [App Store 심사 지침 가이드 라인](https://developer.apple.com/kr/app-store/review/guidelines/)은 계속 변합니다. 아래 내용도 시간이 지나면 달라질 수 있습니다.<br />

#### 로그인을 하기위해 정보(전호번호등..)가 필요하다고 리젝 당했습니다. 😭
- 데모계정(앱을 잘 볼수 있는 계정, 아이디와 패스워드등)을 제공하여 검수자가 로그인을 진행할 수 있게 하면 됩니다. 혹은 그 해당 메일에서 받은 내용을 디테일하게 대응하셔도 됩니다. 로그인 관련 부분이라면 데모계정을 제공하면 문제가 생기지 않을 것입니다.

#### 쇼셜(SNS) 로그인만 있으면 리젝 당하나요?
- 소셜 기능이 전혀 없는데 소셜로그인을 강요하면 (대안이 없으면) 리젝당합니다. 예를들면 페이스북 관련 기능이 필수로 있는게 아니면 리젝 입니다.
- 저는 오래됬지만, 비회원으로 앱을 이용할 수 있는 기능을 추가했습니다. 필요한 기능의 경우에 로그인 해서 이용하도록 하니 통과 되었었던 기억이 있습니다. 

#### 비디오에 대한 링크를 제공하라는 데? 무슨 의미일까요?
- 데모비디오를 제공하라는 이야기입니다. 리뷰어에 따라 다르지만, 구동하는 부분을 앱 실행해서는 확인 할 수 없다 판단되면 연동되는 실행되는 동영상을 찍어서 리뷰어가 확인 할 수 있게 해주면 됩니다.
- 예를 들어, 시연하는 동영상을 찍고, 그것을 유투브에 업로드하고 링크제공하면 되겟죠.

#### 웹뷰로만 된 앱은 리젝인가요?
- 웹만 있는 기능을 단순한게 웹뷰로 감싸서 앱으로 올린 앱은 리젝을 당할 가능성이 매우 높다고 생각됩니다. 리뷰어가 판단하기에 앱의 기능이 하나라도 있어서 앱으로 만들어 올렸다 라는 차이점을 주어야 될 것 같습니다.
- 예를 들어 화면 비중을 일부라도 네이티브로 한다던지..
- 예를 들어 푸시 기능을 추가한다던지..
- 리뷰어에게 설명할 수 있는 네이티브 기능이 있어야 할 것 입니다.

### 라이브러리 사용

#### 라이브러리 사용을 하려면 어떻게 해야 되나요?
- [Cocoapods](https://github.com/ClintJang/cocoapods-tips/blob/master/README.md)를 추천드립니다. 
	- [Cocoapods 사용 팁](https://github.com/ClintJang/cocoapods-tips/blob/master/README.md) 링크입니다.
	- 처음이라 어떻게 해야될 지 막막하시다면 [하울님의 코딩채널](https://www.youtube.com/playlist?list=PLmdU__e_zPf-uiDtI84Gv9SxFicrbw4KV)을 추천드립니다.
- Carthage(카르타고) 라는 비슷한 방식도 있습니다. 워크스페이스를 만드는 방식이 아닌 Embbed Framework를 이용하는 방식이죠.


<br /><br /><br />즐거운 하루 되세요 🙇‍
<br />
