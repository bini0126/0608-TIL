# 마크다운

## 특징
    - 최소한의 문법으로 구성되어 있으며 순수 텍스트로 작성 가능
    - 단순 텍스트 문법으로 내용을 작성하며, 다양한 환경에서 변환하여 보여짐

## 문법

- Heading : 문서의 제목이나 소제목

    - '#'의 개수에 따라 h1 ~ h6 표현 가능

    - 문서의 구조를 위해 작성되며 글짜 크기를 조절하기 위해 사용되어서는 안 됨

    -   # '#' Heading level 1
    -    ## '##' Heading level 2
    -    ### '###' Heading level 3
    -    #### '####' Heading level 4
    -    ##### '#####' Heading level 5
    -    ###### '######' Heading level 6

- List : 목록

    1. 순서 있는 (ol), 순서 없는 (ul)로 구성
    2. Tab으로 하위 항목으로 구성 가능
      
- Fenced Code block : 코드 블록
    - backtick 기호 3개 (```)를 활용하여 작성
    ```python
    print('Hello World")
    ```

- Link : 링크

    ```
    - [문자열](url)을 통해 링크 작성 가능
    
    - ex) [네이버](https://www.naver.com/)
    ```

    =>  [네이버](https://www.naver.com/)

    
- image: 이미지

    ```
    - ![문자열](url)을 통해 이미지 사용 가능
    ```

- BlockQuotes : 인용문

    - ">" 으로 인용문 작성

- 테이블

    ```
    예시)
    |이름|나이|
    |----|----|
    |홍길동|20|
    |이순신|40|
    ```

    |이름|나이|
    |----|----|
    |홍길동|20|
    |이순신|40|

- 텍스트 강조

    ```
    *기울기*     **굵게**     ~~취소선~~
    ```

    *기울기*     
    
    **굵게**     
    
    ~~취소선~~

- 수평선

    - ***, ---, ___ 사용하기

---

- [Mastering Markdown](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)