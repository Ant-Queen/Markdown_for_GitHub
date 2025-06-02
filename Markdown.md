# Markdown

## [제목 (Headings)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/01.%20%EC%A0%9C%EB%AA%A9%20(headings).md)

```markdown
# A first-level heading
## A second-level heading
### A third-level heading
#### A fourth-level heading
##### A fifth-level heading
###### A sixth-level heading
```

# A first-level heading
## A second-level heading
### A third-level heading
#### A fourth-level heading
##### A fifth-level heading
###### A sixth-level heading

## [텍스트 스타일 지정 (Styling text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/02.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%8A%A4%ED%83%80%EC%9D%BC%20%EC%A7%80%EC%A0%95%20(Styling%20text).md)

| 스타일 | 구문 | 예시 | 출력 |
| --- | --- | --- | --- |
| 이탤릭체 | `_ _` (or `* *`)  | `_기울임꼴_ 텍스트` | _기울임꼴_ 텍스트 |
| 굵게 | `** **` (or `__ __`) | `**굵은** 텍스트` | **굵은** 텍스트 |
| 밑줄 | `<ins> </ins>` | `<ins>밑줄</ins> 텍스트` | <ins>밑줄</ins> 텍스트 |
| 취소선 | `~~ ~~` (일부 `~ ~`)| `~~취소선~~ 텍스트` | ~~취소선~~ 텍스트 |
| 위 첨자 | `<sup> </sup>` | `<sup>위 첨자</sup> 텍스트` | <sup>위 첨자</sup> 텍스트 |
| 아래 첨자 | `<sub> </sub>` | `<sub>아래 첨자</sub> 텍스트` | <sub>아래 첨자</sub> 텍스트 |

## [텍스트 인용 (Quoting text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/03.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%9D%B8%EC%9A%A9%20(Quoting%20text).md)

```markdown
> first-level
>> second-level
>>> third-level
>
> first-level
```

> first-level
>> second-level
>>> third-level
>
> first-level

## [인용 코드 (Quoting code)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/04.%20%EC%9D%B8%EC%9A%A9%20%EC%BD%94%EB%93%9C%20(Quoting%20code).md)

````markdown
`text`
````

`text`

---

````markdown
```
text
```
````

```
text
```

## [링크 (Links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/06.%20%EB%A7%81%ED%81%AC%20(Links).md)

```markdown
[GitHub](https://github.com/)
```

[GitHub](https://github.com/)

## [상대 링크 (Relative links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/08.%20%EC%83%81%EB%8C%80%20%EB%A7%81%ED%81%AC%20(Relative%20links).md)

```markdown
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

[Contribution guidelines for this project](docs/CONTRIBUTING.md)

## [섹션 링크 (Section links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/07.%20%EC%84%B9%EC%85%98%20%EB%A7%81%ED%81%AC%20(Section%20links).md)

```markdown
[섹션 링크로 이동](#섹션-링크-section-links)
```

[섹션 링크로 이동](#섹션-링크-section-links)

## [사용자 지정 앵커 (Custom anchors)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/09.%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EC%A7%80%EC%A0%95%20%EC%95%B5%EC%BB%A4%20(Custom%20anchors).md)

```markdown
a  
<a id="my-custom-anchor-point"></a>
b

[A link to that custom anchor](#my-custom-anchor-point)
```

a  
<a id="my-custom-anchor-point"></a>
b

[A link to that custom anchor](#my-custom-anchor-point)

## [줄 바꿈 (Line breaks)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/10.%20%EC%A4%84%20%EB%B0%94%EA%BF%88%20(Line%20breaks).md)

* 첫 번째 줄 끝에 공백 두 개를 포함합니다.
  <pre>
  This example&nbsp;&nbsp; <!-- "  " 실제로는 스페이스바(공백)를 2번 입력 -->
  Will span two lines
  </pre>

  This example  
  Will span two lines

* 첫 번째 줄 끝에 백슬래시를 포함합니다.

  ```markdown
  This example\
  Will span two lines
  ```

  This example\
  Will span two lines

* 첫 번째 줄 끝에 HTML 단일 줄 바꿈 태그를 포함합니다.

  ```markdown
  This example<br/>
  Will span two lines
  ```

  This example<br/>
  Will span two lines

두 줄 사이에 빈 줄을 넣으면 .md 파일과 문제, 끌어오기 요청, 토론에서 사용되는 Markdown이 모두 빈 줄로 구분되어 두 줄로 렌더링합니다.

```markdown
This example

Will have a blank line separating both lines
```

This example

Will have a blank line separating both lines

## [공백 문자](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/3.%20%EC%B6%94%EA%B0%80/51.%20%EA%B3%B5%EB%B0%B1%20%EB%AC%B8%EC%9E%90.md)

| Unicode | 16진수 코드 | 복사하여 사용 | 비고 |
|---|---|---|---|
| 2000 | `&#x2000;` | 가 나 | 1/2 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2001 | `&#x2001;` | 가 나 | 전각 너비. `가장 사용이 권장되는 공백` |
| 2002 | `&#x2002;` | 가 나 | 1/2 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2003 | `&#x2003;` | 가 나 | 전각 너비. `가장 사용이 권장되는 공백` |
| 2004 | `&#x2004;` | 가 나 | 1/3 폭. `가장 사용이 권장되는 공백` |
| 2005 | `&#x2005;` | 가 나 | 1/4 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2006 | `&#x2006;` | 가 나 | 1/6 폭. OS, 브라우저 간 미세한 차이 있음 |
| 200B | `&#x200B;` | 가나 | ZERO WIDTH SPACE |
| 공백문자 | `&nbsp;` | 가&nbsp;나 | 1/3.66 폭? (1/3 호환 가능성 높음) |
| 스페이스바 | ` ` | 가 나 | 1/3.66 폭? (1/3 호환 가능성 높음) |

