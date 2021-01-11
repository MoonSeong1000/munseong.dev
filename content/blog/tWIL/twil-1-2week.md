---
title: ' [tWIL] 21년 1월 2째주'
date: 2021-01-10 19:09:30
category: 'tWIL'
draft: false
keywords: ['tWIL','기술','블로그','회고','pandas','flutter','seaborn','머신러닝 스터디']
---

# [tWIL] 21년 1월 2째주
## 개발
### Flutter
이번주에는 UI 쪽으로 많이 개발해보았다.
#### table_calendar
	- 플러터에 캘린더를 집어넣기 위해서 레퍼런스들을 많이 찾았다. 하지만 뭔가 다들 부족했고, material 디자인 기반의 캘린더들이 마음에 안들었다. 그래서 결국은 커스텀이 답이라 생각하고, 적절한 library를 찾았다. 바로 table_calendar
	- 코드 구조를 좀 파보면 유연하게 커스텀이 가능하다.
	- 사실 커스텀이 용이해서 좋았기 보다는, 플러터에서 UI를 어떻게 코딩해야 아름다울까를 항상 고민했었는데, 아주 좋은 레퍼런스가 될것 같아서 좋았다. 
	- 리액트에서 HOC  개념을 잠깐 본적이 있는데 도움이 됐던 것 같다.
[table_calendar/example at master · aleksanderwozniak/table_calendar · GitHub](https://github.com/aleksanderwozniak/table_calendar/tree/master/example)
#### reorderable list
	- 리스트 순서를 바꾸기 용이하게 해주는 위젯 라이브러리.
	- 만약 native에서 구현해야 됐다면 막막했을 것 같다.
	- 이 라이브러리를 통해 내가 원하는 UI가 완벽히 나온것이 아니라서 필요하다면 커스텀을 해야 될 것 같다.
[reorderables | Flutter Package](https://pub.dev/packages/reorderables)

### ML
####Pandas library
	- 업무 상에 쌓인 로그를 분석해서 시각화를 해야할 일이 있었다. 분석, 처리를 하기 위해서 만들어진 python package인 pandas를 써야해서 바로 공부하고 사용하였다.
	- 데이터를 가공해서 데이터프레임으로 만들고 나서는 sql 사용했던것과 비슷한 느낌으로 접근을 해서 사용하였다. Join, where, 결측값 채우기 등등..
#### seaborn
	- 시각화를 하는 과정에서 seaborn 라이브러리를 접했다. 기본적인 시각화에는 matplotlib도 좋은 선택지지만 seaborn 모듈을 사용하면 좀더 다양한 색상 테마와 통계용 차트를 그릴 수 있어서 편리했다.


## 이번주는 어땠나요?
개인적으로는 플러터 UI를 공부한 한 주였다. UI를 개발하면서 또 느낀건데 역시 Hot Reload = God Reload이다. 안드로이드 Native를 개발하다보면 빌드를 해서 확인을 해야해서 시간이 아깝고, 그때 흐름이 끊길때도 있었다. 업무상 급하게 해야하다 보니 기본적인 데이터 분석과 시각화하는 툴을 다루는데 삽질을 많이 하였다. 그래도 시각화가 된걸 보면 뿌듯했다. ML 스터디도 하고 있지만 twil에 안쓴 이유는 개념? 느낌? 정도만 알고 있고, 실제로 어떤 방식으로 구현되고 어떤 수학적 원리인지 깨닫지 못해서 쓰기에는 부끄러웠다. 
