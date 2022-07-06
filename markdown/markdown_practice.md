# Python

## 1.개요

![](https://wikidocs.net/images/page/5/pahkey_KRRKrp.png)



파이썬(Python)은 1990년 암스테르담의 귀도 반 로섬(Guido Van Rossum)이 개발한 인터프리터 언어이다. 귀도는 파이썬이라는 이름을 자신이 좋아하는 코미디 쇼인 "몬티 파이썬의 날아다니는 서커스(Monty Python’s Flying Circus)"에서 따왔다고 한다.

인터프리터 언어란 한 줄씩 소스 코드를 해석해서 그때그때 실행해 결과를 바로 확인할 수 있는 언어이다.



### 2.특징

ctrl+ b :볼드체, ctrl+i: 이탤릭체

**1.파이썬은 인간다운 언어이다. 아래 코드는 쉽게 해석된다.**



​	**if 4 in [1,2,3,4]: print("4가 있습니다")**



*만약 4가 1, 2, 3, 4 중에 있으면 "4가 있습니다"를 출력한다. 라고 말이다*.



파이썬은 간결하다.

```python
#simple.py
languages = ['python', 'perl', 'c', 'java']

for lang in languages:
	if lang in ['python', 'perl']:
	print("%6s need interpreter" % lang)
elif lang in ['c', 'java']:
	print("%6s need compiler" % lang)
else:
	print("should not reach here")
```





3.공식문서가 자세히 제공된다.

파이썬 공식문서 링크 https://docs.python.org/3/





# 마크다운

![img](https://images.velog.io/images/hotoron/post/26abb02a-c6da-4533-83ab-036cdec510a9/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4.JPG)

## 1. 마크다운이란?

[**Markdown**](http://whatismarkdown.com/)은 텍스트 기반의 마크업언어로 2004년 존그루버에 의해 만들어졌으며 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다. 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 웹에서도 보다 빠르게 컨텐츠를 작성하고 보다 직관적으로 인식할 수 있다. 마크다운이 최근 각광받기 시작한 이유는 깃헙([https://github.com](https://github.com/)) 덕분이다. 깃헙의 저장소Repository에 관한 정보를 기록하는 README.md는 깃헙을 사용하는 사람이라면 누구나 가장 먼저 접하게 되는 마크다운 문서였다. 마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다는 강점이 부각되면서 점점 여러 곳으로 퍼져가게 된다.

## 마크다운의 장-단점

### 장점

```
1. 간결하다.
2. 별도의 도구없이 작성가능하다.
3. 다양한 형태로 변환이 가능하다.
4. 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
5. 텍스트파일이기 때문에 버전관리시스템을 이용하여 변경이력을 관리할 수 있다.
6. 지원하는 프로그램과 플랫폼이 다양하다.
```

### 단점

```
1. 표준이 없다.
2. 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다.
3. 모든 HTML 마크업을 대신하지 못한다.
```

