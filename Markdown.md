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

> > 빛이 있으라.  
> 하니 빛이 있었다.
>> ss  
>
> ddd

ddsfsdf
&nbsp;  
&nbsp;sasdad  
 sssss
 sss
  ssss
  ssss
  sss
    ss
    sss
    s
sssss
ss
s
ss
s
s  
&nbsp;sssss  
 sss









## 공백문자
A&nbsp;A A A​A

| Unicode | 16진수 코드 | 복사하여 사용 | 비고 |
|---|---|---|---|
| 2000 | `&#x2000;` | " " | 1/2 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2001 | `&#x2001;` | " " | 전각 너비. `가장 사용이 권장되는 공백` |
| 2002 | `&#x2002;` | " " | 1/2 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2003 | `&#x2003;` | " " | 전각 너비. `가장 사용이 권장되는 공백` |
| 2004 | `&#x2004;` | " " | 1/3 폭. `가장 사용이 권장되는 공백` |
| 2005 | `&#x2005;` | " " | 1/4 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2006 | `&#x2006;` | " " | 1/6 폭. OS, 브라우저 간 미세한 차이 있음 |
| 200B | `&#x200B;` | "​" | ZERO WIDTH SPACE |
