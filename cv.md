# Krech Aliaksandr

## Contacts:

- tel: +375333506839;
- e-mail: alexkrech1997@gmail.com ;
- telegram: https://t.me/AlexKrech1997 ;
- github: https://github.com/AlexKrech .

## About me:

I'm a **hadrworking** and _sociable_ person who want to be Web Developer (especially React Developer). I have'nt any working expirience now but my goal is do better to impruve technikal skill and receiving any working expirience.

## Skills:

- Html;
- CSS;
- Javascript;
- Git;
- Bootstrap;
- Figma.

## Code Example:

```
// This is example of my scrollbar realisation.

let list = document.querySelector(".images")
let prev = document.querySelector(".prev")
let next = document.querySelector(".next")
let image = document.querySelector("img")
let width = parseInt(getComputedStyle(image).width) * (list.children.length - 3)

prev.onclick = function () {
if (parseInt(getComputedStyle(list).marginLeft) + 250 > 0) {
list.style.marginLeft = 0 + 'px'
} else {
list.style.marginLeft = parseInt(getComputedStyle(list).marginLeft) + 250 + 'px'
}
}

next.onclick = function () {
if (parseInt(getComputedStyle(list).marginLeft) - 250 < -width) {
list.style.marginLeft = -width + 'px'
} else {
list.style.marginLeft = parseInt(getComputedStyle(list).marginLeft) - 250 + 'px'
}
}
```

## Work experience

I've finished a short course on HTML/CSS basics. There are a couple of my projects in [this](https://github.com/AlexKrech/Stepik-projects.git) repository.

## Education:

* HTML, CSS on https://stepik.org/course/38218/syllabus.
* Javascript on https://learn.javascript.ru.

## English level
A2+ according [www.training.by] (https://www.training.by) tests. I also have some experience of conversations with native speakers in [cambly](https://www.cambly.com/en/?lang=ru) platform.