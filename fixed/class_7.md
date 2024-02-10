# class 6

## git 명령어 요약

### git pull
- Revert와 Reset의 차이를 생각해보기
  - 우리가 지금까지 '이 커밋 현재 브런치로 초기화'는 강제 reset --hard를 한것이다.
- push를 하기 전에 revert를 해야한다.
- 장점: commit을 남기고 이전으로 돌아가는 것이다.
- 단점: 충돌이 일어나가 쉽다.

* **pr에서 merge를 했을 경우에는 fetch를 하고 pull을 해오면 된다. 그리고 굳이 해당 브런치를 merge할 필요는 없는 것이다.**