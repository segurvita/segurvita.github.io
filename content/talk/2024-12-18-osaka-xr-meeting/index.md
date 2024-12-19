+++
title = "VisionProで部屋の明るさを反映させるシェーダーを作った話"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date = 2024-12-18T21:15:00+09:00
all_day = false

# Schedule page publish date (NOT talk date).
publishDate = 2024-11-18T21:15:00+09:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Segur"]

# Location of event.
location = "大阪 / Zoom"

# Name of event and optional event URL.
event = "XRミーティング"
event_url = "https://osaka-driven-dev.connpass.com/event/337920/"

# Abstract. What's your talk about?
abstract = "VisionPro向けにシェーダーを自作した話をしました！"

# Summary. An optional shortened abstract.
summary = ""

# Is this a featured talk? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Apple Vision Pro", "Shader", "Unity"]

# Markdown Slides (optional).
#   Associate this page with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = ""

# Optional filename of your slides within your talk folder or a URL.
url_slides = "https://speakerdeck.com/segur/visionprodebu-wu-noming-rusawofan-ying-saserusiedawozuo-tutahua"

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["2024-05-06-environment-diffuse-shader"]

# Links (optional).
url_pdf = "https://speakerdeck.com/segur/visionprodebu-wu-noming-rusawofan-ying-saserusiedawozuo-tutahua"
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "VisionPro向けにシェーダーを自作した話をしました！"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++


スライドはこちらです！

{{<speakerdeck 59063d603f74499eb3679f21f4c4e24a>}}

暗い場所でVision Proアプリを起動したときに、アバターがキレイに見えない問題を解決するために、シェーダーを作りました。

完成したシェーダーはOpenUPMで公開していますので、ぜひご活用ください！

https://openupm.com/packages/com.segur.poly-spatial-environment-diffuse-shader/
