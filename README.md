# ios-brewery
PunkAPI로 데이터를 가져와 멕주 리스트를 표시하는 브루어리 iOS Application

# 기능
- PunkAPI로 맥주 리스트 가져와서 표시하기

<img width="30%" src = "https://user-images.githubusercontent.com/39071796/144990945-4f0ec379-f4d4-4ab7-8577-91e117e3607c.gif"/> 




# 활용 기술

```URLSession``` : 앱과 서버간의 통신을 위해서 애플이 기본적으로 제공하는 API   
        세션을 만들고, Request를 생성한 후, Task를 결정하고 이후 Completion Handler나 Delegate 형태로 받아온 데이터를 사용

- http:// (프로토콜)   
    www.asdf.com (웹서버명 -> DNS명 -> IP 주소) - leyer3: 네트워크계층(IP))   
        :8080 (포트명) - leyer4: 전송 계층(port)   
            /ios.html (데이터 출처(리소스)경로) - leyer7: 응용 계층   

- ```Request``` : Method, URL, Header, Body   
- ```Response``` : Status Code, Message, Header, Body   

- Status Code   
    * 1xx : 정보전달 - 리퀘스트 수신, 진행중
    * 2xx : 성공 - 리퀘스트 성공적으로 수신, 해석, 승인
    * 3xx : 리다이렉션
    * 4xx : 클라이언트 에러
    * 5xx : 서버 에러

```URLSession``` :  HTTP를 이용한 네트워킹을 통해 데이터를 주고받을 수 있게 도와주는 API를 제공해주는 클래스   

```GCD(Grand Central Dispatch)``` : 멀티코어 환경에서 최적화된 프로그래밍을 지원하도록 애플이 개발한 기술
