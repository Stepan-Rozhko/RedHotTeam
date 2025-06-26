# RedHotTeam
Тестове завдання: PDP

Password protection: test123
**PDP** [https://stepan-rozhko-store.myshopify.com/products/red-and-green-pencil](https://stepan-rozhko-store.myshopify.com/products/red-and-green-pencil)


## 📦 Технології
- HTML
- SCSS --> CSS
- Liquid
- JavaScript


## 📁 Структура
``` bash 
assets/main.css 
assets/swiper.min.css 
assets/swiper.min.js 
scss/main.scss
scss/product/_product.scss
sections/main-product.liquid
```

## 🛍️ Нотатки розробнику
1. Компіляція. 
- gulp styles 
- gulp watch
2. Для галереї підключено Swiper. Додано можливість зміни:
а) Кількість слайдів, що відображаються одночасно
б) Увімкнення/вимкнення пагінації
в) Увімкнення/вимкнення стрілок навігації
г) Відступ між слайдами
3. Фільтрація фото за кольором реалізована додаванням відповідного слова у ALT зображення - Red, Green + JS.
4. Акордеон. Заголовк та вміст складаються з різних метаполів. Після чого в коді вони додаються у відповідні масиви, і за допомогою FOR відбувається їхній рендер. Це зроблено так, через те що тут один продукт, в іншому випадку можна було б налаштувати метаобєкти.