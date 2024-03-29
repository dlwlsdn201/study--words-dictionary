# 프로그래밍 용어 사전
---

- **버퍼 오퍼플로우** : 버퍼는 보통 데이터가 저장되는 메모리 공간으로, 메모리 공간을 벗어나는 경우를 말한다.
이때 사용되지 않아야 할 영역에 데이터가 덮어씌워져 주소, 값을 바꾸는 공격이 발생하기도 한다.
- **gzip 압축** : LZ77과 Huffman 코딩의 조합인 DEFLATE 알고리즘을 기반으로 한 압축 기술이다.
gzip 압축을 하면 데이터 전송량⇩ 이지만, 압축 해제 시 서버에서의  CPU 오버헤드도 생각해서 gzip 압축 사용 유무를 결정해야한다.
- **CDN** : Content Delivery Network 의 약자이며, 각 사용자가 인터넷에 접속하는 곳과 가까운 곳에서 콘텐츠를 캐싱 또는 배포하는 서버 네트워크를 말한다. 이를 통해 사용자가 웹 서버로부터 콘텐츠를 다운로드 하는 시간을 줄일 수 있다.
- **CORS** :  Cross-Origin Resource Sharing 의 약자이며, 서버가 웹 브라우저에서 리소스를 로드할 때 다른 오리진을 통해 로드하지 못하게 하는 HTTP 헤더 기반 메커니즘이다.
- **오리진** : 프로토콜과 호스트 이름, 포트의 조합을 말한다. 예를 들어 [https://www.naver.com/blog](https://www.naver.com/blog) 라는 주소에서 오리진은 ‘https://www.naver.com’ 을 뜻한다.
- **이터레이터(iterator)** : 프로그래밍 언어에서 **iterator** 란 배열이나 유사한 자료 구조의 내부의 요소를 **순회**(traversing)하는 객체이다
- **이터레이터 프로토콜** : 이터러블한 객체들을 순회할 때 쓰이는 규칙
- **이터러블한 객체** : 반복 가능한 객체로 배열을 일반화한 객체
- **public** : 클래스에 정의된 함수에서 접근 가능하며 자식 클래스와 외부 클래스에서 접근 가능한 범위
- **protected** : 클래스에 정의된 함수에서 접근 가능, 자식 클래스에서 접근 가능하지만 외부 클래스에서 접근 불가능한 범위.
- **private** : 클래스에 정의된 함수에서 접근 가능하지만 자식 클래스와 외부 클래스에서 접근 불가능한 범위
- **즉시 실행 함수** : 함수를 정의하자마자 바로 호출하는 함수. 초기화 코드, 라이브러리 내 전역 변수의 충돌 방지 등에 사용한다.
- **커맨드** : 여러 가지 요소에 대한 처리를 하나의 액션으로 처리할 수 있게 하는 기법이다.
- **데이터 바인딩** : 화면에 보이는 데이터와 웹 브라우저의 메모리 데이터를 일치시키는 기법으로, 뷰모델을 변경하면 뷰가 변경된다.
- **러닝커브** : . 특정 기술 또는 지식을 실제 필요한 업무와 같은 환경에서 효율적으로 사용하기 위해 드는 학습 비용을 의미하기도 하며 특정 기술을 습득할 때에 처음에는 학습 효과가 더디다가 어느 정도 이해를 하고 나면 빠르게 습득하고 후에는 다시 더뎌지는 곡선.
