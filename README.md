Пакет української локалізації для оновлення InstantCMS з версії 2.7.2 до 2.8.0

Увага! Це оновлення вам підійде якщо для InstantCMS 2.7.2 ви встановлювали мою українську локалізацію (користувача BoAnRo або andriy85if)

На час процесу оновлення не забудьте надати права запису для папки /system/config/ та файлів, які в ній знаходяться. Також потрібно вимкнути кешування, якщо воно використовується на сайті.

Інструкція по оновленню:

1. Переконайтеся, що ви використовуєте InstantCMS 2.7.2 (версію можна подивитися внизу будь-якої сторінки в адмінці).

2. Увімкніть режим відладки в адмінці

3. Завантажте офіційний архів з оновленням тут http://upd.instantcms.ru/dist/instantcms-update-2.8.0.zip

4. Видаліть з нього файли install.sql та install.php

5. Додайте з архіву української локалізації в офіційний архів оновлення файли install.sql, install.php (замість тих, які були видалені) та /manifest.uk.ini

6. Перейдіть в панель керування сайтом;

7. Перейдіть в розділ "компоненти";

8. Натисніть "встановити пакет доповнення", але нічого не вибирайте;

9. Очистіть кеш браузера;
    
10. Згорніть вікно браузера;

11. Весь вміст папки package з офіційного архіву оновлення, завантаженого в п.3 завантажте в корінь вашого сайту;

12. Після цього завантажте в корінь вашого сайту також вміст папки package з пакету української локалізації (з заміною файлів, якщо потрібно)

13. Поверніться у згорнене в п.10 вікно браузера, натисніть F5 на клавіатурі і виберіть архів, який ви завантажили в п.3;

14. На сторінці «Інформація про пакет» натисніть "Встановити";

15. На сторінці введення реквізитів ftp поставте чекбокс "Пропустити цей крок" і натисніть "Встановити";

16. Вимкнути режим відладки в адмінці
    
Оновлення завершено.

Якщо помітите якісь помилки, будь-ласка, повідомте про них у відповідній темі форуму http://www.instantcms.ru/forum/thread24546-1.html
