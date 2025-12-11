[GitHub 마크다운](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

나중에 추가
-

# [Markdown](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md)

[제목](#제목-headings)  
[텍스트 스타일](#텍스트-스타일-지정-styling-text)  
[줄 바꿈](#줄-바꿈-line-breaks)  
[단락](#단락-paragraphs)  
[공백 문자](#공백-문자-whitespace-characters)  

[텍스트 인용](#텍스트-인용-quoting-text)  
[인용 코드](#인용-코드-quoting-code)  
[주석 숨김처리](#주석이-있는-콘텐츠-숨기기-hiding-content-with-comments)  
[Markdown 서식 무시](#markdown-서식-무시-ignoring-markdown-formatting)

[링크](#링크-links)  
[상대 링크](#상대-링크-relative-links)  
[섹션 링크](#섹션-링크-section-links)  
[사용자 지정 앵커](#사용자-지정-앵커-custom-anchors)  

[이미지](#이미지-images)  

[목록](#목록-lists)  
[작업 목록](#작업-목록-task-lists)  
[경고](#경고-alerts)  

[테이블](#테이블로-구성-정보-organizing-information-with-tables)  
[축소된 섹션을 사용하여 정보 구성](#축소된-섹션을-사용하여-정보-구성-organizing-information-with-collapsed-sections)  
[코드 블록 만들기 및 강조 표시](#코드-블록-만들기-및-강조-표시-creating-and-highlighting-code-blocks)  
[다이어그램 만들기](#다이어그램-만들기-creating-diagrams)  
[수학 식 작성](#수학-식-작성-writing-mathematical-expressions)  

|  |  |
|---|---|
|  |  |
|  |  |

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

| 스타일 | 구문 | 예시 | 출력 |
| --- | --- | --- | --- |
| 이탤릭체 | `_ _` (or `* *`)  | `_기울임꼴_` | _기울임꼴_ |
| 굵게 | `** **` (or `__ __`) | `**굵은**` | **굵은** |
| 밑줄 | `<ins> </ins>` | `<ins>밑줄</ins>` | <ins>밑줄</ins> |
| 취소선 | `~~ ~~` (일부 `~ ~`)| `~~취소선~~` | ~~취소선~~ |
| 위 첨자 | `<sup> </sup>` | `<sup>위 첨자</sup>` | <sup>위 첨자</sup> |
| 아래 첨자 | `<sub> </sub>` | `<sub>아래 첨자</sub>` | <sub>아래 첨자</sub> |

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

## [공백 문자 (Whitespace characters)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/3.%20%EC%B6%94%EA%B0%80/51.%20%EA%B3%B5%EB%B0%B1%20%EB%AC%B8%EC%9E%90.md) [![](<list icon.jpg>)](#markdown)

```markdown
 
```
`&#x2004;`  

<br/>
<br/>
<br/>

## [텍스트 인용 (Quoting text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/03.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%9D%B8%EC%9A%A9%20(Quoting%20text).md) [![](<list icon.jpg>)](#markdown)

```markdown
> 
```

## [인용 코드 (Quoting code)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/04.%20%EC%9D%B8%EC%9A%A9%20%EC%BD%94%EB%93%9C%20(Quoting%20code).md) [![](<list icon.jpg>)](#markdown)

````markdown
`text`
````

````markdown
```
text
```
````

## [주석이 있는 콘텐츠 숨기기 (Hiding content with comments)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/22.%20%EC%A3%BC%EC%84%9D%EC%9D%B4%20%EC%9E%88%EB%8A%94%20%EC%BD%98%ED%85%90%EC%B8%A0%20%EC%88%A8%EA%B8%B0%EA%B8%B0%20(Hiding%20content%20with%20comments).md) [![](<list icon.jpg>)](#markdown)

```markdown
<!-- not appear -->
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

```markdown
[Contribution guidelines for this project](docs/CONTRIBUTING.md)
```

## [섹션 링크 (Section links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/07.%20%EC%84%B9%EC%85%98%20%EB%A7%81%ED%81%AC%20(Section%20links).md) [![](<list icon.jpg>)](#markdown)

```markdown
[섹션 링크로 이동](#섹션-링크-section-links)
```

## [사용자 지정 앵커 (Custom anchors)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/09.%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EC%A7%80%EC%A0%95%20%EC%95%B5%EC%BB%A4%20(Custom%20anchors).md) [![](<list icon.jpg>)](#markdown)

```markdown
a  
<a id="my-custom-anchor-point"></a>
b

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

## [목록 (Lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/12.%20%EB%AA%A9%EB%A1%9D%20(Lists).md) [![](<list icon.jpg>)](#markdown)

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

## [Markdown 서식 무시 (Ignoring Markdown formatting)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/23.%20Markdown%20%EC%84%9C%EC%8B%9D%20%EB%AC%B4%EC%8B%9C%20(Ignoring%20Markdown%20formatting).md) [![](<list icon.jpg>)](#markdown)


문자 앞에 `\`를 사용

```markdown
Let's rename \*our-new-project\* to \*our-old-project\*.
```

<br/>
<br/>
<br/>

# [테이블로 구성 정보 (Organizing information with tables)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/31.%20%ED%85%8C%EC%9D%B4%EB%B8%94%EC%9D%84%20%EC%82%AC%EC%9A%A9%ED%95%98%EC%97%AC%20%EA%B5%AC%EC%84%B1%EB%90%9C%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20(Organizing%20information%20with%20tables).md) [![](<list icon.jpg>)](#markdown)

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




# [축소된 섹션을 사용하여 정보 구성 (Organizing information with collapsed sections)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/32.%20%EC%B6%95%EC%86%8C%EB%90%9C%20%EC%84%B9%EC%85%98%20(Organizing%20information%20with%20collapsed%20sections).md) [![](<list icon.jpg>)](#markdown)

````markdown
<details open>
<summary>Tips for collapsed sections</summary>

</details>
````



# [코드 블록 만들기 및 강조 표시 (Creating and highlighting code blocks)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/33.%20%EC%BD%94%EB%93%9C%20%EB%B8%94%EB%A1%9D%20%EB%A7%8C%EB%93%A4%EA%B8%B0%20%EB%B0%8F%20%EA%B0%95%EC%A1%B0%20%ED%91%9C%EC%8B%9C%20(Creating%20and%20highlighting%20code%20blocks).md) [![](<list icon.jpg>)](#markdown)

````text
```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
````



# [다이어그램 만들기 (Creating diagrams)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/34.%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8%20%EB%A7%8C%EB%93%A4%EA%B8%B0%20(Creating%20diagrams).md) [![](<list icon.jpg>)](#markdown)





# [수학 식 작성 (Writing mathematical expressions)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/35.%20%EC%88%98%ED%95%99%20%EC%8B%9D%20(Writing%20mathematical%20expressions).md) [![](<list icon.jpg>)](#markdown)


Markdown을 사용하여 GitHub에 수학식을 표시합니다.

## 수학 식 작성 정보 (About writing mathematical expressions)

수학식의 명확한 전달을 위해 GitHub는 Markdown 내에서 LaTeX 형식의 수학을 지원합니다. 자세한 내용은 Wikibooks에서 [LaTeX/Mathematics](http://en.wikibooks.org/wiki/LaTeX/Mathematics)를 참조하세요.

GitHub의 수학 렌더링 기능은 오픈 소스 JavaScript 기반 디스플레이 엔진인 MathJax를 사용합니다. MathJax는 다양한 LaTeX 매크로 및 몇 가지 유용한 접근성 확장을 지원합니다. 자세한 내용은 [MathJax 설명서](http://docs.mathjax.org/en/latest/input/tex/index.html#tex-and-latex-support) 및 [MathJax 접근성 확장 설명서](https://mathjax.github.io/MathJax-a11y/docs/#reader-guide)를 참조하세요.

다이어그램 렌더링은 GitHub Issues, GitHub Discussions, pull request, wiki 및 markdown 파일에서 사용할 수 있습니다.

## 인라인 식 작성 (Writing inline expressions)

텍스트와 인라인으로 수학식을 구분하는 두 가지 옵션이 있습니다. 식을 달러 기호(`$`)로 묶거나 식을 <code>$\`</code>로 시작하고 <code>\`$</code>로 끝낼 수 있습니다. 후자의 구문은 작성 중인 식에 markdown 구문과 겹치는 문자가 포함된 경우에 유용합니다. 자세한 내용은 [기본 쓰기 및 서식 지정 구문](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)을(를) 참조하세요.

```markdown
This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$
```

This sentence uses `$` delimiters to show math inline: $\sqrt{3x-1}+(1+x)^2$

```markdown
This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$
```

This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$

## 식을 블록으로 작성 (Writing expressions as blocks)

수학 식을 블록으로 추가하려면 새 줄을 시작하고 식을 이중 달러(`$$`) 기호로 구분합니다.

>[!TIP]  
.md 파일에서 작성하는 경우 아래 예제와 같이 백슬래시로 줄을 끝내는 등 특정 서식을 사용하여 줄 바꿈을 만들어야 합니다. Markdown의 줄 바꿈에 대한 자세한 내용은 [기본 쓰기 및 서식 지정 구문](/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#line-breaks)을(를) 참조하세요.

```markdown
**The Cauch-Schwarz Inequality**\
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$
```

**The Cauchy-Schwarz Inequality**\
$$\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)$$

또는 <code>\`\`\`math</code> 코드 블록 구문을 사용하여 수학 식을 블록으로 표시할 수 있습니다. 이 구문을 사용하면 `$$` 구분 기호를 사용할 필요가 없습니다. 다음은 위와 동일하게 렌더링됩니다.

````markdown
**The Cauchy-Schwarz Inequality**

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```
````

**The Cauchy-Schwarz Inequality**

```math
\left( \sum_{k=1}^n a_k b_k \right)^2 \leq \left( \sum_{k=1}^n a_k^2 \right) \left( \sum_{k=1}^n b_k^2 \right)
```

## 수학 식과 동일한 줄 또는 수학 식 내부에서 달러 기호 사용 (Writing dollar signs in line with and within mathematical expressions)

달러 기호를 수학 식과 동일한 줄에 문자로 표시하려면 구분 기호가 아닌 `$`를 이스케이프하여 줄이 올바르게 렌더링되도록 해야 합니다.

To display a dollar sign as a character in the same line as a mathematical expression, you need to escape the non-delimiter `$` to ensure the line renders correctly.

* 수학 식 내에서 명시적 `$` 앞에 `\` 기호를 추가합니다.

  ```markdown
  This expression uses `\$` to display a dollar sign: $`\sqrt{\$4}`$
  ```

  This expression uses `\$` to display a dollar sign: $`\sqrt{\$4}`$

* 수학 식 외부에 있지만 동일한 줄에서 명시적 `$` 주위에 범위 태그를 사용합니다.

  ```markdown
  To split <span>$</span>100 in half, we calculate $100/2$
  ```

  To split <span>$</span>100 in half, we calculate $100/2$