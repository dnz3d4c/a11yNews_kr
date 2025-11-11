# Appt News Issue #74 - 한국어 번역

번역 날짜: 2025년 11월 12일
원본 해시: 05f3f6bd313c9b3911fbdc724353f6fda339f46000abdceb70bcb342aff5d317

---

# Appt News (접근 가능한 모바일 앱) - Issue #74

안녕하세요,

이번 호에서는 접근성 뉴스를 전해줄 특별 게스트가 있습니다! [Rob Whitaker](https://iosdev.space/@RobW?ref=appt.news)는 iOS 엔지니어이자 네이티브 접근성 전문가입니다. 그의 [블로그](https://mobilea11y.com/?ref=appt.news)나 [그의 책 "포용적인 모바일 앱 개발하기: iOS와 Android를 위한 접근 가능한 앱 만들기"](https://a.co/d/elxNnde?ref=appt.news) 또는 접근성에 관한 컨퍼런스 발표를 통해 그를 아실 수도 있습니다. 더 이상의 말 없이, Rob이 전하는 뉴스를 시작하겠습니다!

## Rob Whitaker의 뉴스

9월은 전통적으로 Apple 플랫폼에 중요한 달이며, 2025년 9월은 가장 의미 있는 달 중 하나로 기억될 것입니다. Apple 사용자들은 모든 플랫폼에 걸쳐 주요한 새 디자인 언어의 도입을 보게 될 것이며, 이는 앞으로 수년간 우리가 이러한 플랫폼을 사용하는 방식을 정의할 것입니다. 디자인 측면에서 이것은 약 12년 전 iOS 7 이후 가장 큰 변화라고 할 수 있습니다. 모바일 접근성 분야에서 일한 지 오래된 사람이라면 그 출시가 시각 장애가 있는 사람들에게 미친 부정적인 영향을 기억할 것입니다.

자연스러운 "나는 변화가 싫다"는 반응과 주요 재설계 첫 몇 주 동안 발생하는 매우 심각한 "이것은 내 기기를 사용하는 능력에 실질적인 영향을 미친다"는 우려를 구분하는 것은 항상 까다롭습니다. 하지만 많은 시각 장애인들이 새로운 디자인으로 어려움을 겪지 않는다면 놀랄 것입니다. 적어도 제 비디자이너의 눈으로는 기능과 사용성보다는 시각적 화려함에 더 초점을 맞춘 것처럼 보입니다.

저는 긍정적으로 보려고 노력하며, Liquid Glass의 두 가지 긍정적인 면을 볼 수 있습니다. 첫째, 디자인은 부인할 수 없이 인상적이고 현대적이며, 상호작용을 즐겁게 만드는 재미있는 요소들이 있습니다. 둘째, 디자인 채택의 복잡성과 앱이 자체 브랜딩의 많은 부분을 제거하도록 강제하는 방식이 결합되어, 대다수의 타사 앱들이 새로운 디자인을 천천히 채택하거나 전혀 채택하지 않을 것이며, 이는 사용자에게 자연스러운 학습 곡선을 제공합니다(비록 플랫폼의 앱 간 일관성이 감소하더라도).

그러나 이러한 긍정적인 면들은 Liquid Glass가 Apple 자체의 [휴먼 인터페이스 가이드라인](https://developer.apple.com/design/human-interface-guidelines/accessibility?ref=appt.news#Vision)을 훼손하는 것에 비하면 미약하게 느껴집니다.

Liquid Glass가 설정한 선례는 필연적으로 업계 전반의 디자이너들에게 복사될 것이며, 이는 접근성 노력에 위축 효과를 가져올 것입니다. 저는 앞으로 몇 달 동안 '...하지만 이것이 Apple이 하는 방식입니다'라는 운명적인 말을 점점 더 많이 듣게 될 이 글을 읽는 모든 분들에게 깊이 공감합니다.

### WCAG 3.0 편집자 초안

이번 달 W3C는 WCAG 3.0의 편집자 초안 출판을 발표했습니다. 이는 웹 콘텐츠 접근성 가이드라인의 다음 주요 버전 출판을 향한 중요한 이정표입니다. 이 초안이 아직 소프트웨어의 접근성을 평가하는 데 사용되어서는 안 된다는 점이 중요하지만, 지금은 피드백을 제공하는 중요한 시기입니다. 누락된 고려사항이나 불명확하거나 비실용적인 사항이 있다면 [Github에](https://github.com/w3c/wcag3/issues?ref=appt.news) 이슈를 제출하세요.

### 애니메이션이 필요 없는 경우

동작 민감성을 가진 사람으로서 저는 아마도 대부분의 사람들보다 인터페이스 애니메이션에 대해 더 많이 생각합니다. 이 사려 깊은 블로그는 애니메이션을 사용하지 않는 것을 고려해야 할 때를 제시하지만 - 중요하게도 - 애니메이션이 사용자에게 구조와 기능을 전달하는 필수적인 부분인 경우도 다룹니다.

### 앱의 접근성 테스트하기

올해 AppDevCon의 영상들이 여름 동안 온라인에 조금씩 공개되었습니다. [Abra의 친구들](https://abra.ai/?ref=appt.news)이 제공하는 모바일 앱 접근성 테스트에 대한 이 빠른 소개는 유럽 접근성법이 모바일 앱 테스트나 개발에 무엇을 의미하는지 이해하기 시작하는 모든 사람에게 훌륭한 출발점입니다.

[https://appdevcon.nl/session/testing-the-accessibility-of-your-app/](https://appdevcon.nl/session/testing-the-accessibility-of-your-app/?ref=appt.news)

### 스마트 안경에 대한 가장 강력한 주장은 접근성입니다

저는 불운했던 Google Glass 이후로 스마트 안경의 접근성 잠재력에 대해 흥분해왔습니다. 시각, 청각, 인지 및 신체 장애가 있는 사람들을 위한 가능성은 매우 유망해 보입니다. 이것은 여전히 초기 단계에 있는 보조 기술이며, 이 기술이 점점 더 소비자에게 도달함에 따라 흥미로운 혁신과 새로운 도전 과제를 모두 볼 수 있을 것이라고 확신합니다.

## iOS 개발자를 위한...

### iOS 26의 새로운 접근성 기능

Apple의 휴먼 인터페이스 디자인 팀의 작업이 빅테크 중 접근성 리더로서 회사가 어렵게 얻은 명성을 손상시킬 위험이 있는 반면, 접근성 엔지니어링 팀은 계속해서 장애가 있는 사용자의 요구에 초점을 맞추고 의미 있는 혁신을 제공합니다 - 예를 들어 iPhone의 개선된 점자 경험과 같은 것입니다. 이러한 기능들은 [올해 초에 발표되었으며](https://www.apple.com/uk/newsroom/2025/05/apple-unveils-powerful-accessibility-features-coming-later-this-year/?ref=appt.news) 이제 대중에게 제공되므로 다시 살펴볼 가치가 있습니다.

아마도 가장 중요한 변화는 접근성 영양 라벨의 도입인데, 이에 대해서는 [Robin의 지난 이메일](https://www.appt.news/appt-news-accessible-mobile-apps-issue-73/?ref=accessible-mobile-apps-weekly-newsletter)에서 더 자세히 읽을 수 있습니다.

활발한 개발 팀이 접근성 표준을 유지하면서 Liquid Glass를 앱에 어떻게 적용하고 있는지에 대한 통찰을 얻으려면 BBC의 Andy Ronskley의 발표를 확인해보세요.

## Android 개발자를 위한...

### TalkBack 버전 16.1의 새로운 기능

TalkBack 16.1이 이번 달 Google에서 출시되었습니다. '포인트 릴리스'로서 주요한 새 기능은 없지만, 지연 및 점자 입력에 대한 수많은 조정을 가져와 매우 강력할 것입니다.

### Wear OS 접근성 고려사항

[Eevis Panula](https://bsky.app/profile/eevis.codes?ref=appt.news)가 웨어러블 기기의 접근성 고려사항을 살펴봅니다. 작은 화면은 콘텐츠 표시와 모터 입력에 사용 가능한 공간을 모바일 기기보다 훨씬 더 제한하지만, 이로 인해 두 가지 모두를 신중하게 고려하는 것이 더욱 중요해집니다.

오늘 호는 여기까지입니다! 즐거우셨기를 바랍니다.

이번 달 게스트 작성을 해준 Rob에게 큰 감사를 드립니다!

다음 달을 위한 피드백과 기사 제안은 [hello@robinkanatzar.com](mailto:hello@robinkanatzar.com)으로 보내주시고, Rob Whitaker를 [Mastodon](https://iosdev.space/@RobW?ref=appt.news) 또는 [LinkedIn](https://www.linkedin.com/in/rob-whitaker/?ref=appt.news)에서 팔로우하세요.

감사합니다,

[Robin](https://www.linkedin.com/in/robin-kanatzar-63851a58/?ref=appt.news)

### Swift for Swifts

kg-card-begin: html
Swift for Swifts 지원하기

kg-card-end: html

### Appt Foundation

Appt® 플랫폼은 비영리 단체인 [Appt Foundation](https://appt.org/en/about?ref=appt.news)의 이니셔티브입니다. 우리의 사명은 모든 사람을 위해 앱을 접근 가능하게 만드는 것입니다. 우리는 무료 콘텐츠와 오픈소스 코드를 공유함으로써 이를 달성하려고 노력합니다.

무료 접근성 핸드북은 여기에서 다운로드할 수 있습니다:

---

**원본 출처**: [Appt News Issue #74](https://www.appt.news/appt-news-issue-74/)
