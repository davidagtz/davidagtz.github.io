---
layout: post
title: "Red-Black Trees"
date: 2020-06-30 23:17:56 -0500
preview: "/assets/REDBLACK.png"
# categories: boids quadtree p5S
gh_link: https://github.com/davidagtz/RedBlack
gh_page: https://davidagtz.github.io/RedBlack
text_indent: true
tags: [Data Structures, Red Black Trees, p5]
---

<iframe src="https://davidagtz.github.io/RedBlack" style="width: 40em; height:30em; display: inline-block"></iframe><br/>

In my Data Structures class at UTD, we learned a lot about a variety of data structures. We implemented some of those structures, but one of those that we didn't implement intriguied me: Red Black Trees. I learned of the neat tricks it uses to self-balance, and not only that but of it's efficiency compared to an AVL tree that needs balancing on every insertion and deletion.

I chose to write this program with p5.js in the browser. I did not think this would be the least bit difficult, but this project taught me a lot. I had to implement a lot nifty tricks because of the nature of JavaScript. I had a very C++ mentality when writing this, but JS does not have references. So I had transfer data between objects so that a reference would be preserved. An alternative would be working with copies of objects and reassigning certain variables, but I found that to be inefficient as copying is of order O(n). This project taught me new ways to work with JS and references, so overall this project was very interesting.
