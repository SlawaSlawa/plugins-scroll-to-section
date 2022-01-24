# scrollToSection - Плавная прокрутка по странице
## Инструкция:
* Подключить плагин до основного файла скриптов
* Запустить функцию
```
scrollToSections()
```
* Так же можно передавать опции объектом:
  * behavior: auto (или smooth) по умолчанию auto - Определяет анимацию скролла
  * block: start (или center или end или nearest) по умолчанию start - Вертикальное выравнивание
  * inline: start (или center или end или nearest) по умолчанию nearest
  
  element.scrollIntoView({
      behavior: 'smooth',
      block: 'start'
  })
  
* Так же есть возможность использования полифила **seamless-scroll-polyfill**
  * npm install seamless-scroll-polyfill --save
  * или **CDN** <script src="https://cdn.jsdelivr.net/npm/seamless-scroll-polyfill@latest/lib/bundle.min.js" defer></script>
  * Полифил подключается до основного файла скриптов и плагина
