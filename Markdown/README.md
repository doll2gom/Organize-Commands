# reference

수업에서 추천한 참고 자료 링크 :
[link 1](https://github.github.com/gfm/),
[link 2](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), [link 3](https://www.markdownguide.org/)

[나무위키](https://namu.wiki/w/%EB%A7%88%ED%81%AC%EB%8B%A4%EC%9A%B4),
[레퍼런스1](https://github.com/dream-ellie/markdown), [레퍼런스2](https://ansohxxn.github.io/vs/snippets/)

# Heading

```
# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

Paragraph
```

# Line

라인 만들기

---

---

```
***
---
```

# Text attributes

줄바꿈 : \
\

볼드체

```
**bold**
```

기울임

```
_italic_
```

취소선

```
~~strikethrough~~
```

This is the **bold** text and this is the _italic_ text and let's do ~~strikethrough~~.

# Quote

인용문

```
> Don't forget to code your dream.
>> 인용문 속 인용문
```

> Don't forget to code your dream.
>
> > 인용문 속 인용문

# Bullet list

```
- A
    * 1
        + ㄱ
        + ㄴ
    * 2
- B
```

- A
  - 1
    - 가
  - 2
- B

# Numbered list

1. first
2. second
3. third

리스트 다양하게 조합 가능

```
- C
    - 123
        - 가
            1. ㄱㄴ
            2. ㄷㄹ
```

- C
  - 123
    - 가
      1. ㄱㄴ
      2. ㄷㄹ

# Link

```
Click [here](https://github.com/dream-ellie/markdown)
```

Click [here](https://github.com/dream-ellie/markdown)

```
지금 폴더(디렉토리)에서
[a 파일](a.md)
[b 폴더](b/)
```

[a 파일](a.md)
[b 폴더](b/)

# Image

```
![image description](https://i.pinimg.com/564x/57/dd/81/57dd816dd0100ca1ec296c9ccabc4055.jpg)
```

![image description](https://i.pinimg.com/564x/57/dd/81/57dd816dd0100ca1ec296c9ccabc4055.jpg)

# Table

```
| Header | Description |
| :----: | :---------: |
| Cell1  |    Cel12    |
| Cell1  |    Cell2    |
| Cell1  |    Cell2    |
| Cell1  |    Cell2    |
```

| Header | Description |
| :----: | :---------: |
| Cell1  |    Cel12    |
| Cell1  |    Cell2    |
| Cell1  |    Cell2    |
| Cell1  |    Cell2    |

# Code

코드블럭

백틱(```)기호를 사용해
문자열 속의 문자를 하이라이팅 or 코드를 해당 언어의 문법대로 하이라이팅되어 호출한다.

To print message in the console, use `console.log('your message')` and ..

```python
console. log ('your message')
```

# Task Lists

기타 표현법

- [x] 체크됨
- [ ] 체크안됨
