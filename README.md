<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Белов Ярослав Евгеньевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №3.«HTML»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>HTML (от английского HyperText Markup Language) </b> —  это язык гипертекстовой разметки текста. Он нужен, чтобы размещать на веб-странице элементы: текст, картинки, таблицы и видео. Когда вы заходите на сайт, браузер подгружает HTML-файл с информацией о структуре и контенте веб-страницы.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>ВЫПОЛНИТЬ ЗАДАНИЯ:</p>

1. Создать все виды заголовков с текстом "Hello world" c классом "heading". <br>
   ``` <h1>Hello world</h1> ```
2. Каждому заголовку также дать id (к прим. heading-1, heading-2...) 
3. Задать всем заголовкам цвет текста на красный 
4. Второму заголовку синий 
5. Третьему заголовку поменять задний фон на чёрный 
6. Четвертому заголовку сделать border и округлить углы 
7. Пятому заголовку создать :hover эффект (любой) 
 8. Создайте 6 input с разными типами. 
9. Создать нумерованный список из 4 элементов с текстом “Нумерованный”. 
10. Создать маркированный список из 4 элементов с текстом “Маркированный” и квадратным маркером. 
11. Создайте веб-страницу с зеленым фоном и белым текстом из 30 слов. 
12. Создать 6 блоков с нумерацией и такими параметрами (ширина 100px и высота 100px, зеленого цвета , внешним отступом 10px). Их родительским элементом должен быть container. 
13. Поставить все блоки по центру страницы. 
14. Добавьте тэг ```<iframe>``` на вашу страницу.
15. Сделайте простую форму регистрации на сайте (Только верстка).
16. Сделайте таблицу на странице.<br>

17.Создайте стиль для заголовка h1 с красным цветом текста.

18. Установите шрифт Arial для всех параграфов на странице.
19. Добавьте тень на блок div с помощью свойства box-shadow.
20. Установите фоновый цвет #f0f0f0 для всего документа.
21. Создайте анимацию, которая будет мигать красным цветом.
22. Установите отступы внутри блока div с помощью свойства padding.
23. Создайте стиль для ссылок, которые будут менять цвет при наведении на них курсора.
24. Добавьте границу вокруг изображения с помощью свойства border.
25. Создайте стиль для списка ul с маркерами в виде квадратов.
26. Установите ширину и высоту блока div с помощью свойств width и height.
27. Создайте стиль для таблицы, который будет делать каждую вторую строку серой.
28. Добавьте эффект перехода при наведении на кнопку с помощью свойства transition.
29. Установите фоновое изображение для элемента с помощью свойства background-image.
30. Создайте стиль для формы с полями для ввода текста и кнопкой отправки.
31. Добавьте рамку вокруг текстового поля с помощью свойства outline.
32. Установите выравнивание текста по центру в блоке div с помощью свойства text-align.
33. Создайте стиль для выпадающего меню с помощью псевдоэлемента :hover.
34. Добавьте тень на текст с помощью свойства text-shadow.
35. Создайте стиль для анимации появления элемента на странице с помощью свойства opacity.
36. Установите шрифт размером 18 пикселей для всех заголовков на странице.




<p></p>



<h1 align = "center">Решение</h1>



<h2 align = "center">Файл index3(1-7).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .heading {
            color: tomato;
        }
        #heading-2{
    color:aquamarine;
}
#heading-3{
    background-color: black;
}
#heading-4{
    border: 3px dashed seagreen;
    border-radius: 20px;
}
#heading-5:hover{
    font-size: 2px;
    color: black;
    
}
    </style>
</head>
<body>
    <h1 id="heading-1" class="heading">Hello world</h1>
    <h2 id="heading-2" class="heading">Hello world</h2>
    <h3 id="heading-3" class="heading">Hello world</h3>
    <h4 id="heading-4" class="heading">Hello world</h4>
    <h5 id="heading-5" class="heading">Hello world</h5>
    <h6 id="heading-6" class="heading">Hello world</h6>
