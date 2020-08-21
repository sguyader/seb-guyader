+++
# Tag Cloud widget.
widget = "tag_cloud"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 5  # Order that this section will appear.

title = "Sujets populaires"
subtitle = ""

[content]
  # Choose the taxonomy from `config.toml` to display (e.g. tags, categories)
  taxonomy = "tags"
  
  # Choose how many tags you would like to display (0 = all tags)
  count = 20

[design]
  # Minimum and maximum font sizes (1.0 = 100%).
  font_size_min = 0.7
  font_size_max = 2.0

#[design.spacing]
#  # Customize the section spacing. Order is top, right, bottom, left.
#  padding = ["20px", "20px", "20px", "20px"]
  
[design.background]
  # color = "navy"
  # Background image.
  text_color_light = true
  image = "background.jpg"  # Name of image in `static/img/`.
  image_darken = 0.5  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  
[advanced]
 # Custom CSS. 
 css_style = "background-size: auto; background-position: center top"

 # CSS class.
 css_class = "mini"
+++
