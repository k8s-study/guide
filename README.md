# microservices x kubernetes study

단순한 (하지만 현실적인) 서비스를 마이크로서비스 형태로 만들어 기본 철학을 이해하고 쿠버네티스를 이용하여 배포, 모니터링, 확장하면서 실제적인 사용법을 익히는게 목적입니다.

마이크로서비스를 제대로 구축한다는 것은 굉장히 어렵기 때문에 여기서는 단순하게 API Gateway + REST API 패턴을 사용하고 왜 안티패턴인지 느껴보는 정도로 진행합니다.

## pongpong

pongpong(가칭)은 https://apex.sh/ping/ 클론 프로젝트 입니다. 체크 하고 싶은 웹 서비스 주소를 입력하면 주기적으로 체크하고 결과를 알려줍니다.

![pong-microservices-design](imgs/pong-microservices-design.png)