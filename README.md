# ШРИ 2019: Performance

###Список улучшений.

Так как главной задачей была максимальная оптимизация страницы, в случаях, когда стоял вопрос
об сохранении читаемости кода, его дальнейшей поддержки и производительности приоритет отдавался последнему.

- Все изображения были пережаты, отресайзены и переконвертированы в подходящий формат (webp, png, jpeg)
- Некоторые мелкие svg преобразовал в base64 и заинлайнил на страницу
- Убраны лишние скрипты (banner.js, main.js)
- Из main.js убрано почти 25 тыс строк кода и весь код заинлайнен в страницу.
- Убрал неиспользуемые библиотеки ( react, jquery, hls, owl carusel, pep)
- Стили для страницы были почищены от неиспользуемых стилей и sourcemap'ов и смержены в единый файл. Затем минифициронные стили заинлайнены в страницу
- Выполнение скриптов асинхронное
- Иконка favicon уменьшена в размере
- Из страницы убраны все <template>
- Из скриптов почищены бесполезные части (например: 'if (false) ...')

## Задание
Оптимизировать страницу, выложить результат на [Github-Pages](https://help.github.com/en/articles/creating-a-github-pages-site) и проверить его на [shri-perf.ru](https://shri-perf.ru), отправив адрес вашей страницы.

☝🏻Будьте внимательны, не отправляйте страницу на проверку, не дождавшись, пока внесенные вами изменения доедут до Github-Pages (обычно задержка составляет не более минуты).

## Рекомендации

* сдавать работу итерациями, чтобы наблюдать прогресс и иметь возможность откатиться;
* не откладывать выполнение задания на последний день 🙃
