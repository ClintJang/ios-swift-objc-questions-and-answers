# iOS(Swift, Objc) 자주하는 질문과 답변 모음

## 소개
iOS (swift, objc)개발을 하면서 알게된 질문과 답변 내용을 모아보았습니다. 개발 언어는 공부를 하면 빠르게 익힐 수 있지만, 개발 경험은 물어보고 정보를 얻기가 쉽지 않습니다. 도움이 될 수 있도록 정리를 꼼꼼히 해보겠습니다.

잘못 작성된 정보는 열심히 수정 하겠습니다. 언제든지 문제가 있으면, 편하게 수정해주세요. 

지금은 작성을 시작해서 내용이 적지만, 알차게 계속 업데이트 하겠습니다.

## <font color="blue">주요 목차</font>
- [개발입문](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B0%9C%EB%B0%9C%EC%9E%85%EB%AC%B8)
- [appstore](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#appstore)
- [Xcode](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#xcode)
- [시뮬레이터](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0)
- [reject](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#reject)
- [라이브러리 사용](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9)

## <font color="red">질문과 답변</font>
### 개발입문
#### Swift 개발을 처음 시작할 때 좋은 링크 가 있을 까요?
- 개인적으로 [야곰님의 유투브](https://www.youtube.com/channel/UCkwWWEv3C-3ToeO57r5LCHQ?app=desktop), &nbsp; [야곰님의 동영상 강의](https://www.inflearn.com/course/ios-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D/), &nbsp; [인프런 스탠퍼드 강의](https://www.inflearn.com/course/stanford-ios-%ED%95%9C%EA%B8%80%EC%9E%90%EB%A7%89-%EA%B0%95%EC%9D%98/), &nbsp; [프로그래머스의 iOS swift입문](https://programmers.co.kr/learn/courses/4)이 좋다고 생각합니다.
- [swift 한국어 동영상 강의 링크 모음](https://github.com/ClintJang/awesome-swift-korean-lecture/blob/master/README.md)

#### Objective C 공부할 좋은 방법이 있나요?
- "아론 힐리가스의 오브젝티브-C 프로그래밍" 책을 검색해 보세요, 국내에서는 이정도가 좋은 것 같습니다.

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
> 기본적인 검수 진행은 진행되는 사항 중 중요한 정보들은 메일로 받아져 있을 것 입니다. 메일함을 우선 확인해 봅시다 😁


### 라이브러리 사용

#### 라이브러리 사용을 하려면 어떻게 해야 되나요?
- [Cocoapods](https://github.com/ClintJang/cocoapods-tips/blob/master/README.md)를 추천드립니다. 
	- [Cocoapods 사용 팁](https://github.com/ClintJang/cocoapods-tips/blob/master/README.md) 링크입니다.
	- 처음이라 어떻게 해야될 지 막막하시다면 [하울님의 코딩채널](https://www.youtube.com/playlist?list=PLmdU__e_zPf-uiDtI84Gv9SxFicrbw4KV)을 추천드립니다.
- Carthage(카르타고) 라는 비슷한 방식도 있습니다. 워크스페이스를 만드는 방식이 아닌 Embbed Framework를 이용하는 방식이죠.


<br /><br /><br />즐거운 하루 되세요 🙇‍
<br />
