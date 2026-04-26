
# [Markdown](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md)

> [GitHub Markdown Docs](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | |
| --- | --- | --- |
| [Markdown 서식 무시](#markdown-서식-무시-ignoring-markdown-formatting) | [주석 숨김처리](#주석이-있는-콘텐츠-숨기기-hiding-content-with-comments) | [수학 식](#수학-식-작성-writing-mathematical-expressions) |
| [제목](#제목-headings) | [텍스트 인용](#텍스트-인용-quoting-text) | [다이어그램](#다이어그램-만들기-creating-diagrams) |
| [텍스트 스타일](#텍스트-스타일-지정-styling-text) | [코드 인용/블록](#코드-인용-quoting-code--코드-블록-code-block) | |
| [줄 바꿈](#줄-바꿈-line-breaks) | [섹션 축소](#축소된-섹션을-사용하여-정보-구성-organizing-information-with-collapsed-sections) | [이모지](#이모지-emojis) |
| [단락](#단락-paragraphs) | [경고](#경고-alerts) | |
| [수평선](#수평선-horizontal-rule) | | |
| [공백 문자](#공백-문자-whitespace-characters) | [링크](#링크-links) | |
| | [상대 링크](#상대-링크-relative-links) | |
| [테이블](#테이블로-구성-정보-organizing-information-with-tables) | [섹션 링크](#섹션-링크-section-links) | |
| [목록](#목록-lists) | [사용자 지정 앵커](#사용자-지정-앵커-custom-anchors) | |
| [작업 목록](#작업-목록-task-lists) | | |
| [작업 목록 정보](#작업-목록-정보-about-task-lists) | [이미지](#이미지-images) | |

## [Markdown 서식 무시 (Ignoring Markdown formatting)](</1. 기본 서식 구문/23. Markdown 서식 무시 (Ignoring Markdown formatting).md>) [![](</images/list icon.jpg>)](#markdown)

문자 앞에 `\`를 사용

```markdown
Let's rename \*our-new-project\* to \*our-old-project\*.
```

## [제목 (Headings)](</1. 기본 서식 구문/01. 제목 (headings).md>) [![](</images/list icon.jpg>)](#markdown)
```markdown
# 
## 
### 
#### 
##### 
###### 
```

## [텍스트 스타일 지정 (Styling text)](</1. 기본 서식 구문/02. 텍스트 스타일 지정 (Styling text).md>) [![](</images/list icon.jpg>)](#markdown)

| 스타일 | 구문 | 예시 |
| --- | --- | --- |
| _기울임꼴_ | `_ _` (or `* *`) | `_기울임꼴_` |
| **굵은글씨** | `** **` (or `__ __`) | `**굵은글씨**` |
| <ins>밑줄</ins> | `<ins> </ins>` | `<ins>밑줄</ins>` |
| ~~취소선~~ | `~~ ~~` (일부 `~ ~`) | `~~취소선~~` |
| <sup>위 첨자</sup> | `<sup> </sup>` | `<sup>위 첨자</sup>` |
| <sub>아래 첨자</sub> | `<sub> </sub>` | `<sub>아래 첨자</sub>` |

## [줄 바꿈 (Line breaks)](</1. 기본 서식 구문/10. 줄 바꿈 (Line breaks).md>) [![](</images/list icon.jpg>)](#markdown)

줄 끝에 공백 두 개를 포함

<pre>
This example&nbsp;&nbsp;<!-- "  " 실제로는 스페이스바(공백)를 2번 입력 -->
Will span two lines
</pre>

줄 끝에 HTML 단일 줄 바꿈 태그를 포함

```markdown
This example<br>
Will span two lines
```

## [단락 (Paragraphs)](</1. 기본 서식 구문/19. 단락 (Paragraphs).md>) [![](</images/list icon.jpg>)](#markdown)

텍스트 줄 사이에 빈 줄을 둠

<pre>
This example

Will span two lines
</pre>

## [수평선 (Horizontal Rule)](</3. 추가/52. 수평선.md>) [![](</images/list icon.jpg>)](#markdown)

`***`, `___`, `---`

## [공백 문자 (Whitespace characters)](</3. 추가/51. 공백 문자.md>) [![](</images/list icon.jpg>)](#markdown)

```markdown
 
```

`&#x2004;`  
`&nbsp;`  

<br>
<br>
<br>

## [테이블로 구성 정보 (Organizing information with tables)](</2. 고급 서식 지정 작업/31. 테이블을 사용하여 구성된 데이터 (Organizing information with tables).md>) [![](</images/list icon.jpg>)](#markdown)

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

## [목록 (Lists)](</1. 기본 서식 구문/12. 목록 (Lists).md>) [![](</images/list icon.jpg>)](#markdown)

행 앞에 `숫자` 또는 `-`, `*`, `+`을(를) 입력

```markdown
1. First list item
   - First nested list item
     - Second nested list item
2. Second list item
   - First nested list item
     - Second nested list item
```

## [작업 목록 (Task lists)](</1. 기본 서식 구문/13. 작업 목록 (Task lists).md>) [![](</images/list icon.jpg>)](#markdown)

`- [ ] `

```markdown
- [ ] 
- [x] 
```

## [작업 목록 정보 (About task lists)](</2. 고급 서식 지정 작업/38. 작업 목록 정보 (About task lists).md>) [![](</images/list icon.jpg>)](#markdown)

> for GitHub  
깃허브 이슈에서 작업목록 사용

<br>
<br>
<br>

## [주석이 있는 콘텐츠 숨기기 (Hiding content with comments)](</1. 기본 서식 구문/22. 주석이 있는 콘텐츠 숨기기 (Hiding content with comments).md>) [![](</images/list icon.jpg>)](#markdown)

```markdown
<!--  -->
```

## [텍스트 인용 (Quoting text)](</1. 기본 서식 구문/03. 텍스트 인용 (Quoting text).md>) [![](</images/list icon.jpg>)](#markdown)

```markdown
> 
```

## [코드 인용 (Quoting code) & 코드 블록 (Code Block)](</1. 기본 서식 구문/03. 텍스트 인용 (Quoting text).md>) [![](</images/list icon.jpg>)](#markdown)

[코드 블록](</2. 고급 서식 지정 작업/33. 코드 블록 만들기 및 강조 표시 (Creating and highlighting code blocks).md>)

````markdown
`text`
````

````markdown
```python
text
```
````

## [축소된 섹션을 사용하여 정보 구성 (Organizing information with collapsed sections)](</2. 고급 서식 지정 작업/32. 축소된 섹션 (Organizing information with collapsed sections).md>) [![](</images/list icon.jpg>)](#markdown)

````markdown
<details open>
<summary>Tips for collapsed sections</summary>

</details>
````

  ## [강조 메세지 (Alerts)](</1. 기본 서식 구문/21. 강조 메세지 (Alerts).md>) [![](</images/list icon.jpg>)](#markdown)

> for GitHub  

```markdown
> [!NOTE]  
> 참고: 추가적인 설명이나 주석을 나타냅니다.

> [!TIP]  
> 팁: 유용한 힌트나 권장 사항을 제공합니다.

> [!IMPORTANT]  
> 중요: 반드시 알아야 할 핵심 정보를 강조합니다.

> [!WARNING]  
> 경고: 잠재적인 문제나 위험 요소를 알립니다.

> [!CAUTION]  
> 주의: 조심해야 할 상황이나 조건을 안내합니다.
```

<br>
<br>
<br>

## [링크 (Links)](</1. 기본 서식 구문/06. 링크 (Links).md>) [![](</images/list icon.jpg>)](#markdown)

`[]()`

```markdown
[GitHub](https://github.com/)
```

## [상대 링크 (Relative links)](</1. 기본 서식 구문/08. 상대 링크 (Relative links).md>) [![](</images/list icon.jpg>)](#markdown)

동일 레포지토리 내의 다른 파일로 연결

- /images/ → 루트 기준 <!-- 권장 -->
- images/ 와 ./images/ → 현재 폴더 기준
- ../images/ → 상위 폴더 기준

```markdown
[Contribution guidelines for this project](/docs/CONTRIBUTING.md)
```

## [섹션 링크 (Section links)](</1. 기본 서식 구문/07. 섹션 링크 (Section links).md>) [![](</images/list icon.jpg>)](#markdown)

해당 파일 내의 섹션으로 연결

```markdown
[섹션 링크로 이동](#섹션-링크-section-links)
```

## [사용자 지정 앵커 (Custom anchors)](</1. 기본 서식 구문/09. 사용자 지정 앵커 (Custom anchors).md>) [![](</images/list icon.jpg>)](#markdown)

섹션을 가리키는 사용자 지정 앵커 만들기

```markdown
text  
<a id="my-custom-anchor-point"></a>
text  

[A link to that custom anchor](#my-custom-anchor-point)
```

<br>
<br>
<br>

## [이미지 (Images)](</1. 기본 서식 구문/11. 이미지 (Images).md>) [![](</images/list icon.jpg>)](#markdown)

`![]()`

```markdown
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`
```

<br>
<br>
<br>

## [수학 식 작성 (Writing mathematical expressions)](</2. 고급 서식 지정 작업/35. 수학 식 (Writing mathematical expressions).md>) [![](</images/list icon.jpg>)](#markdown)

<code>$\`</code>

```markdown
This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$
```

This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$

## [다이어그램 만들기 (Creating diagrams)](</2. 고급 서식 지정 작업/34. 다이어그램 만들기 (Creating diagrams).md>) [![](</images/list icon.jpg>)](#markdown)

<br>
<br>
<br>

## [이모지 (emojis)](</1. 기본 서식 구문/18. 이모지 사용 (Using emojis).md>) [![](</images/list icon.jpg>)](#markdown)

- [Get Emoji](https://getemoji.com/)

<big><big>

☰️⚙️🎨📁🖱️⌨️

⭕️❌❓❔❗️❕️‼️⁉️✔️☑️✅❎⏸️

💠🔺🔻🔸🔹🔶🔷♦️🔴🟠🟡🟢🔵🟣🟤⚫️⚪️🟥🟧🟨🟩🟦🟪🟫⬛️⬜️

⬆️↗️➡️↘️⬇️↙️⬅️↖️🔼🔽⏫⏬↕️↔️↩️↪️⤴️⤵️🔃🔄🔙🔚🔛🔜🔝

0️⃣1️⃣2️⃣3️⃣4️⃣5️⃣6️⃣7️⃣8️⃣9️⃣🔟#️⃣*️⃣

➕➖➗✖️🟰

♠️♥️♦️♣️

⚠️⛔🚫🚨🚥🚦🛑🚧

📱📲💻🖥️⌨️🖱🖱️📞☎️🛠️⚙️🎨

🔗⛓️‍💥🧱⛓️

🧲🔑🗝️🪟📁📂📋📃📄📑📆🔍🔎🔏🔒🔓🫆🎵🆔️

💵💰🪙💲

💫⭐️✨⚡️🔥💧💎💡📌🔖🏷️📢📖📓📒📚📕📗📘📙🪄🔔🧹🎉🚩💬🌍🌎🌏🌐⌛⏳🎲

</big></big>

⌨️ `Ctrl` + `Alt` + `Shift` +

- 🖱️ Click
- 🖱️ Left Click
- 🖱️ Double Click
- 🖱️ Right Click
- 🖱️ Middle Click
- 🖱️ Drag and Drop
- 🖱️ Scroll
- 🖱️ Hover (호버) <!-- 버튼을 누르지 않고 커서를 올려놓기 -->

|  |  |
|---|---|
|  |  |
|  |  |