+++
# Project title.
title = "Masscat Follows Hand"

# Date this page was created.
date = 2019-03-22T00:00:00

# Project summary to display on homepage.
summary = "Leap Motionで手をセンシングし、Looking Glassのカメラ操作を手で行うことができるアプリです。"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Application", "Game", "Leap Motion", "Looking Glass", "Masscat", "Unity", "xR"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Links (optional).
url_pdf = ""
url_slides = ""
url_video = ""
url_code = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{icon_pack = "fab", icon="twitter", name="Follow", url = "https://twitter.com/segur_vita"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your project's folder. 
[image]
  # Caption (optional)
  caption = "ますきゃっと様"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++



Looking Glassにキャラクターを表示して遊んでいたときに思いました。

全身を見ようとすると、顔の解像度が下がってしまう。**全身も見たいし、顔も見たい！！**
カメラをズームイン／アウトできればいいんだけど、Looking Glassにタッチパネルは付いてないし、マウスもキーボードも使いたくない・・・

そうだ！ **Leap Motion** を使おう！

そうして作ったのが、 **Masscat Follows Hand** です。ますきゃっと様と戯れることができます。

Leap Motionによって、両手の動きを検出し、ズームや回転等の操作をすることができるんです！

{{<twitter user="segur_vita" id="1109754332092624896" >}}

バックパックPCと組み合わせて、歩き展示をしたかったので、片手操作モードも実装しましたｗ

{{<twitter user="segur_vita" id="1108794958318702592" >}}

[Looking Glass Library](https://madewith.lookingglassfactory.com/app/128/) にリリースしましたので、Looking Glassをお持ちの方はぜひ、遊んでみてください。


## 概要

- 開発環境: Unity
- 動作環境: Looking Glass, Leap Motion
- リリース: [Looking Glass Library](https://madewith.lookingglassfactory.com/app/128/)




## 技術記事

- [【LeapMotion+UniRx】手の動きでカメラを動かす](https://qiita.com/segur/items/13d22727c913f8159990)
- [【LeapMotion+UniRx】手の動きでカメラを動かす：両手編](https://qiita.com/segur/items/4d9947db66d70def9762)



## 展示

- [xR Tech Tokyo #15](https://vrtokyo.connpass.com/event/121561/)（野良）
- [Looking Glass ミートアップ](https://connpass.com/event/124916/)



