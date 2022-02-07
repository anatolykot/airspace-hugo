---
title: Pretty-print dates
date: 2021-04-01T00:00:00.000+01:00
author: John Doe
image: images/blog/blog-post-1.jpg
bg_image: images/feature-bg.jpg
categories:
- Technical Assistance
tags:
- How to
- Technology
type: post
draft: true

---
Чтобы сохранить временную метку [ISO 8601](https://en.wikipedia.org/wiki/ISO_8601) на необходимом языке, вы можете использовать `date_l10n`краткий код:

Письмо

    {{%/* date_l10n "2020-10-20" */%}}

падение к

    {{% date_l10n "2020-10-20" %}}

При корректировке можно задать другой [формат макетирования](https://gohugo.io/functions/dateformat/#datetime-formatting-layouts) :

Например, затем

    {{%/* date_l10n "2020-10-20" ":date_short" */%}}

падение к

    {{% date_l10n "2020-10-20" ":date_short" %}}