---
title: Work with Dynamic Data in D3
---
## Work with Dynamic Data in D3
---

In this lesson you're going to be using the value of the element in the array

```    d3.select("body").selectAll("h2")
      .data(dataset)
      .enter()
      .append("h2")
      .text((d) => (d + " USD"))
      ```
      this way you are changing the text for each element 

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
