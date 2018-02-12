---
layout: default
avatar: true
permalink: /
---

## 🚀 Paper Survey

機械学習 (特にDeep Learning) に関する先行研究および関連研究をまとめています。

---

## Contents

- [Paper Summary of Computer Vision]({{ site.baseurl | append: '/category/cv/' }})
- [Paper Summary of Natural Language Processing]({{ site.baseurl | append: '/category/nlp/' }})
- [Paper Summary of Others]({{ site.baseurl | append: '/category/others' }})

## Latest posts

{% for post in site.posts limit: 3 %}
- [{{ post.title }}]({{ post.url | append: site.baseurl }}){% endfor %}

---

## Rules

* 読もうと思っている論文は[Issue](https://github.com/shunk031/paper-survey/issues)に上げる
* [ProjectsのRelated Works](https://github.com/shunk031/paper-survey/projects/2)に論文を読んだかどうかを管理する
* [format.md](https://github.com/shunk031/paper-survey/blob/master/format.md)にしたがって論文の要旨をまとめる

## Abount Summary Format

- [高速で論文がバリバリ読める落合先生のフォーマットがいい感じだったのでメモ](http://lafrenze.hatenablog.com/entry/2015/08/04/120205)

```
---
layout: post
title:  "論文タイトル"
date:   YYYY-MM-DD
categories: CV NLP Others
---

## 1. どんなもの？

## 2. 先行研究と比べてどこがすごいの？

## 3. 技術や手法の"キモ"はどこにある？

## 4. どうやって有効だと検証した？

## 5. 議論はあるか？

## 6. 次に読むべき論文はあるか？

### 論文情報・リンク

* [著者，"タイトル，" ジャーナル名，voluem，no.，ページ，年](論文リンク)
```

## Example

- [先端技術とメディア表現1 #FTMA15](http://www.slideshare.net/Ochyai/1-ftma15) from [Yoichi Ochiai](http://www.slideshare.net/Ochyai)

![]({{ site.baseurl }}/assets/img/FTMA15-1-page-65.png)
