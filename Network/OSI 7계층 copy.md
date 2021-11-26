## 쿠키와 세션
- HTTP 는 상태를 저장 안함 (= 사용자 구별 못함) 
- 쿠키와 세션 모두 HTTP에 상태 정보를 유지하기 위해 사용 
=> <span style="color:red">서버에서는 클라이언트 별로 인증 및 인가 가능</span>
### 쿠키
- 작은 정보를 담은 파일
- 크롬 부라우저(Application - Storage - Cookies)에 도메인 별로 저장됨
  - Name: 쿠키 구별 (중복 X)
  - Value: 쿠키 값
  - Domain: 쿠키가 저장된 도메인
  - Path: 쿠키가 사용되는 경로
  - Expires: 만료기한 (지나면 삭제)
![](https://teamsparta.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fc40e9cab-c6cd-4b43-aac9-ba66f99491cb%2FUntitled.png?table=block&id=1f802e98-7112-456a-be43-b276cff6ee58&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=2000&userId=&cache=v2)
### 세션
- 서버에서 클라이언트 상태 유지하기 위해 사용 (클라이언트 별로 유일한 세션ID를 부여)
- 서버에서 생성한 세션ID는 클라이언트 쿠키(=세션쿠키)로 저장한후 식별에 사용됨 
![](https://teamsparta.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F504b0182-867a-40b2-a52e-1b9901f4aa89%2FUntitled.png?table=block&id=8a135dd7-675a-4c92-a5f7-e527a1daf398&spaceId=83c75a39-3aba-4ba4-a792-7aefe4b07895&width=980&userId=&cache=v2)

![](https://images.velog.io/images/kju190920/post/8c1a8482-96c6-4083-84cc-81e2b2633f6f/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA%202021-11-26%20%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE%203.18.07.png)