<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        * {
            padding: 0px;
            margin: 0px;
        }

        #kuang {
            width: 200px;
            height: 30px;
            text-align: center;

        }

        #sousuo {
            height: 33px;
            width: 60px;

        }

        #con {
            height: 300px;
            width: 630px;
            position: relative;
            left: 50%;
            top: 100px;
            margin-left: -250px;

        }

        #cont{
            height: 50px;
            width: 270px;
            position: relative;
            left: 50%;
            margin-left: -150px;
        }
        td {
            display: inline-block;
            width: 100px;
            height: 45px;
            border: 1px solid black;
            text-align: center;
            line-height: 45px;

        }

        table {
            border-collapse: collapse;
        }
    </style>
</head>

<body>
    <div id="con">
        <div id="cont">
            <input type="text" id="kuang" placeholder="请输入城市例如:西安市" value="">
            <button id="sousuo">搜索</button>
        </div>
        
        <table>
            <tr>
                <td>天气</td>
                <td>温度</td>
                <td>风向</td>
                <td>风力</td>
                <td style="width: 200px;">时间</td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td></td>
                <td></td>
                <td style="width: 200px;"></td>
            </tr>
        </table>
    </div>

    <script>
        var kuang = document.getElementById('kuang');
        var but = document.getElementById('sousuo');
        var td = document.getElementsByTagName('td');

        but.onclick = function () {
            var xhr = new XMLHttpRequest();
            xhr.open('GET', 'https://restapi.amap.com/v3/weather/weatherInfo?key=a580854dc86124eaf0eefc9a3d15bcae&city=' + kuang.value);
            xhr.send();
            xhr.onload = function () {
                var arry = JSON.parse(xhr.response).lives;
                console.log(arry[0].city);
                td[5].innerHTML = arry[0].weather;
                td[6].innerHTML = arry[0].temperature + '℃';
                td[7].innerHTML = arry[0].winddirection;
                td[8].innerHTML = arry[0].windpower + '级';
                td[9].innerHTML = arry[0].reporttime;
            }
        }
    </script>
</body>