</body>
</html>
```
<h2 align = "center">Файл index3(8-10).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <label>
        Текст 
        <input type="text" placeholder="">
    </label>
    <br>
    <label>
        Дата и время
        <input type="datetime-local">
    </label>
    <br>
    <label>
        Добавление файла
        <input type="file" >
    </label>
    <br>
    <label>
        Кружок
        <input type="radio" >
    </label>
    <br>
    <label>
        Сброс формы
        <input type="reset">
    </label>
    <br>
    <label>
        Поиск
        <input type="search">
    </label>
    <br>
    <ol>
        <li>Нумерованный</li>
        <li>Нумерованный</li>
        <li>Нумерованный</li>
        <li>Нумерованный</li>
      </ol>
      <ul type = "square">
        <li>Маркированный</li>
        <li>Маркированный</li>
        <li>Маркированный</li>
        <li>Маркированный</li>
      </ul>
</body>
</html>
```
<h2 align = "center">Файл index3(11).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: green;
            color: white;
        }
    </style>
</head>
<body >
    Раскольников сидел в своей каморке, угрюмый и желчный. Он был в лихорадке, голова его горела. Мысли его перепутались и неслись в беспорядке. Он встал и подошел к окну. Он смотрел на улицу, на противоположный дом, и ему казалось, что оттуда кто-то на него смотрит и следит за ним.
    
</body>
</html>
```
<h2 align = "center">Файл index3(12-14).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .container {
      display: flex;
      flex-wrap: wrap;
      gap: 10px;
      justify-content: center;
      align-items: center;
      }   

      .block {
      width: 100px;
      height: 100px;
      background-color: green;
      
      }
      .iframe {
  margin: 10px;
  background-color: black;
}
    </style>
</head>
<body>
    <div class="container">
        <div class="block"></div>
        <div class="block"></div>
        <div class="block"></div>
        <div class="block"></div>
        <div class="block"></div>
        <div class="block"></div>
      </div><br>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/dCEMSaho0io?si=UkC7yrn7VVr1DsRp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen>


</body>
</html>
```
<h2 align = "center">Файл index3(15).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        div label{
            display: block;
        }
        div{
            border: 10px dashed aquamarine;
            border-radius: 10px;
            background-color: aquamarine;
        }
        
        body{
            font-family: sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
             min-height: 100vh;
             background-color: peru;
        }
        .container{
            display: flex;
            justify-content: center;
            align-items: center;
            margin: auto;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 3px;
        }
        
    </style>
</head>
<body>
    <div>
    <label>
        Имя пользователя<br>
        <input type="text" placeholder="">
    </label>
    <label>
        Пароль<br>
        <input type="text">
    </label>
    <button class = "container">Войти</button>
    <br>
    <button class="container">Регистрация</button>
    </div>
</body>
</html>
```
<h2 align = "center">Файл index3(16).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <table>
        <thead>
        <tr>
            <th>Заголовок 1</th>
            <th>Заголовок 2</th>
            <th>Заголовок 3</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>Ячейка 1-1</td>
            <td>Ячейка 1-2</td>
            <td>Ячейка 1-3</td>
        </tr>
        <tr>
            <td>Ячейка 2-1</td>
            <td>Ячейка 2-2</td>
            <td>Ячейка 2-3</td>
        </tr>
        <tr>
            <td>Ячейка 3-1</td>
            <td>Ячейка 3-2</td>
            <td>Ячейка 3-3</td>
        </tr>
        </tbody>
    </table>
</body>
</html>
```
<h2 align = "center">Файл index3(17-26).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        h1{
            color: red;
        }
        p{
            font-family: Arial, Helvetica, sans-serif;
        }
        div{
            box-shadow: 2px 2px 4px rgba(0, 0, 0, 2);
             width: 120px;
             height: 100px;
            background-color: aquamarine;
            padding: 10px;

        }
        body{
            background-color: #f0f0f0 ;
        }
        .blinking {
      animation: blink 2s linear infinite;
      color: red;
    }
    .naved:hover{
        
        color: red;
    }
    .photo{
        width: 200px;
        border: 3px dashed green;
        border-radius: 5px;
    }
    .kvadsp{
        list-style-type: square;
    }

    @keyframes blink {
        100%{
            color: green;
        }
      50% {
        opacity: 0;
        color: red;
      }
      2%{
        color: blue;
      }
    }
        
    </style>
