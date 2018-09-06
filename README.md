# iOS(Swift, Objc) 질문과 답변 모음

## **소개**
iOS (swift, objc)개발을 하면서 알게된 질문과 답변 내용을 모아보았습니다. 개발 언어는 공부를 하면 빠르게 익힐 수 있지만, 개발 경험은 물어보고 정보를 얻기가 쉽지 않습니다. 도움이 될 수 있도록 정리를 꼼꼼히 해보겠습니다.

잘못 작성된 정보는 열심히 수정 하겠습니다. 언제든지 문제가 있으면, 편하게 수정해주세요. 

지금은 작성을 시작해서 내용이 적지만, 알차게 계속 업데이트 하겠습니다.

## **목차**
- [1. 개발입문](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#1-%EA%B0%9C%EB%B0%9C%EC%9E%85%EB%AC%B8)
	- [Swift 공부할 때 보면 좋은 책은 어떤 것이 있을 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#swift-%EA%B3%B5%EB%B6%80%ED%95%A0-%EB%95%8C-%EB%B3%B4%EB%A9%B4-%EC%A2%8B%EC%9D%80-%EC%B1%85%EC%9D%80-%EC%96%B4%EB%96%A4-%EA%B2%83%EC%9D%B4-%EC%9E%88%EC%9D%84-%EA%B9%8C%EC%9A%94)
	- [Swift 개발을 처음 시작할 때 공부하기 좋은 링크 가 있을 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#swift-%EA%B0%9C%EB%B0%9C%EC%9D%84-%EC%B2%98%EC%9D%8C-%EC%8B%9C%EC%9E%91%ED%95%A0-%EB%95%8C-%EA%B3%B5%EB%B6%80%ED%95%98%EA%B8%B0-%EC%A2%8B%EC%9D%80-%EB%A7%81%ED%81%AC-%EA%B0%80-%EC%9E%88%EC%9D%84-%EA%B9%8C%EC%9A%94)
	- [Objective C 공부할 좋은 방법이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#objective-c-%EA%B3%B5%EB%B6%80%ED%95%A0-%EC%A2%8B%EC%9D%80-%EB%B0%A9%EB%B2%95%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
	- [처음 개발에 입문 했는 데, 좋은 커뮤니티가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%B2%98%EC%9D%8C-%EA%B0%9C%EB%B0%9C%EC%97%90-%EC%9E%85%EB%AC%B8-%ED%96%88%EB%8A%94-%EB%8D%B0-%EC%A2%8B%EC%9D%80-%EC%BB%A4%EB%AE%A4%EB%8B%88%ED%8B%B0%EA%B0%80-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
- [2. appstore](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#2-appstore)
	- [애플 개발자 전화 지원은 몇번인가요? 전화가 가능한가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%A0%ED%94%8C-%EA%B0%9C%EB%B0%9C%EC%9E%90-%EC%A0%84%ED%99%94-%EC%A7%80%EC%9B%90%EC%9D%80-%EB%AA%87%EB%B2%88%EC%9D%B8%EA%B0%80%EC%9A%94-%EC%A0%84%ED%99%94%EA%B0%80-%EA%B0%80%EB%8A%A5%ED%95%9C%EA%B0%80%EC%9A%94)
	- [AppStore에 검수 신청하면 얼마나 걸리나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#appstore%EC%97%90-%EA%B2%80%EC%88%98-%EC%8B%A0%EC%B2%AD%ED%95%98%EB%A9%B4-%EC%96%BC%EB%A7%88%EB%82%98-%EA%B1%B8%EB%A6%AC%EB%82%98%EC%9A%94)
	- [앱스토어를 등록하기 전에 UUID(디바이스) 등록 안된 분들이 테스트 해볼려면 어떻게 해야될 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%B1%EC%8A%A4%ED%86%A0%EC%96%B4%EB%A5%BC-%EB%93%B1%EB%A1%9D%ED%95%98%EA%B8%B0-%EC%A0%84%EC%97%90-uuid%EB%94%94%EB%B0%94%EC%9D%B4%EC%8A%A4-%EB%93%B1%EB%A1%9D-%EC%95%88%EB%90%9C-%EB%B6%84%EB%93%A4%EC%9D%B4-%ED%85%8C%EC%8A%A4%ED%8A%B8-%ED%95%B4%EB%B3%BC%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%EB%90%A0-%EA%B9%8C%EC%9A%94)
	- [정말 급하게 앱스토어에 등록해야되는 데.. 어떻게 해야될 까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%A0%95%EB%A7%90-%EA%B8%89%ED%95%98%EA%B2%8C-%EC%95%B1%EC%8A%A4%ED%86%A0%EC%96%B4%EC%97%90-%EB%93%B1%EB%A1%9D%ED%95%B4%EC%95%BC%EB%90%98%EB%8A%94-%EB%8D%B0-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC%EB%90%A0-%EA%B9%8C%EC%9A%94)
	- [검수통과해서 "판매 준비됨"으로 바뀌었는 데, 왜? iOS 앱스토어에서 검색하면 나타나지 않을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B2%80%EC%88%98%ED%86%B5%EA%B3%BC%ED%95%B4%EC%84%9C-%ED%8C%90%EB%A7%A4-%EC%A4%80%EB%B9%84%EB%90%A8%EC%9C%BC%EB%A1%9C-%EB%B0%94%EB%80%8C%EC%97%88%EB%8A%94-%EB%8D%B0-%EC%99%9C-ios-%EC%95%B1%EC%8A%A4%ED%86%A0%EC%96%B4%EC%97%90%EC%84%9C-%EA%B2%80%EC%83%89%ED%95%98%EB%A9%B4-%EB%82%98%ED%83%80%EB%82%98%EC%A7%80-%EC%95%8A%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [appstore에서 앱 다운로드 할때 단말별로 앱사이즈가 다른가요?? 이미지 해상도라던지.. 차이때문에, 만약에 다르다면 영향 받는 부분이 어디일까요?
](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#appstore%EC%97%90%EC%84%9C-%EC%95%B1-%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C-%ED%95%A0%EB%95%8C-%EB%8B%A8%EB%A7%90%EB%B3%84%EB%A1%9C-%EC%95%B1%EC%82%AC%EC%9D%B4%EC%A6%88%EA%B0%80-%EB%8B%A4%EB%A5%B8%EA%B0%80%EC%9A%94-%EC%9D%B4%EB%AF%B8%EC%A7%80-%ED%95%B4%EC%83%81%EB%8F%84%EB%9D%BC%EB%8D%98%EC%A7%80-%EC%B0%A8%EC%9D%B4%EB%95%8C%EB%AC%B8%EC%97%90-%EB%A7%8C%EC%95%BD%EC%97%90-%EB%8B%A4%EB%A5%B4%EB%8B%A4%EB%A9%B4-%EC%98%81%ED%96%A5-%EB%B0%9B%EB%8A%94-%EB%B6%80%EB%B6%84%EC%9D%B4-%EC%96%B4%EB%94%94%EC%9D%BC%EA%B9%8C%EC%9A%94)
- [3. Xcode](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#3-xcode)
	- [Xcode에서 자동완성이 안될 때는?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#xcode%EC%97%90%EC%84%9C-%EC%9E%90%EB%8F%99%EC%99%84%EC%84%B1%EC%9D%B4-%EC%95%88%EB%90%A0-%EB%95%8C%EB%8A%94)
- [4. 시뮬레이터](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#4-%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0)
	- [시뮬레이터 재설정 하는 방법은?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%8B%9C%EB%AE%AC%EB%A0%88%EC%9D%B4%ED%84%B0-%EC%9E%AC%EC%84%A4%EC%A0%95-%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95%EC%9D%80)
- [5. reject](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#5-reject)
	- [로그인을 하기위해 정보(전호번호등..)가 필요하다고 리젝 당했습니다.😭](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%A1%9C%EA%B7%B8%EC%9D%B8%EC%9D%84-%ED%95%98%EA%B8%B0%EC%9C%84%ED%95%B4-%EC%A0%95%EB%B3%B4%EC%A0%84%ED%98%B8%EB%B2%88%ED%98%B8%EB%93%B1%EA%B0%80-%ED%95%84%EC%9A%94%ED%95%98%EB%8B%A4%EA%B3%A0-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%96%88%EC%8A%B5%EB%8B%88%EB%8B%A4-)
	- [쇼셜(SNS) 로그인만 있으면 리젝 당하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%87%BC%EC%85%9Csns-%EB%A1%9C%EA%B7%B8%EC%9D%B8%EB%A7%8C-%EC%9E%88%EC%9C%BC%EB%A9%B4-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [비디오에 대한 링크를 제공하라는 데? 무슨 의미일까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%87%BC%EC%85%9Csns-%EB%A1%9C%EA%B7%B8%EC%9D%B8%EB%A7%8C-%EC%9E%88%EC%9C%BC%EB%A9%B4-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [웹뷰로만 된 앱은 리젝인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9B%B9%EB%B7%B0%EB%A1%9C%EB%A7%8C-%EB%90%9C-%EC%95%B1%EC%9D%80-%EB%A6%AC%EC%A0%9D%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [페이지 한개 짜리 앱이 리젝 사유인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%ED%8E%98%EC%9D%B4%EC%A7%80-%ED%95%9C%EA%B0%9C-%EC%A7%9C%EB%A6%AC-%EC%95%B1%EC%9D%B4-%EB%A6%AC%EC%A0%9D-%EC%82%AC%EC%9C%A0%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [앱내 공지사항에 안드 출시소식 있다구 리젝 당하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%B1%EB%82%B4-%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD%EC%97%90-%EC%95%88%EB%93%9C-%EC%B6%9C%EC%8B%9C%EC%86%8C%EC%8B%9D-%EC%9E%88%EB%8B%A4%EA%B5%AC-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [강제 종료 함수를 사용하면 리젝 당하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EA%B0%95%EC%A0%9C-%EC%A2%85%EB%A3%8C-%ED%95%A8%EC%88%98%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EB%A9%B4-%EB%A6%AC%EC%A0%9D-%EB%8B%B9%ED%95%98%EB%82%98%EC%9A%94)
	- [아이폰X 대응 안하면 리젝인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%84%EC%9D%B4%ED%8F%B0x-%EB%8C%80%EC%9D%91-%EC%95%88%ED%95%98%EB%A9%B4-%EB%A6%AC%EC%A0%9D%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [우리 앱은 iPhone만 지원하고 iPad를 지원안하는 데, iPad에서 실행했을 때 더이상 진행할 수 없다고 사진과 합께 리젝 내용을 받았습니다. 😭](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%9A%B0%EB%A6%AC-%EC%95%B1%EC%9D%80-iphone%EB%A7%8C-%EC%A7%80%EC%9B%90%ED%95%98%EA%B3%A0-ipad%EB%A5%BC-%EC%A7%80%EC%9B%90%EC%95%88%ED%95%98%EB%8A%94-%EB%8D%B0-ipad%EC%97%90%EC%84%9C-%EC%8B%A4%ED%96%89%ED%96%88%EC%9D%84-%EB%95%8C-%EB%8D%94%EC%9D%B4%EC%83%81-%EC%A7%84%ED%96%89%ED%95%A0-%EC%88%98-%EC%97%86%EB%8B%A4%EA%B3%A0-%EC%82%AC%EC%A7%84%EA%B3%BC-%ED%95%A9%EA%BB%98-%EB%A6%AC%EC%A0%9D-%EB%82%B4%EC%9A%A9%EC%9D%84-%EB%B0%9B%EC%95%98%EC%8A%B5%EB%8B%88%EB%8B%A4-)
- [6. 라이브러리 사용](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#6-%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9)
	- [라이브러리 사용을 하려면 어떻게 해야 되나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%9D%BC%EC%9D%B4%EB%B8%8C%EB%9F%AC%EB%A6%AC-%EC%82%AC%EC%9A%A9%EC%9D%84-%ED%95%98%EB%A0%A4%EB%A9%B4-%EC%96%B4%EB%96%BB%EA%B2%8C-%ED%95%B4%EC%95%BC-%EB%90%98%EB%82%98%EC%9A%94)
- [7. 디자인](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#7-%EB%94%94%EC%9E%90%EC%9D%B8)
	- [안드로이드는 UI 개발 중 크기 선택은 dp로 작업하는 데 iOS에서는 dp를 지원하나요? 현업에서는 보통 디자이너에게 요구할때 어떻게 요구를 하나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%88%EB%93%9C%EB%A1%9C%EC%9D%B4%EB%93%9C%EB%8A%94-ui-%EA%B0%9C%EB%B0%9C-%EC%A4%91-%ED%81%AC%EA%B8%B0-%EC%84%A0%ED%83%9D%EC%9D%80-dp%EB%A1%9C-%EC%9E%91%EC%97%85%ED%95%98%EB%8A%94-%EB%8D%B0-ios%EC%97%90%EC%84%9C%EB%8A%94-dp%EB%A5%BC-%EC%A7%80%EC%9B%90%ED%95%98%EB%82%98%EC%9A%94-%ED%98%84%EC%97%85%EC%97%90%EC%84%9C%EB%8A%94-%EB%B3%B4%ED%86%B5-%EB%94%94%EC%9E%90%EC%9D%B4%EB%84%88%EC%97%90%EA%B2%8C-%EC%9A%94%EA%B5%AC%ED%95%A0%EB%95%8C-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%9A%94%EA%B5%AC%EB%A5%BC-%ED%95%98%EB%82%98%EC%9A%94)
- [8. Apple 개발: UIKit](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#8-apple-%EA%B0%9C%EB%B0%9C-uikit)
	- [멀티 터치 는 최대 갯수가 5개 인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%A9%80%ED%8B%B0-%ED%84%B0%EC%B9%98-%EB%8A%94-%EC%B5%9C%EB%8C%80-%EA%B0%AF%EC%88%98%EA%B0%80-5%EA%B0%9C-%EC%9D%B8%EA%B0%80%EC%9A%94)
- [9. Apple 개발: Foundation](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#9-apple-%EA%B0%9C%EB%B0%9C-foundation)
- [10. Apple 개발: 그외](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#10-apple-%EA%B0%9C%EB%B0%9C-%EA%B7%B8%EC%99%B8)
	- [delegate 는 어떻게 사용하는 것인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#delegate-%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EA%B2%83%EC%9D%B8%EA%B0%80%EC%9A%94)
	- [여러 컨트롤러에서 보여줘야하는 뷰가 있는데 재사용성을 높일수있는 방안이 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%97%AC%EB%9F%AC-%EC%BB%A8%ED%8A%B8%EB%A1%A4%EB%9F%AC%EC%97%90%EC%84%9C-%EB%B3%B4%EC%97%AC%EC%A4%98%EC%95%BC%ED%95%98%EB%8A%94-%EB%B7%B0%EA%B0%80-%EC%9E%88%EB%8A%94%EB%8D%B0-%EC%9E%AC%EC%82%AC%EC%9A%A9%EC%84%B1%EC%9D%84-%EB%86%92%EC%9D%BC%EC%88%98%EC%9E%88%EB%8A%94-%EB%B0%A9%EC%95%88%EC%9D%B4-%EC%9E%88%EB%82%98%EC%9A%94)
- [11. design pattern](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#11-design-pattern)
	- [아키텍쳐 패턴으로 공부할만한 좋은 셈플 링크가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90-%ED%8C%A8%ED%84%B4%EC%9C%BC%EB%A1%9C-%EA%B3%B5%EB%B6%80%ED%95%A0%EB%A7%8C%ED%95%9C-%EC%A2%8B%EC%9D%80-%EC%85%88%ED%94%8C-%EB%A7%81%ED%81%AC%EA%B0%80-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
	- [MVC 패턴이 무엇인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#mvc-%ED%8C%A8%ED%84%B4%EC%9D%B4-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
- [12. RxSwift](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#12-rxswift)
	- [RxSwift가 무엇인가요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#rxswift%EA%B0%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80%EC%9A%94)
- [13. 기타](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#13-%EA%B8%B0%ED%83%80)
	- [애플 사이트나 시스템 운영 상태의 에러 유무는 어떻게 알 수가 있나요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EC%95%A0%ED%94%8C-%EC%82%AC%EC%9D%B4%ED%8A%B8%EB%82%98-%EC%8B%9C%EC%8A%A4%ED%85%9C-%EC%9A%B4%EC%98%81-%EC%83%81%ED%83%9C%EC%9D%98-%EC%97%90%EB%9F%AC-%EC%9C%A0%EB%AC%B4%EB%8A%94-%EC%96%B4%EB%96%BB%EA%B2%8C-%EC%95%8C-%EC%88%98%EA%B0%80-%EC%9E%88%EB%82%98%EC%9A%94)
	- [iOS 배포 최소 버전에 대해 고민중입니다. iOS OS버전을 사용하는 통계 정보를 알 수 있는 정보나 링크가 있을까요?](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#ios-%EB%B0%B0%ED%8F%AC-%EC%B5%9C%EC%86%8C-%EB%B2%84%EC%A0%84%EC%97%90-%EB%8C%80%ED%95%B4-%EA%B3%A0%EB%AF%BC%EC%A4%91%EC%9E%85%EB%8B%88%EB%8B%A4-ios-os%EB%B2%84%EC%A0%84%EC%9D%84-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%ED%86%B5%EA%B3%84-%EC%A0%95%EB%B3%B4%EB%A5%BC-%EC%95%8C-%EC%88%98-%EC%9E%88%EB%8A%94-%EC%A0%95%EB%B3%B4%EB%82%98-%EB%A7%81%ED%81%AC%EA%B0%80-%EC%9E%88%EC%9D%84%EA%B9%8C%EC%9A%94)
	
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
- 보통 케바케라서 정확하지 않습니다. 평균적인 시간보다 오래 걸린다면, 검수 진행에 대해 문의를 진행해 해보시면 될 것 같습니다. 

#### 앱스토어를 등록하기 전에 UUID(디바이스) 등록 안된 분들이 테스트 해볼려면 어떻게 해야될 까요?
1. 개인 및 법인 계정이라면 : [Apple TestFlight](https://developer.apple.com/testflight/) 가 있습니다. 
	- 구글에서 "TestFlight 사용법" 으로 검색을 해보셔요.
2. 기업(Enterprice) 계정이라면 : 디바이스 등록없이 기업내 배포가 가능합니다. 단, 자사 외의 다른 목적으로 배포시 계정이 블락 될 수 있습니다. (알고 계시는 분들이 애플에 신고도 가능할 수 있어요~)

#### 정말 급하게 앱스토어에 등록해야되는 데.. 어떻게 해야될 까요?
- [긴급 리뷰 요청](https://developer.apple.com/contact/app-store/?topic=expedite)이 있습니다. 정말 긴급할 때만 사용하세요..
- "appstore 긴급 리뷰 요청" 정도로 구글에 검색하면 방법을 알 수 있습니다.

	```
	빠른 앱 심사

	참작이 가능한 상황에 직면하는 경우 빠른 앱 심사를 요청할 수 있습니다. 
	이러한 상황으로는 App Store에 있는 앱의 심각한 버그를 수정하거나 직접 관련된 이벤트와 동시에 앱을 출시해야 하는 경우 등이 해당됩니다.
	```

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

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`4. 시뮬레이터`**
#### 시뮬레이터 재설정 하는 방법은?
1. 시뮬레이터 실행 후 왼쪽 상단 메뉴에서 중에서 

```
Hardware -> Erase All Content and Settings..  
```
2. 팝업에서 Erase 를 선택하시면됩니다.

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

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`7. 디자인`**
#### 안드로이드는 UI 개발 중 크기 선택은 dp로 작업하는 데 iOS에서는 dp를 지원하나요? 현업에서는 보통 디자이너에게 요구할때 어떻게 요구를 하나요?
- iOS에서는 dp를 사용하지 않습니다. point라는 개념을 사용합니다. 
- [제드님의 블러그 링크](https://zeddios.tistory.com/6)를 들어가 보세요. 제일 설명이 잘 되어있는 것 같습니다.
- [제플린](https://zeplin.io/) 이라는 협업 툴로 개발을 많이 합니다. iOS용으로 제공받으면 편하게 개발 하실 수 있습니다.
- 유지보수 관점에서 디자이너 분들과 협의하면 좋은 결과를 도출 할 수 있을 것입니다. 파이팅!

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`8. Apple 개발: UIKit`**
#### 멀티 터치 는 최대 갯수가 5개 인가요?
- iPhone 류에서는 5개 입니다.
- iPad 류에서는 11개 입니다.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br />
<br />

### **`9. Apple 개발: Foundation`**

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
View는 화면을 보여주는 역활을 하지요. 웹이라면 웹페이지, 모바일이라면 어플의 화면의 보여지는 부분입니다.
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
- 리엑티브 (Reactive eXtension) 라고 부르지요. Reactive는 같은 말로 알엑스(Rx) 라고 부릅니다. 리엑티브 페러다임은 마이크로소프트가 창안한 개념으로 데이터의 흐름에 따른 변화를 만드는 비동기적인 프로그래밍 패러다임입니다.
- RxSwift가 궁금하시면 곰튀김님 동영상 설명을 들으면 이해가 쏙쏙 됩니다. 정말 최고에요. 한번 보세요. 총 2편입니다. 1편부터 고고
	- 1편, [곰튀김님 - Functional Reactive Programming 패러다임](https://www.youtube.com/watch?v=cXi_CmZuBgg&feature=youtu.be)
	- 2편, [곰튀김님 - Functional Programming이 뭐하는 건가요? ](https://www.youtube.com/watch?v=HZkqMiwT-5A&feature=youtu.be)
- [마기님 블로그 RxSwift 1편](https://magi82.github.io/ios-rxswift-01/)을 봐보셔요. 여기 설명도 좋습니다. **계속 연재해주세요.!**

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

<table>
  <tr>
	<th>2018년 09월 03일</th> 
	<th>2017년 12월 04일</th>
	<th>2017년 02월 20일</th>
  </tr>
  <tr>
  	<td><img width="236" height="321" src="/Image/AppStoreOSMeasured_20180903.png"></img></td>
  	<td><img width="217" height="326" src="/Image/AppStoreOSMeasured_20171204.png"></img></td>
  	<td><img width="211" height="352" src="/Image/AppStoreOSMeasured_20170220.png"></img></td>
  </tr>
</table>
- iOS 사용자는 업데이트를 빠르게 수용합니다. Earlier 는 테스트 장비나 오래되서 방치된 단말이 많이 포함되어있을 것입니다. 빠르게 업데이트해서 사용하니 최신 OS에 근접한 OS를 하셔도 괜찮을 것입니다. 그래야 유지보수 이슈에 들어가는 비용도 줄어들고, 신기술을 적용하기 좋습니다. 그만큼 사용시 문제점(버그)도 줄어들죠.

<br />

[Top으로 가기](https://github.com/ClintJang/ios-swift-objc-questions-and-answers/blob/master/README.md#%EB%AA%A9%EC%B0%A8)

<br /><br /><br />즐거운 하루 되세요 🙇‍
<br />
