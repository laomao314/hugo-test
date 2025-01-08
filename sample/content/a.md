+++
date = '2025-01-06T11:56:46-05:00'
draft = true
title = 'A'
tags = ["tag1", "tag2", "tag3"]
categories = ["cat1"]
moods = ["Happy", "Upbeat"]
myVar = "My Varaible Value"
+++

This is a.md file in content root!

{{< myshortcode color="lightblue" >}}
    This Is My ShortCode Inner Text!!!
{{< /myshortcode >}}

NOTE: you cannot indent your markdown text inside a shortcode!!!
{{% myshortcode2 "lightblue" %}}
**This Is My Another ShortCode Inner Text with Indexed Parameter!!!**
{{% /myshortcode2 %}}

NOTE: Karkdown text inside a shortcode must be in a separate line!!!
{{% myshortcode color="red" %}}
Stuff to `process` in the *center*.
{{% /myshortcode %}}

**This Is My Another ShortCode in Content!!!**
