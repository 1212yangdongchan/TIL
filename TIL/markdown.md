# TIL
 
마크다운 용어정리
___
_3개를 입력하면 Horizon(수평선)이 생겨 라인이 추가됩니다.
<!-- Heading -->
# Heading 1
Heading 1아래에는 자동으로 Horizon이 생성됩니다.
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
#갯수를 1~6개 까지 입력해 최대 6개까지 Heading 스타일이 지원됩니다.
___
Paragraph
이렇게 일반적으로 텍스트만 입력하면 텍스트 그대로 출력됩니다.
___

<!-- Text attributes -->
bold text, italic text, strikethrough.
**~**은 ~양옆에 **을 입력하면 **bold**체가 되고, *을 하나만 감싸면 *italic*이탈릭이 됩니다.
그리고 ~~로 감싸주게 되면 ~~strikethrough~~도 할 수 있습니다
___

<!-- Qoute -->
>TIL
이처럼 텍스트 앞에 >를 붙여 인용구 안에 넣을 수도 있습니다.
___
<!-- bullet list -->
fruits:
별모양 하나만 앞에 달아주면 목록변환도 됩니다.
* 목록 1.
* 목록 2.

혹은 -를 이용해도 됩니다.
other fruits:

- 목록 1.
- 목록 2.
___
<!-- Numbered list -->
Numbers :

1. first
2. second
3. third
또는 이렇게 앞에 숫자를 붙여 숫자목록으로도 만들 수 있습니다.
___
<!-- Link -->
다음은 클릭이 가능한 링크를 만드는 것입니다.
Click [TIL link](https://github.com/1212yangdongchan/TIL/edit/main/README.md)
이처럼 대괄호 안에 원하는 단어나 문장을 작성하고, 소괄호 안에 원하는 링크를 작성하면
클릭이 가능하게 나타낼 수 있습니다.
___
<!-- Image -->
다음은 이미지 입니다.
이미지를 첨부하는 방법은 느낌표 옆에 대괄호 안에 이미지에 대한 설명을 작성한 다음,
소괄호 안에 이미지 링크를 추가하면 됩니다.
![Git hub logo](https://th.bing.com/th/id/R.b814e47ff9e37fc62b60daa8cceaef53?rik=V8BYOc%2bdQstR0A&riu=http%3a%2f%2fwiki.hash.kr%2fimages%2fthumb%2fe%2fe7%2f%ea%b9%83%ed%97%88%eb%b8%8c_%ea%b8%80%ec%9e%90.png%2f450px-%ea%b9%83%ed%97%88%eb%b8%8c_%ea%b8%80%ec%9e%90.png&ehk=MaBxvVWHxzcgWcKOKlyxyZOPYXJZEKC3So0jHKYqXLw%3d&risl=&pid=ImgRaw&r=0)
___
>다음은 테이블 입니다.
<!-- Table -->
|~|~|를 하고 밑에 |--|--|를 해주면 테이블로 변환됩니다.
그래서 동일하게 
|Header|Description|
|--|--|
|Cell1|Cell2|
|Cell1|Cell2|


이런식으로 밑에 셀들을 작성하면 테이블이 완성됩니다.
여기서 셀들을 정렬이 가능한데요,
오른쪽으로 정렬하고 싶으면 
|--|--|에 --오른쪽에 :를 붙이면
|Header|Description|
|--:|--:| 
|Cell1|Cell2|

이런식으로 오른쪽 정렬이되고,
왼쪽으로 정렬하고 싶으면 :을 --왼쪽으로, 가운데로 정렬하고 싶다면 --양쪽에 :를 붙이면 됩니다

|Header|Description|
|:--|:--|
|Cell1|Cell2|
>왼쪽 정렬

|Header|Description|
|--:|--:|
|Cell1|Cell2|
>오른쪽 정렬

|Header|Description|
|:--:|:--:|
|Cell1|Cell2|
>양쪽 정렬
___
<!-- Code -->
다음은 코드입니다.
To print message in the console, use`console.log('your message')` and...
이처럼 `로 묶어 가독성이 좋게 할 수도 있고,
```
console.log('your message')
```
로 할 수도 있고,
```으로 묶는 경우 첫번째 ```줄 옆에 language를 작성하면 문법이 하이라이트가 되어 더 예쁘게 나옵니다

```ts
console.log('your message')
```
