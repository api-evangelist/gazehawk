---
title: "Comment on PHP “require” Performance by Dominevski"
url: "http://gazehawk.com/blog/php-require-performance/#comment-10332"
date: "2012-02-18"
author: "Dominevski"
feed_url: "https://gazehawk.com/blog/comments/feed/"
---
I would say comparing "require_once" vs "require" is pointless. Its true that "require" is almost twice as fast than "require_once" but that cannot be tested, really, not in a real world scenario. If you know for sure you are only including a script ONCE, why would you use require_once?
