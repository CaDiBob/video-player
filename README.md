
# Видеоплеер

Плеер, который играет видео по [этой ссылке](https://dvmn.org/media/filer_public/78/db/78db3456-3fd3-4504-9ed9-d2d1fd843c0b/highest_peak.mp4).

**Использует скрипт `player.js` и иконки [Fontawesome](https://fontawesome.ru/).  [Видео как подключить fontawesome](https://www.youtube.com/watch?v=xrEcfPQYKIY),
плеер можно разместить на GitHub Pages, [инструкция как опубликовать сайт](https://medium.com/nuances-of-programming/%D0%BA%D0%B0%D0%BA-%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D1%82%D1%8C-%D0%B1%D0%B5%D1%81%D0%BF%D0%BB%D0%B0%D1%82%D0%BD%D1%8B%D0%B9-%D1%81%D0%B0%D0%B9%D1%82-%D0%BD%D0%B0-github-pages-e0f3c258ee22).

[Пример опубликованного плеера](https://cadibob.github.io/video-player/).

Пример работы:
![](gif/player.gif)

### Как использовать

Также можно использовать локально, используйте `pip`, [более подробная инструкция по установке](https://pypi.org/project/livereload/):

```bash
pip install -r requirements.txt
```

Затем используйте локальный сервер:

```bash
 user@user:~$ livereload
```

Пример работы:
```
[I 220318 18:43:43 server:335] Serving on http://127.0.0.1:35729
[I 220318 18:43:43 handlers:62] Start watching changes
[I 220318 18:43:43 handlers:64] Start detecting changes
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).