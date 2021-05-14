# 분산 부하 테스트

## 로컬 시나리오

1. base gatling image만들기
   1. jdk11, gradle, zsh, apine, curl등 기본 app 설치
   2. gatling 설치
   3. docker build -t gatling .
2. 로컬 맥에서 실행, 로그 분석


## 클라우드 시나리오

1. base host image - docker 설치
1. self provisioning api를 이용하여 서버 N대 발급
1. gatling이 포함된 docker image pull (ansible)
1. 동시 실행 





