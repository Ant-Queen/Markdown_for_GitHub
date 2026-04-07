# [Markdown 서식 요약](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md)

| 스타일 | 구문 | 예시 |
| --- | --- | --- |
| _기울임꼴_ | `_ _` (or `* *`) | `_기울임꼴_` |
| **굵은글씨** | `** **` (or `__ __`) | `**굵은글씨**` |
| <ins>밑줄</ins> | `<ins> </ins>` | `<ins>밑줄</ins>` |
| ~~취소선~~ | `~~ ~~` (일부 `~ ~`) | `~~취소선~~` |

|  |  |  |
|---|---|---|
| 서식 무시 | `\` | 문자 앞에 사용|
| 제목 | # |  |
| 줄 바꿈 | `  ` or \<br> | 줄 끝에 공백 두 개 or \<br> 태그 |

| 제목 | # | dd |
| 단락 | (빈 줄) | 텍스트 줄 사이에 빈 줄을 둠 |
| 수평선 | `***`, `___`, `---` |  |
| 공백문자 | ` ` or `&nbsp;` |  |
| 작업 목록 | `- [ ] ` and `- [x] ` |  |

```markdown
|  |  |
|---|---|
|  |  |
|  |  |

| :---     |   :---:   |     ---: |
```

```markdown
 1. 
   - 
     * 
       + 
 2. 
```


## [작업 목록 (Task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/13.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20(Task%20lists).md) [![](</images/list icon.jpg>)](#markdown)

`- [ ] `

```markdown
- [ ] 
- [x] 
```

## [작업 목록 정보 (About task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/38.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20%EC%A0%95%EB%B3%B4%20(About%20task%20lists).md) [![](</images/list icon.jpg>)](#markdown)

> for GitHub  
깃허브 이슈에서 작업목록 사용

<br>
<br>
<br>

## [주석이 있는 콘텐츠 숨기기 (Hiding content with comments)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/22.%20%EC%A3%BC%EC%84%9D%EC%9D%B4%20%EC%9E%88%EB%8A%94%20%EC%BD%98%ED%85%90%EC%B8%A0%20%EC%88%A8%EA%B8%B0%EA%B8%B0%20(Hiding%20content%20with%20comments).md) [![](</images/list icon.jpg>)](#markdown)

```markdown
<!--  -->
```

## [텍스트 인용 (Quoting text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/03.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%9D%B8%EC%9A%A9%20(Quoting%20text).md) [![](</images/list icon.jpg>)](#markdown)

```markdown
> 
```

## [코드 인용 (Quoting code) & 코드 블록 (Code Block)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/04.%20%EC%9D%B8%EC%9A%A9%20%EC%BD%94%EB%93%9C%20(Quoting%20code).md) [![](</images/list icon.jpg>)](#markdown)

````markdown
`text`
````

````markdown
```python
text
```
````

## [축소된 섹션을 사용하여 정보 구성 (Organizing information with collapsed sections)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/32.%20%EC%B6%95%EC%86%8C%EB%90%9C%20%EC%84%B9%EC%85%98%20(Organizing%20information%20with%20collapsed%20sections).md) [![](</images/list icon.jpg>)](#markdown)

````markdown
<details open>
<summary>Tips for collapsed sections</summary>

</details>
````

## [경고 (Alerts)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/21.%20%EA%B2%BD%EA%B3%A0%20(Alerts).md) [![](</images/list icon.jpg>)](#markdown)

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

<br>
<br>
<br>

## [링크 (Links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/06.%20%EB%A7%81%ED%81%AC%20(Links).md) [![](</images/list icon.jpg>)](#markdown)

`[]()`

```markdown
[GitHub](https://github.com/)
```

## [상대 링크 (Relative links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/08.%20%EC%83%81%EB%8C%80%20%EB%A7%81%ED%81%AC%20(Relative%20links).md) [![](</images/list icon.jpg>)](#markdown)

동일 레포지토리 내의 다른 파일로 연결

```markdown
[Contribution guidelines for this project](/docs/CONTRIBUTING.md)
```

## [섹션 링크 (Section links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/07.%20%EC%84%B9%EC%85%98%20%EB%A7%81%ED%81%AC%20(Section%20links).md) [![](</images/list icon.jpg>)](#markdown)

해당 파일 내의 섹션으로 연결

- images/ 와 ./images/ → 현재 폴더 기준
- ../images/ → 상위 폴더 기준
- /images/ → 루트 기준

```markdown
[섹션 링크로 이동](#섹션-링크-section-links)
```

## [사용자 지정 앵커 (Custom anchors)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/09.%20%EC%82%AC%EC%9A%A9%EC%9E%90%20%EC%A7%80%EC%A0%95%20%EC%95%B5%EC%BB%A4%20(Custom%20anchors).md) [![](</images/list icon.jpg>)](#markdown)

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

## [이미지 (Images)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/11.%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20(Images).md) [![](</images/list icon.jpg>)](#markdown)

`![]()`

```markdown
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`
```

<br>
<br>
<br>

## [수학 식 작성 (Writing mathematical expressions)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/35.%20%EC%88%98%ED%95%99%20%EC%8B%9D%20(Writing%20mathematical%20expressions).md) [![](</images/list icon.jpg>)](#markdown)

<code>$\`</code>

```markdown
This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$
```

This sentence uses <code>$\`</code> and <code>\`$</code> delimiters to show math inline: $`\sqrt{3x-1}+(1+x)^2`$

## [다이어그램 만들기 (Creating diagrams)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/2.%20%EA%B3%A0%EA%B8%89%20%EC%84%9C%EC%8B%9D%20%EC%A7%80%EC%A0%95%20%EC%9E%91%EC%97%85/34.%20%EB%8B%A4%EC%9D%B4%EC%96%B4%EA%B7%B8%EB%9E%A8%20%EB%A7%8C%EB%93%A4%EA%B8%B0%20(Creating%20diagrams).md) [![](</images/list icon.jpg>)](#markdown)

<br>
<br>
<br>

## [이모지 (emojis)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/18.%20%EC%9D%B4%EB%AA%A8%EC%A7%80%20%EC%82%AC%EC%9A%A9%20(Using%20emojis).md) [![](</images/list icon.jpg>)](#markdown)

- [Get Emoji](https://getemoji.com/)

<big><big>

☰️⚙️🎨📁🖱️⌨️

⭕️❌❓❔❗️❕️‼️⁉️✔️☑️✅❎

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