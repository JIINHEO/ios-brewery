# ios-brewery
PunkAPI로 데이터를 가져와 멕주 리스트를 표시하는 브루어리 iOS Application

# 기능
- PunkAPI로 맥주 리스트 가져와서 표시하기






# 활용 기술

(Uniform Resource Locator)

- PunkAPI


- http:// (프로토콜)   
    www.asdf.com (웹서버명 -> DNS명 -> IP 주소) - leyer3: 네트워크계층(IP))   
        :8080 (포트명) - leyer4: 전송 계층(port)   
            /ios.html (데이터 출처(리소스)경로) - leyer7: 응용 계층   

- ```Request``` : Method, URL, Header, Body   
- ```Response``` : Status Code, Message, Header, Body   

- Status Code   
    * 1.. : 정보전달 - 리퀘스트 수신, 진행중
    * 2.. : 성공 - 리퀘스트 성공적으로 수신, 해석, 승인
    * 3.. : 리다이렉션
    * 4.. : 클라이언트 에러
    * 5.. : 서버 에러

```URLSession``` :  HTTP를 이용한 네트워킹을 통해 데이터를 주고받을 수 있게 도와주는 API를 제공해주는 클래스   

```GCD(Grand Central Dispatch)``` : 멀티코어 
```GCD(Grand Central Dispatch)``` : 시스템에 의해 관리되는 Dispatch Queue들에 작업을 보내어 멀티코어 하드웨어 위에서 동시에 코드를 실행
