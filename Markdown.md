# [Markdown](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md)

[제목 (Headings)](#%EC%A0%9C%EB%AA%A9-headings)  
[텍스트 스타일 지정 (Styling text)](#%ED%85%8D%EC%8A%A4%ED%8A%B8-%EC%8A%A4%ED%83%80%EC%9D%BC-%EC%A7%80%EC%A0%95-styling-text)  
[텍스트 인용 (Quoting text)](#%ED%85%8D%EC%8A%A4%ED%8A%B8-%EC%9D%B8%EC%9A%A9-quoting-text)  
[인용 코드 (Quoting code)](#%EC%9D%B8%EC%9A%A9-%EC%BD%94%EB%93%9C-quoting-code)  
[링크 (Links)](#%EB%A7%81%ED%81%AC-links)  
[상대 링크 (Relative links)](#%EC%83%81%EB%8C%80-%EB%A7%81%ED%81%AC-relative-links)  
[섹션 링크 (Section links)](#%EC%84%B9%EC%85%98-%EB%A7%81%ED%81%AC-section-links)  
[사용자 지정 앵커 (Custom anchors)](#%EC%82%AC%EC%9A%A9%EC%9E%90-%EC%A7%80%EC%A0%95-%EC%95%B5%EC%BB%A4-custom-anchors)  
[줄 바꿈 (Line breaks)](#줄-바꿈-line-breaks)  
[공백 문자](#공백-문자)  
[이미지 (Images)](#이미지-images)  
[목록 (Lists)](#목록-lists)  
[작업 목록 (Task lists)](#작업-목록-task-lists)

## [제목 (Headings)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/01.%20%EC%A0%9C%EB%AA%A9%20(headings).md) [![](<The unordered list icon.jpg>)](#markdown)

https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md#%EC%A0%9C%EB%AA%A9-headings

```markdown
# 
## 
### 
#### 
##### 
###### 
```
<details>

# A first-level heading
## A second-level heading
### A third-level heading
#### A fourth-level heading
##### A fifth-level heading
###### A sixth-level heading

</details>

## [텍스트 스타일 지정 (Styling text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/02.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%8A%A4%ED%83%80%EC%9D%BC%20%EC%A7%80%EC%A0%95%20(Styling%20text).md) [![](<The unordered list icon.jpg>)](#markdown)

| 스타일 | 구문 | 예시 | 출력 |
| --- | --- | --- | --- |
| 이탤릭체 | `_ _` (or `* *`)  | `_기울임꼴_ 텍스트` | _기울임꼴_ 텍스트 |
| 굵게 | `** **` (or `__ __`) | `**굵은** 텍스트` | **굵은** 텍스트 |
| 밑줄 | `<ins> </ins>` | `<ins>밑줄</ins> 텍스트` | <ins>밑줄</ins> 텍스트 |
| 취소선 | `~~ ~~` (일부 `~ ~`)| `~~취소선~~ 텍스트` | ~~취소선~~ 텍스트 |
| 위 첨자 | `<sup> </sup>` | `<sup>위 첨자</sup> 텍스트` | <sup>위 첨자</sup> 텍스트 |
| 아래 첨자 | `<sub> </sub>` | `<sub>아래 첨자</sub> 텍스트` | <sub>아래 첨자</sub> 텍스트 |

## [텍스트 인용 (Quoting text)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/03.%20%ED%85%8D%EC%8A%A4%ED%8A%B8%20%EC%9D%B8%EC%9A%A9%20(Quoting%20text).md) [![](<The unordered list icon.jpg>)](#markdown)

```markdown
> 
```

<details>

> first-level
>> second-level
>>> third-level
>
> first-level

</details>

## [인용 코드 (Quoting code)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/04.%20%EC%9D%B8%EC%9A%A9%20%EC%BD%94%EB%93%9C%20(Quoting%20code).md)

````markdown
`text`
````

````markdown
```
text
```
````

<details>

`text`

```
text
```

</details>

## [링크 (Links)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/06.%20%EB%A7%81%ED%81%AC%20(Links).md)

`[]()`

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
  This example&nbsp;&nbsp;<!-- "  " 실제로는 스페이스바(공백)를 2번 입력 -->
  Will span two lines
  </pre>


<details>

* 첫 번째 줄 끝에 백슬래시를 포함합니다.

  ```markdown
  This example\
  Will span two lines
  ```

* 첫 번째 줄 끝에 HTML 단일 줄 바꿈 태그를 포함합니다.

  ```markdown
  This example<br/>
  Will span two lines
  ```

  This example  
  Will span two lines

  This example\
  Will span two lines

  This example<br/>
  Will span two lines

두 줄 사이에 빈 줄을 넣으면 .md 파일과 문제, 끌어오기 요청, 토론에서 사용되는 Markdown이 모두 빈 줄로 구분되어 두 줄로 렌더링합니다.

```markdown
This example

Will have a blank line separating both lines
```

This example

Will have a blank line separating both lines

</details>

## [공백 문자](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/3.%20%EC%B6%94%EA%B0%80/51.%20%EA%B3%B5%EB%B0%B1%20%EB%AC%B8%EC%9E%90.md)

```markdown
 
```
`&#x2004;`

<details>

| Unicode | 16진수 코드 | 복사하여 사용 | 비고 |
|---|---|---|---|
| 2000 | `&#x2000;` | 가 나 | 1/2 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2001 | `&#x2001;` | 가 나 | 전각 너비. `가장 사용이 권장되는 공백` |
| 2002 | `&#x2002;` | 가 나 | 1/2 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2003 | `&#x2003;` | 가 나 | 전각 너비. `가장 사용이 권장되는 공백` |
| **2004** | `&#x2004;` | 가 나 | 1/3 폭. `가장 사용이 권장되는 공백` |
| 2005 | `&#x2005;` | 가 나 | 1/4 폭. OS, 브라우저 간 미세한 차이 있음 |
| 2006 | `&#x2006;` | 가 나 | 1/6 폭. OS, 브라우저 간 미세한 차이 있음 |
| 200B | `&#x200B;` | 가​나 | ZERO WIDTH SPACE |
| 공백문자 | `&nbsp;` | 가&nbsp;나 | 1/3.66 폭? (1/3 호환 가능성 높음) |
| 스페이스바 | ` ` | 가 나 | 1/3.66 폭? (1/3 호환 가능성 높음) |

</details>

## [이미지](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/11.%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20(Images).md)

`![]()`

```markdown
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`  
```

<details>

![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)

| 컨텍스트 | 상대 링크 |
| ------ | -------- |
| 동일한 분기의 `.md` 파일에서 | `/assets/images/_fixtures/electrocat.png` |
| 다른 분기의 `.md`파일에서 | `/../main/assets/images/_fixtures/electrocat.png` |
| 리포지토리의 이슈, 끌어오기 요청, 주석에서 | `../blob/main/assets/images/_fixtures/electrocat.png?raw=true` |
| 다른 리포지토리의 `.md` 파일에서 | `/../../../../github/docs/blob/main/assets/images/_fixtures/electrocat.png` |
| 다른 리포지토리의 이슈, 끌어오기 요청, 주석에서 | `../../../github/docs/blob/main/assets/images/_fixtures/electrocat.png?raw=true` |

![test1](/assets/images/_fixtures/electrocat.png)
![test2](/../main/assets/images/_fixtures/electrocat.png)
![test3](../blob/main/assets/images/_fixtures/electrocat.png?raw=true)
![test4](/../../../../github/docs/blob/main/assets/images/_fixtures/electrocat.png)
![test5](../../../github/docs/blob/main/assets/images/_fixtures/electrocat.png?raw=true)

### Picture 요소 (The Picture element)

`<picture>` HTML 요소가 지원됩니다.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

</details>

## [목록](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/12.%20%EB%AA%A9%EB%A1%9D%20(Lists).md)

```markdown
1. First list item
  - First nested list item
    - Second nested list item
2. Second list item
  - First nested list item
    - Second nested list item
```

<details>

1. First list item
   - First nested list item
     - Second nested list item
2. Second list item
   - First nested list item
     - Second nested list item

하나 이상의 텍스트 행 앞에 <kbd>-</kbd>, <kbd>*</kbd> 또는 <kbd>+</kbd>을(를) 입력하여 순서가 지정되지 않은 목록을 만들 수 있습니다.

```markdown
- George Washington
* John Adams
+ Thomas Jefferson
```

- George Washington
* John Adams
+ Thomas Jefferson

목록의 순서를 지정하려면 각 줄 앞에 숫자를 입력합니다.

```markdown
1. James Madison
2. James Monroe
3. John Quincy Adams
```

1. James Madison
2. James Monroe
3. John Quincy Adams

### 중첩된 목록 (Nested Lists)

하나 이상의 목록 항목을 다른 항목 아래에 포함하여 중첩된 목록을 만들 수 있습니다.

GitHub의 웹 편집기 또는 [Visual Studio Code](https://code.visualstudio.com/)와 같은 고정 폭 글꼴을 사용하는 텍스트 편집기를 사용하여 중첩 목록을 만들기 위해 목록을 시각적으로 정렬할 수 있습니다. 목록 표식 문자(<kbd>-</kbd> 또는 <kbd>*</kbd>)가 위 항목에 있는 텍스트의 첫 번째 문자 바로 아래에 올 때까지 중첩 목록 항목 앞에 공백 문자를 입력합니다.

```markdown
1. First list item
   - First nested list item
     - Second nested list item
```

1. First list item
   - First nested list item
     - Second nested list item

> [!NOTE]  
> 웹 기반 편집기에서 원하는 줄을 먼저 강조 표시한 다음 kbd>Tab</kbd> 또는 <kbd>Shift</kbd>+<kbd>Tab</kbd>을 각각 사용하여 하나 이상의 텍스트 줄을 들여쓰거나 내어쓸 수 있습니다.

고정 폭 글꼴을 사용하지 않는 GitHub의 주석 편집기에서 중첩된 목록을 만들려면 중첩된 목록 바로 위에 있는 목록 항목을 확인하고 항목의 내용 앞에 표시되는 문자 수를 계산할 수 있습니다. 그런 다음 중첩된 목록 항목 앞에 해당 수만큼의 공백 문자를 입력합니다.

이 예제에서는 `100. First list item` 앞에 5개 문자(`100. `)가 있으므로 중첩된 목록 항목을 최소 5개 공백으로 들여써서 목록 항목 `100. First list item` 아래에 중첩된 목록 항목을 추가할 수 있습니다.

```markdown
100. First list item
     - First nested list item
```

100. First list item
     - First nested list item

동일한 방법을 사용하여 여러 수준의 중첩된 목록을 만들 수 있습니다. 예를 들어 첫 번째 중첩된 목록 항목에는 중첩된 목록 내용 `First nested list item` 앞에 일곱 자의 문자(`␣␣␣␣␣-␣`)가 있으므로, 두 번째 중첩된 목록 항목은 첫 번째 목록 항목보다 두 자 이상 더 들여써야 하며, 이 경우에는 최소 9 개의 공백이 필요합니다.

```markdown
100. First list item
     - First nested list item
       - Second nested list item
```

100. First list item
     - First nested list item
       - Second nested list item

더 많은 예제는 [GitHub Flavored Markdown 사양](https://github.github.com/gfm/#example-265)을 참조하세요.

</details>

## [작업 목록 (Task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/13.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20(Task%20lists).md)

`- [ ] `

```markdown
- [ ] 
- [x] 
```

- [ ] 
- [x] 

```markdown
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```
<details>

작업 목록을 만들려면 하이픈`-`과 공백` ` 뒤에 `[ ]`이 오는 목록 항목의 접두사를 설정합니다. 작업을 완료로 표시하려면 `[x]`를 사용합니다.

> [!NOTE]  
> for GitHub  
> `- [ ]` 뒤에 공백 ` `을 추가하면 체크박스로 표현됩니다.

```markdown
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:
```

- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

작업 목록 항목 설명이 괄호로 시작하는 경우 `\`로 이스케이프해야 합니다.  
(공백을 넣는경우 `\`로 이스케이프하지 않아도 됩니다.)

```markdown
- [x](Optional) Open a followup issue
- [x]\(Optional) Open a followup issue
- [x] (Optional) Open a followup issue
- [x] \(Optional) Open a followup issue
```

- [x](Optional) Open a followup issue
- [x]\(Optional) Open a followup issue
- [x] (Optional) Open a followup issue
- [x] \(Optional) Open a followup issue

자세한 내용은 [작업 목록 정보](/get-started/writing-on-github/working-with-advanced-formatting/about-task-lists)을(를) 참조하세요.

</details>