</head>
<body>
    <div>
    <h1 class="blinking"><p>" Text "</p></h1></div>
    <p class="naved">https://github.com/KTGZR</p>
    <img class="photo" src="https://img.freepik.com/free-photo/the-red-or-white-cat-i-on-white-studio_155003-13189.jpg?w=826&t=st=1717769930~exp=1717770530~hmac=8fd2945d4fb23eefde4f47335c2b51a6eaca0fb04fe234fe21dad71dae129912">
    <ul class="kvadsp">
        <li>Маркированный</li>
        <li>Маркированный</li>
        <li>Маркированный</li>
        <li>Маркированный</li>
      </ul>
</body>
</html>
```
<h2 align = "center">Файл index3(27-29).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        table {
  border-collapse: collapse;
}

tr:nth-child(even) {
  background-color: grey;
}
body{
    background-color: aquamarine;
}
button{
    display: flex;
    margin-top: 10px;
    transition: all 1s ease;
    margin-bottom: 10px;

}
button:hover {
  transform: scale(1.1);
  color: blueviolet;
  background-color: chocolate;
  border: none;
  border-radius: 5px;
}
div{
    background-image: url(https://upload.wikimedia.org/wikipedia/commons/a/aa/Testudo_horsfieldii%3B_Baikonur_001.jpg);
    width: 1000px;
    height: 750px;
    background-size: 1000px;
}
    </style>
</head>
<body>
    <table>
        <thead>
        <tr>
            <th>Заголовок 1</th>
            <th>Заголовок 2</th>
            <th>Заголовок 3</th>
        </tr>
        </thead>
        <tbody>
        <tr>
            <td>Ячейка 1-1</td>
            <td>Ячейка 1-2</td>
            <td>Ячейка 1-3</td>
        </tr>
        <tr>
            <td>Ячейка 2-1</td>
            <td>Ячейка 2-2</td>
            <td>Ячейка 2-3</td>
        </tr>
        <tr>
            <td>Ячейка 3-1</td>
            <td>Ячейка 3-2</td>
            <td>Ячейка 3-3</td>
        </tr>
        <tr>
            <td>Ячейка 3-1</td>
            <td>Ячейка 3-2</td>
            <td>Ячейка 3-3</td>
        </tr> <tr>
            <td>Ячейка 3-1</td>
            <td>Ячейка 3-2</td>
            <td>Ячейка 3-3</td>
        </tr>
        <tr>
            <td>Ячейка 3-1</td>
            <td>Ячейка 3-2</td>
            <td>Ячейка 3-3</td>
        </tr>
        </tbody>
    </table>
    <button >Кнопка</button>
    <div></div>
</body>
</html>
```
<h2 align = "center">Файл index3(30).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        form {
        width: 300px;
        margin: 0 auto;
      }

      input[type="text"],
      input[type="submit"] {
        display: block;
        width: 100%;
        padding: 10px;
        margin-bottom: 10px;
        box-sizing: border-box;
      }

      input[type="submit"] {
        background-color: tomato;
        color: white;
        cursor: pointer;
      }

      input[type="submit"]:hover {
        background-color: blue;
      }
      div{
        background-color: aquamarine;
        min-width: fit-content;
        max-width: fit-content;
      }
    </style>
</head>
<body>
    <div>
    <form>
        Набор символов<br>
        <input type="text" placeholder="Жду"><br>
        <input type="submit" value="Ввод">  
    </form>
    </div>
</body>
</html>
```
<h2 align = "center">Файл index3(31-36).html</h2>

```htmlmixed
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        p{
            text-align: center;
            text-shadow: 2px 2px 2px blueviolet;
        }
        select:hover {
  background-color:aquamarine;
  border: 1px solid #ccc;
  border-radius: 5px;
}
@keyframes poyav {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
h1, h2, h3, h4, h5, h6 {
      font-size: 18px;
    }
.poyav {
  animation: poyav 5s ease-in-out;
}
    </style>
</head>
<body>
    <input type="text" style="outline: 3px dashed red;">
    <div><p>Тут есть текст</p></div>
    <select>
        <option value="1">Один</option>
        <option value="2">Два</option>
        <option value="3">Три</option>
      </select>
      <div class="poyav">
        text poyavlyzetsya
      </div>
  <h1>Пример 1</h1>
  <h2>Пример 2</h2>
  <h3>Пример 3</h3>
  <h4>Пример 4</h4>
  <h5>Пример 5</h5>
  <h6>Пример 6</h6>
</body>
</html>
```

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я поработал с множеством различных возможностей языка HTML. Я строил таблицы, работал с текстом и полями, а также делал простые анимации.</p>

