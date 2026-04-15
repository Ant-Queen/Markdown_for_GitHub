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
| 단락 | (빈 줄) | 텍스트 줄 사이에 빈 줄을 둠 |
| 수평선 | `***`, `___`, `---` |  |
| 공백문자 | ` ` or `&nbsp;` |  |
| 테이블 |\|  \|  \|<br>\|---\|---\|<br>\|  \|  \|<br> | \| :---     \|   :---:   \|     ---: \| |
| 목록 |1.&nbsp;<br> &nbsp;&nbsp; -&nbsp;<br> | *, + |
| 작업 목록 |`- [ ] ` <br> `- [x] ` | ex) 깃허브 이슈에서 활용하기 좋음 |
| 주석 숨김 | `<!--  -->` |  |
| 텍스트 인용 | `>` |  |
| 코드 인용 | ``` `` ``` |  |
| 코드 블록  | <code>```언어<br>코드<br>```</code> | 여러 줄 코드, 언어 지정 가능 (`bash`, `python` 등) |
| 코드 블록 | \```markdown<br><br>\``` | python, bash |
| 섹션 축소 | \<details><br>\<summary>\</summary><br><br>\</details> | 선택 \<details open><br>선택 \<summary>Tips for collapsed sections\</summary> |
| 경고 |  | > [!NOTE]<br>> Useful information that users should know, even when skimming content. |

경고
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

1. 
   - 
     * 
       + 
2. 

|  |  |  |
|---|---|---|
| 링크 | `[텍스트](주소)` |  |
| 상대 링크 | `[텍스트](/경로/파일명)` | 동일 레포지토리 내의 다른 파일로 연결 |
| 섹션 링크 | `[텍스트](#앵커-이름)` | 해당 파일 내의 특정 섹션으로 연결 |
| 사용자 지정 앵커 | `<a id="my-custom-anchor-point"></a>` |  |
| 이미지 | `![대체 텍스트](경로)` |  |
| 수학 식 | <code>$\`</code> | $`\sqrt{3x-1}+(1+x)^2`$ |
| 다이어그램 |  |  |
| 이모지 | [Get Emoji](https://getemoji.com/) |  |

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
