+++
# Project title.
title = "Leapat"

# Date this page was created.
date = 2019-03-22T00:00:00

# Project summary to display on homepage.
summary = "Leap Motionで手をセンシングし、Looking Glassのカメラ操作を手で行うことができるアプリです。"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Looking Glass", "Leap Motion", "xR", "Unity"]

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

そうして作ったのが、 **Leapat** です。ますきゃっと様と戯れることができます。

Leap Motionによって、両手の動きを検出し、ズームや回転等の操作をすることができるんです！

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr">両手グーでズーム・回転等をできるようにしました。地図アプリのピンチアウトとかの操作の3D版という感じでしょうか。ちょっと癖はあるけど、慣れると便利！デバッグでマウス触らなくてよくなるのが地味に嬉しい。<a href="https://twitter.com/hashtag/LeapMotion?src=hash&amp;ref_src=twsrc%5Etfw">#LeapMotion</a> <a href="https://twitter.com/hashtag/LookingGlass?src=hash&amp;ref_src=twsrc%5Etfw">#LookingGlass</a> <a href="https://t.co/NhizrDS7Tj">pic.twitter.com/NhizrDS7Tj</a></p>&mdash; せぎゅ (@segur_vita) <a href="https://twitter.com/segur_vita/status/1109754332092624896?ref_src=twsrc%5Etfw">2019年3月24日</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

バックパックPCと組み合わせて、歩き展示をしたかったので、片手操作モードも実装しましたｗ

<blockquote class="twitter-tweet" data-lang="ja"><p lang="ja" dir="ltr"><a href="https://twitter.com/hashtag/LookingGlass?src=hash&amp;ref_src=twsrc%5Etfw">#LookingGlass</a> 用のアプリを作成中。 <a href="https://twitter.com/hashtag/LeapMotion?src=hash&amp;ref_src=twsrc%5Etfw">#LeapMotion</a> で取得した手の動きで、Unity内のカメラを動かしてみました。手をグーの形にしている間はカメラを動かせます。グーの形じゃなくなったら終了します。マウスドラッグみたいな感覚で使えるの便利です。更に、前後にも動かせます！ <a href="https://t.co/fE8lM754vW">pic.twitter.com/fE8lM754vW</a></p>&mdash; せぎゅ (@segur_vita) <a href="https://twitter.com/segur_vita/status/1108794958318702592?ref_src=twsrc%5Etfw">2019年3月21日</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>



## 概要

- 開発環境: Unity
- 動作環境: Looking Glass, Leap Motion




## 技術記事

- [【LeapMotion+UniRx】手の動きでカメラを動かす](https://qiita.com/segur/items/13d22727c913f8159990)
- [【LeapMotion+UniRx】手の動きでカメラを動かす：両手編](https://qiita.com/segur/items/4d9947db66d70def9762)



## 展示

- [xR Tech Tokyo #15](https://vrtokyo.connpass.com/event/121561/) （野良）
- [Looking Glass ミートアップ](https://connpass.com/event/124916/)



