# iOS(Swift, Objc) 질문과 답변 모음

## **소개**
iOS (swift, objc)개발을 하면서 알게된 질문과 답변 내용을 모아보았습니다. 개발 언어는 공부를 하면 빠르게 익힐 수 있지만, 개발 경험은 물어보고 정보를 얻기가 쉽지 않습니다. 도움이 될 수 있도록 정리를 꼼꼼히 해보겠습니다.

잘못 작성된 정보는 열심히 수정 하겠습니다. 언제든지 문제가 있으면, 편하게 수정해주세요. 

지금은 작성을 시작해서 내용이 적지만, 알차게 계속 업데이트 하겠습니다.<br />
디테일한 지식 보다는 iOS 개발을 하면서 이정도는 알고 있으면 좋은...<br />
정도의 질문과 답변 형식으로 정리 하려고 합니다. 

## **목차**
- **[1. 개발입문](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#1-%EA%B0%9C%EB%B0%9C%EC%9E%85%EB%AC%B8)**
	- [Swift 공부할 때 보면 좋은 책은 어떤 것이 있을 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#swift-%EA%B3%B5%EB%B6%80%ED%95%A0-%EB%95%8C-%EB%B3%B4%EB%A9%B4-%EC%A2%8B%EC%9D%80-%EC%B1%85%EC%9D%80-%EC%96%B4%EB%96%A4-%EA%B2%83%EC%9D%B4-%EC%9E%88%EC%9D%84-%EA%B9%8C%EC%9A%94)
	- [Swift 개발을 처음 시작할 때 공부하기 좋은 링크 가 있을 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#swift-%EA%B0%9C%EB%B0%9C%EC%9D%84-%EC%B2%98%EC%9D%8C-%EC%8B%9C%EC%9E%91%ED%95%A0-%EB%95%8C-%EA%B3%B5%EB%B6%80%ED%95%98%EA%B8%B0-%EC%A2%8B%EC%9D%80-%EB%A7%81%ED%81%AC-%EA%B0%80-%EC%9E%88%EC%9D%84-%EA%B9%8C%EC%9A%94)
	- [Objective C 공부할 좋은 방법이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#objective-c-%EA%B3%B5%EB%B6%80%ED%95%A0-%EC%A2%8B%EC%9D%80-%EB%B0%A9%EB%B2%95%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	- [처음 개발에 입문 했는 데, 좋은 커뮤니티가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%B2%98%EC%9D%8C-%EA%B0%9C%EB%B0%9C%EC%97%90-%EC%9E%85%EB%AC%B8-%ED%96%88%EB%8A%94-%EB%8D%B0-%EC%A2%8B%EC%9D%80-%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%EA%B0%80-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [ios 공부할만한 깃헙 프로젝트 혹시 추천해주실 수 있나요? 독학하는데 가이드가 없으니 힘드네용 알려주시면 감사하겠습니다](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#ios-%EA%B3%B5%EB%B6%80%ED%95%A0%EB%A7%8C%ED%95%9C-%EA%B9%83%ED%97%99-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%98%B9%EC%8B%9C-%EC%B6%94%EC%B2%9C%ED%95%B4%EC%A3%BC%EC%8B%A4-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94-%EB%8F%85%ED%95%99%ED%95%98%EB%8A%94%EB%8D%B0-%EA%B0%80%EC%9D%B4%EB%93%9C%EA%B0%80-%EC%97%86%EC%9C%BC%EB%8B%88-%ED%9E%98%EB%93%9C%EB%84%A4%EC%9A%A9-%EC%95%8C%EB%A0%A4%EC%A3%BC%EC%8B%9C%EB%A9%B4-%EA%B0%90%EC%82%AC%ED%95%98%EA%B2%A0%EC%8A%B5%EB%8B%88%EB%8B%A4)

- **[2. appstore](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#2-appstore)**
	- [애플 개발자 전화 지원은 몇번인가요? 전화가 가능한가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%A0%ED%94%8C-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EC%A0%84%ED%99%94-%EC%A7%80%EC%9B%90%EC%9D%80-%EB%AA%87%EB%B2%88%EC%9D%B8%EA%B0%80%EC%9A%94-%EC%A0%84%ED%99%94%EA%B0%80-%EA%B0%80%EB%8A%A5%ED%95%9C%EA%B0%80%EC%9A%94)
	- [AppStore에 검수 신청하면 얼마나 걸리나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#appstore%EC%97%90-%EA%B2%80%EC%88%98-%EC%8B%A0%EC%B2%AD%ED%95%98%EB%A9%B4-%EC%96%BC%EB%A7%88%EB%82%98-%EA%B1%B8%EB%A6%AC%EB%82%98%EC%9A%94)
	- [앱스토어를 등록하기 전에 UUID(디바이스) 등록 안된 분들이 테스트 해볼려면 어떻게 해야될 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%B1%EC%8A%A4%ED%86%A0%EC%96%B4%EB%A5%BC-%EB%93%B1%EB%A1%9D%ED%95%98%EA%B8%B0-%EC%A0%84%EC%97%90-uuid%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4-%EB%93%B1%EB%A1%9D-%EC%95%88%EB%90%9C-%EB%B6%84%EB%93%A4%EC%9D%B4-%ED%85%8C%EC%8A%A4%ED%8A%B8-%ED%95%B4%EB%B3%BC%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%EB%90%A0-%EA%B9%8C%EC%9A%94)
	- [정말 급하게 앱스토어에 등록해야되는 데.. 어떻게 해야될 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%A0%95%EB%A7%90-%EA%B8%89%ED%95%98%EA%B2%8C-%EC%95%B1%EC%8A%A4%ED%86%A0%EC%96%B4%EC%97%90-%EB%93%B1%EB%A1%9D%ED%95%B4%EC%95%BC%EB%90%98%EB%8A%94-%EB%8D%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%EB%90%A0-%EA%B9%8C%EC%9A%94)
	- [검수통과해서 "판매 준비됨"으로 바뀌었는 데, 왜? iOS 앱스토어에서 검색하면 나타나지 않을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B2%80%EC%88%98%ED%86%B5%EA%B3%BC%ED%95%B4%EC%84%9C-%ED%8C%90%EB%A7%A4-%EC%A4%80%EB%B9%84%EB%90%A8%EC%9C%BC%EB%A1%9C-%EB%B0%94%EB%80%8C%EC%97%88%EB%8A%94-%EB%8D%B0-%EC%99%9C-ios-%EC%95%B1%EC%8A%A4%ED%86%A0%EC%96%B4%EC%97%90%EC%84%9C-%EA%B2%80%EC%83%89%ED%95%98%EB%A9%B4-%EB%82%98%ED%83%80%EB%82%98%EC%A7%80-%EC%95%8A%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [appstore에서 앱 다운로드 할때 단말별로 앱사이즈가 다른가요?? 이미지 해상도라던지.. 차이때문에, 만약에 다르다면 영향 받는 부분이 어디일까요?
](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#appstore%EC%97%90%EC%84%9C-%EC%95%B1-%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C-%ED%95%A0%EB%95%8C-%EB%8B%A8%EB%A7%90%EB%B3%84%EB%A1%9C-%EC%95%B1%EC%82%AC%EC%9D%B4%EC%A6%88%EA%B0%80-%EB%8B%A4%EB%A5%B8%EA%B0%80%EC%9A%94-%EC%9D%B4%EB%AF%B8%EC%A7%80-%ED%95%B4%EC%83%81%EB%8F%84%EB%9D%BC%EB%8D%98%EC%A7%80-%EC%B0%A8%EC%9D%B4%EB%95%8C%EB%AC%B8%EC%97%90-%EB%A7%8C%EC%95%BD%EC%97%90-%EB%8B%A4%EB%A5%B4%EB%8B%A4%EB%A9%B4-%EC%98%81%ED%96%A5-%EB%B0%9B%EB%8A%94-%EB%B6%80%EB%B6%84%EC%9D%B4-%EC%96%B4%EB%94%94%EC%9D%BC%EA%B9%8C%EC%9A%94)
	- [미성년자는 애플 개발자 등록이 가능한가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AF%B8%EC%84%B1%EB%85%84%EC%9E%90%EB%8A%94-%EC%95%A0%ED%94%8C-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EB%93%B1%EB%A1%9D%EC%9D%B4-%EA%B0%80%EB%8A%A5%ED%95%9C%EA%B0%80%EC%9A%94)
	- [개인개발자도 앱 등록시 개인정보 취급방침 URL을 반드시 추가해야되나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B0%9C%EC%9D%B8%EA%B0%9C%EB%B0%9C%EC%9E%90%EB%8F%84-%EC%95%B1-%EB%93%B1%EB%A1%9D%EC%8B%9C-%EA%B0%9C%EC%9D%B8%EC%A0%95%EB%B3%B4-%EC%B7%A8%EA%B8%89%EB%B0%A9%EC%B9%A8-url%EC%9D%84-%EB%B0%98%EB%93%9C%EC%8B%9C-%EC%B6%94%EA%B0%80%ED%95%B4%EC%95%BC%EB%90%98%EB%82%98%EC%9A%94)
	- [스토어 스크린샷에 디바이스를 같이 보여주소 싶은데 가이드라인 같은걸 확인 할 수 있는데가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#스토어-스크린샷에-디바이스를-같이-보여주소-싶은데-가이드라인-같은걸-확인-할-수-있는데가-있을까요)
	- [앱스토어에서 앱 이름 아래에 개발자 이름을 변경하고 싶은데 따로 변경할 수 있나요? 고객센터에 문의해봐야되나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#앱스토어에서-앱-이름-아래에-개발자-이름을-변경하고-싶은데-따로-변경할-수-있나요-고객센터에-문의해봐야되나요)
	- [애플로 로그인을 하는 것을 꼭 추가해야되나요? 기존에 서드파티 로그인 기능이 있는 데, 넣어야 된다는 것 같더군요. 기능을 추가한다면 언제까지 반드시 추가해야되나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%A0%ED%94%8C%EB%A1%9C-%EB%A1%9C%EA%B7%B8%EC%9D%B8%EC%9D%84-%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%84-%EA%BC%AD-%EC%B6%94%EA%B0%80%ED%95%B4%EC%95%BC%EB%90%98%EB%82%98%EC%9A%94-%EA%B8%B0%EC%A1%B4%EC%97%90-%EC%84%9C%EB%93%9C%ED%8C%8C%ED%8B%B0-%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EA%B8%B0%EB%8A%A5%EC%9D%B4-%EC%9E%88%EB%8A%94-%EB%8D%B0-%EB%84%A3%EC%96%B4%EC%95%BC-%EB%90%9C%EB%8B%A4%EB%8A%94-%EA%B2%83-%EA%B0%99%EB%8D%94%EA%B5%B0%EC%9A%94-%EA%B8%B0%EB%8A%A5%EC%9D%84-%EC%B6%94%EA%B0%80%ED%95%9C%EB%8B%A4%EB%A9%B4-%EC%96%B8%EC%A0%9C%EA%B9%8C%EC%A7%80-%EB%B0%98%EB%93%9C%EC%8B%9C-%EC%B6%94%EA%B0%80%ED%95%B4%EC%95%BC%EB%90%98%EB%82%98%EC%9A%94)

- **[3. Xcode](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#3-xcode)**
	- [Xcode에서 자동완성이 안될 때는?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#xcode%EC%97%90%EC%84%9C-%EC%9E%90%EB%8F%99%EC%99%84%EC%84%B1%EC%9D%B4-%EC%95%88%EB%90%A0-%EB%95%8C%EB%8A%94)
	- [Xcode 10으로 올리고 나서 빌드 에러가 났는 데, 어떻게 하죠? 과거로 돌아갈 수 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#xcode-10%EC%9C%BC%EB%A1%9C-%EC%98%AC%EB%A6%AC%EA%B3%A0-%EB%82%98%EC%84%9C-%EB%B9%8C%EB%93%9C-%EC%97%90%EB%9F%AC%EA%B0%80-%EB%82%AC%EB%8A%94-%EB%8D%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%98%EC%A3%A0-%EA%B3%BC%EA%B1%B0%EB%A1%9C-%EB%8F%8C%EC%95%84%EA%B0%88-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94)
	- [작업 중인 현재 프로젝트 폴더 위치로 이동된 터미널을 띄우고 싶은 데, 혹시 Xcode 에서 가능한 방법이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9E%91%EC%97%85-%EC%A4%91%EC%9D%B8-%ED%98%84%EC%9E%AC-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%ED%8F%B4%EB%8D%94-%EC%9C%84%EC%B9%98%EB%A1%9C-%EC%9D%B4%EB%8F%99%EB%90%9C-%ED%84%B0%EB%AF%B8%EB%84%90%EC%9D%84-%EB%9D%84%EC%9A%B0%EA%B3%A0-%EC%8B%B6%EC%9D%80-%EB%8D%B0-%ED%98%B9%EC%8B%9C-xcode-%EC%97%90%EC%84%9C-%EA%B0%80%EB%8A%A5%ED%95%9C-%EB%B0%A9%EB%B2%95%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	- [아이폰 앱 로그 속도 측정하고 있는 데, 앱 런처스크린 실행하면서 시간이 많이 걸립니다. 이 부분도 설정하는 것이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%84%EC%9D%B4%ED%8F%B0-%EC%95%B1-%EB%A1%9C%EA%B7%B8-%EC%86%8D%EB%8F%84-%EC%B8%A1%EC%A0%95%ED%95%98%EA%B3%A0-%EC%9E%88%EB%8A%94-%EB%8D%B0-%EC%95%B1-%EB%9F%B0%EC%B2%98%EC%8A%A4%ED%81%AC%EB%A6%B0-%EC%8B%A4%ED%96%89%ED%95%98%EB%A9%B4%EC%84%9C-%EC%8B%9C%EA%B0%84%EC%9D%B4-%EB%A7%8E%EC%9D%B4-%EA%B1%B8%EB%A6%BD%EB%8B%88%EB%8B%A4-%EC%9D%B4-%EB%B6%80%EB%B6%84%EB%8F%84-%EC%84%A4%EC%A0%95%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	- [Swift 프로젝트의 컴파일 시간 최적화를 시키려면 어떻게 하면 좋을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#swift-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%EC%9D%98-%EC%BB%B4%ED%8C%8C%EC%9D%BC-%EC%8B%9C%EA%B0%84-%EC%B5%9C%EC%A0%81%ED%99%94%EB%A5%BC-%EC%8B%9C%ED%82%A4%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%98%EB%A9%B4-%EC%A2%8B%EC%9D%84%EA%B9%8C%EC%9A%94)

- **[4. 시뮬레이터](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#4-%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0)**
	- [시뮬레이터 재설정 하는 방법은?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0-%EC%9E%AC%EC%84%A4%EC%A0%95-%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80)
	- [Mac에서 복사한 텍스트(클립보드)를 시뮬레이터에 붙여넣기가 안되는 데, 가능한 방법이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#mac%EC%97%90%EC%84%9C-%EB%B3%B5%EC%82%AC%ED%95%9C-%ED%85%8D%EC%8A%A4%ED%8A%B8%ED%81%B4%EB%A6%BD%EB%B3%B4%EB%93%9C%EB%A5%BC-%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0%EC%97%90-%EB%B6%99%EC%97%AC%EB%84%A3%EA%B8%B0%EA%B0%80-%EC%95%88%EB%90%98%EB%8A%94-%EB%8D%B0-%EA%B0%80%EB%8A%A5%ED%95%9C-%EB%B0%A9%EB%B2%95%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	- [시뮬레이터라고 하는 데, 애뮬레이터와 차이가 무엇인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0%EB%9D%BC%EA%B3%A0-%ED%95%98%EB%8A%94-%EB%8D%B0-%EC%95%A0%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0%EC%99%80-%EC%B0%A8%EC%9D%B4%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)

- **[5. reject](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#5-reject)**
	- [로그인을 하기위해 정보(전호번호등..)가 필요하다고 리젝 당했습니다.😭](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%A1%9C%EA%B7%B8%EC%9D%B8%EC%9D%84-%ED%95%98%EA%B8%B0%EC%9C%84%ED%95%B4-%EC%A0%95%EB%B3%B4%EC%A0%84%ED%98%B8%EB%B2%88%ED%98%B8%EB%93%B1%EA%B0%80-%ED%95%84%EC%9A%94%ED%95%98%EB%8B%A4%EA%B3%A0-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%96%88%EC%8A%B5%EB%8B%88%EB%8B%A4-)
	- [쇼셜(SNS) 로그인만 있으면 리젝 당하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%87%BC%EC%85%9Csns-%EB%A1%9C%EA%B7%B8%EC%9D%B8%EB%A7%8C-%EC%9E%88%EC%9C%BC%EB%A9%B4-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [비디오에 대한 링크를 제공하라는 데? 무슨 의미일까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%87%BC%EC%85%9Csns-%EB%A1%9C%EA%B7%B8%EC%9D%B8%EB%A7%8C-%EC%9E%88%EC%9C%BC%EB%A9%B4-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [웹뷰로만 된 앱은 리젝인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9B%B9%EB%B7%B0%EB%A1%9C%EB%A7%8C-%EB%90%9C-%EC%95%B1%EC%9D%80-%EB%A6%AC%EC%A0%9D%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [페이지 한개 짜리 앱이 리젝 사유인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%ED%8E%98%EC%9D%B4%EC%A7%80-%ED%95%9C%EA%B0%9C-%EC%A7%9C%EB%A6%AC-%EC%95%B1%EC%9D%B4-%EB%A6%AC%EC%A0%9D-%EC%82%AC%EC%9C%A0%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [앱내 공지사항에 안드 출시소식 있다구 리젝 당하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%B1%EB%82%B4-%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD%EC%97%90-%EC%95%88%EB%93%9C-%EC%B6%9C%EC%8B%9C%EC%86%8C%EC%8B%9D-%EC%9E%88%EB%8B%A4%EA%B5%AC-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [강제 종료 함수를 사용하면 리젝 당하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B0%95%EC%A0%9C-%EC%A2%85%EB%A3%8C-%ED%95%A8%EC%88%98%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%A9%B4-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [아이폰X 대응 안하면 리젝인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%84%EC%9D%B4%ED%8F%B0x-%EB%8C%80%EC%9D%91-%EC%95%88%ED%95%98%EB%A9%B4-%EB%A6%AC%EC%A0%9D%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [우리 앱은 iPhone만 지원하고 iPad를 지원안하는 데, iPad에서 실행했을 때 더이상 진행할 수 없다고 사진과 합께 리젝 내용을 받았습니다. 😭](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9A%B0%EB%A6%AC-%EC%95%B1%EC%9D%80-iphone%EB%A7%8C-%EC%A7%80%EC%9B%90%ED%95%98%EA%B3%A0-ipad%EB%A5%BC-%EC%A7%80%EC%9B%90%EC%95%88%ED%95%98%EB%8A%94-%EB%8D%B0-ipad%EC%97%90%EC%84%9C-%EC%8B%A4%ED%96%89%ED%96%88%EC%9D%84-%EB%95%8C-%EB%8D%94%EC%9D%B4%EC%83%81-%EC%A7%84%ED%96%89%ED%95%A0-%EC%88%98-%EC%97%86%EB%8B%A4%EA%B3%A0-%EC%82%AC%EC%A7%84%EA%B3%BC-%ED%95%A9%EA%BB%98-%EB%A6%AC%EC%A0%9D-%EB%82%B4%EC%9A%A9%EC%9D%84-%EB%B0%9B%EC%95%98%EC%8A%B5%EB%8B%88%EB%8B%A4-)
	- [자체로그인 없이 소셜로그인만 붙이려고 하는데, 애플 리젝사유인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9E%90%EC%B2%B4%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EC%97%86%EC%9D%B4-%EC%86%8C%EC%85%9C%EB%A1%9C%EA%B7%B8%EC%9D%B8%EB%A7%8C-%EB%B6%99%EC%9D%B4%EB%A0%A4%EA%B3%A0-%ED%95%98%EB%8A%94%EB%8D%B0-%EC%95%A0%ED%94%8C-%EB%A6%AC%EC%A0%9D%EC%82%AC%EC%9C%A0%EC%9D%B8%EA%B0%80%EC%9A%94)

- **[6. 라이브러리 사용](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#6-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9)**
	- [라이브러리 사용을 하려면 어떻게 해야 되나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9%EC%9D%84-%ED%95%98%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC-%EB%90%98%EB%82%98%EC%9A%94)
	- [라이브러리들 모아놓은 좋은 블로그니 링크가 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC%EB%93%A4-%EB%AA%A8%EC%95%84%EB%86%93%EC%9D%80-%EC%A2%8B%EC%9D%80-%EB%B8%94%EB%A1%9C%EA%B7%B8%EB%8B%88-%EB%A7%81%ED%81%AC%EA%B0%80-%EC%9E%88%EB%82%98%EC%9A%94)

- **[7. 디자인](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#7-%EB%94%94%EC%9E%90%EC%9D%B8)**
	- [안드로이드는 UI 개발 중 크기 선택은 dp로 작업하는 데 iOS에서는 dp를 지원하나요? 현업에서는 보통 디자이너에게 요구할때 어떻게 요구를 하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C%EB%8A%94-ui-%EA%B0%9C%EB%B0%9C-%EC%A4%91-%ED%81%AC%EA%B8%B0-%EC%84%A0%ED%83%9D%EC%9D%80-dp%EB%A1%9C-%EC%9E%91%EC%97%85%ED%95%98%EB%8A%94-%EB%8D%B0-ios%EC%97%90%EC%84%9C%EB%8A%94-dp%EB%A5%BC-%EC%A7%80%EC%9B%90%ED%95%98%EB%82%98%EC%9A%94-%ED%98%84%EC%97%85%EC%97%90%EC%84%9C%EB%8A%94-%EB%B3%B4%ED%86%B5-%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88%EC%97%90%EA%B2%8C-%EC%9A%94%EA%B5%AC%ED%95%A0%EB%95%8C-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%9A%94%EA%B5%AC%EB%A5%BC-%ED%95%98%EB%82%98%EC%9A%94)
	- [앱 디자인 툴로는 스케치가 대세인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%B1-%EB%94%94%EC%9E%90%EC%9D%B8-%ED%88%B4%EB%A1%9C%EB%8A%94-%EC%8A%A4%EC%BC%80%EC%B9%98%EA%B0%80-%EB%8C%80%EC%84%B8%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [1024 앱 아이콘 한번에 다 변환해주는 사이트 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#1024-%EC%95%B1-%EC%95%84%EC%9D%B4%EC%BD%98-%ED%95%9C%EB%B2%88%EC%97%90-%EB%8B%A4-%EB%B3%80%ED%99%98%ED%95%B4%EC%A3%BC%EB%8A%94-%EC%82%AC%EC%9D%B4%ED%8A%B8-%EC%9E%88%EB%82%98%EC%9A%94)

- **[8. Apple 개발: UIKit](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#8-apple-%EA%B0%9C%EB%B0%9C-uikit)**
	- [멀티 터치 는 최대 갯수가 5개 인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%A9%80%ED%8B%B0-%ED%84%B0%EC%B9%98-%EB%8A%94-%EC%B5%9C%EB%8C%80-%EA%B0%AF%EC%88%98%EA%B0%80-5%EA%B0%9C-%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [상태바를 히든 시키거나 나타내고 싶은 데, 어떻게 해야되나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%83%81%ED%83%9C%EB%B0%94%EB%A5%BC-%ED%9E%88%EB%93%A0-%EC%8B%9C%ED%82%A4%EA%B1%B0%EB%82%98-%EB%82%98%ED%83%80%EB%82%B4%EA%B3%A0-%EC%8B%B6%EC%9D%80-%EB%8D%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%EB%90%98%EB%82%98%EC%9A%94)
	- [App-Prefs:root 와 Prefs:root 는 어떻게 사용하는 것인가요? 사용 가능한가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#app-prefsroot-%EC%99%80-prefsroot-%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%B8%EA%B0%80%EC%9A%94-%EC%82%AC%EC%9A%A9-%EA%B0%80%EB%8A%A5%ED%95%9C%EA%B0%80%EC%9A%94)
	- [화면을 수동으로 갱신시키려고 하는 데, 어떻게 해야될까요? 원하는 시점에 변경된 값이 정확하게 반영된 화면을 표현하고 싶습니다.](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%ED%99%94%EB%A9%B4%EC%9D%84-%EC%88%98%EB%8F%99%EC%9C%BC%EB%A1%9C-%EA%B0%B1%EC%8B%A0%EC%8B%9C%ED%82%A4%EB%A0%A4%EA%B3%A0-%ED%95%98%EB%8A%94-%EB%8D%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%EB%90%A0%EA%B9%8C%EC%9A%94-%EC%9B%90%ED%95%98%EB%8A%94-%EC%8B%9C%EC%A0%90%EC%97%90-%EB%B3%80%EA%B2%BD%EB%90%9C-%EA%B0%92%EC%9D%B4-%EC%A0%95%ED%99%95%ED%95%98%EA%B2%8C-%EB%B0%98%EC%98%81%EB%90%9C-%ED%99%94%EB%A9%B4%EC%9D%84-%ED%91%9C%ED%98%84%ED%95%98%EA%B3%A0-%EC%8B%B6%EC%8A%B5%EB%8B%88%EB%8B%A4)
	- [오토레이아웃 깨지면 상황이 발생했을 때, 문제점을 해결하기 위해 보면 좋은 사이트 어디 인지 아세요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%98%A4%ED%86%A0%EB%A0%88%EC%9D%B4%EC%95%84%EC%9B%83-%EA%B9%A8%EC%A7%80%EB%A9%B4-%EC%83%81%ED%99%A9%EC%9D%B4-%EB%B0%9C%EC%83%9D%ED%96%88%EC%9D%84-%EB%95%8C-%EB%AC%B8%EC%A0%9C%EC%A0%90%EC%9D%84-%ED%95%B4%EA%B2%B0%ED%95%98%EA%B8%B0-%EC%9C%84%ED%95%B4-%EB%B3%B4%EB%A9%B4-%EC%A2%8B%EC%9D%80-%EC%82%AC%EC%9D%B4%ED%8A%B8-%EC%96%B4%EB%94%94-%EC%9D%B8%EC%A7%80-%EC%95%84%EC%84%B8%EC%9A%94)

- **[9. Apple 개발: Foundation](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#9-apple-%EA%B0%9C%EB%B0%9C-foundation)**
	- [date는 string으로 변경안하면 무조건 9시간 차이가 나나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#date%EB%8A%94-string%EC%9C%BC%EB%A1%9C-%EB%B3%80%EA%B2%BD%EC%95%88%ED%95%98%EB%A9%B4-%EB%AC%B4%EC%A1%B0%EA%B1%B4-9%EC%8B%9C%EA%B0%84-%EC%B0%A8%EC%9D%B4%EA%B0%80-%EB%82%98%EB%82%98%EC%9A%94)
	- [Codable 클래스는 Objective-C에서 사용할 수 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#codable-%ED%81%B4%EB%9E%98%EC%8A%A4%EB%8A%94-objective-c%EC%97%90%EC%84%9C-%EC%82%AC%EC%9A%A9%ED%95%A0-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94)
	- [UrlRequest를 여러개 날리는데 모두 끝날때까지 대기하는 방법은 어떤걸 봐야하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#urlrequest%EB%A5%BC-%EC%97%AC%EB%9F%AC%EA%B0%9C-%EB%82%A0%EB%A6%AC%EB%8A%94%EB%8D%B0-%EB%AA%A8%EB%91%90-%EB%81%9D%EB%82%A0%EB%95%8C%EA%B9%8C%EC%A7%80-%EB%8C%80%EA%B8%B0%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80-%EC%96%B4%EB%96%A4%EA%B1%B8-%EB%B4%90%EC%95%BC%ED%95%98%EB%82%98%EC%9A%94)

- **[10. Apple 개발: 그외](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#10-apple-%EA%B0%9C%EB%B0%9C-%EA%B7%B8%EC%99%B8)**
	- [delegate 는 어떻게 사용하는 것인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#delegate-%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [여러 컨트롤러에서 보여줘야하는 뷰가 있는데 재사용성을 높일수있는 방안이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%97%AC%EB%9F%AC-%EC%BB%A8%ED%8A%B8%EB%A1%A4%EB%9F%AC%EC%97%90%EC%84%9C-%EB%B3%B4%EC%97%AC%EC%A4%98%EC%95%BC%ED%95%98%EB%8A%94-%EB%B7%B0%EA%B0%80-%EC%9E%88%EB%8A%94%EB%8D%B0-%EC%9E%AC%EC%82%AC%EC%9A%A9%EC%84%B1%EC%9D%84-%EB%86%92%EC%9D%BC%EC%88%98%EC%9E%88%EB%8A%94-%EB%B0%A9%EC%95%88%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	- [푸시로 기본적으로 보내는 것 메시지 외에 다른 정보들을 보내고 싶은 데, 전송 시에 많은 정보를 담아 보낼 수 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%ED%91%B8%EC%8B%9C%EB%A1%9C-%EA%B8%B0%EB%B3%B8%EC%A0%81%EC%9C%BC%EB%A1%9C-%EB%B3%B4%EB%82%B4%EB%8A%94-%EA%B2%83-%EB%A9%94%EC%8B%9C%EC%A7%80-%EC%99%B8%EC%97%90-%EB%8B%A4%EB%A5%B8-%EC%A0%95%EB%B3%B4%EB%93%A4%EC%9D%84-%EB%B3%B4%EB%82%B4%EA%B3%A0-%EC%8B%B6%EC%9D%80-%EB%8D%B0-%EC%A0%84%EC%86%A1-%EC%8B%9C%EC%97%90-%EB%A7%8E%EC%9D%80-%EC%A0%95%EB%B3%B4%EB%A5%BC-%EB%8B%B4%EC%95%84-%EB%B3%B4%EB%82%BC-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94)
	- [swift로 개발할때 c++ 라이브러리 사용할 수 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#swift%EB%A1%9C-%EA%B0%9C%EB%B0%9C%ED%95%A0%EB%95%8C-c-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9%ED%95%A0-%EC%88%98-%EC%9E%88%EB%82%98%EC%9A%94)
	

- **[11. design pattern](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#11-design-pattern)**
	- [아키텍쳐 패턴으로 공부할만한 좋은 셈플 링크가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90-%ED%8C%A8%ED%84%B4%EC%9C%BC%EB%A1%9C-%EA%B3%B5%EB%B6%80%ED%95%A0%EB%A7%8C%ED%95%9C-%EC%A2%8B%EC%9D%80-%EC%85%88%ED%94%8C-%EB%A7%81%ED%81%AC%EA%B0%80-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [MVC 패턴이 무엇인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#mvc-%ED%8C%A8%ED%84%B4%EC%9D%B4-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)

- **[12. RxSwift](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#12-rxswift)**
	- [RxSwift가 무엇인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#rxswift%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)

- **[13. 기타](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#13-%EA%B8%B0%ED%83%80)**
	- [애플 사이트나 시스템 운영 상태의 에러 유무는 어떻게 알 수가 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%A0%ED%94%8C-%EC%82%AC%EC%9D%B4%ED%8A%B8%EB%82%98-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%9A%B4%EC%98%81-%EC%83%81%ED%83%9C%EC%9D%98-%EC%97%90%EB%9F%AC-%EC%9C%A0%EB%AC%B4%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%95%8C-%EC%88%98%EA%B0%80-%EC%9E%88%EB%82%98%EC%9A%94)
	- [iOS 배포 최소 버전에 대해 고민중입니다. iOS OS버전을 사용하는 통계 정보를 알 수 있는 정보나 링크가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#ios-%EB%B0%B0%ED%8F%AC-%EC%B5%9C%EC%86%8C-%EB%B2%84%EC%A0%84%EC%97%90-%EB%8C%80%ED%95%B4-%EA%B3%A0%EB%AF%BC%EC%A4%91%EC%9E%85%EB%8B%88%EB%8B%A4-ios-os%EB%B2%84%EC%A0%84%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%ED%86%B5%EA%B3%84-%EC%A0%95%EB%B3%B4%EB%A5%BC-%EC%95%8C-%EC%88%98-%EC%9E%88%EB%8A%94-%EC%A0%95%EB%B3%B4%EB%82%98-%EB%A7%81%ED%81%AC%EA%B0%80-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [이전 OS,Xcode 나 최신 OS, Xcode를 받으려면 어디서 받을 수 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9D%B4%EC%A0%84-osxcode-%EB%82%98-%EC%B5%9C%EC%8B%A0-os-xcode%EB%A5%BC-%EB%B0%9B%EC%9C%BC%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%94%94%EC%84%9C-%EB%B0%9B%EC%9D%84-%EC%88%98-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [새로운 iOS에 대한 beta일정 같은걸 확인할수 있는 곳이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%83%88%EB%A1%9C%EC%9A%B4-ios%EC%97%90-%EB%8C%80%ED%95%9C-beta%EC%9D%BC%EC%A0%95-%EA%B0%99%EC%9D%80%EA%B1%B8-%ED%99%95%EC%9D%B8%ED%95%A0%EC%88%98-%EC%9E%88%EB%8A%94-%EA%B3%B3%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	
<br />

## **질문과 답변**
### **`1. 개발입문`**
#### Swift 공부할 때 보면 좋은 책은 어떤 것이 있을 까요?
- 개인적으로 바이블과 스토리진행을 따라해보는 2가지가 있을 것 같은데요. 
	- 바이블 쪽이면 : **`스위프트 프로그래밍: Swift4 객체지향, 함수형, 프로토콜 지향 패러다임까지 한 번에! 2판`** 을 검색해보시면 좋은 것 같습니다.
	- 스토리 진행이면 : **`꼼꼼한재은씨의 스위프트 실전편`**, **[`Do it! 스위프트로 아이폰 앱 만들기 (입문) [개정 2판]`](https://github.com/doitswift)** 이 좋다는 말은 들었었고, 요즘에는 다양한 책들이 있는 것 같습니다. 알게 되는 책들이 있으면 업데이트 하겠습니다. 

#### Swift 개발을 처음 시작할 때 공부하기 좋은 링크 가 있을 까요?
- 개인적으로 [야곰님의 유투브](https://www.youtube.com/channel/UCkwWWEv3C-3ToeO57r5LCHQ?app=desktop), &nbsp; [야곰님의 동영상 강의](https://www.inflearn.com/course/ios-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D/), &nbsp; [인프런 스탠퍼드 강의](https://www.inflearn.com/course/stanford-ios-%ED%95%9C%EA%B8%80%EC%9E%90%EB%A7%89-%EA%B0%95%EC%9D%98/), &nbsp; [프로그래머스의 iOS swift입문](https://programmers.co.kr/learn/courses/4)이 좋다고 생각합니다.
- [swift 한국어 동영상 강의 링크들 모음](https://github.com/ClintJang/awesome-swift-korean-lecture/blob/master/README.md) 은 개인적으로 모아둔 링크입니다.
- [giftbot님의 Links For iOS Developer](https://github.com/giftbott/iOSDevLinks), iOS 개발자를 위한 링크모음 입니다.

#### Objective C 공부할 좋은 방법이 있나요?
- **`아론 힐리가스의 오브젝티브-C 프로그래밍`** 책을 검색해 보세요, 국내에서는 이정도가 좋은 것 같습니다.
- 오브젝티브-C 한국어 동영상강좌는 [T아카데미 Objective C](https://www.youtube.com/watch?v=dzv8L5lKsuk&feature=youtu.be) 강좌 정도 인 것 같습니다.

#### 처음 개발에 입문 했는 데, 좋은 커뮤니티가 있을까요?
- 스위프트 관련 커뮤니티 그룹은 [스위프트 한국 개발자 그룹(페이스북)](https://www.facebook.com/groups/swiftkor/), [맥부기(네이버 카페)](https://cafe.naver.com/mcbugi) 두가지 정도를 알고 있습니다.
- 오픈된 대화방은 [카카오톡 iOS 오픈채팅방(iOS Developers KR)](https://open.kakao.com/o/gyLape), [Slack swiftkorea](http://slack.swiftkorea.org/), [카카오톡 RxSwift 오픈채팅방](https://open.kakao.com/o/gl2YZjq) 정도가 있는 것 같습니다. 
- iOS 개발자는 소수이니 커뮤니티에서 함께 개발을 진행하며, 어려운 내용은 공유하고 도움도 주고 받고 하면 개발일을 더 즐겁게 할 수 있는 것 같습니다.

#### ios 공부할만한 깃헙 프로젝트 혹시 추천해주실 수 있나요? 독학하는데 가이드가 없으니 힘드네용 알려주시면 감사하겠습니다
- https://github.com/ClintJang/awesome-swift-korean-lecture
- https://github.com/soapyigu/Swift-30-Projects

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`2. AppStore`**

#### 애플 개발자 전화 지원은 몇번인가요? 전화가 가능한가요?
- 제가 알기로는 080-860-9797 입니다. [참고한 링크](http://www.zosolution.com/69), 현재는 공식적으로는 온라인으로 요청하면 전화 연결을 해준다고 합니다. 아래 전화 지원 링크를 눌러서 진행해 보세요.
- [애플 전 세계 전화지원 링크](https://developer.apple.com/contact/phone/kr/) : 온라인으로 요청하세요.

	```
	전 세계 전화 지원
	
	등록 및 멤버십, 앱 제출 및 관리, 분석 등 일부 주제에 대해서는 
	Apple Developer 전화 지원이 전 세계에서 제공됩니다. 
	지원 전화를 받으시려면 온라인에서 요청하십시오. 
	전문가와 연결해 드리겠습니다.
	```

#### AppStore에 검수 신청하면 얼마나 걸리나요?
- [App review Times](http://appreviewtimes.com/) : 현재 검수 시간이 평균적으로 얼마나 걸리는 지 정보를 제공해줘서 대략적인 판단을 할 수 있게 해주는 사이트 입니다.
	- (간헐적으로 사이트 접속이 안될 때도 있었습니다. 그때는 나중에 다시 시도해봐 주세요.😀)
- 보통 케바케라서 정확하지 않습니다. 평균적인 시간보다 오래 걸린다면, 검수 진행에 대해 문의를 진행해 해보시면 될 것 같습니다. 

#### 앱스토어를 등록하기 전에 UUID(디바이스) 등록 안된 분들이 테스트 해볼려면 어떻게 해야될 까요?
1. 개인 및 법인 계정이라면 : [Apple TestFlight](https://developer.apple.com/testflight/) 가 있습니다. 
	- 구글에서 "TestFlight 사용법" 으로 검색을 해보셔요.
2. 기업(Enterprice) 계정이라면 : 디바이스 등록없이 기업내 배포가 가능합니다. 단, 자사 외의 다른 목적으로 배포시 계정이 블락 될 수 있습니다. (알고 계시는 분들이 애플에 신고도 가능할 수 있어요~)

#### 정말 급하게 앱스토어에 등록해야되는 데.. 어떻게 해야될 까요?
- [긴급심사 리뷰 요청](https://developer.apple.com/contact/app-store/?topic=expedite)이 있습니다. 정말 긴급할 때만 사용하세요..
- "appstore 긴급 리뷰 요청" 정도로 구글에 검색하면 방법을 알 수 있습니다.

	```
	빠른 앱 심사

	참작이 가능한 상황에 직면하는 경우 빠른 앱 심사를 요청할 수 있습니다. 
	이러한 상황으로는 App Store에 있는 앱의 심각한 버그를 수정하거나 직접 관련된 이벤트와 동시에 앱을 출시해야 하는 경우 등이 해당됩니다.
	```
	
- 그냥 요청이 아니라 어쩔수 없는 이유와 사연을 정확히 전달해야 합니다. 그냥 대충 신청하면 무조건 거절될 것 입니다.
- 예를 들어 심각한 문제점이나 프로모션 과 같은상황은 긴급심사가 가능 한 것으로 알고 있습니다.
- Select a reason (이유) 에는 3가지 항목이 있습니다.  
	- Critical Bug Fix   
	- Time-Sensitive Event   
	- Other

#### 검수통과해서 "판매 준비됨"으로 바뀌었는 데, 왜? iOS 앱스토어에서 검색하면 나타나지 않을까요?
- 개인적인 경험으로 볼 때, 케바케 인 것 같습니다. 1시간도 안되서 나타난적도 있고, 몇시간이 지났는 데, 어떤 단말에서는 나타나지 않은 경우도 있었습니다. 24시간 안에는 모두 나타나는 것 같습니다.
- [앱스토어 심사지침](https://developer.apple.com/kr/app-store/review/guidelines/) 의 내용 중에 "출시일"로 검색해보세요. 앱이 나타나려면 최대 24시간이 걸릴 수 있다고 합니다. 

	```
	출시일:  .. (중략) .. 
	또한 선택한 모든 지역의 App Store에 앱이 나타나려면 
	최대 24시간이 소요될 수 있음에 유의하십시오.
	```
	
#### appstore에서 앱 다운로드 할때 단말별로 앱사이즈가 다른가요?? 이미지 해상도라던지.. 차이때문에, 만약에 다르다면 영향 받는 부분이 어디일까요?
- App Thinning으로 검색해보시면 나옵니다. Bitcode, On-Demand Resources (ODRs), Slicing 차이로 있습니다.
- [참고한 링크](https://medium.com/@vikaskore/bitcode-slicing-odrs-app-thinning-7c4b294ddec3)

#### 미성년자는 애플 개발자 등록이 가능한가요? 
- 가능하지 않습니다.
- 법적인 이유로 만 18세 미만의 청소년은 개발자 프로그램을 신청할 때에 동의해야 하는 동의서에 동의를 할 수 있는 효력을 지니지 못하기 때문에 가능하지 않습니다.

#### 개인개발자도 앱 등록시 개인정보 취급방침 URL을 반드시 추가해야되나요?
- 구글에서 'AppStore용 프라이버시 정책' 으로 검색해 보세요.
- 2018년 10월 3일부터 Appstore에서 새로운 앱 및 앱 업데이트를 위한 앱 제출시 개인 정보 취급 방침을 요구하도록 바뀌었습니다.
- [앱스토어 심사지침](https://developer.apple.com/kr/app-store/review/guidelines/) 의 5.1.1 내용을 확인해보세요.

	```
	5.1.1 데이터 수집 및 보관
	(i) 개인정보 취급방침: 모든 앱에는 App Store Connect 메타데이터 영역과 앱 내부에 쉽게 볼 수 있는 개인정보 취급방침 관련 링크가 포함되어야 합니다. 개인정보 취급방침은 분명하고 명시적으로 다음 요건을 준수해야 합니다.
	앱과 서비스가 수집하는 대상 정보(있는 경우), 정보 수집 방법, 수집한 정보의 사용 목적을 정의해야 합니다.
	```

- **☆** [심사지침 팁](http://13.125.229.142/?p=1213)에 쉽게 작성하는법이 적혀있습니다.

#### 스토어 스크린샷에 디바이스를 같이 보여주소 싶은데 가이드라인 같은걸 확인 할 수 있는데가 있을까요?
- 앱 미리보기 및 스크린샷 이미지 업로드 하는 부분에 "?" 아이콘을 클릭하시면 가이드 링크가 나타납니다.
- [앱 미리보기 사양](https://help.apple.com/app-store-connect/#/dev4e413fcb8)
- [App Store 아이콘, 앱 미리보기 및 스크린샷 개요](https://help.apple.com/app-store-connect/#/dev910472ff2)

#### 앱스토어에서 앱 이름 아래에 개발자 이름을 변경하고 싶은데 따로 변경할 수 있나요? 고객센터에 문의해봐야되나요?
- 과거에는 실명과 다른 이름이 허용이 되던 시기도 있었지만, 현재는 제한하고 있습니다.
- 개인 개발자는 실명, 법인은 법인명으로 제한 되는 것으로 알고 있습니다. 물론 개인이 개명을 한다던가 여권이름과 다른 오기가 있었다던 가 또는 법인 명이 변경되었다던가 하면, 그런 부분(합당한 사유)은 당연히 변경될 수 있는 것으로 알고 있습니다. 
- 문의해보신 분도 위의 내용으로 답변을 들은 것으로 알고 있습니다.
- 확인이 필요하시면 고객센터에 문의해보셔도 좋을 것 같습니다. 

#### 애플로 로그인을 하는 것을 꼭 추가해야되나요? 기존에 서드파티 로그인 기능이 있는 데, 넣어야 된다는 것 같더군요. 기능을 추가한다면 언제까지 반드시 추가해야되나요?
- 추가하셔야 되지만, 현재 운영 중인 앱이니.. 2020년 4월까지는 현행대로 하셔도 괜찮을 것으로 보입니다.
- [Apple로 로그인에 대한 신규 가이드라인(2019년 09월 12일)](https://developer.apple.com/kr/news/?id=09122019b) 관련 뉴스 글을 보시면 기존 앱은 2020년 4월까지, 신규 앱은 뉴스 글이 올라온 2019년 09월 12일 부터 추가해야되는 상황이라면 추가하셔야 됩니다.
	
	```
	.. 중략 ..
	오늘부터 App Store에 제출하는 신규 앱은 해당 가이드라인을 따라야 하며, 
	기존의 앱과 앱 업데이트는 2020년 4월 전까지 해당 가이드라인을 따라야 합니다.
	.. 중략 ..
	```

- 애플로 로그인을 구현 안해도 되는 경우 `(애플 로그인 구현 불필요)`
	- 자체회원 가입만 있는 경우
	- 교육 또는 기업 계정
	- 특정 써드파티 소셜 로그인이 필수 인 경우
- 위의 경우를 제외하고는 로그인 기능이 있다면 애플로 로그인을 함께 구현해야됩니다. `(애플 로그인 구현 필요)`
	- 자체회원 로그인 + 서드파티 로그인 의 경우
	- 서드파티 로그인만 있는 경우
- [App Store 심사 지침 보기(영문)](https://developer.apple.com/app-store/review/guidelines/#sign-in-with-apple)의 `4.8 Sign in with Apple` 에 정보가 있습니다.
	- Sign in with Apple is not required if:
		- Your app exclusively uses your company’s own account setup and sign-in systems.
		- Your app is an education, enterprise, or business app that requires the user to sign in with an existing education or enterprise account.
		- Your app uses a government or industry-backed citizen identification system or electronic ID to authenticate users.
		- Your app is a client for a specific third-party service and users are required to sign in to their mail, social media, or other third-party account directly to access their content.
- 추가로 [Sign in with Apple REST API](https://developer.apple.com/documentation/signinwithapplerestapi) 링크 입니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`3. Xcode`**
#### Xcode에서 자동완성이 안될 때는?
- Xcode clean, Xcode 재 실행
- 재부팅
- derivedData 를 제거해보기 
	- xcode deriveddata clean 정도로 구글 검색해보셔요. 

#### Xcode 10으로 올리고 나서 빌드 에러가 났는 데, 어떻게 하죠? 과거로 돌아갈 수 있나요?
- 이전 버전을 다운받을 수 있습니다. 
	- https://developer.apple.com/download/
	- https://developer.apple.com/download/more/
- Xcode 10은 새로운 빌드 시스템을 사용합니다. 새로운 빌드 시스템은 향상된 안정성과 빌드 성능을 제공하며 레거시 빌드 시스템에서는 볼 수 없는 프로젝트 구성 문제를 포착합니다. 만약 문제가 있다면 이전 빌드시스템을 사용할 수 있습니다. 
	- File > Project/Workspace Settings
	
	<table>
	  <tr>
		<th>Xcode 10 기본</th> 
		<th>이전 빌드시스템(1/2)</th>
		<th>이전 빌드시스템(2/2)</th>
	  </tr>
	  <tr>
	  	<td><img width="226" height="115" src="/Image/NewBuild01.png"></img></td>
	  	<td><img width="240" height="109" src="/Image/RegacyBuild01.png"></img></td>
	  	<td><img width="233" height="110" src="/Image/RegacyBuild02.png"></img></td>
	  </tr>
  
	</table>
	
	
#### 작업 중인 현재 프로젝트 폴더 위치로 이동된 터미널을 띄우고 싶은 데, 혹시 Xcode 에서 가능한 방법이 있나요?
- 이미지 처럼 이렇게 설정하는 방법이 있습니다. 

<img width="308" height="98" src="/Image/Xcode_Open_Terminal00.jpeg"></img>

- [곰튀김님의 유투브 동영상](https://youtu.be/GNu6IuU_UeE) 링크를 참고해 주세요. 짱입니다.

#### 아이폰 앱 로그 속도 측정하고 있는 데, 앱 런처스크린 실행하면서 시간이 많이 걸립니다. 이 부분도 설정하는 것이 있나요?
- 아래 이미지 처럼 환경변수 설정해주시면, 디버그콘솔에 찍혀요.

	<table>
	  <tr>
		<th>환경변수 설정</th> 
		<th>콘솔 로그</th>
	  </tr>
	  <tr>
	  	<td><img width="300" src="/Image/AppLogSpeedSetting.jpg"></img></td>
	  	<td><img width="300" src="/Image/AppLogSpeedConsole.jpg"></img></td>
	  </tr>
  
	</table>

- 이건 pre-main타임 입니다. 그이후 시간은 AppDelegate가 호출된 이후라 그건 직접 찍으시면 됩니다.
- 환경변수 : `DYLD_PRINT_STATISTICS`, value : 1

#### Swift 프로젝트의 컴파일 시간 최적화를 시키려면 어떻게 하면 좋을까요?
> Swift는 기존 Objective-C의 단점을 보완하며, 현대 프로그래밍 언어가 갖고 있는 기능을 많이 포함하고 더불어 일정한 성능 향상을 시켰지만... Objective-C에 비해서 빌드 속도가 현저히 느려졌지요? 😭

- 성능 좋은 PC를 선택하는 것도 중요할 것 입니다. 더불어..
- 개인적으로 이 링크를 들어가서 보시길 추천드립니다. 👍
	- https://github.com/fastred/Optimizing-Swift-Build-Times
- 그외 링크
	- [민소네님 : 컴파일 시간을 아주 많이 줄이기](http://minsone.github.io/mac/ios/improve-compile-time-of-swift)
	- [제드님 : OptimizationTips (Writing High-Performance Swift Code](https://zeddios.tistory.com/593)
	- [WMO  알아보기(컴파일 최적화)](https://brunch.co.kr/@joonwonlee/14)

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`4. 시뮬레이터`**
#### 시뮬레이터 재설정 하는 방법은?
1. 시뮬레이터 실행 후 왼쪽 상단 메뉴에서 중에서 

```
Choose Hardware -> Erase All Content and Settings..  
```
2. 팝업에서 Erase 를 선택하시면됩니다.

#### Mac에서 복사한 텍스트(클립보드)를 시뮬레이터에 붙여넣기가 안되는 데, 가능한 방법이 있나요?
1. 시뮬레이터 실행 후 왼쪽 상단 메뉴에서 중에서 `Automatically Sync Pasteboard`을 선택하시면 됩니다.

```
Choose Edit -> Automatically Sync Pasteboard to turn on and turn off  
```

- [simulator help topics](https://developer.apple.com/library/archive/documentation/IDEs/Conceptual/simulator_help_topics/Chapter/Chapter.html) 링크를 참고해보세요.
- 가끔 잘 안되면.. 체크를 해제했다가 체크했다가 복사 몇번 해보시면 되실 거에요.😭


#### 시뮬레이터라고 하는 데, 애뮬레이터와 차이가 무엇인가요?
- 둘 다 실제 하드웨어를 사용할 필요없이 앱(어플리케이션)을 테스트 하기 위한 목적을 가지고 있습니다.
- 안드로이드 개발할 때, 에뮬레이터 (`emulator`) 를 사용하지요.
- 에뮬레이터는 아키텍쳐를 재현하여 만듭니다. 현재 시스템 안에 다른 시스템을 완벽히 재현한 것이지요. 안드로이드 에뮬레이터는 arm용과 x86용 등등을 따로 만들수 있고 비교적 무겁고 느립니다.
- 에뮬레이터는 실제 기기와 유사한 테스트가 가능합니다.
- 에뮬레이터가 완벽한 구현이라면 시뮬레이터는 부분적인 구현입니다.
- 시뮬레이터(`simulator`)는 대상 시스템을 추상화 하여 실제환경에 가깝고 유사하게 동작하도록 테스트 환경을 만들어 줍니다. 속도가 빠르지요.
- 시뮬레이터는 기존의 플랫폼에서 동작만 재현합니다. 예를 들면, iOS 디바이스는 arm64에서 시뮬레이터는 x86_64에서 돌아가요.
- '시뮬레이터 애뮬레이터' 정도로만 검색해도 내용이 많이 나옵니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`5. Reject`**
>1. 기본적인 검수 진행은 진행되는 사항 중 중요한 정보들은 메일로 받아져 있을 것 입니다. 메일함을 우선 확인해 봅시다 😁<br />
>2. 검수자에 따라 케바케로 검수결과가 달라질 수 있습니다. 항상 통과되던 앱이 이번에 왜 리젝된거지? 하고 당황하지 말고 리젝 내용을 확인해보세요.<br />
>3. [App Store 심사 지침 가이드 라인](https://developer.apple.com/kr/app-store/review/guidelines/)은 계속 변합니다. 아래 내용도 시간이 지나면 달라질 수 있습니다.<br />


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
- [App Store Review Guidelines 4.2](https://developer.apple.com/kr/app-store/review/guidelines/#minimum-functionality)

```
4.2 최소한의 기능
앱에는 웹 사이트를 단순히 바꾼 수준을 넘어서는 기능, 콘텐츠, UI가 있어야 합니다. 
**특별히 유용하거나 고유하지 않은, '앱 같지 않은' 앱은 App Store에 등록할 수 없습니다.** 
지속적인 엔터테인먼트 가치를 제공하지 못하는 앱이나 지나치게 공포스러운 앱은 거부될 수 있습니다. 
단순히 노래나 동영상으로 된 앱은 iTunes Store에 제출해야 하며 
책이나 게임 설명서로 된 앱은 iBooks Store에 제출해야 합니다.
```

#### 페이지 한개 짜리 앱이 리젝 사유인가요?
- 리뷰어에 따라 다릅니다. 중요한게 수준미달이라 판단되도 리젝 당할 수 있습니다. 작동하지 않거나 수준 미달의 경험을 제공하는 앱은 언제든지 App Store에서 삭제될 수 있습니다.

#### 앱내 공지사항에 안드 출시소식 있다구 리젝 당하나요?
- 리뷰어 판단이지만, 안드로이드 정보가 iOS앱에 표시되고있다면 리젝될 수 있다는 이야기를 많이 들은 것 같습니다. 문제가 될 소지를 줄이세요.
- 앱 스샷에 안드로이드 이미지를 넣어도 리젝될 수 있습니다.
- 이벤트때 아이패드 준다 이런것도 리젝 될 수 있습니다.
- 리젝사유를 읽어보시고 거기에 해당하는 조치를 취하시면 됩니다. 대화로 풀 수 있느건 대화로 풀면 됩니다.

#### 강제 종료 함수를 사용하면 리젝 당하나요?
- 의도하지 않는 강제 종료함수 사용은 리젝 대상이긴 합니다.
- 안정성이 확보되지 않아 에러가 나서 앱이 강종된 것인지, 사유가 명확해서 이런 상황에서 이용못하게 하기 위해, 고객에게 알려주고 exit(0) 처리를 하였다면 리젝되지 않을 것입니다. (의도된 것이라면 OK)

#### 아이폰X 대응 안하면 리젝인가요?
- [애플 공지](https://developer.apple.com/news/?id=05072018a&1525716802) 링크를 클릭해 보면 2018년 7월(Starting July 2018)부터 대응이 되어야 된다고 합니다. 이제부터는 당연히 대응된 앱이 아니라면 리젝사유입니다.

#### 컨텐츠결제 부분을 xxx페이나 신용카드결제로 하면 리젝 사유인가요?
- 실물결제 는 리젝 사유가 아닙니다. 실물결제가 아니면 리젝입니다.

#### 우리 앱은 iPhone만 지원하고 iPad를 지원안하는 데, iPad에서 실행했을 때 더이상 진행할 수 없다고 사진과 합께 리젝 내용을 받았습니다. 😭
- 리뷰어는 아이패드를 쓰기 때문에 아이폰이 아닐수도 있습니다. 
- 아이폰 용 앱이라도 아이패드에서 실행가능 합니다.
- 보통 iPhone은 대부분(iPhoneX를 제외) 9:16 비율의 해상도 입니다.
- 옛날 iPad에서 지금 iPhone용 앱을 실행하면 3:4 비율입니다. 그래서 하단 부분에 버튼을 만드신 것이 안나오거나 UX/UI가 이상하게 나올 수 있습니다. 최소한 iPad에서 버튼을 누를 수 있는 정도의 UI는 리뷰어와 대화가 가능하겠죠.

#### 자체로그인 없이 소셜로그인만 붙이려고 하는데, 애플 리젝사유인가요?
- 소셜로그인만 있으면 리젝사유가 아니라 소셜로그인을 이용한 이유가 있어야 합니다.
- 페이스북 로그인을 한다면 페이스북에 공유하는 기능이 있다던지 그 특정 소셜로그인을 해야하는 이유가 있어야합니다
- [가이드라인 5.1.1.v 를 찾아보세요](https://developer.apple.com/kr/app-store/review/guidelines/) 
	- "앱의 핵심 기능이 특정 소셜 네트워크(예: Facebook, WeChat, Weibo, Twitter 등)와 관련이 없다면 로그인이나 다른 비슷한 메커니즘을 거치지 않고 바로 기능을 사용할 수 있도록 해야 합니다."

	```
	5.1 개인 정보 보호
	5.1.1 데이터 수집 및 보관
	
	(v) 계정 로그인: 계정이 반드시 필요한 주요 기능이 포함되지 않은 앱인 경우에는 로그인하지 않아도 사용할 수 있도록 해야 합니다. 
	앱의 핵심 기능과 직접적으로 관련이 있거나 법적으로 필요한 경우가 아니라면, 앱을 작동하는 데 사용자 개인 정보를 입력하도록 요구하지 않아야 합니다. 
	앱의 핵심 기능이 특정 소셜 네트워크(예: Facebook, WeChat, Weibo, Twitter 등)와 관련이 없다면 로그인이나 다른 비슷한 메커니즘을 거치지 않고 바로 기능을 사용할 수 있도록 해야 합니다. 
	기본 프로필 정보를 가져오거나 소셜 네트워크에 공유하거나 앱을 사용하도록 친구를 초대하는 행위는 앱의 핵심 기능에 해당하지 않습니다. 
	앱은 앱 내에서 소셜 네트워크 자격 증명을 철회하거나 앱과 소셜 네트워크 간 데이터 접근을 비활성화하는 메커니즘을 포함해야 합니다. 
	앱은 자격 증명이나 토큰을 기기 밖 소셜 네트워크에 저장해서는 안 되며, 
	앱을 사용하는 동안 앱에서 소셜 네트워크에 직접 연결하려는 목적으로만 자격 증명이나 토큰을 사용해야 합니다.
	```

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`6. 라이브러리 사용`**

#### 라이브러리 사용을 하려면 어떻게 해야 되나요?
- [Cocoapods](https://github.com/ClintJang/cocoapods-tips/blob/master/README.md)를 추천드립니다. 
	- [Cocoapods 사용 팁](https://github.com/ClintJang/cocoapods-tips/blob/master/README.md) 링크입니다.
	- 처음이라 어떻게 해야될 지 막막하시다면 [하울님의 코딩채널](https://www.youtube.com/playlist?list=PLmdU__e_zPf-uiDtI84Gv9SxFicrbw4KV)을 추천드립니다.
- Carthage(카르타고) 라는 비슷한 방식도 있습니다. 워크스페이스를 만드는 방식이 아닌 Embbed Framework를 이용하는 방식이죠.

#### 라이브러리들 모아놓은 좋은 블로그니 링크가 있나요?
- [awesome-ios](https://github.com/vsouza/awesome-ios) : 저는 처음에 여기 링크를 보고 사용했었습니다. 
- [MotionBook](https://github.com/younatics/MotionBook) 앱을 받아보셔도 좋고..
- [cocoacontrols](https://www.cocoacontrols.com/) : 여기서 키워드 검색을 해보세요. 예를 들어 테이블 뷰의 헤더 커스텀이 필요하면 .. 'header'로 검색을 ~
- 전 이정도로 찾아보거나 보통은 키워드로 구글 검색을 해봅니다. 당연히 커뮤니티나 지인에게 물어보기도 하구요~. 


<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`7. 디자인`**
> 당연히 iOS 개발과 관련된 디자인 내용입니다.

#### 안드로이드는 UI 개발 중 크기 선택은 dp로 작업하는 데 iOS에서는 dp를 지원하나요? 현업에서는 보통 디자이너에게 요구할때 어떻게 요구를 하나요?
- iOS에서는 dp를 사용하지 않습니다. point라는 개념을 사용합니다. 
- [제드님의 블러그 링크](https://zeddios.tistory.com/6)를 들어가 보세요. 제일 설명이 잘 되어있는 것 같습니다.
- [제플린](https://zeplin.io/) 이라는 협업 툴로 개발을 많이 합니다. iOS용으로 제공받으면 편하게 개발 하실 수 있습니다.
- 유지보수 관점에서 디자이너 분들과 협의하면 좋은 결과를 도출 할 수 있을 것입니다. 파이팅!

#### 앱 디자인 툴로는 스케치가 대세인가요?

- [스케치(sketch)](https://www.sketchapp.com/)를 많이 사용하는 것으로 알고 있습니다.
- 스케치를 이용해서 디자인하고 디자인 가이드의 공유는 [제플린(zeplin)](https://zeplin.io/) 으로 하죠.
- 요즘은 [Adobe XD](https://helpx.adobe.com/kr/xd/how-to/what-is-xd.html)로 넘어가는 추세라는 말도 들어봤습니다.
- 어도비 엑스디의 장점으로 포토샵이나 일러에서 작업한 걸 스케치 같은 경우는 가져오기가 불편한 데, 엑스디는 복붙으로 가져올 수 있는 것 같습니다.
- 애플에서 제공하는 리소스들도 엑스디가 지원한다 하구요.
- 더불어 엑스디는 어도비와 같은? 단축키를 사용해서, 어도비의 단축키에 익숙하신 상태라면 러닝커브도 적을 것입니다. 
- 검색해 주세요. 😁

#### 1024 앱 아이콘 한번에 다 변환해주는 사이트 있나요?
- https://appiconmaker.co
- 맥용 앱 사용하시면 더 편할 수 있습니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`8. Apple 개발: UIKit`**
#### 멀티 터치 는 최대 갯수가 5개 인가요?
- iPhone 류에서는 5개 입니다.
- iPad 류에서는 11개 입니다.

#### 상태바를 히든 시키거나 나타내고 싶은 데, 어떻게 해야되나요?
- [statusBarHidden](https://developer.apple.com/documentation/uikit/uiapplication/1622982-statusbarhidden) 인스턴스 프로퍼티는 9.0에서 Deprecated 되었습니다.
- 앱 시작시에(런치시) info.plist에서 숨길지 여부를 설정할 수 있고..
	- Status bar style : [UIStatusBarStyle](https://developer.apple.com/documentation/uikit/uistatusbarstyle)
	- Status bar is initially hidden : NO/YES
	- View controller-based status bar appearance :NO
- UIViewController에서 [prefersStatusBarHidden](https://developer.apple.com/documentation/uikit/uiviewcontroller/1621440-prefersstatusbarhidden) 처리를 해서 보여줄 지 여부를 설정할 수 있습니다.
- 더불어 필요시 변경시키고 싶다면 [setNeedsStatusBarAppearanceUpdate](https://developer.apple.com/documentation/uikit/uiviewcontroller/1621354-setneedsstatusbarappearanceupdat) 를 호출해 주면, 변경이 될 것 입니다.


#### App-Prefs:root 와 Prefs:root 는 어떻게 사용하는 것인가요? 사용 가능한가요?
- 이제 설정에서 자기 앱의 설정말고 다른 건 못 엽니다. (iOS 11 부터로 알고 있습니다.)
- [UIApplicationOpenSettingsURLString](https://developer.apple.com/documentation/uikit/uiapplicationopensettingsurlstring?language=objc) 를 이용하시면 됩니다.
- 이제 리젝 됩니다. 사유는.. : [review guidelines 2.5 Software Requirements](https://developer.apple.com/app-store/review/guidelines/#software-requirements) 의 2.5.1. 의 내용을 보면 애플에서 제공하는 공식적인 최신 API를 사용하라고 합니다. 

	```
	2.5.1 앱은 공용 API만 사용할 수 있으며 현재 판매되는 OS에서 실행되어야 합니다. 
	공용 API(영문)에 대한 자세한 내용을 확인하십시오. 
	앱을 최신 상태로 유지하고 OS의 다음 버전에서 더 이상 지원하지 않아 사용할 수 없는 기능, 프레임워크 또는 기술을 단계적으로 삭제하십시오. 
	앱은 원래 목적에 맞는 프레임워크와 API를 사용해야 하고 앱 설명에 이와 관련된 내용을 기재해야 합니다. 
	예를 들어 HomeKit 프레임워크의 경우 홈 자동화 서비스를 제공해야 하고, HealthKit의 경우 건강 및 피트니스 목적으로 사용되어야 하며, 건강 앱과 연동되어야 합니다.
	```

- iOS 10 에서는 App-Prefs?, iOS 10 미만에서는 Prefs? 는 조건을 걸면 가능할 것입니다. 하지만 하위 버전은 사용자도 희소하고, 리젝 되리라 생각됩니다. 
- 참고 링크 : [리젝된 경험 링크](https://qiita.com/_mogaming/items/cf1b2b75e4be7041c011)
- 다른 참고 예시 : 리젝되어 받은 내용 중 일부 글 

	```
	... (중략) ...
	
	Your app uses the "prefs:root=" non-public URL scheme, 
	which is a private entity. 
	The use of non-public APIs is not permitted on the App Store 
	because it can lead to a poor user experience should these APIs change.
	
	Continuing to use or conceal non-public APIs 
	in future submissions of this app may result in the termination of your Apple Developer account,
	 as well as removal of all associated apps from the App Store.
	
	... (중략) ...
	
	```




#### 화면을 수동으로 갱신시키려고 하는 데, 어떻게 해야될까요? 원하는 시점에 변경된 값이 정확하게 반영된 화면을 표현하고 싶습니다.
- `setNeedsLayout`과 `layoutIfNeeded` 를 검색해 보세요. 추가적으로 `layoutSubviews` 키워드도 같이 검색해보면 좋습니다.
- [Runloop](https://developer.apple.com/documentation/foundation/runloop), 실행 루프 라고 하지요. 실행 루프 안에서 터치나 여러 이벤트가 발생하면 거기에 따라 시스템 상황에 맞게 화면을 업데이트 합니다. 이런 업데이트 사이클에 맞춰서 화면을 갱신 시키는 시점에 [setNeedsLayout](https://developer.apple.com/documentation/uikit/uiview/1622601-setneedslayout) 가 호출되어있었다면 해당 시점에 화면을 갱신 할 것입니다. setNeedsLayout 를 사용했다면, 비동기적이며, 시스템에 효율적인 갱신 방법입니다. 단, 우리가 정확히 업데이트 시점을 컨트롤 할 수는 없을 것 입니다.
- 즉각적으로 사용하고 싶다면 [layoutIfNeeded](https://developer.apple.com/documentation/uikit/uiview/1622507-layoutifneeded) 를 사용합니다. 강제적이고 즉시 업데이트가 가능하죠.

#### 오토레이아웃 깨지면 상황이 발생했을 때, 문제점을 해결하기 위해 보면 좋은 사이트 어디 인지 아세요?
- https://www.wtfautolayout.com/
- iOS와 macOS의 자동 레이아웃에서 오류 로그를 구문 분석하여 충돌하는 제약조건에 대한 보다 직관적인 시각적 설명을 제공하는 사이트입니다.
- 오류 로그 를 복사해서 넣으면 보기 쉽게 알려줍니다. 아래는 제가 강제로 발생시킨 오류 로그 입니다.

```
[LayoutConstraints] Unable to simultaneously satisfy constraints.
	Probably at least one of the constraints in the following list is one you don't want. 
	Try this: 
		(1) look at each constraint and try to figure out which you don't expect; 
		(2) find the code that added the unwanted constraint or constraints and fix it. 
(
    "<NSLayoutConstraint:0x6000019218b0 V:|-(66)-[UIScrollView:0x7fb177025200]   (active, names: '|':UIView:0x7fb1765096d0 )>",
    "<NSLayoutConstraint:0x600001921a40 UIScrollView:0x7fb177025200.bottom == UIView:0x7fb1765096d0.bottom - 44   (active)>",
    "<NSLayoutConstraint:0x600001921a90 UIScrollView:0x7fb177025200.height == 100   (active)>",
    "<NSLayoutConstraint:0x600001921ae0 'UIView-Encapsulated-Layout-Height' UIView:0x7fb1765096d0.height == 896   (active)>"
)

Will attempt to recover by breaking constraint 
<NSLayoutConstraint:0x600001921a90 UIScrollView:0x7fb177025200.height == 100   (active)>

Make a symbolic breakpoint at UIViewAlertForUnsatisfiableConstraints to catch this in the debugger.
The methods in the UIConstraintBasedLayoutDebugging category on UIView listed in <UIKitCore/UIView.h> may also be helpful.
```

<table>
   <tr>
   <th>오류 로그를 넣어서 Run</th>
 	<th>보기 쉬운 결과</th>
  </tr>
  <tr>
	<td><img width="300" src="/Image/wtfautolayout_before_run.png"></img></td>
 	<td><img width="300" src="/Image/wtfautolayout_after_run.png"></img></td>
  </tr>
</table>

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`9. Apple 개발: Foundation`**

#### date는 string으로 변경안하면 무조건 9시간 차이가 나나요?
- 구글에서 `swift date utc format`등 아래의 키워드를 활용해서 검색해보세요.
- date 객체는 기본적으로 UTC, GMT+0의 시간을 저장합니다.
- date 객체는 timezone이나 locale 같은 값을 안 갖고 있습니다.
- [SwiftDate](https://github.com/malcommac/SwiftDate) 같은 라이브러리는 그걸 같이 저장할 수 있는 객체를 제공합니다.
- 현지 시간으로 잘 변환하려면 Formatter를 쓰거나 Calendar를 써서 변환 해야 됩니다.

#### Codable 클래스는 Objective-C에서 사용할 수 있나요?
- 아니요. 사용할 수 없습니다. 
- [Codable](https://developer.apple.com/documentation/swift/codable)은 **Swift** Standard Library 입니다.
- Swift 4 이상에서만 사용할 수 있습니다.
- [Codable 샘플소스](https://github.com/ClintJang/sample-swift-codable)

#### UrlRequest를 여러개 날리는데 모두 끝날때까지 대기하는 방법은 어떤걸 봐야하나요?
- [`DispatchGroup`](https://developer.apple.com/documentation/dispatch/dispatchgroup) 을 이용해서 `notify` 로 처리하는 방법이 있습니다. 강조한 키워드로 검색해 보세요.
- 참고할 만한 [셈플 소스 링크](https://github.com/ClintJang/sample-swift-dispatchgroup)입니다.
- 그 외에 [RxSwift의 Zip](http://reactivex.io/documentation/operators/zip.html)등의 오퍼레이터를 활용하는 방법
- 그 외에 라이브러리로 [Bolts-Swift](https://github.com/BoltsFramework/Bolts-Swift) 등을 활용할 수 있습니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`10. Apple 개발: 그외`** 

#### delegate 는 어떻게 사용하는 것인가요?
- [마기님의 블로그의 delegate 설명](https://magi82.github.io/ios-delegate/)이 좋은 것 같습니다. 여기를 봐보셔요.
- 위의 블로그 설명에 개인적으로는 제일 마음에 들었습니다. 위임자의 의미를 가지고 있습니다. 필요한 상황을 정의하고 대신 해달라고 요청하면 됩니다. 필요한 상황에 사용하면 좋습니다. 
- 저는 데이터를 공유하거나 기능처리 요청을 하는 여러 방법 중 가능하면 delegate 패턴부터 고민하고 이게 가용한 상황이 아니라면 다른 방법을 찾아봅니다.

#### 여러 컨트롤러에서 보여줘야하는 뷰가 있는데 재사용성을 높일수있는 방안이 있나요?
- xib 가 있습니다. 구글에 'xib' 만 검색하셔도 다양한 자료를 얻을 수 있습니다. nib 파일이라고도 합니다. 같은 개념으로 이해하시면 됩니다.
- Nib : Next Interface Builder
- Xib : Xcode Interface Builder

<br />

#### 푸시로 기본적으로 보내는 것 메시지 외에 다른 정보들을 보내고 싶은 데, 전송 시에 많은 정보를 담아 보낼 수 있나요?
- "ios push payload size" 정도로 구글링해보시면, 관련 정보를 얻을 수 있을 것 같습니다. 
- 예전에는 256 bytes 인 시절도 있었지만, 과거 이야기 이죠..
- [CreatingtheNotificationPayload 애플문서](https://developer.apple.com/library/archive/documentation/NetworkingInternet/Conceptual/RemoteNotificationsPG/CreatingtheNotificationPayload.html)
- [stackoverflow 관련글](https://stackoverflow.com/questions/26233730/apn-apple-push-notification-payload-size-limit) 

```
As per the updated Apple docs the size is 4KB.

For regular remote notifications, the maximum size is 4KB (4096 bytes)
For Voice over Internet Protocol (VoIP) notifications, the maximum size is 5KB (5120 bytes) NOTE
```


#### swift로 개발할때 c++ 라이브러리 사용할 수 있나요?
- 구글에서 `swift c++`정도로 검색을 하면 될 것 같습니다.
- Objc로 Wrapping해서 Bridge를 통해서 불러와야 합니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`11. design pattern`**
#### 아키텍쳐 패턴으로 공부할만한 좋은 셈플 링크가 있을까요?
- 제가 알고있는 셈플 링크입니다. 좋은 링크 알게 되는 데로 업데이트 더 할께요.
- [giftbot 님의 iOS-Architecture-Sample](https://github.com/giftbott/iOS-Architecture-Sample) : MVC, MVP, MVVM, VIPER 👍
- [ReactorKit](https://github.com/ReactorKit/ReactorKit) : RxSwift + MVVM
- [iOS-Viper-Architecture](https://github.com/kor45cw/iOS-Viper-Architecture) : VIPER
- [마기님의 MVP, RxTodo](https://github.com/magi82/IOS_MVP_Sample_RxTodo) : MVP + RxTodo
- [마기님의 MVVM](https://github.com/magi82/RxMVVMExample)
- [저의 MVVM 샘플](https://github.com/ClintJang/sample-swift-mvvm) : 언젠가 완성을..


#### MVC 패턴이 무엇인가요?
```
MVC는 Model-View-Controller의 약자입니다. 
개발할 때 3가지 형태로 구분하여 개발하는 소프트웨어 개발 방법론입니다.

그 3가지 요소를 설명하면
Model은 무엇을 할지 정의합니다. 비지니스 로직에서의 알고리즘, 데이터 등의 기능을 처합니다.
Controller는 어떻게 할지를 정의합니다. 화면의 처리기능과 Model과 View를 연결시켜주는 연활을 하지요. 
View는 화면을 보여주는 역할을 하지요. 웹이라면 웹페이지, 모바일이라면 어플의 화면의 보여지는 부분입니다.
MVC는 복잡한 대규모 프로그램을 개발을 하게 되면서 문제점이 확인되었습니다.

다수의 View와 Model이 Controller를 통해 복잡하게 연결될 수 있기 때문에 Controller가 뚱뚱해지게 되는 Massive ViewController(대규모 MVC 어플리케이션)가 되어버립니다.

View와 Controller가 라이브사이클에 강하게 연결되어있고, 더불어 Controller를 통해 View와 Model간에도 관계가 복잡하게 연결되어있어서 수정시 테스트가 힘들고, 파악이 어렵기 때문에 여러 Side-Effect를 불러오게 되는 문제점이 있습니다.

그래서 MVC는 위 문제점을 해결하기 위해 여러 페러다임을 수용한 다양한 패턴을 파생시켰습니다.
```
- [참조한 링크](https://medium.com/@jang.wangsu/%EB%94%94%EC%9E%90%EC%9D%B8%ED%8C%A8%ED%84%B4-mvc-%ED%8C%A8%ED%84%B4%EC%9D%B4%EB%9E%80-1d74fac6e256)

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`12. RxSwift`** 
#### RxSwift가 무엇인가요?
- 리엑티브 (Reactive eXtension) 라고 부르지요. Reactive는 같은 말로 알엑스(Rx) 라고 부릅니다. 리엑티브 페러다임은 마이크로소프트가 창안한 개념으로 데이터의 흐름에 따른 변화를 만드는 비동기적인 프로그래밍 패러다임을 구체화 시킨 swift용 라이브러리라고 생각하시면 됩니다.
- [http://reactivex.io/documentation/ko/observable.html](reactivex.io)에서 한국어가 지원되는 페이지가 있어서 처음에는 사이트를 이용하셔서 의미를 알아보셔도 좋습니다.
- RxSwift를 왜 하는 지 궁금하시면 곰튀김님 동영상 설명을 들으면 이해가 쏙쏙 됩니다. 정말 최고에요. 한번 보세요. 총 2편입니다. 1편부터 고고
	- 1편, [곰튀김님 - Functional Reactive Programming 패러다임](https://www.youtube.com/watch?v=cXi_CmZuBgg&feature=youtu.be)
	- 2편, [곰튀김님 - Functional Programming이 뭐하는 건가요? ](https://www.youtube.com/watch?v=HZkqMiwT-5A&feature=youtu.be)
- [Rx에겐 특별한 것이 있다.](https://iamchiwon.github.io/2018/11/29/rxhasmore/) 를 한번 읽어보세요.
- [RxSwift 왜 사용하면 좋을까요?](https://medium.com/@jang.wangsu/ios-swift-rxswift-%EC%99%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%A9%B4-%EC%A2%8B%EC%9D%84%EA%B9%8C%EC%9A%94-5c9995f47bab) : RxSwift 개발을 하면서 개인적인 생각을 작성해보았습니다.
- [마기님 블로그 RxSwift 1편](https://magi82.github.io/ios-rxswift-01/)을 봐보셔요. 여기 설명도 좋습니다. **계속 연재해주세요.!**
- 제가 정리한 [RxSwift관련 한국어 동영상 링크](https://github.com/ClintJang/awesome-swift-korean-lecture/blob/master/README.md#rxswift)도 참고하셔도 좋습니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`13. 기타`**
#### 애플 사이트나 시스템 운영 상태의 에러 유무는 어떻게 알 수가 있나요?
- 여기 링크에 들어가보시면 됩니다. 
- [System Status 링크](https://www.apple.com/support/systemstatus/)

#### iOS 배포 최소 버전에 대해 고민중입니다. iOS OS버전을 사용하는 통계 정보를 알 수 있는 정보나 링크가 있을까요?
- [애플 공식 제공 링크](https://developer.apple.com/support/app-store/)
- 점유율 (매년 9월 중순 즈음, 신규 OS를 업데이트 합니다.)
- iOS 12때의 마지막 통계정보에서 2019년 8월 6일 기준으로 iOS 11 이상 사용자가 97% 입니다. 
- iOS 13 반영되고 2019년 10월 15일 기준으로 iPhone iOS 12 이상은 93% 이군요.
	- 사용안하고 묵혀준 핸드폰이라던지, 테스트 장비나 어느정도 오래된 장비를 포함해서 말이죠.
	- 이제 iOS 13이 나왔는 데.. 이제 iOS 11 이상으로 해도 괜찮치 않을 까요? iOS 12 이상은? 아직 무리인가요?
	- 최대한 사용자를 받아들이는 것도 중요하겠지만, 조금 더 개발 품질을 높이고, 유지 보수 공수를 낮출 수 있도록 말이죠..

	<details><summary><b>국민 앱 카카오톡도 iOS는 iOS11 부터 지원합니다.</b> 상세 내용은 펴주세요.</summary>
	
	- 종료 일자 : 2019년 09월 17일
	- 종료 내용 : iOS 10.3.4 이하 버전에 대한 카카오톡 업데이트 지원중단
	
	<img width="400" src="/Image/kakao_only_support_ios11.jpeg">
	
	</details>

<details open><summary><b>2019년 점유율</b></summary>

<table>
   <tr>
   <th>2019년 10월 15일</th>
   <th>2019년 08월 06일</th>
   <th>2019년 05월 30일</th>
 	<th>2019년 02월 24일</th>
 	<th>2019년 01월 01일</th>
  </tr>
  <tr>
   <td>
   <table>
   		<tr>
   			<td>
   			<img width="160" src="/Image/AppStoreOSMeasured_20191015.png"></img>
   			</td>
   			<td>
   			<img width="160" src="/Image/AppStoreOSMeasured_20191015_ipad.png"></img>
   			</td>
   		</tr>
   	</table>
   </td>
  	<td><img width="160" src="/Image/AppStoreOSMeasured_20190806.png"></img></td>
	<td><img width="160" src="/Image/AppStoreOSMeasured_20190530_2.png"></img></td>
 	<td><img width="160" src="/Image/AppStoreOSMeasured_20190224_1.png"></img></td>
   <td><img width="160" src="/Image/AppStoreOSMeasured_20190101_1.png"></td>
  </tr>
</table>

</details>

<details open><summary><b>2018년 점유율</b></summary>

<table>
  <tr>
 	<th>2018년 12월 03일</th>
   <th>2018년 10월 29일</th>
   <th>2018년 10월 10일</th> 
	<th>2018년 09월 03일</th> 
	<th>2018년 04월 22일</th>
  </tr>
  <tr>
 	<td><img width="160" src="/Image/AppStoreOSMeasured_20181203_1.jpg"></img></td>
   <td><img width="160" src="/Image/AppStoreOSMeasured_20181029_2.jpeg"></img></td>
   <td><img width="160" src="/Image/AppStoreOSMeasured_20181010_01.jpeg"></img></td>
  	<td><img width="160" src="/Image/AppStoreOSMeasured_20180903.png"></img></td>
  	<td><img width="160" src="/Image/AppStoreOSMeasured_20180422.png"></img></td>
  	
  </tr>
</table>

</details>


<details><summary><b>2017년 점유율</b> (12월 4일, 07월 28일, 2월 20일, 접힌 것을 펴주세요.)</summary>

<table>
  <tr>
	<th>2017년 12월 04일</th>
	<th>2017년 07월 28일</th>
	<th>2017년 02월 20일</th>
	<th>-</th>
	<th>-</th>
  </tr>
    <tr>
    <td><img width="160" src="/Image/AppStoreOSMeasured_20171204.png"></img></td>
    <td><img width="160" src="/Image/AppStoreOSMeasured_20170728.png"></img></td>
  	<td><img width="160" src="/Image/AppStoreOSMeasured_20170220.png"></img></td>
  	<td width="160" ></td>
  	<td width="160" ></td>
  </tr>
</table>

</details>
<br />

---

- 최신 OS가 높은 점유율을 차지 하고 있고, 이전 OS까지 합하면 90%가 넘을 것 입니다. 그래서 보통 반영한다면, 현재와 이전 정보까지를 포함해서 배포하면 좋을 것 같습니다.
- iOS 사용자는 업데이트를 빠르게 수용합니다. Earlier 는 테스트 장비나 오래되서 방치된 단말이 많이 포함되어있을 것입니다. 빠르게 업데이트해서 사용하니 최신 OS에 근접한 OS를 하셔도 괜찮을 것입니다. 그래야 유지보수 이슈에 들어가는 비용도 줄어들고, 신기술을 적용하기 좋습니다. 그만큼 사용시 문제점(버그)도 줄어들죠.
- [iOS 10, 11, 12, 13에서 호환되는 기기.. 에 대한 메모 내용입니다.](https://medium.com/@jang.wangsu/ios-ios-10-11-12-13%EC%97%90%EC%84%9C-%ED%98%B8%ED%99%98%EB%90%98%EB%8A%94-%EA%B8%B0%EA%B8%B0-cc2a65ca577e) : 판단에 참고가 되실 것 같아요.


## 이전 OS,Xcode 나 최신 OS, Xcode를 받으려면 어디서 받을 수 있을까요?
- [download 링크](https://developer.apple.com/download/) : 다운로드 링크 입니다. 최신 다운로드 정보를 알 수 있습니다.
- [download more 링크](https://developer.apple.com/download/more/) : 지나간 다운로드 정보를 찾을 수 있습니다.

## 새로운 iOS에 대한 beta일정 같은걸 확인할수 있는 곳이 있나요?
- [news 링크](https://developer.apple.com/news/) : 다운로드 링크 입니다. 최신 다운로드 정보를 알 수 있습니다.
- [releases 링크](https://developer.apple.com/news/releases/) : 지나간 다운로드 정보를 찾을 수 있습니다.
- 다운로드 링크는 바로 위의 질문의 답변 링크를 보시면 될 것 같습니다.

<br /><br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />

# Contributors
> 항상 환영합니다.

- [Jo Sesang](https://github.com/sesang06)
- [JERCY](https://github.com/JeaSungLEE)
- [ClintJang](https://github.com/clintjang)

<br /><br />즐거운 하루 되세요 🙇‍
<br />
