# 🎉마크다운

![download](README.assets/download-16570940070262.png)

## 도움 되는 자료

- [치트시트](https://gist.github.com/ihoneymon/652be052a0727ad59601)
- https://heropy.blog/2017/09/30/markdown/
- https://goddaehee.tistory.com/307



## 내용

* [마크다운 문법](./마크다운.md)





## 실습

* [마크다운 실습 내용](./markdown practice.md)

| 내용            | 실습 |      |
| --------------- | ---- | ---- |
| 문법 정리       | 내용 |      |
| 마크다운 실습1  | 실습 |      |
| 마크다운 실습 2 | 실습 |      |

# 마크다운(MarkDown)에 대해서



## 마크다운의 장점

- 문법이 쉽다.
- 관리가 쉽다.
- 지원 가능한 플랫폼과 프로그램이 다양하다.

## 마크다운의 단점

- 표준이 없어 사용자마다 문법이 상이할 수 있다.
- 모든 HTML 마크업을 대신하지 못한다.

# 마크다운 문법(syntax)

## 제목(Header)

`<h1>`부터 `<h6>`까지 제목을 표현할 수 있습니다.

```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```

제목1(h1)과 제목2(h2)는 다음과 같이 표현할 수 있습니다.

```
제목 1
=====

제목 2
-----
```

## 강조(Emphasis)

각각 `<em>`, `<strong>`, `<del>` 태그로 변환됩니다.

밑줄을 입력하고 싶다면 `<u></u>` 태그를 사용하세요.

```
이텔릭체는 *별표(asterisks)* 혹은 _언더바(underscore)_를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 __언더바(underscore)__를 사용하세요.
**_이텔릭체_와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
<u>밑줄</u>은 `<u></u>`를 사용하세요.
```

이텔릭체는 *별표(asterisks)* 혹은 *언더바(underscore)*를 사용하세요.
두껍게는 **별표(asterisks)** 혹은 **언더바(underscore)**를 사용하세요.
***이텔릭체\*와 두껍게**를 같이 사용할 수 있습니다.
취소선은 ~~물결표시(tilde)~~를 사용하세요.
밑줄은 `<u></u>`를 사용하세요.

## 목록(List)

`<ol>`, `<ul>` 목록 태그로 변환됩니다.

```
1. 순서가 필요한 목록
1. 순서가 필요한 목록
  - 순서가 필요하지 않은 목록(서브) 
  - 순서가 필요하지 않은 목록(서브) 
1. 순서가 필요한 목록
  1. 순서가 필요한 목록(서브)
  1. 순서가 필요한 목록(서브)
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
```

1. 순서가 필요한 목록
2. 순서가 필요한 목록
   - 순서가 필요하지 않은 목록(서브)
   - 순서가 필요하지 않은 목록(서브)
3. 순서가 필요한 목록
   1. 순서가 필요한 목록(서브)
   2. 순서가 필요한 목록(서브)
4. 순서가 필요한 목록

- 순서가 필요하지 않은 목록에 사용 가능한 기호

  - 대쉬(hyphen)

  - 별표(asterisks)

  - 더하기(plus sign)

## 링크(Links)

<a>로 변환됩니다.

```
[GOOGLE](https://google.com)

[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")

[상대적 참조](../users/login)

[Dribbble][Dribbble link]

[GitHub][1]

문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.

다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.
구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동합니다!"
```

[GOOGLE](https://google.com/)

[NAVER](https://naver.com/)

[상대적 참조](https://heropy.blog/2017/09/30/users/login)

[Dribbble](https://dribbble.com/)

[GitHub](https://github.com/)

문서 안에서 [참조 링크](https://naver.com/)를 그대로 사용할 수도 있습니다.

다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.

구글 홈페이지: [https://google.com](https://google.com/)
네이버 홈페이지: [https://naver.com](https://naver.com/)
