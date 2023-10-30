<!DOCTYPE html> указываем как интерпритировать браузеру данную страницу
<html lang="en"> указываем язык сайта
<head>
    <meta charset="UTF-8"> кодировка
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- ключевые слова для поисковика -->
    <meta name="keywords" content="Shivers"/>
    <!-- описание сайта -->
    <meta name="description" content="Hello world"/>
    <!-- название страницы -->
    <title>Shivers</title>
    <!-- добавляем иконку возле названия -->
    <link rel="shortcut icon" type="image/png" href="images/favicon.png">
</head>
<body>
    <!-- Основной заголовок сайта h1, исползуется один раз на сайте. 
    если есть заголовок h2 то обязательно должен быть h1 и т.д по иерархии -->
    <h1>My first page</h1>
        <p>My first paragraph</p>
    <h2>Hello world</h2>
    <!-- атрибут flt необходим для описания изображения. отображается, 
    если картинка не загружена -->
    <!-- атрибут title отображает надпись при наведении на картинку -->
    <img src="images/zima.jpg" alt="winter" title="winter">
    <img src="images/zima_small.jpg" alt="winter small">
    <!-- маркерованный список -->
    <ul>
        <li>1</li>
        <li>2</li>
        <li>3</li>
    </ul>
    <!-- нумерованный список -->
    <ol>
        <li>1</li>
        <li>2</li>
        <li>3</li>
    </ol>
    <!-- список определений -->
    <dl>
        <dt>Recipe</dt>
        <dd>Recipe info</dd>
        <dt>Recipe</dt>
        <dd>Recipe info</dd>
    </dl>
    <!-- атрибут tel для открытия клавиатуры набора номера в телефоне -->
    <a href="tel:+375257202686">+375 25 7202686</a>
    <!-- ссылка для отправки почты -->
    <a href="mailto:alex.shivers1234@gmail.com">Gmail</a>


</body>
</html>

Большие картинки измененные css параметром width/height все равно загружаются
в исходном размере, а после этого уменьшаются стилем