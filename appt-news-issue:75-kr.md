# Appt News Issue #75 - 한국어 번역

번역 날짜: 2025년 11월 12일
원본 해시: 8bbc2f69efd4f2bb50052c166ab8ee41373543cbd86ad60452fa9221c7131992

---

# Appt News (접근 가능한 모바일 앱) - Issue #75

안녕하세요,

이번 호에서는 접근성 뉴스를 전해줄 특별 게스트가 있습니다! [Daniel Devesa Derksen-Staats](https://www.linkedin.com/in/ACoAAAddFqsBZwIBQzaaJzWCPkPlL5CFAxXi5Rc?lipi=urn%3Ali%3Apage%3Ad_flagship3_messaging_conversation_detail%3BR5NGHPhTQZeVocTt4tJsgA%3D%3D&ref=appt.news)는 iOS 엔지니어이자 네이티브 접근성 전문가입니다. 그의 [블로그](https://accessibilityupto11.com/?ref=appt.news)나 [저서 "Developing Accessible iOS Apps: Support VoiceOver, Dynamic Type, and More"](https://www.amazon.com/Developing-Accessible-iOS-Apps-VoiceOver/dp/1484253078?ref=appt.news) 또는 접근성에 관한 컨퍼런스 강연으로 그를 알고 계실 겁니다. 더 이상의 말은 생략하고, Dani의 소식으로 바로 가보겠습니다!

## Daniel Devesa Derksen-Staats의 뉴스

[SwiftLeeds](https://swiftleeds.co.uk/?ref=appt.news)가 몇 주 전에 열렸는데, 언제나처럼 훌륭한 컨퍼런스였습니다! 올해의 몇 가지 하이라이트를 공유하고 싶습니다.

첫째, 놀라운 일이 있었습니다: 사람들이 접근성에 대해 더 배우려면 누구를 팔로우해야 하는지 자주 물어보는데, 그들 중 많은 분들이 한 자리에 모두 모였습니다. 그들과 함께 사진을 찍지 않을 수 없었습니다. 여기 그 사진과 함께 그들의 Mastodon 핸들이 있습니다. 보너스: Bas의 훌륭한 대체 텍스트의 좋은 예시입니다:

kg-card-begin: html
> Post by @bas@iosdev.spaceView on Mastodon

kg-card-end: html
둘째, 제 좋은 친구 Rob과 함께 접근성 드롭인 세션을 진행했습니다. 접근성과 관련하여 커뮤니티가 무엇을 생각하고 있는지 (그리고 무엇을 어려워하는지) 듣는 것은 언제나 좋습니다.

몇 가지 요점:

- **인식이 여전히 가장 큰 장애물입니다**. 흥미롭게도, 자신의 앱 접근성이 "나쁘다"고 말하는 사람들은 종종 자신에게 너무 가혹하며, 그들은 보통 "더 나아지기를 바란다"는 뜻입니다. 그들은 관심을 갖고, 배우고 있으며, 그들의 앱은 보통 평균보다 훨씬 낫습니다.

- 일부 개발자들은 접근성을 개선하기 위한 적극적인 작업을 많이 하지 않았기 때문에 자신의 앱이 접근 가능하지 않다고 생각합니다. 그러나 접근성이 많은 추가 작업을 의미한다는 일반적인 통념에도 불구하고, **때로는 적은 것이 더 좋습니다**. 저는 작은 스타트업에서 유일한 모바일 개발자로 일할 때 몇 년 전에 처음으로 접근성이라는 단어를 들었습니다. 시간을 절약하기 위해 네이티브 컴포넌트를 고수하고 불필요한 커스터마이징을 피했습니다. 어느 날, 앱을 접근 가능하게 만들어줘서 고맙다는 앱스토어 리뷰를 받았습니다. 저는 팀에게 "접근 가능하다는 게 뭔가요?"라고 말하고 이어서 "저는 아무것도 하지 않았는데요!"라고 말했습니다. 결국 간단하게 유지함으로써 제가 한 일이었습니다.

- 우리는 여전히 **같은 생각을 가진 사람들에게만 설교하고 있습니다**. 다른 사람들이 우리만큼 관심을 갖게 하려면 어떻게 해야 할까요?

**접근성은 여전히 상향식으로 추진됩니다**. 조직 내의 놀라운 모바일 개발자들이 주도합니다. 계속해서 훌륭한 일을 하세요! 회사에서 마찰을 겪을 때 정말 쉽지 않습니다. 유럽 접근성법이 우리가 일할 수 있는 여유를 조금 더 준 것 같지만, 많은 회사들에게 주요 목표는 여전히 법적 조치를 피하는 것인 것 같습니다. 그리고 우리는 그것이 접근성의 본질이 아니라는 것을 알고 있습니다.

앱을 더 접근 가능하고 포용적으로 만들기 위해 노력하는 모든 분들께 감사드립니다.

## iOS 개발자를 위한...

### 학습 가능하고, 기억 가능하며, 접근 가능한

네이티브 컴포넌트를 사용하는 것이 앱을 접근 가능하게 유지하는 가장 좋은 방법 중 하나라고 전에 말씀드렸습니다. 하지만 때로는 커스텀 컴포넌트를 만들어야 할 필요가 있습니다... 사용 가능한 옵션이 브랜드를 표현하기에 충분히 유연하지 않거나, 기본적으로 지원되지 않는 기능을 추가하고 싶을 수 있습니다. 그럴 때, [Jordan Morgan](https://x.com/jordanmorgan10?ref=appt.news)은 학습 가능하고, 기억 가능하며, 물론... 접근 가능하게 만들 것을 올바르게 제안합니다!

### 향상된 접근성

SwiftLeeds의 드롭인 세션에서 나온 또 다른 훌륭한 결과입니다! [Daniel Saidi](https://danielsaidi.com/?ref=appt.news)가 들러서 [KeyboardKit](https://keyboardkit.com/?ref=appt.news)을 더 접근 가능하게 만드는 방법에 대해 이야기했습니다. [keyboardKey](https://developer.apple.com/documentation/uikit/uiaccessibilitytraits/keyboardkey?ref=appt.news) 접근성 특성을 사용하고 싶지 않았던 사람이 있을까요? 저는 확실히 그랬습니다! 그래서 우리처럼 가장 모호한 접근성 API와 기능에 대해 열정적으로 탐구하는 것을 즐긴다면, 이것을 좋아하실 것입니다.

### 터치프리 터치 스크린 | iOSKonf25 | Rob Whitaker

때때로 강연을 보고 "내가 그 아이디어를 생각해냈으면 좋았을 텐데!"라고 생각합니다. [Rob Whitaker](https://mastodon.social/@RobW@iosdev.space?ref=appt.news)의 이 강연이 바로 그것입니다. 저는 종종 접근성이란 사람들이 여러 입력 및 출력 메커니즘을 통해 앱을 사용하고 정보를 소비할 수 있도록 사용자 인터페이스를 추상화하는 것이라고 말합니다. Rob은 그 아이디어를 한 단계 더 발전시켜, 사용자가 화면을 터치하지 않고도 앱과 상호작용할 수 있는 모든 방법을 보여줍니다. 또한 "같은 생각을 가진 사람들에게만 설교하는" 문제를 해결하는 좋은 예시입니다: 표면적으로는 접근성에 관한 것처럼 보이지 않지만 사람들이 진정으로 관심을 갖게 만드는 재미있는 강연입니다.

### Robin Kanatzar, 앱 접근성 연사 및 개발자

우리의 [Robin Kanatzar](https://iosdev.space/@Robinkanatzar@mastodon.green?ref=appt.news)는 접근성을 옹호하고 그에 대한 애정을 퍼뜨리는 놀라운 일을 계속하고 있습니다. 전체 에피소드를 들으시면, 그녀가 (에피소드를 녹화한 후 얼마 지나지 않아) 호스트와 다시 만나 방 안의 코끼리, 즉 접근성과 Liquid Glass에 대한 생각을 공유하는 순간을 들으실 수 있습니다.

### Swift Connection 2025 - Ben Freiband - 사람들이 접근성에 대해 오해하는 것

그리고 접근 가능한 iOS 앱을 개발할 때 때로는 적은 것이 더 좋다고 제가 앞서 말했을 때 믿지 않으셨다면, 제 말만 믿지 마세요. [Ben Freiband](https://iosdev.space/@benfreiband@mastodon.social?ref=appt.news)가 올해 Swift Connection에서 바로 그것에 대한 전체 강연을 했습니다.

## Android 개발자를 위한...

DroidCon 시즌입니다! 다음은 베를린과 방글라데시에서 열린 컨퍼런스 에디션에서 진행된 접근성 세션 중 일부입니다

### It's All About Focus - and Accessibility - Eeva-Jonna Panula | droidcon Berlin 2025:

이 강연에서 Eeva-Jonna는 포커스 관리와 내비게이션 순서가 Android에서 접근성을 어떻게 뒷받침하는지 탐구합니다. 그녀는 포커스 동작 변경이 보조 기술 사용자에게 어떻게 영향을 미칠 수 있는지에 대한 예시를 다룹니다.

### Navigating the Roadblocks to European Accessibility Act - Maxim Malisciuc | droidcon Berlin 2025

Maxim은 Android 앱을 유럽 접근성법(EAA)에 맞추는 실질적인 과제들을 다룹니다. 그는 규제, 접근성 서비스 사용의 함정 및 Android 개발자들이 주의해야 할 사항들을 다룹니다.

### Building Inclusive and Accessible Android Apps - Sashoto Seeam

Sashoto는 접근성이 내장된 Android 앱 구축에 대한 개발자 중심의 안내를 제공합니다: 디자인 선택, 기술 구현 및 포용적 자동화 전략입니다.

### What's New in Google Accessibility – Episode 10

텍스트 윤곽선이 앱 전반에 걸쳐 텍스트에 더 나은 대비를 제공하며 도움을 줍니다. 이제 키보드도 확대할 수 있습니다. 그리고 제가 가장 좋아하는 업데이트: 이제 접근성 설정으로 직접 딥링크할 수 있습니다!

오늘 호는 여기까지입니다! 즐거우셨기를 바랍니다.

이번 달 게스트 작성을 해준 Dani에게 큰 감사를 드립니다!

다음 달을 위한 피드백과 기사 제안은 [hello@robinkanatzar.com](mailto:hello@robinkanatzar.com)으로 자유롭게 보내주세요. [Mastodon](https://iosdev.space/@dadederk?ref=appt.news) 또는 [LinkedIn](https://www.linkedin.com/in/danieldevesa/?ref=appt.news) 또는 [X](https://x.com/dadederk?ref=appt.news)에서 Dani를 팔로우하세요.

감사합니다,

[Robin](https://www.linkedin.com/in/robin-kanatzar-63851a58/?ref=appt.news)

### Appt Foundation

Appt® 플랫폼은 비영리 조직인 [Appt Foundation](https://appt.org/en/about?ref=appt.news)의 이니셔티브입니다. 우리의 사명은 모든 사람이 앱에 접근할 수 있도록 만드는 것입니다. 우리는 무료 콘텐츠와 오픈소스 

---

**원본 출처**: [Appt News Issue #75](https://www.appt.news/appt-news-accessible-mobile-apps-issue-75/)
