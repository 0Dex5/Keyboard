<!DOCTYPE html>
<html>
    <head>
        <style>
            *{
                margin: 0;
                padding: 0;
                box-sizing: border-box;
            }
            body{
                height: 100vh;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            .container{
                display: flex;
                flex-direction: column;
                width: 300px;
                padding: 15px;
                border: 1px solid skyblue;
                border-radius: 5px;
            }
            input{
                margin: 5px 0px;
                height: 35px;
                padding: 7px;
            }
            button{
                height: 35px;
                margin: 5px 0px;
                background-color: skyblue;
                border: none;
                border-radius: 5px;
                color: #333;
            }
            button:hover{
                background-color: #333;
                color: skyblue;
            }
        </style>
    </head>
    <body>
        <div class="container">
            <input type="email"
            placeholder="email">
            <input type="password"
            placeholder="password">
            <button>Login</button>
        </div>
    </body>
</html>
