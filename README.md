## 클래스 구현하기

- [ o ] `class`키워드를 이용해서 Product 클래스를 만들어 주세요.
- [ o ] `name`(상품명)`description`(상품 설명),`price`(판매 가격),`tags`(해시태그 배열),`images`(이미지 배열),`favoriteCount`(찜하기 수)프로퍼티를 가집니다.
- [ o ] `favorite`메소드를 가집니다.`favorite`메소드가 호출될 경우 찜하기 수가 1 증가합니다.
- [ o ] `class`키워드를 이용해서 ElectronicProduct 클래스를 만들어 주세요.
- [ o ] Product를 상속하며, 추가로`manufacturer`(제조사) 프로퍼티를 가집니다.
- [ o ] class 키워드를 이용해서 Article 클래스를 만들어 주세요.
- [ o ] `title`(제목),`content`(내용),`writer`(작성자),`likeCount`(좋아요 수) 프로퍼티를 가집니다.
- [ o ] `like`메소드를 가집니다.`like`메소드가 호출될 경우 좋아요 수가 1 증가합니다.
- [ o ] 각 클래스 마다**constructor**를 작성해 주세요.
- [ o ] 추상화/캡슐화/상속/다형성을 고려하여 코드를 작성해 주세요.

## Article 요청 함수 구현하기

- [ o ] [https://panda-market-api-crud.vercel.app/docs](https://panda-market-api-crud.vercel.app/docs)의 Article API를 이용하여 아래 함수들을 구현해 주세요.
- [ o ] `getArticleList()`: GET 메소드를 사용해 주세요.
- [ o ] `page`,`pageSize`,`keyword`쿼리 파라미터를 이용해 주세요.
- [ o ] `getArticle()`: GET 메소드를 사용해 주세요.
- [ o ] `createArticle()`: POST 메소드를 사용해 주세요.
- [ o ] request body에`title`,`content`,`image`를 포함해 주세요.
- [ o ] `patchArticle()`: PATCH 메소드를 사용해 주세요.
- [ o ] `deleteArticle()`: DELETE 메소드를 사용해 주세요.
- [ o ] `fetch`혹은`axios`를 이용해 주세요.
- [ o ] 응답의 상태 코드가 2XX가 아닐 경우, 에러 메시지를 콘솔에 출력해 주세요.
- [ o ] `.then()`메소드를 이용하여 비동기 처리를 해주세요.
- [ o ] `.catch()`를 이용하여 오류 처리를 해주세요.

### Article 요청 함수 구현하기 (심화)

- [ o ] Article 클래스에`createdAt`(생성일자) 프로퍼티를 만들어 주세요.
- [ o ] 새로운 객체가 생성되어 constructor가 호출될 시`createdAt`에 현재 시간을 저장합니다.

## Product 요청 함수 구현하기

- [ o ] [https://panda-market-api-crud.vercel.app/docs](https://panda-market-api-crud.vercel.app/docs)의 Product API를 이용하여 아래 함수들을 구현해 주세요.
- [ o ] `getProductList()`: GET 메소드를 사용해 주세요.
- [ o ] `page`,`pageSize`,`keyword`쿼리 파라미터를 이용해 주세요.
- [ o ] `getProduct()`: GET 메소드를 사용해 주세요.
- [ o ] `createProduct()`: POST 메소드를 사용해 주세요.
- [ o ] request body에`name`,`description`,`price`,`tags`,`images`를 포함해 주세요.
- [ o ] `patchProduct()`: PATCH 메소드를 사용해 주세요.
- [ o ] `deleteProduct()`: DELETE 메소드를 사용해 주세요.
- [ o ] `async/await`을 이용하여 비동기 처리를 해주세요.
- [ o ] `try/catch`를 이용하여 오류 처리를 해주세요.
- [ o ] `getProductList()`를 통해서 받아온 상품 리스트를 각각 인스턴스로 만들어`products`배열에 저장해 주세요.
- [ o ] 해시태그에 "**전자제품**"이 포함되어 있는 상품들은`Product`클래스 대신`ElectronicProduct`클래스를 사용해 인스턴스를 생성해 주세요.
- [ o ] 나머지 상품들은 모두`Product`클래스를 사용해 인스턴스를 생성해 주세요.

## 기타

- [ o ] 구현한 함수들을 아래와 같이 파일을 분리해 주세요.
- [ o ] **export**를 활용해 주세요.
- [ o ] `ProductService.js`파일**Product**API 관련 함수들을 작성해 주세요.
- [ o ] `ArticleService.js`파일에**Article**API 관련 함수들을 작성해 주세요.
- [ o ] 이외의 코드들은 모두`main.js`파일에 작성해 주세요.
- [ o ] **import**를 활용해 주세요.
- [ o ] 각 함수를 실행하는 코드를 작성하고, 제대로 동작하는지 확인해 주세요.
- [ o ] `README.md`파일을 작성해 주세요.
- [ o ] 마크다운 언어를 숙지하여 작성해 주세요.
- [ o ] 내용은 자유롭게 작성해 주세요.
