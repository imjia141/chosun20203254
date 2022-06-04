# chosun20203254
조선대학교 컴퓨터공학과 오픈소스SW개론 : 두번째 과제

#리눅스명령어

***
***top***

리눅스 명령어 top은 동작중인 프로세스의 상태를 실시간으로 화면에 출력해주는 명령어로 프로세스의 상태뿐만 아니라 CPU, 메모리, 부하 상태 등도 확인할 수 있다.
|옵션|설명|
|---|---|
|-top d 갱신 시간|갱신 시간 설정(초 단위)|
|-top p|특정 PID값을 갖는 프로세스를 모니터링할 때 사용|
|-top b|배치 모드로 실행하는 옵션, 파일에 전송할 때 사용|
|-top n 값|top 명령의 실행 횟수를 지정|
***
***ps***

리눅스 명령어 ps는 process status의 약자로 동작중인 프로세스의 상태를 출력해주는 명령어다. 정확한 옵션 사용이 중요한 명령어다.
|옵션|설명|
|---|---|
|-ps a|터미널과 연관된 프로세스 출력|
|-ps u|프로세스의 소유자를 기준으로 출력|
|-ps x|터미널에 종속되지 않는 프로세스 출력|
|-ps i|프로세스 정보 길게 보여줌|
***
***jobs***

리눅스 명령어 jobs은 백그라운드로 실행중인 프로세스 목록을 출력해주는 명령어다. 현재 중지된 프로세스 목록을 출력해주기도 한다.
|옵션|설명|
|---|---|
|-jobs i|프로세스 번호(pid)를 추가로 출력|
***
***kill***

리눅스 명령어 kill은 옵션 없이 실행하면 프로세스에 종료 신호를 보내는 명령어다. 보통은 중지시킬 수 없는 프로세스를 종료시킬 때 사용한다.
|옵션|설명|
|---|---|
|-kill -l|시그널의 종류 출력|
|-kill -s signal|시그널의 이름을 지정|
***


***vim 에디터에서 매크로 사용 방법에 대해 조사하기***

> q는 vim 에디터에서 나가는 걸 뜻한다. quit의 뜻으로 q와 q!는 다른 것이다. q는 파일을 나가겠다는 명령어지만 q!는 변경된 내용이 있더라도 저장하지 않고 무조건 종료한다는 명령어다.

>> @는 vim 에디터에서 이전 문자를 출력하면서 종료를 하는 걸 뜻한다. 강의자료에는 없지만 교수님께서 vimgolf 설명해주시면서 언급해주셨다. 

![vimgolff](https://user-images.githubusercontent.com/106863241/171995185-8e2b9998-8728-4b59-a30b-42f6b613cfca.png)
