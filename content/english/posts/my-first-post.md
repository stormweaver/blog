+++
date = "2019-05-01T22:34:30+03:00"
title = "What's the drama for?"
tags = ["hi","there"]
keywords = ["hi","there"]
+++

Inter UI is a free font family designed by Rasmus Andersson for featuring an excellent readability on computer screens. Typeface comes in 4 weights (regular,  medium bold and black) and includes italic style. It works great for English-language text, and pretty well for other Latin and Cyrillic languages.

Inter UI is very similar to Roboto for many aspects. The project started out in late 2016 as an experiment to build a perfectly pixel-fitting font at a specific small size (11px.)

The idea was that crafting a font in a particular way, with a particular coordinate system (Units Per EM), and for a particular target rasterisation size (11), it would be possible to get the best of both sharpness and readability.

Raffy Plovdiv търси да назначи хостеси, сервитьори и бармани за новооткриващ се ресторант в кв. Тракия!
Работата е свежа и динамична!
Кандидатите трябва да са навършили 18 годишна възраст и да имат желание за кариерно развитие!
Може и без опит!
Предлагаме отлично обучение, специализация, добро заплащане и гъвкаво работно време.
При интерес, кандидатствайте в тази обява или се свържете с нас на телефон

```javascript
const menuTrigger = document.querySelector('.menu-trigger')
const menu = document.querySelector('.menu')
const mobileQuery = getComputedStyle(document.body).getPropertyValue('--phoneWidth')
const isMobile = () => window.matchMedia(mobileQuery).matches
const isMobileMenu = () => {
  menuTrigger.classList.toggle('hidden', !isMobile())
  menu.classList.toggle('hidden', isMobile())
}
 
isMobileMenu()

menuTrigger.addEventListener('click', () => menu.classList.toggle('hidden'))

window.addEventListener('resize', isMobileMenu)
```

{{< image src="/wallhaven-760703.jpg" alt="Hello Friend" position="center" style="border-radius: 8px;" >}}

{{< image  >}}

