[GitHub 마크다운](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)



# [Markdown](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md)

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; |  |
|---|---|---|
| [Markdown 서식 무시](#markdown-서식-무시-ignoring-markdown-formatting) | [주석 숨김처리](#주석이-있는-콘텐츠-숨기기-hiding-content-with-comments) | [수학 식](#수학-식-작성-writing-mathematical-expressions) |
| [제목](#제목-headings) | [텍스트 인용](#텍스트-인용-quoting-text) | [다이어그램](#다이어그램-만들기-creating-diagrams) |
| [텍스트 스타일](#텍스트-스타일-지정-styling-text) | [코드 인용/블록](#코드-인용-quoting-code--코드-블록-code-block) |  |
| [줄 바꿈](#줄-바꿈-line-breaks) |[섹션 축소](#축소된-섹션을-사용하여-정보-구성-organizing-information-with-collapsed-sections) |  |
| [단락](#단락-paragraphs) | [경고](#경고-alerts) |  |
| [수평선](#수평선) |  |  |
| [공백 문자](#공백-문자-whitespace-characters) | [링크](#링크-links) |  |
|  | [상대 링크](#상대-링크-relative-links) |  |
| [테이블](#테이블로-구성-정보-organizing-information-with-tables) | [섹션 링크](#섹션-링크-section-links) |  |
| [목록](#목록-lists) | [사용자 지정 앵커](#사용자-지정-앵커-custom-anchors) |  |
| [작업 목록](#작업-목록-task-lists) |  |  |
| [작업 목록 정보](#작업-목록-정보-about-task-lists) | [이미지](#이미지-images) |  |

## [Markdown 서식 무시 (Ignoring Markdown formatting)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/23.%20Markdown%20%EC%84%9C%EC%8B%9D%20%EB%AC%B4%EC%8B%9C%20(Ignoring%20Markdown%20formatting).md) [![](<list icon.jpg>)](#markdown)

문자 앞에 `\`를 사용

```markdown
Let's rename \*our-new-project\* to \*our-old-project\*.
```

## [제목 (Headings)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/01.%20%EC%A0%9C%EB%AA%A9%20(headings).md) [![](<list icon.jpg>)](#markdown)

```markdown
# 
## 
### 
#### 
##### 
###### 
```

## [텍스트 스타일 지정 (Styling text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/02.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%8A%A4%ED%83%80%EC%9D%BC%20%EC%A7%80%EC%A0%95%20(Styling%20text).md) [![](<list icon.jpg>)](#markdown)

| 스타일 | 구문 | 예시 |
|---|---|---|
| _기울임꼴_ | `_ _` (or `* *`)  | `_기울임꼴_` |
| **굵은글씨** | `** **` (or `__ __`) | `**굵은글씨**` |
| <ins>밑줄</ins> | `<ins> </ins>` | `<ins>밑줄</ins>` |
| ~~취소선~~ | `~~ ~~` (일부 `~ ~`)| `~~취소선~~` |
| <sup>위 첨자</sup> | `<sup> </sup>` | `<sup>위 첨자</sup>` |
| <sub>아래 첨자</sub> | `<sub> </sub>` | `<sub>아래 첨자</sub>` |

## [줄 바꿈 (Line breaks)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/10.%20%EC%A4%84%20%EB%B0%94%EA%BF%88%20(Line%20breaks).md) [![](<list icon.jpg>)](#markdown)

줄 끝에 공백 두 개를 포함
<pre>
This example&nbsp;&nbsp;<!-- "  " 실제로는 스페이스바(공백)를 2번 입력 -->
Will span two lines
</pre>

줄 끝에 HTML 단일 줄 바꿈 태그를 포함
```markdown
This example<br/>
Will span two lines
```

## [단락 (Paragraphs)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/19.%20%EB%8B%A8%EB%9D%BD%20(Paragraphs).md) [![](<list icon.jpg>)](#markdown)

텍스트 줄 사이에 빈 줄을 둠
<pre>
This example

Will span two lines
</pre>

## [수평선 (Horizontal Rule)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/3.%20%EC%B6%94%EA%B0%80/52.%20%EC%88%98%ED%8F%89%EC%84%A0.md) [![](<list icon.jpg>)](#markdown)

`---`, `***`, `___`

## [공백 문자 (Whitespace characters)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/3.%20%EC%B6%94%EA%B0%80/51.%20%EA%B3%B5%EB%B0%B1%20%EB%AC%B8%EC%9E%90.md) [![](<list icon.jpg>)](#markdown)

```markdown
 
```
`&#x2004;`  
`&nbsp;`  

<br/>
<br/>
<br/>

## [테이블로 구성 정보 (Organizing information with tables)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/31.%20%ED%85%8C%EC%9D%B4%EB%B8%94%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC%20%EA%B5%AC%EC%84%B1%EB%90%9C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20(Organizing%20information%20with%20tables).md) [![](<list icon.jpg>)](#markdown)

```markdown
|  |  |
|---|---|
|  |  |
|  |  |
```

```markdown
| Left-aligned | Center-aligned | Right-aligned |
| :---         |     :---:      |          ---: |
| git status   | git status     | git status    |
| git diff     | git diff       | git diff      |
```

## [목록 (Lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/12.%20%EB%AA%A9%EB%A1%9D%20(Lists).md) [![](<list icon.jpg>)](#markdown)
행 앞에 `숫자` 또는 `-`, `*`, `+`을(를) 입력
```markdown
1. First list item
   - First nested list item
     - Second nested list item
2. Second list item
   - First nested list item
     - Second nested list item
```

## [작업 목록 (Task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/13.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20(Task%20lists).md) [![](<list icon.jpg>)](#markdown)

`- [ ] `

```markdown
- [ ] 
- [x] 
```

## [작업 목록 정보 (About task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/38.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20%EC%A0%95%EB%B3%B4%20(About%20task%20lists).md) [![](<list icon.jpg>)](#markdown)
> for GitHub  
깃허브 이슈에서 작업목록 사용

<br/>
<br/>
<br/>

## [주석이 있는 콘텐츠 숨기기 (Hiding content with comments)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/22.%20%EC%A3%BC%EC%84%9D%EC%9D%B4%20%EC%9E%88%EB%8A%94%20%EC%BD%98%ED%85%90%EC%B8%A0%20%EC%88%A8%EA%B8%B0%EA%B8%B0%20(Hiding%20content%20with%20comments).md) [![](<list icon.jpg>)](#markdown)

```markdown
<!--  -->
```

## [텍스트 인용 (Quoting text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/03.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%9D%B8%EC%9A%A9%20(Quoting%20text).md) [![](<list icon.jpg>)](#markdown)

```markdown
> 
```

## [코드 인용 (Quoting code) & 코드 블록 (Code Block)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/04.%20%EC%9D%B8%EC%9A%A9%20%EC%BD%94%EB%93%9C%20(Quoting%20code).md) [![](<list icon.jpg>)](#markdown)

````markdown
`text`
````

````markdown
```python
text
```
````

## [축소된 섹션을 사용하여 정보 구성 (Organizing information with collapsed sections)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/32.%20%EC%B6%95%EC%86%8C%EB%90%9C%20%EC%84%B9%EC%85%98%20(Organizing%20information%20with%20collapsed%20sections).md) [![](<list icon.jpg>)](#markdown)

````markdown
<details open>
<summary>Tips for collapsed sections</summary>

</details>
````

## [경고 (Alerts)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/21.%20%EA%B2%BD%EA%B3%A0%20(Alerts).md) [![](<list icon.jpg>)](#markdown)
> for GitHub  

```markdown
> [!NOTE]  
> Useful information that users should know, even when skimming content.

> [!TIP]  
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]  
> Key information users need to know to achieve their goal.

> [!WARNING]  
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]  
> Advises about risks or negative outcomes of certain actions.
```

<br/>
<br/>
<br/>

## [링크 (Links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/06.%20%EB%A7%81%ED%81%AC%20(Links).md) [![](<list icon.jpg>)](#markdown)

`[]()`

```markdown
[GitHub](https://github.com/)
```

## [상대 링크 (Relative links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/08.%20%EC%83%81%EB%8C%80%20%EB%A7%81%ED%81%AC%20(Relative%20links).md) [![](<list icon.jpg>)](#markdown)

동일 레포지토리 내의 다른 파일로 연결

```markdown
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

## [섹션 링크 (Section links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/07.%20%EC%84%B9%EC%85%98%20%EB%A7%81%ED%81%AC%20(Section%20links).md) [![](<list icon.jpg>)](#markdown)

해당 파일 내의 섹션으로 연결

```markdown
[섹션 링크로 이동](#섹션-링크-section-links)
```

## [사용자 지정 앵커 (Custom anchors)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/09.%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EC%A7%80%EC%A0%95%20%EC%95%B5%EC%BB%A4%20(Custom%20anchors).md) [![](<list icon.jpg>)](#markdown)

섹션을 가리키는 사용자 지정 앵커 만들기

```markdown
text  
<a id="my-custom-anchor-point"></a>
text  

[A link to that custom anchor](#my-custom-anchor-point)
```

<br/>
<br/>
<br/>

## [이미지 (Images)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/11.%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20(Images).md) [![](<list icon.jpg>)](#markdown)

`![]()`

```markdown
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`  
```

<br/>
<br/>
<br/>

## [수학 식 작성 (Writing mathematical expressions)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/35.%20%EC%88%98%ED%95%99%20%EC%8B%9D%20(Writing%20mathematical%20expressions).md) [![](<list icon.jpg>)](#markdown)

<code>$\`</code>

```markdown
This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$
```

This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$

## [다이어그램 만들기 (Creating diagrams)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/34.%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8%20%EB%A7%8C%EB%93%A4%EA%B8%B0%20(Creating%20diagrams).md) [![](<list icon.jpg>)](#markdown)

<br/>
<br/>
<br/>

