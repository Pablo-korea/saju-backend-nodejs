# saju-backend-nodejs

## Project setup
```
도커 컴포즈 실행 : docker-compose up -d
.env 파일을 생성 후 .env.template 내용을 복사
npm install
```

### Compiles and hot-reloads for development
```
npm run dev

// 세션 끊겨도 계속 실행
nohup npm run dev &
 
// 세션 연결 중에만 계속 실행
npm run dev &
 
// 종료
ps auxf | grep node // node를 실행중인 프로세스 검색
kill -9 프로세스ID // 위에서 찾은 ID를 이용해 프로세스 종료

```


