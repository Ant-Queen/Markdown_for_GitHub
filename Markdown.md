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
[자동 링크된 참조 및 URL](#자동-링크된-참조-및-url-autolinked-references-and-urls)  

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

<code>$\`</code>

```markdown
This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$
```

This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$




# [자동 링크된 참조 및 URL (Autolinked references and URLs)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/36.%20%EC%9E%90%EB%8F%99%20%EB%A7%81%ED%81%AC%EB%90%9C%20%EC%B0%B8%EC%A1%B0%20%EB%B0%8F%20URL%20(Autolinked%20references%20and%20URLs).md) [![](<list icon.jpg>)](#markdown)




# [파일 첨부 (Attaching files)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/37.%20%ED%8C%8C%EC%9D%BC%20%EC%B2%A8%EB%B6%80%20(Attaching%20files).md) [![](<list icon.jpg>)](#markdown)


# [작업 목록 정보 (About task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/38.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20%EC%A0%95%EB%B3%B4%20(About%20task%20lists).md) [![](<list icon.jpg>)](#markdown)
> for GitHub  
깃허브 이슈에서 작업목록 사용


# [코드 조각에 대한 고정 링크 만들기 (Creating a permanent link to a code snippet)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/39.%20%EC%BD%94%EB%93%9C%EC%97%90%20%EB%8C%80%ED%95%9C%20%EC%98%81%EA%B5%AC%20%EB%A7%81%ED%81%AC%20(Creating%20a%20permanent%20link%20to%20a%20code%20snippet).md) [![](<list icon.jpg>)](#markdown)

파일 또는 끌어오기 요청의 특정 버전에서 특정 줄 또는 코드 줄 범위에 대한 영구 링크를 만들 수 있습니다.

## 코드에 연결 (Linking to code)

이 유형의 고정 링크는 원래 출처인 리포지토리에서만 코드 조각으로 렌더링됩니다. 다른 리포지토리에서 고정 링크 코드 조각은 URL로 렌더링됩니다. 이는 Markdown 파일에서만 작동하지 않으며 주석에서만 작동합니다.

![Screenshot of an issue comment. A code snippet has a header that lists the file name and line numbers, and a body that lists the code on those lines.](https://docs.github.com/assets/cb-68457/mw-1440/images/help/repository/rendered-code-snippet.webp)

> [!TIP]  
> 전체 파일에 대한 고유 링크를 만들려면 [파일에 대한 영구 링크 가져오기](/repositories/working-with-files/using-files/getting-permanent-links-to-files)을(를) 참조하세요.

1. GitHub에서 리포지토리의 기본 페이지로 이동합니다.

1. 연결할 코드를 찾습니다.

    * 파일에서 코드에 연결하려면 해당 파일로 이동합니다.
    * 끌어오기 요청에서 코드에 연결하려면 끌어오기 요청으로 이동하고  **![alt text](<첨부-코드에 대한 영구 링크. diff.jpg>) 변경된 파일**을 클릭합니다. 그런 다음 주석에 포함할 코드가 포함된 파일을 찾아 **보기**를 클릭합니다.
    To link to code from a pull request, navigate to the pull request and click **{% octicon "diff" aria-hidden="true" %} Files changed**. Then, browse to the file that contains the code you want include in your comment, and click **View**.

1. 한 줄 또는 범위를 선택할지 여부를 선택합니다.

   * 한 줄의 코드를 선택하려면 줄 번호를 클릭하여 줄을 강조 표시합니다.
   * 코드 범위를 선택하려면 범위의 첫 번째 줄 수를 클릭하여 코드 줄을 강조 표시합니다. 그런 다음 코드 범위의 마지막 줄 위로 마우스를 가져가고 <kbd>Shift</kbd> 키를 누른 다음 줄 번호를 클릭하여 범위를 강조 표시합니다.

1. 줄의 왼쪽 또는 줄의 범위에서 ![alt text](<첨부-코드에 대한 영구 링크. kebab-horizontal.jpg>)을(를) 클릭합니다. 드롭다운 메뉴에서 **고정 링크 복사**를 클릭합니다.

   ![Screenshot of a file, with 8 lines selected. To the left of the first selected line, a button labeled with a kebab icon is outlined in dark orange.](https://docs.github.com/assets/cb-40280/mw-1440/images/help/repository/open-new-issue-specific-line.webp)

1. 코드 조각에 연결하려는 대화로 이동합니다.

1. 고정 링크를 주석에 붙여넣고 **주석**을 클릭합니다.

## Markdown에 연결 (Linking to Markdown)

Markdown 렌더링 없이 Markdown 파일을 로드하여 Markdown 파일의 특정 줄에 연결할 수 있습니다. 렌더링하지 않고 Markdown 파일을 로드하려면 파일의 URL 끝에 있는 `?plain=1` 매개 변수를 사용할 수 있습니다. 예들 들어 `github.com/<organization>/<repository>/blob/<commit_SHA>/README.md?plain=1`입니다.

코드에서와 동일한 방식으로 Markdown 파일의 특정 줄에 연결할 수 있습니다. URL 끝에 줄 번호 또는 숫자와 함께 `#L`을 추가합니다. 예를 들어 `github.com/<organization>/<repository>/blob/<commit_SHA>/README.md?plain=1#L14`는 일반 README.md 파일에서 줄 14를 강조 표시합니다.




# [이슈 및 끌어오기 요청에 키워드 사용 (Using keywords in issues and pull requests)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/40.%20%EC%9D%B4%EC%8A%88%20%EB%B0%8F%20%EB%81%8C%EC%96%B4%EC%98%A4%EA%B8%B0%20%EC%9A%94%EC%B2%AD%EC%97%90%20%ED%82%A4%EC%9B%8C%EB%93%9C%20%EC%82%AC%EC%9A%A9%20().md) [![](<list icon.jpg>)](#markdown)

키워드를 사용하여 문제를 연결하고 요청을 끌어오거나 문제를 표시하거나 끌어오기 요청을 중복으로 표시합니다.

## 끌어오기 요청을 이슈에 연결 (Linking a pull request to an issue)

끌어오기 요청을 이슈에 연결하여 수정이 진행 중임을 표시하고 누군가가 끌어오기 요청을 병합할 때 이슈를 자동으로 닫으려면, 다음 키워드 중 하나를 입력하고 그 뒤에 이슈에 대한 참조를 입력합니다. 예를 들어 `Closes #10` 또는 `Fixes octo-org/octo-repo#100`입니다.

<!-- markdownlint-disable GHD034 -->
* close
* closes
* closed
* fix
* fixes
* fixed
* resolve
* resolves
* resolved
<!-- markdownlint-enable GHD034 -->

자세한 내용은 [끌어오기 요청을 이슈에 연결](https://docs.github.com/ko/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)을(를) 참조하세요.

## 이슈 또는 끌어오기 요청을 중복으로 표시 (Marking an issue or pull request as a duplicate)

이슈 또는 끌어오기 요청을 중복으로 표시하려면 “Duplicate of”를 입력한 다음 새 주석 본문에 중복되는 이슈 또는 끌어오기 요청 번호를 입력합니다. 자세한 내용은 [문제 또는 끌어오기 요청을 중복으로 표시](https://docs.github.com/ko/issues/tracking-your-work-with-issues/marking-issues-or-pull-requests-as-a-duplicate)을(를) 참조하세요.

dd

<!-- https://github.com/Ant-Queen/Markdown_for_GitHub/blob/6a35d742275c5f98847460a03db99aa0377caa1e/example.py#L4-L5 -->

dd

https://github.com/Ant-Queen/Markdown_for_GitHub/blob/6a35d742275c5f98847460a03db99aa0377caa1e/example.py#L4-L5


dd

https://github.com/Ant-Queen/Markdown_for_GitHub/blob/6a35d742275c5f98847460a03db99aa0377caa1e/example.py?plain=1#L4-L5

dd

https://github.com/Ant-Queen/Markdown_for_GitHub/blob/ca97e4dd275fcbdcfcd666a83d315af083328608/test%20copy.md?plain=1#L31-L44

dd


https://github.com/Ant-Queen/Markdown_for_GitHub/blob/ca97e4dd275fcbdcfcd666a83d315af083328608/test%20copy.md#L31-L44

dd


https://github.com/Ant-Queen/Markdown_for_GitHub/blob/ca97e4dd275fcbdcfcd666a83d315af083328608/test%20copy.md

dd

https://github.com/Ant-Queen/Markdown_for_GitHub/blob/ca97e4dd275fcbdcfcd666a83d315af083328608/test%20copy.md?plain=1