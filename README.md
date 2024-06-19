# Charles Proxy
Перехватывала трафик веб-приложения ["Интернет-магазин"](https://qa.demoshopping.ru/) и мобильного приложения [«shopping-list.apk»](https://drive.google.com/file/d/1BEta0NqWVn_T54jboSk0naTaKNvVeVRf/view?usp=drive_link), используя Charles Proxy. 
1. Проверка тестовых сценариев в веб-приложении с использованием Charles Proxy:
- [Изменение кол-ва товаров в корзине](https://drive.google.com/file/d/1Q-CMAjH7enYCwFjw_vA4TH0Drgt01KWB/view?usp=drive_link) (в запросе 2 товара, а в ответе 500 товаров) 
- [Сервер возвращает статус-код 403](https://drive.google.com/file/d/1dM2KPw3cNyAjc8CvrOWGrod57_Z8Buov/view?usp=drive_link)
- [Перенаправление запроса](https://drive.google.com/file/d/1lijB5DmsuaocM77r3lK6YmXvsyjkbG-z/view?usp=drive_link) с https://demoshopping.ru на https://qa.demoshopping.ru 
2. Проверка тестовых сценариев в мобильном приложении с использованием Charles Proxy:
- Удаление другого товара в корзине: [запись экрана на ноутбуке](https://drive.google.com/file/d/1Ay3jTjS3w0k3QxvuUukKpwiptHbIxG90/view?usp=drive_link), [запись экрана на iPhone](https://drive.google.com/file/d/1B-PCV1-t2UK2NZJ2NNvWzHRl9odxCp92/view?usp=drive_link)
- [Отображение картинки](https://drive.google.com/file/d/17Fvn2A9xiMrGMRj4zNmgBmueMhd2v3tV/view?usp=drive_link) при обращении к  https://demoshopping.ru: ![Снимок](https://github.com/VikaDov/mobile/assets/118528449/7ae4a740-5964-41fa-b043-286483864be0)
- Информация о мобильном устройстве в header user-agent: ![Снимок](https://github.com/VikaDov/mobile/assets/118528449/b1e6e724-0bce-4382-878c-6bd37ea31b76)  
