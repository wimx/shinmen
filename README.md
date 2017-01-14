#shinmen



###how to add new posts

1. create new file in _posts directory YEAR-MONTH-DATE-title-of-post.md
2. open in a text editor (textedit or vim)

the files needs to start with:

---
layout: post
title:  [title]
date:   [YEAR-MONTH-DATE]
categories: [any tags you want here]
---

[text of post]

3. save post
4. in terminal build post with “jekyll build” (or do “jekyll serve” if you want to see how it looks)
5. push it up to github
	a. git add .
	b. git commit -m “whatever”
	c. git push