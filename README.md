# 발견된 문제점

- 2024.05.17 17:53 PM

- 기존 서버 세팅인 application.yml 은
  
  ```markdown
  server:
    port: 9091
    servlet:
      context-path: /api
  ```

인데 이렇게 하면 브라우저에서 localhost:9091/api 로 접근 시 처음 연결은 가능함.

그런데 Connect 버튼을 클릭하면 localhost:9091/api/? 으로 URL 이 변경되면서 접근이 안 되고 있음.

이유 ?

- 아직 파악 못함 ...
