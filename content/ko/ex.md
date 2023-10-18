---
title: Example Page
type: docs
---



{{% detail summary="Code 샘플" %}}
```go

```
{{% /detail %}}

------------------------------------------

<div style="text-align: left;">
  <a href="https://hits.seeyoufarm.com">
    <img
      src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fhl5ky.github.io&count_bg=%230DC276&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=+%EB%B0%A9%EB%AC%B8%EC%9E%90+%EC%88%98+&edge_flat=false"
    />
  </a>
</div>

<br>

--------------------------------------------

{{% detail summary="Code 새로운 탭에서 외부링크" %}}
```go
{< newtabref href="https://www.qrz.com/lookup/jo1dza" title="JO1DZA QRZ.COM Page" >}}
```
{{% /detail %}}

{{< newtabref href="https://www.qrz.com/lookup/jo1dza" title="JO1DZA QRZ.COM Page" >}})

----------------------------------

{{% detail summary="Code 그림넣기" %}}
```go
<img src="/friendship/events/img/jh1nbn.jpeg"><br>
```
{{% /detail %}}


<img src="/friendship/events/img/jh1nbn.jpeg" style="width:438px;height:359"><br>

----------------------------------
{{% detail summary="Code 글자색, 배경색, 강조" %}}
```go
<span style="color:red; background-color:#fff5b1">**실화**</span>
```
{{% /detail %}}

<span style="color:red; background-color:#fff5b1">**실화**</span>

-----------------------------------

{{% detail summary="Code 글자 부분 배경" %}}
```go
Code snippets like `var foo = "bar";` Also,  ~~`with this`~~ ~~and this~~.
```
{{% /detail %}}

Code snippets like `var foo = "bar";` Also,  ~~`with this`~~ ~~and this~~.

----------------------------------
{{% detail summary="Code 사각 설명문" %}}
```go
{% pageinfo %}
This is a placeholder page. Replace it with your own content.
{% /pageinfo %}
```
{{% /detail %}}

{{% pageinfo %}}
This is a placeholder page. Replace it with your own content.
{{% /pageinfo %}}

------------------------------------------------
{{% detail summary="Code 바탕색 변경 설명문" %}}
```go
시작과 끝 라인에 ``` 이 필요함.
시작 라인에 go 를 추가하면 복사아이콘이 생김.

