---
layout:     post
title:      "Caesar square box encryption"
date:       2014-05-25 18:56:17
categories: code update
tags:       encryption
---

One of the most easiest and simplest types of encryption known today is called the caesar cipher.
Other names include the caesar shift, and caesar square box. It's fairly easy to encrypt using this method.
First the string that you have is written into a rectangle where:

length <= ceil(sqrt(length(word))) and the width >= floor(sqrt(length(word)))

After doing that we also need to make sure that we can properly fit the entire string into the rectangle so we
need to make sure that the area (length * width) is larger than the total length of the string. If the area is
smaller than the total length, we then set the smaller of the length or width to the others higher value.

Now we create the 2 dimensional array that will hold the values.

after that we encode string by traversing column by column and adding spaces when we finish a column.

At the end of the encryption we now have an encrypted text.

I did this encryption method to get back into the groove of programming and work my brain muscles again.
I'll add code snippets hopefully later on.
