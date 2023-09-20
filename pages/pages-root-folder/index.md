---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header.jpg
widget1:
  title: "Why small AI?"
  url: '/about/'
  image: widget-1-302x182.jpg
  text: "You have probably heard of Big Data and Large Language Models. But the next frontier in AI is the ability to make intelligent decisions with as little data as possible, and with minimal power consumption. We are designing some of the smallest AIs on the planet."
widget2:
  title: "Solutions"
  url: '/solutions/'
  image: widget-2-302x182.jpg
  text: "Do you need help deciding what AI system is best for your business or your community? We will help you give the best service to your customers, while minimising your costs and environmental impact. We provide learning material and bespoke consultancy."
widget3:
  title: "Proven expertise"
  url: '/company/'
  image: widget-3-302x182.jpg
  text: "Today, AI is everywhere and it is difficult to discern the experts from the newcomers in the field. Denotation is built on a line of research started in 2006 at the University of Cambridge, supported by an international community of specialists. You can trust our advice."

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
#callforaction:
#  url: /contact/
#  text: Contact us ›
#  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<!-- 
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
-->
