+++
# Slider widget.
widget = "slider"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 1  # Order that this section will appear.

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval = 4000

# Slide height (optional).
# E.g. `500px` for 500 pixels or `calc(100vh - 70px)` for full screen.
height = "500px"

# Slides.
# Duplicate an `[[item]]` block to add more slides.
[[item]]
  title = "Välkommen till Apotekens Service"
  content = "Vi levererar IT-tjänster inom apotek och e-hälsa</br></br>"
  align = "center"  # Choose `center`, `left`, or `right`.

  # Overlay a color or image (optional).
  #   Deactivate an option by commenting out the line, prefixing it with `#`.
  overlay_color = "#00FF00"  # An HTML color value.
  overlay_img = "pexels-george-desipris-1046334.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.

  # Call to action button (optional).
  #   Activate the button by specifying a URL and button label below.
  #   Deactivate by commenting out parameters, prefixing lines with `#`.
  cta_label = "Kontakta oss"
  cta_url = "#contact"
  cta_icon_pack = "fas"
  cta_icon = "address-card"

[[item]]
  title = "Konsulttjänster"
  content = "Projektledning och arkitektur"
  align = "left"

  overlay_color = "#555"  # An HTML color value.
  overlay_img = "pexels-bongkarn-thanyakij-3734603.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.3  # Darken the image. Value in range 0-1.

[[item]]
  title = "Två hål i väggen"
  content = "Software as a service"
  align = "right"

  overlay_color = "#333"  # An HTML color value.
  overlay_img = "pexels-freestocksorg-167300.jpg"  # Image path relative to your `static/media/` folder.
  overlay_filter = 0.2  # Darken the image. Value in range 0-1.
+++
