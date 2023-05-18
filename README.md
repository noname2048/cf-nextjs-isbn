# cf-nextjs-isbn

nextjs 를 공부하기 위해 여러가지 app 을 만들고 수정해봅니다.

* nextjs-blog (js)
  * 튜토리얼을 위해 이것저것 만져보는 사이트
* nextjs-isbn (js)
  * isbn13 (ean13) 을 키로, 책의 정보를 저장하는 크롤링 웹사이트
  * Frontend:
    * Next.js
    * 기본 UI를 위해 유명한 조합인 TailwindCSS, Headless UI 를 사용하기로 한다
    * 데이터 관리로 react-query + atom 를 사용할 계획
  * Backend:
    * app.superbase.com
    * lambda function 을 이용해볼 예정
  * Modile
    * 웹캡성능이 좋지 않다. 모바일에서 이용해야 할 것 같다.
    * ios 사용자를 위해 네이티브를 포기하고 flutter 를 이용할까 고민중
    * 아무래도 가장 큰 주요점은 배포가 빠르냐가 되어야 할 것으로 예측
  * Devops
    * 기본적인 CD만 하고 싶다. master 에 커밋하면 자동으로 배포되게끔.
  * 기타
    * axiom, upstash 등을 적용할 기회가 있을까
* nextjs-isbn-ts (ts)
  * js 버전을 다 만들고 나면 ts 버전으로 새로 만들어보자
