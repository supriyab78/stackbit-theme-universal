---
title: Home
sections:
  - section_id: intro
    component: "content_block.html"
    type: contentblock
    title: Content Section with Image
    image: images/1.jpg
    content: |-
      This is the content with the image block. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis sit amet felis tincidunt, auctor magna eu, convallis libero. Sed mollis ipsum nec dictum bibendum. Nullam bibendum tortor lacinia, fringilla risus ac, pellentesque ante. Etiam consectetur est eu pulvinar malesuada. Fusce sodales diam ante, vel imperdiet nibh commodo ut.
    actions:
    - label: Learn More
      url: style-guide.html
  - section_id: recent-posts
    component: "posts_block.html"
    type: postsblock
    title: Posts Section
    num_posts_displayed: 3
    actions:
    - label: View Blog
      url: blog/index.html
menus:
  main:
    weight: 1
    title: Home
template: home
---
