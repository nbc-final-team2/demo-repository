---
name: Bug report
about: 프로젝트 버그 발생 이슈
title: "[BUG]"
labels: "\U0001F41E bug"
assignees: ''

---

💎 문제 사항

<!-- 어떤 문제가 발생했는지 말씀해주세요. -->

- 검색 및 탭 이동 이후, 홈 화면으로 돌아오면 앱이 죽습니다

🚨 문제 재현 방법

- [1] 실행 후, 홈 화면에서 검색 버튼을 누름
- [2] 검색 결과 받아온 후, 다른 탭으로 이동
- [3] 다시 홈 화면으로 돌아오면, ~~~ Error 띄우며 앱이 꺼짐

📝 시도해 본 것

- 네트워크가 없는 상황에선 해당 버그가 발생하지 않는 것으로 보아, API 활용 부분이 의심됨
- Break point 걸고 디버깅 해보았는데, MainViewModel 내의 searchItem() 메소드 호출 중간에 앱이 죽음 

📖 참고 사항

<!-- 레퍼런스, 스크린샷 등을 넣어 주세요. -->

- 스샷
- 스샷
