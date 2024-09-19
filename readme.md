# План/вимоги релізного проекту

1. Проект має бути написаний на HTML, CSS, JS
2. Проект має містити декілька сторінок

Тобто декілька html файлів, навігація між якими має бути реалізована за допомогою посилань. Наприклад

```
    <a href="./page1">Посилання на інщшу сторінку</a>
```
3. Перед власне створенням проекту, повинен бути макет FIGMA
4. В проекті мають бути анімації, наприклад

```
.my-button {
    height: 40px;
    width: 120px;
    color: black;
    background-color: "yellow";
    transition: all 0.4s ease-in;
}

.my-button:hover {
    transform: scale(1.02);
}
```
5. В проекта має бути логічна тематика

Тобто якщо у вас інтернет магазин, то буде недоречно в ньому розміщувати інфу про комп'ютерні ігри.

6. Весь інтерактив користувача з сайтом має бути реалізований через JS.

7. Використовувати chatGPT **можна**, оскільки він навряд вам сильно допоможе)))

8. Робота над проектом має виконуватись через git

```
    git add . // додати усі файли до коміту
    git commit -m 'назва коміту' // зафіксувати зміни перед відправкою до репозиторію
    git push // власне відправити
```

до речі з роботою з гітом дуже допоможе СhatGPT.

9. Потрібно захостити сайт на github pages.