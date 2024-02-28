# FW_Vue.js

# *Семинар 1 HomeWork001* Введение в Vue.js

Часть 1. Работа с макетом(```https://www.figma.com/file/okdYD45Tj2JpKsNASccUmf/Interior-Design-Webflow-Website-Template-(Community)-(Copy)-(Copy)?type=design&node-id=101-14&mode=design```)

По заданному макету создать вёрстку главной страницы (без использования vue).

Задание по работе с макетом направлено на подготовку проекта к итоговой аттестации.

Часть 2. Задание по Vue

1. Создать кнопку "Перевернуть". При клике на кнопку текст кнопки должен перевернуться и отобразиться в обратном порядке.
2. Есть список элементов. Пользователь может добавлять новые элементы списка с текстом “Новый элемент списка” нажав на кнопку "Добавить".
3. *Дополнительное задание: При клике на элемент списка он должен быть удален. (по желанию)

Формат сдачи: ссылка на гитхаб.

# *Семинар 2 HomeWork002* Семинар: Методы и работа с контентом

Продолжаем создание макета(```https://www.figma.com/file/okdYD45Tj2JpKsNASccUmf/Interior-Design-Webflow-Website-Template-(Community)-(Copy)-(Copy)?type=design&node-id=209-15&t=VK2zHccBmhGGNIzu-0```):

— Реализовать страницу Blog (Домашнее задание 2).

Что мы можем заметить в проекте, что часть "Articles & News" повторяется. Как итог, вам необходимо создать блок Articles & News с помощью Vue.js, где данные для вёрстки будут храниться в массиве объектов и выводить на страницу с помощью цикла v-for.

Задание по работе с макетом направлено на подготовку проекта к итоговой аттестации.

Часть 2. Задание Vue

Вы разрабатываете приложение для отображения и сортировки списка товаров. У вас есть массив объектов products, где каждый объект представляет товар с его названием и ценой. Вам необходимо отобразить список товаров и предоставить пользователю возможность сортировать товары по цене (по возрастанию и по убыванию).

Формат сдачи: ссылка на гитхаб.

# *Семинар 3 HomeWork003* Семинар: Компоненты

Работа с макетом  

Продолжаем работу с макетом(```https://www.figma.com/file/okdYD45Tj2JpKsNASccUmf/Interior-Design-Webflow-Website-Template-(Community)-(Copy)-(Copy)?type=design&node-id=541-13&t=mhOD6yhLJuH2Biy0-0```):

— Реализовать страницу Blog details (Домашнее задание 3).  

На странице отображается подробное описание статьи, а под ней размещаются остальные статьи. Необходимо, чтобы на выборе Tags происходила сортировка статей по выбранному тегу. Тег можно выбрать только один.  

Задание по работе с макетом направлено на подготовку проекта к итоговой аттестации.  

Формат сдачи: ссылка на гитхаб.

# *Семинар 4 HomeWork004* Семинар: Vue cli

Установить и настроить Vue CLI.

Перевести свой проект (работа с макетом) на Vue CLI. Все компоненты, которые создали с помощью vue.components, необходимо переделать на синтаксис Vue CLI.

Задание по работе с макетом направлено на подготовку проекта к итоговой аттестации.

Формат сдачи: ссылка на гитхаб.

# *Семинар 5 HomeWork005* Семинар: Встроенные директивы и работа с данными компонента

Продолжаем работу с макетом(```https://www.figma.com/file/okdYD45Tj2JpKsNASccUmf/Interior-Design-Webflow-Website-Template-(Community)-(Copy)-(Copy)?type=design&node-id=1-5&mode=design&t=ebkazpiG5BOth8x7-0```):  
Создайте компоненты шапки и подвала, чтобы можно было подключать их к новым страницам.  

Задание по работе с макетом направлено на подготовку проекта к итоговой аттестации.  

Часть 2. Задание Vue  

Вы разрабатываете приложение для интернет-магазина и у вас есть компонент Vue под названием ```"ProductDetails"```. Компонент отображает детали о конкретном продукте, включая его название, цену и статус доступности.  

Внутри компонента ```"ProductDetails"``` создайте свойство ```"product"``` с объектом, представляющим информацию о продукте. Объект должен иметь свойства "name" (название продукта), ```"price"``` (цена продукта) и ```"available"``` (флаг, указывающий на доступность продукта).  

Используя вычисляемое свойство, назовите его ```"formattedPrice"</```, которое будет возвращать форматированную цену продукта со знаком валюты. Например, если цена равна 99.99, вычисляемое свойство должно вернуть строку "$99.99".  

В компоненте ```"ProductDetails"``` отобразите название продукта, его форматированную цену и статус доступности.  

Если продукт доступен, отобразите текст ```"Available"```, в противном случае - ```"Out of stock"```.  

Формат сдачи: ссылка на гитхаб.  