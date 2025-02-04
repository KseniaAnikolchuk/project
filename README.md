![{3DFDC5A1-B06A-43EE-9886-AB3807FBE6DD}](https://github.com/user-attachments/assets/d6897cb9-94e3-4652-a13c-e45d8dafe86c)


[Uplo<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>БАиПОИ и МЦА</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #F6F9FB;
        }
       .text {
        color: #000000;
       }

       .main {
        
        border-radius: 5px;
        background-color:  #FFFFFF;

       }
        .sidebar {
            width: 250px;
            height: 70vh;
            background-color: #040D26;
            color: white;
            padding-top: 20px;
            position: fixed;
        }
      
        .sidebar .menu {
            list-style-type: none;
            padding: 0;
        }
        .sidebar .menu li {
            padding: 10px 20px;
        }
        .sidebar .menu li:hover {
            background-color: #2072EC;
            cursor: pointer;
            border-radius: 5px;
        }
        .sidebar .menu .active {
            background-color: #2072EC;
            border-radius: 5px;
            
        }
        .breadcrumb{
            color: #00000050
        }
        .sidebar .version {
            position: absolute;
            bottom: 20px;
            left: 20px;
        }
        .content {
            margin-left: 250px;
            padding: 20px;
        }
        .header {
            margin-top: 20px;
            font-size: 24px;
            margin-bottom: 20px;
        }
        .toolbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            
            
        }
        .toolbar input {
            padding: 10px;
            width: 200px;
            margin-right: 10px;
            
        }
        .toolbar button {
            padding: 10px 20px;
            background-color: #1261D8;
            color: white;
            border-radius: 5px;
            border: none;
            cursor: pointer;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            
        }
        th, td {
            padding: 12px;
            border: 1px solid #FFFFFF;
            text-align: left;
            border: 5px #F8F8F8;
            border-bottom: 5px #F8F8F8;
        }
       .bottom-border td, th{
        border-bottom: 1px solid #F8F8F8;
       }
        table#t01 tr:nth-child(even) {
             background-color: #F8F8F8;
        }
        table#t01 tr:nth-child(odd) {
             background-color: #fff;
        }
        
    
        .pagination {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }
        .pagination button {
            padding: 10px 20px;
            margin: 0 5px;
            border-radius: 5px;
            border: 1px solid #ddd;
            background-color: white;
            cursor: pointer;
        }
        .pagination button.active {
            border-radius: 5px;
            border-color: #1261D8;
            color: #1261D8;
        }
      
    
    
    </style>
</head>
<body>
    <div class="sidebar">
        <ul class="menu">
            <div class="image-container">
                
            <img src="POLUS.jpeg" alt="ПОЛЮС карт"  width="100"/> 
            <img src="poluus.jpeg" alt="полюс им" width="100"/>
                
        </div>
            <li>Главная</li>
            <li>Датчики</li>
            <li>Приборы типа МТ</li>
            <li class="active">БАиПОИ и МЦА</li>
            <li>Изделия</li>
        </ul>
        <div class="version">Версия: 1.01</div>
    </div>
    <div class="content">
        
        <div class="breadcrumb">
        <a class="text">Главная</a> <span> / БаиПОИ и МЦА</span>
        </div>
       <b> <div class="header">БАиПОИ и МЦА</div></b>
    <div class="main">
        <div class="tabs">
            <b><span style="color: #2072EC; margin: top 10px; margin-left: 20px; ">Комплектующие</span></b>
            <b><span style="margin-left: 30px;">База БаиПОИ и МЦА</span></b>
            <hr>
            
        </div>
        <div class="toolbar">
            <div>
                <input type="text" style="margin-top: 30px;" width="10" class="place" placeholder="Поиск по названию...">
                <input type="text" class="place" placeholder="Поиск по ЖГДК...">
            </div>
            <button style="margin-top: 10px;">+ Добавить комплектующую</button>
        </div>
        <table id="t01">
            <thead>
                <tr>
                    <th>Название</th>
                    <th>Ревизия</th>
                    <th>ЖГДК</th>
                    <th>Описание</th>
                </tr>
            </thead>
            <tbody>
                
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td> План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
              
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td> План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
           
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
                <tr>
                    <td>Плата счётчиков или длинное название комплектующей</td>
                    <td>9999</td>
                    <td>ЖГДК.12345-00</td>
                    <td>План размещения позиционирует стратегический <br> рыночный план. Искусство медиапланирования <br> специфицирует метод изучения рынка, осознав марк...</td>
                </tr>
            </tbody>
        </table>
        <div class="pagination">
            <button>⟨</button>
            <button class="active">1</button>
            <button>2</button>
            <button>3</button>
            <button>4</button>
            <button>5</button>
            <button>⟩</button>
        </div>
    </div>
</body>
</html>
ading practic.html…]()
