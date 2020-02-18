- 이 레포지토리는 `https://www.valentinog.com/blog/drf/` 튜토리얼임.

- django에서 react를 call하는 부분은 django의 template에서　  
`<script src="{% static "frontend/main.js" %}"></script>`
　  
이때 main.js는 App.js를 webpack으로 컴파일한 상태

- react에서 django rest api를 call하는 부분은 App.js에서　  
`fetch("api/lead")`　  

- python manage.py dbshell 접속해서, App.js에서 값을 취득하는 api가 바라보는 model에 데이터 넣어주지 않으면 화면 표시안됨.

