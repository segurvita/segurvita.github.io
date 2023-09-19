+++
# Project title.
title = "Led Matrix with IoT and VR"

# Date this page was created.
date = 2020-10-10T00:00:00

# Project summary to display on homepage.
summary = "VR空間内でお絵描きすると、自宅の8x8LEDに反映される仕組みを作ってみました！"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["IoT", "JavaScript", "MQTT", "STYLY", "Unity", "xR"]

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
  caption = "Led Matrix with IoT and VR"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++

「VR と IoT を組み合わせて何か面白いことしましょう！」

そんな風に [SensitiveCube](https://twitter.com/onCube_jp) さんに誘われて、２人での制作が始まりました。

たまたま私が LED Matrix というデバイスを持っていたので、最初にこんな技術デモを制作しました。

{{<tweet 1301404377387683846>}}

VR 空間内のブロックの状態が、リアルタイムに現実世界の LED へ反映されます！

この技術デモをベースに [SensitiveCube](https://twitter.com/onCube_jp) さんが、よりリッチな空間にしたものがこちらです！

{{<tweet 1314857582956220416>}}

光り輝くセイバーがとてもかっこいいシーンになりました！

## 利用技術

主に以下の技術を利用しています。

- RGB LED Matrix Screen
  - 8x8 の LED デバイス です。
  - 詳細はこちらをご覧ください。 https://qiita.com/segur/items/c56a70189c56acff6100
- RGB LED Matrix Driver Shield
  - LED と Arduino を接続するデバイスです。
- Arduino UNO
  - LED の制御および MQTT Subscriber を担当します。
  - C++ で実装しました。
- shiftr.io
  - MQTT Broker を担当します。
- Firebase
  - MQTT Publisher を担当します。
  - JavaScript Express で実装しました。
- STYLY
  - VR 空間を担当します。
  - Firebase との通信します。
  - Playmaker で実装しました。

上記のように、VR から IoT まで幅広い技術を駆使する必要がありました。
（障害が発生したときに、問題箇所を特定するのに大変苦労しました。）

## 概要

- 開発環境: Unity, Playmaker, JavaScript, Firebase, shiftr.io
- 動作環境: STYLY
- 担当箇所: 通信技術全般, シーンの技術部分全般

## 発表

- [Unity 道場 ロボティクススペシャル 龍の巻](https://meetup.unity3d.jp/jp/events/1257)

## 公開資料

- [Arduino で 8x8 の LED Matrix を光らせる](https://qiita.com/segur/items/c56a70189c56acff6100)
- [Firebase Cloud Functions で MQTT Publisher を作ってみた](https://qiita.com/segur/items/bf9a31b6906a99a7ae26)

## Special Thanks

Sensitive Cube
https://www.artstation.com/artwork/w6LKgL