foo := "bar";
bar := "foo";
```
{{% /detail %}}

```
foo := "bar";
bar := "foo";
```

-----------------------------------------------

{{% detail summary="Code 문장 펼침" %}}
```go
{를 하나씩 더 추가해야 함.

{% detail summary="5단계단어연습" %}
---go
QSO
TKS
QKS FOR QSO
73
CUAGN
---
{% /detail %}
```
{{% /detail %}}

<br>

{{% detail summary="5단계단어연습" %}}
```go
QSO
TKS
QKS FOR QSO
73
CUAGN
```
{{% /detail %}}

---------------------------------
{{% detail summary="Code 글자-강조,이태릭체,취소선" %}}
```go
**bold**, _italic_ *italic*, or ~~strikethrough~~
[Links_name](https://gohugo.io)
```
{{% /detail %}}

**bold**, _italic_ *italic*, or ~~strikethrough~~

[Links_name](https://gohugo.io)

--------------------------------------
{{% detail summary="Code " %}}
```go
> There should be no margin above this first sentence.
>
> Blockquotes should be a lighter gray with a border along the left side in the secondary color.
```
{{% /detail %}}

> There should be no margin above this first sentence.
>
> Blockquotes should be a lighter gray with a border along the left side in the secondary color.

-----------------------------------------
{{% detail summary="Code" %}}
```go
{< alert >}This is an alert.{< /alert >}
{< alert title="Note" >}This is an alert with a title.{< /alert >}
{% alert title="Note" %}This is an alert with a title and **Markdown**.{% /alert %}
{< alert color="success" >}BLUE COLOR  BLUE COLOR  BLUE COLOR{< /alert >} BLUE COLOR
{< alert color="warning" >}This is a warning.{< /alert >}
{< alert color="warning" title="Warning" >}This is a warning with a title.{< /alert >}
```
{{% /detail %}}

{{< alert >}}This is an alert.{{< /alert >}}
{{< alert title="Note" >}}This is an alert with a title.{{< /alert >}}
{{% alert title="Note" %}}This is an alert with a title and **Markdown**.{{% /alert %}}
{{< alert color="success" >}} BLUE COLOR  BLUE COLOR  BLUE COLOR{{< /alert >}}
{{< alert color="warning" >}}This is a warning.{{< /alert >}}
{{< alert color="warning" title="Warning" >}}This is a warning with a title.{{< /alert >}}

-------------------------------------------
{{% detail summary="Code" %}}
```go
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```
{{% /detail %}}
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

---------------------------------------

{{% detail summary="Code" %}}
```go
| What      | Follows         |
|-----------|-----------------|
| A table   | A header        |
| A table   | A header        |
| A table   | A header        |
```
{{% /detail %}}

| What      | Follows         |
|-----------|-----------------|
| A table   | A header        |
| A table   | A header        |
| A table   | A header        |

----------------

{{% detail summary="Code" %}}
```go
* Liverpool F.C.
* Chelsea F.C.
* Manchester United F.C.

And an ordered list:

1. Michael Brecker
2. Seamus Blake
3. Branford Marsalis

And an unordered task list:

- [x] Create a Hugo theme
- [x] Add task lists to it
- [ ] Take a vacation
```
{{% /detail %}}

* Liverpool F.C.
* Chelsea F.C.
* Manchester United F.C.

And an ordered list:

1. Michael Brecker
2. Seamus Blake
3. Branford Marsalis

And an unordered task list:

- [x] Create a Hugo theme
- [x] Add task lists to it
- [ ] Take a vacation

-----------------------------------

{{% detail summary="Code" %}}
```go
* Jackson 5
  * Michael
  * Tito
  * Jackie
  * Marlon
  * Jermaine
```
{{% /detail %}}

A nested list:

* Jackson 5
  * Michael
  * Tito
  * Jackie
  * Marlon
  * Jermaine

----------------------------------
{{% detail summary="Code" %}}
```go
Name
: Godzilla

Born
: 1952

Birthplace
: Japan
```
{{% /detail %}}

Name
: Godzilla

Born
: 1952

Birthplace
: Japan

----------------
{{% detail summary="Code" %}}
```go
| Artist            | Album           | Year |
|-------------------|-----------------|------|
| Michael Jackson   | Thriller        | 1982 |
| Prince            | Purple Rain     | 1984 |
| Beastie Boys      | License to Ill  | 1986 |
```
{{% /detail %}}


Tables should have bold headings and alternating shaded rows.

| Artist            | Album           | Year |
|-------------------|-----------------|------|
| Michael Jackson   | Thriller        | 1982 |
| Prince            | Purple Rain     | 1984 |
| Beastie Boys      | License to Ill  | 1986 |

------------------------------------
{{% detail summary="Code" %}}
```go
| Artist            | Album           | Year | Label       | Awards   | Songs     |
|-------------------|-----------------|------|-------------|----------|-----------|
| Michael Jackson   | Thriller        | 1982 | Epic Records | Grammy Award for Album of the Year, American Music Award for Favorite Pop/Rock Album, American Music Award for Favorite Soul/R&B Album, | Wanna Be Startin' Somethin', Baby Be Mine, The Girl Is Mine, Thriller, Beat It, Billie Jean, Human Nature, P.Y.T. |
| Prince            | Purple Rain     | 1984 | Warner Brothers Records | Grammy Award for Best Score Soundtrack for Visual Media, American Music Award for Favorite Pop/Rock Album, American Music Award | Take Me With U, The Beautiful Ones, Computer Blue, Darling Nikki, |
| Beastie Boys      | License to Ill  | 1986 | Mercury Records | noawardsbutthistablecelliswide | Rhymin & Stealin, The New Style, She's Crafty, Posse in Effect, Slow Ride, Girls, (You Gotta) |
```
{{% /detail %}}

If a table is too wide, it should scroll horizontally.

| Artist            | Album           | Year | Label       | Awards   | Songs     |
|-------------------|-----------------|------|-------------|----------|-----------|
| Michael Jackson   | Thriller        | 1982 | Epic Records | Grammy Award for Album of the Year, American Music Award for Favorite Pop/Rock Album, American Music Award for Favorite Soul/R&B Album, | Wanna Be Startin' Somethin', Baby Be Mine, The Girl Is Mine, Thriller, Beat It, Billie Jean, Human Nature, P.Y.T. |
| Prince            | Purple Rain     | 1984 | Warner Brothers Records | Grammy Award for Best Score Soundtrack for Visual Media, American Music Award for Favorite Pop/Rock Album, American Music Award | Take Me With U, The Beautiful Ones, Computer Blue, Darling Nikki, |
| Beastie Boys      | License to Ill  | 1986 | Mercury Records | noawardsbutthistablecelliswide | Rhymin & Stealin, The New Style, She's Crafty, Posse in Effect, Slow Ride, Girls, (You Gotta) |

----------------


