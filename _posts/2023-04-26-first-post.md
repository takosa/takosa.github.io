---
layout: post
title:  "First Post"
date:   2023-04-26 00:00:00 +0900
categories: misc
---

This is a test post.

{% highlight r %}
# R code highlite test
library(dplyr)
iris %>%
  summarize(Mean.Sepal.Length = mean(Sepal.Length), .by = Species)
f <- function(x) sum(dbinom(x, size = 10, prob = 0.5, log = TRUE))
{% endhighlight %}

```rust
// Rust code highlite test
fn main() {
  println!("Hello world!");
}
```
