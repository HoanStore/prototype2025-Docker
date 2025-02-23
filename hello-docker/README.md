# Docker로 간단하게 Web 호스팅 하기 


1. 도커 빌드
```
docker build -t hello-docker .
```

2. 실행
```
docker run -d -p 9090:80 --name hello-docker-web hello-docker
```


3. 중지
```
docker stop [컨테이너 이름:hello-docker-web]
```
