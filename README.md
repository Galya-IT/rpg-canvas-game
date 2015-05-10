# rpg-canvas-game
NOTE: On Chrome browser the game is working on live server, but not on localhost due to
Chrome bug where the browser considers file:// path as url to another domain (crossdomain
security issue). Please take a look at our live demo or use another browser.

Disclaimer: Играта не е довършена.

Използвани технологии:
 Kinetic JS
 Raphaël JS
 JQuery

Цел на проекта: Да се създаде RPG игра за браузър.

Геймплей: Със стартиране на играта животът на героя започва постепенно да се
намалява с по една точка на определен интервал от време. Отчитат се редица колизии
с различни обекти, които повлияват движението на играча. На определен интервал от
време на случайни позиции се създават enemies. Когато играчът удари enemy, си
връща 50 точки към живота. Когато точките на живота достигнат 0, играта свършва.

Контроли:
 Space - изстрел
 Arrows - движение в съответната посока