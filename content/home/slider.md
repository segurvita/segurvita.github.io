+++
widget = "slider"  # Use the Slider widget
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 30  # Order that this section will appear in.

# ... Put Your Section Options Here (section position etc.) ...

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.

[[item]]
  title = "Zepping Maguro"
  content = "This is a VR art that recreates the comical and powerful landscape depicted on the Great Fishing Flag. A finalist of the STYLY ParticleLive Awards."
  align = "left"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "zepping-maguro/featured.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "For more info"
  cta_url = "/project/zepping-maguro/"

[[item]]
  title = "Masscat vs Maguro"
  content = "This is a VR art that expresses the fierce battle between Masscat and Maguro. A finalist of the STYLY Avatar Diorama Awards 2019."
  align = "right"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#666"  # An HTML color value.
  overlay_img = "masscat-vs-maguro/featured.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.

  cta_label = "For more info"
  cta_url = "/project/masscat-vs-maguro/"
  # cta_icon_pack = "fas"
  # cta_icon = "graduation-cap"

[[item]]
  title = "Luminaries"
  content = "This is a Game using VFX and sound. The winner of the Looking Glass Hackathon!"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "luminaries/slide01.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "For more info"
  cta_url = "/project/luminaries/"
  # cta_icon_pack = "fas"
  # cta_icon = "link"

[[item]]
  title = "Masscat follows ball"
  content = "This is a Looking Glass Game where you can play with Masscat!"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "masscat-follows-ball/featured.png"  # Image path relative to your `static/img/` folder.
  overlay_filter = 0.5  # Darken the image. Value in range 0-1.

  cta_label = "For more info"
  cta_url = "/project/masscat-follows-ball/"
  # cta_icon_pack = "fas"
  # cta_icon = "link"

+++