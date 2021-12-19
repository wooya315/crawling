## 크롤링(crawling)
크롤링이란 단어는 웹 크롤러(crawler)라는 단어에서 시작한 말이다.
크롤러란 조직적, 자동화된 방법으로 월드와이드 웹을 탐색하는 컴퓨터 프로그램이다.(출처: 위키백과)
크롤링은 크롤러가 하는 작업을 부르는 말로, 여러 인터넷 사이트의 페이지(문서, html 등)를 수집해서 분류하는 것이다.
대체로 찾아낸 데이터를 저장한 후 쉽게 찾을 수 있게 인덱싱한다.

## 파싱(parsing)
파싱이란 어떤 페이지(문서, html 등)에서 내가 원하는 데이터를 특정 패턴이나 순서로 추출하여 정보를 가공하는 것이다.
위 문장만 보면 굉장히 간단해 보이지만 컴퓨터 과학적 정의를 보면 파싱이란 일련의 문자열을 의미있는 토큰(token)으로 분해하고 이들로 이루어진 파스 트리(parse tree)를 만드는 과정을 말한다.(출처: 위키백과)
인터프리터나 컴파일러의 구성 요소 가운데 하나로, 입력 토큰에 내제된 자료 구조를 빌드하고 문법을 검사하는 역할을 한다.

## 스크래핑(scraping)
스크래핑이란 HTTP를 통해 웹 사이트의 내용을 긁어다 원하는 형태로 가공하는 것이다.
쉽게 말해 웹 사이트의 데이터를 수집하는 모든 작업을 뜻한다.
크롤링도 일종의 스크래핑 기술이라고 할 수 있다.

requests는 파이썬으로 HTTP 호출하는 프로그램을 작성할 때 가장 많이 사용되는 라이브러리이다.
BeautifulSoup는 HTML과 XML에서 데이터를 쉽게 처리하는 라이브러리이다. Python 파서를 사용하여 원하는 정보를 쉽게 추출할 수 있다.
