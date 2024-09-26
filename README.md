<i>Создать Deployment приложения, состоящего из контейнеров nginx и multitool.
Решить возникшую проблему с помощью ConfigMap.</i>

Для обеспечения лучшей безопасности и контроля ресурсов лучше создать отдельное пространство имен. Создаем Namespace nginx-space

![alt text](https://github.com/powermetall/netology_01/blob/main/pic_1.png?raw=true)
 
Проблема при запуске контейнеров была в том, что оба контейнера пытались использовать один порт. Заменим в ConfigMap значение HTTP_PORT на 1212.




  <i>

  Продемонстрировать, что pod стартовал и оба конейнера работают.</i>
 
![alt text](https://github.com/powermetall/netology_01/blob/main/pic_2.png?raw=true)
![alt text](https://github.com/powermetall/netology_01/blob/main/pic_3.png?raw=true)

<i>Сделать простую веб-страницу и подключить её к Nginx с помощью ConfigMap. Подключить Service и показать вывод curl или в браузере.
Предоставить манифесты, а также скриншоты или вывод необходимых команд.</i>
 
![alt text](https://github.com/powermetall/netology_01/blob/main/pic_4.png?raw=true)

Манифесты прилагаются.
