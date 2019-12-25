---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: tellas.png
widget1:
  title: "Blog"
  url: 'https://black-photon.github.io/blog/'
  image: rising.png
  text: 'Keep up-to-date with the latest blog posts'
widget2:
  title: "Who am I?"
  url: 'https://black-photon.github.io/info/'
  image: photon.jpg
  text: 'My name is Joseph Keane, and I am a programmer in the UK, currently in the 2nd year of a CS degree at Warwick'
widget3:
  title: "See my GitHub"
  url: 'https://github.com/Black-Photon'
  image: avatar.png
  text: 'I am constantly working on projects both for my degree and completely unrelated. You can find them all on my GitHub page.'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/Black-Photon
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---