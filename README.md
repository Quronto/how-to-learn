# Научиться учиться
Этой мой первый проект Я.Практикум, выложенный на Github.
Тут представлен проект о том, как научиться учиться. Он помогает понять, как структурировать мысли, как не терять время зря,принципы и полезные ресурсы для обучения. По сравнению с прошлой версией этого проекта, тут добавлены новые блоки, а также анимации некоторых элементов.
В этом проекте я использовал несколько технологий, вот некторые из них:
1. Использовние анимации с помощью css, а точнее использование keyframes:
``` css
@keyframes rotation {
    from {
      transform: rotate(0deg);
    }
    to {
      transform: rotate(360deg);
    }
  }
```
2. Использовние iframes для вставки видео с YouTube:
``` html
<li class="video__iframe">
    <iframe width="515" height="316" src="https://www.youtube.com/embed/5MgBikgcWnY" title="YouTube video player" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</li>
```

Ссылка на проект: https://Quronto.github.io/how-to-learn
