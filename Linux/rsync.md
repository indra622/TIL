# 서버 간 파일 전송 모듈 rsync

네트워크 프로토콜임과 동시에 서버 간 파일 전송을 해주는 tool.
주로 동기화에 쓰인다.
중간에 파일 전송이 stop되더라도, 이어서 전송할 수 있는 장점이 있다.

### [참고 사이트](http://www.joinc.co.kr/w/Site/Tip/Rsync)

### 설치

Ubuntu
```
# apt-get install rsync
```

### Usage

```
# rsync options source destination
```

### options

-v verbose
-r Recursively 데이터 복사
-a archive mode. 심볼릭 링크 등도 같이 복사함
-z 파일 데이터 압축

### 
