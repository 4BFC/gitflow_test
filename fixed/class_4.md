# class 4

## git 명령어 요약

### git pull
- pull : 서버의 내용이 내 PC보다 최신일 경우 pull을 적용한다.
- 충돌이 날 수 있지만 놀라지 말자.
- pull = fetch + merge
  - 현재 나의 branch를 변경함과 동시에 master나 다른 branch에서 변경사항이 있는 도중 내가 branch를 merge하려는 순간 충돌이 발생한다. 이때 직접 에디터에서 변경사항들을 확인하고 변경사항을 저장해준다. 그리고 커밋을 해준다.
  - 또는 '저장소 것으로 충돌 해결' 하는 방법을 사용하면 된다. 이는 코드가 많이 충돌 될경우 실행하면 좋다.