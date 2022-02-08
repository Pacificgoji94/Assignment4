<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .item1 {
            grid-area: header;
        }

        .item2 {
            grid-area: main;
            height: 80px;
        }

        .item3 {
            grid-area: right;
            height: 80px;
        }

        .item5 {
            grid-area: footer;
        }

        .grid-box {
            display: grid;
            grid-template-areas:
                'header header header header header header'
                'main main main main main right'
                'footer footer footer footer footer footer';
            grid-gap: 8px;
            background-color: #a1a1a1;
            padding: 20px;
        }

        .grid-box>div {
            background-color: rgb(255, 255, 255);
            text-align: center;
            align-items: center;
            justify-content: center;
            padding: 20px;
            font-size: 12px;
        }

        h1{
            align-items: center;
            text-align: center;
            font-size: 40px;
            margin:0 auto;
        }

        .dark-box{
            background-color: rgb(77, 77, 77);
            width: 100vw;
            height: 100vh;
            
        }
    </style>
</head>

<body>
    <div class="dark-box"> 
    <h1> Two Column Flex</h1>
    

    
    <div class="grid-box">

        <div class="item1">Header</div>
        <div class="item2">col1 </div>
        <div class="item3">col2</div>
        <div class="item5">Footer</div>
    </div>
    
</div>
</body>

</html>
