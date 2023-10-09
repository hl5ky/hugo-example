---
title: Example Page
date: 2017-01-05
description: >
  A short lead description about this content page. It can be **bold** or _italic_ and can be split over multiple paragraphs.
categories: [Examples]
tags: [test, sample, docs]
---
{{% detail summary="Code" %}}
```go

```
{{% /detail %}}

----------------------------------

{{% detail summary="Code" %}}
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
{{% detail summary="Code" %}}
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

{{% detail summary="Code" %}}
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
{{% detail summary="Code" %}}
```go
**bold**, _italic_ *italic*, or ~~strikethrough~~
[Links_name](https://gohugo.io)
```
{{% /detail %}}

**bold**, _italic_ *italic*, or ~~strikethrough~~

[Links_name](https://gohugo.io)

--------------------------------------
{{% detail summary="Code" %}}
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
{{% detail summary="Code" %}}
```go
Code snippets like `var foo = "bar";` Also,  ~~`with this`~~ ~~and this~~.
```
{{% /detail %}}

Code snippets like `var foo = "bar";` Also,  ~~`with this`~~ ~~and this~~.

-----------------------------------

