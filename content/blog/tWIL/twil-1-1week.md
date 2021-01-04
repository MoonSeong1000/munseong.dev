---
title: ' [tWIL] 21년 1월 1째주'
date: 2021-01-04 19:09:30
category: 'tWIL'
draft: false
keywords: ['tWIL','기술','블로그','회고','Graphql','Flutter', '머신러닝 스터디']
---

# [tWIL] 21년 1월 1째주
## 개발
### Flutter
#### Graphql
이번주에는 개인 공부로 Flutter에 Graphql를 연동하는 작업을 해봤다. 이전에 Web 공부를 하면서 React와 Graphql를 적용하는 것을 해봐서 시간이 오래 안걸릴줄 알았는데, Flutter에 적용하는데 적지 않은 삽질을 했다. [Ultimate toolchain to work with GraphQL in FlutterIntro | by Vasil Vasilich | Medium](https://medium.com/@v.ditsyak/ultimate-toolchain-to-work-with-graphql-in-flutter-13aef79c6484) 링크를 참고해서 구현하였다. Flutter에 Graphql를 적용하는 것은 추후 포스팅으로 다루려고 한다.

#### ValueListenableBuilder
플러터를 사용한 토이프로젝트를 하면서 안드로이드 네이티브에서 다뤘던 패턴을 적용해보고 싶었다. (MVVM + Clean Architecture) 적용하면서 답답했던 부분이 안드로이드에 liveData 같은 라이브러리가 제공되지 않는다는 점이었다. 물런 플러터에서의 Provide 패턴이나 Rx 등을 사용해 pub-sub 구조를 가져갈 수 있긴 하다. 하지만 뭔가.. liveData처럼 직관적인 도구를 Flutter에서 찾고 싶었다. 내가 찾은 답은ValueListenableBuilder 위젯을 사용하는 것이다. viewModel에서 데이터를 정의해주고, 이 데이터를 UI에서 구독하게 하면 기존의 liveData에 익숙한 개발자 분들이라면 편하게 쓸 수 있을 것이다.
[ValueListenableBuilder class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/ValueListenableBuilder-class.html)


## 이번주는 어땠나요?
2021년이 왔다.  연말, 연초가 왔다는 것에 상관없이 페이스를 유지 하려 했지만 마음에 약간 뜬 것 같다. 이번주도 회사 업무를 하면서, 또 개인적으로 공부를 하면서 많은 것을 터득하였다. 아 요즘 데이터를 다루고 분석해야 하는 큰 업무가 있어서 머신러닝 스터디에 참여했는데 생각보다 어렵다.. 단순 학생때 y=f(x)만 계산 했던 것이 아니라 진짜 의미를 깨달아야 될것 같다. 머신러닝을 공부해서 나중에 이력서에 써야지가 아니라 개발자로서 기본적인 상식은 쌓는 의미에서 스터디중이다. 하지만 오랜만에 통계, 수학 공부도 하고 좋은 시간이다. 꾸준히 하면 아하 모먼트가 올때가 생기지 않을까 싶다. 
