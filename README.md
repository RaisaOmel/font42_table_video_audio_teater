#  Таблицы   видео   и аудио

Таблицы - формируется рядами <tr>. 
Ячейки <td>, <th>

/* способы скрытия ячеек */
.wrapper table th{
    /* opacity: 0;прозрачность */
    /* visibility: hidden; видимость */
    /* display: none;блок исчез(для других исчез) */
}

объединение рядов по колонке

<td rowspan="2">1</td>

объединение колонок в ряде
<td colspan="3">Итого</td>

# Видео
много браузеров - много форматов
<video autoplay muted controls loop >
  <sourse....
  <sourse....
  <sourse....
</video>
Особености определяется атрибутами
- controls- управление (без него как картинка )
- autoplay -сейчас блокирует автозапуск без выключения звука. Поэтому сразу..... autoplay muted
- loop - зацикливание
- poster="" - картинка перед запуском видео. При автозапуске пролетает незаметно.
- preloader - загрузка. Используется для загрузки видео вместе с загрузкой веб-страницы. Этот атрибут игнорируется, если установлен autoplay.
    -none - видео загружать на страницу не нужно
    - auto - видео должно загрузиться на страницу не зависимо будет пользователь смотреть
    - medio - подгружается медио контент по запросу пользователя.
  
