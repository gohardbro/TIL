# H2 db 설치할때 zsh: permission denied: ./h2.sh 해결

![H2DB-permission-denied](img/%EC%8A%A4%ED%81%AC%EB%A6%B0%EC%83%B7%202022-06-02%20%EC%98%A4%ED%9B%84%207.57.05.png)

터미널로 h2/bin 경로로 가서 아래 명령어를 입력하면 된다.
```java
chmod 755 h2.sh 
```