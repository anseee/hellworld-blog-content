# Node.js에서 HTTP2 이용하기

## HTTP의 버전들, 그리고 HTTP2
※ 제가 어설프게 알아서 실제와는 다를수도 있으니 양해바랍니다.

HTTP 프로토콜은 우리들에게 매우 익숙한 프로토콜입니다. 그래서 이 HTTP 자체에 대한 이야기는 하지 않겠습니다. ~~괜히 뇌피셜 믿고 혼자 뻘소리 하다가 팩트폭력 당하면 좀 거시기하니까요 ㅋㅋ~~
그러나 여기서 끝내면 이 포스팅의 의미가 없으니 HTTP 버전에 대해 이야기를 하고자 합니다. HTTP는 1991년 0.9버전으로 처음 세상에 등장했다고 합니다. 이후 계속 보정되다가 1996년 1.0이 세상에 처음으로 등장합니다. 이후 HTTP는 승승장구 하였으나 이후 웹이 발달함에 따라 기존의 프로토콜로는 성능이 딸리다 판단하여 1999년 1.1로 버전업을 합니다.

### HTTP 1.0과 HTTP 1.1의 차이점?
다른 문서에 좋은 자료들이 많으니 여기선 간략하게만 이야기하겠습니다. 한 마디로 말하면 비연결 프로토콜(Connectionless Protocol)의 단점을 극복하고자 하려는 것입니다. 비연결 프로토콜은 간단하게 말하면 명령을 1회 수행하고 연결을 끊어버리는 방법입니다. 그러다보니 

## 참고 문헌
[HTTP:Brief History of HTTP](https://hpbn.co/brief-history-of-http/)