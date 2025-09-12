[GitHub 마크다운](https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

# [Markdown](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/Markdown.md)

[제목](#제목-headings)  
[텍스트 스타일 지정](#텍스트-스타일-지정-styling-text)  
[텍스트 인용](#텍스트-인용-quoting-text)  
[인용 코드](#인용-코드-quoting-code)  
[링크](#링크-links)  
[상대 링크](#상대-링크-relative-links)  
[섹션 링크](#섹션-링크-section-links)  
[사용자 지정 앵커](#사용자-지정-앵커-custom-anchors)  
[줄 바꿈](#줄-바꿈-line-breaks)  
[공백 문자](#공백-문자)  
[이미지](#이미지-images)  
[목록](#목록-lists)  
[작업 목록](#작업-목록-task-lists)

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
| 이탤릭체 | `_ _` (or `* *`)  | `_기울임꼴_ 텍스트` | _기울임꼴_ 텍스트 |
| 굵게 | `** **` (or `__ __`) | `**굵은** 텍스트` | **굵은** 텍스트 |
| 밑줄 | `<ins> </ins>` | `<ins>밑줄</ins> 텍스트` | <ins>밑줄</ins> 텍스트 |
| 취소선 | `~~ ~~` (일부 `~ ~`)| `~~취소선~~ 텍스트` | ~~취소선~~ 텍스트 |
| 위 첨자 | `<sup> </sup>` | `<sup>위 첨자</sup> 텍스트` | <sup>위 첨자</sup> 텍스트 |
| 아래 첨자 | `<sub> </sub>` | `<sub>아래 첨자</sub> 텍스트` | <sub>아래 첨자</sub> 텍스트 |

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

## [줄 바꿈 (Line breaks)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/10.%20%EC%A4%84%20%EB%B0%94%EA%BF%88%20(Line%20breaks).md) [![](<list icon.jpg>)](#markdown)

줄 끝에 공백 두 개를 포함
<pre>
This example&nbsp;&nbsp;<!-- "  " 실제로는 스페이스바(공백)를 2번 입력 -->
Will span two lines
</pre>

## [공백 문자](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/3.%20%EC%B6%94%EA%B0%80/51.%20%EA%B3%B5%EB%B0%B1%20%EB%AC%B8%EC%9E%90.md) [![](<list icon.jpg>)](#markdown)

```markdown
 
```
`&#x2004;`  

## [이미지](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/11.%20%EC%9D%B4%EB%AF%B8%EC%A7%80%20(Images).md) [![](<list icon.jpg>)](#markdown)

`![]()`

```markdown
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://myoctocat.com/assets/images/base-octocat.svg)`  
```

## [목록](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/12.%20%EB%AA%A9%EB%A1%9D%20(Lists).md) [![](<list icon.jpg>)](#markdown)

```markdown
1. First list item
  - First nested list item
    - Second nested list item
2. Second list item
  - First nested list item
    - Second nested list item
```

1. ㅁㄹㄹㄹ
   - 
     - 
     
       - Third nested list item
2. Second list item
   - First nested list item
     - Second nested list item

## [작업 목록 (Task lists)](https://github.com/Ant-Queen/Markdown_for_GitHub/blob/main/1.%20%EA%B8%B0%EB%B3%B8%20%EC%84%9C%EC%8B%9D%20%EA%B5%AC%EB%AC%B8/13.%20%EC%9E%91%EC%97%85%20%EB%AA%A9%EB%A1%9D%20(Task%20lists).md) [![](<list icon.jpg>)](#markdown)

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
