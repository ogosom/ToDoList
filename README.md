### 📌 HW

- **django로 프론트 백 둘다 한번에 개발이 가능한데 보통 협업에서 나눠서 개발하는 이유는?**
- - 프론트와 백을 분리하는 것이 관리에 용이하기 때문이다. 또한 프론트 개발을 위해서는 장고 프론트 문법을 또 새롭게 익혀야 하는 번거로움이 발생하기 때문이다
- **적으면 아래 페이지처럼 나오는데 제목이 왜 “백엔드로 공부하기” 일까요?(2)**
- - return 값을 self.title로 설정했기 때문에 제목이었던 “백엔드로 공부하기”가 표시된다. 만약 self.descriptions으로 설정한다면 내용이 표시된다.
- **templates 안에 todo라는 이름의 폴더를 굳이 만들어서 안에 템플릿을 관리할까요?(3)**
- - 템플릿으로 개발을 많이 하다보면 그만큼 app별로 html도 다수 생성되는데, 이름이 똑같은 html 파일이 있다면 이후 view를 통해 불러오게 될 때 가장 위쪽에 있는 html을 불러오게 된다. 본인이 원하는 html 파일이 정확히 어느 폴더에 있는 어느 파일인지 명확이 호출하기 위해 분리해서 관리합니다.
