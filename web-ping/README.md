1. docker build
```
docker image build -t my-web-ping:v1
```

2. docker run 
```
docker run my-web-ping:v1
```

3. 설정 파일 .env로 두고 그거 활용하기
```
docker run --env-file .env my-web-ping:v1 
```

4. 실행시킬 때 값을 주기
```
docker run -e TARGET="blog.sixeyed.com" -e METHOD="HEAD" -e INTERVAL="2000" my-web-ping:v1
```