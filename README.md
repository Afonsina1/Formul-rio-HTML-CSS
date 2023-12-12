# Formulario-HTML-CSS
Formulario simples feito com html e css.

---HTML---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
<form action="">
        
        <div class="form">
             <div class="logo">
            <img src="Nova pasta/Captura de ecrã 2023-12-10 183626.png" alt="">
        </div>
            <span class="span1">INSTITUTO POLITÉCNICO DOM DAMÃO FRANKLIN</span>
            <span>Formulário de entrada no sistema</span>
                
            <input type="email" id="email" name="email" placeholder="Digite seu e-mail"><br>
            <input type="password" name="senha" id="password" placeholder="Digite sea senha"><br>
            <a href="#">Esqueceu a senha?</a><br>
            <div class="buttom">
                <button class="buttom1">Voltar</button>
                <button class="buttom2">Entrar</button>
            </div>
        </div>
</form>
</body>
</html>

---CSS---

*{
    padding: 0;
    margin: 0;

}
body{
    background-color: rgb(205, 204, 204);
    
}.logo img{
    height: 150px;
    margin: auto;
}
/*hr{
    height: 3px;
    background-color: rgba(35, 153, 212, 0.996);
    border: 0;
}*/
.form{
    background-color: white;
    text-align: center; 
    margin: auto;
    margin-top: 50px;
    height: 500px;
    width: 500px;
    display: grid;
    gap: 1px; 
    box-shadow: 10px 10px  10px #a09d9d;
}
.span1{
    margin-top: 7px;
    color: rgba(35, 153, 212, 0.996) ;
    margin: auto;
}
span{
    margin: 5px;
    font-family: 'Times New Roman', Times, serif;
}
input{
     border: 1px solid#3498db;
    border-radius: 7px;
    height: 40px;
    width: 300px;
    margin: auto;
    

}
input::placeholder{
    color: rgba(0, 0, 0, 0.22);
    font-family: 'Times New Roman', Times, serif;
}
a{
    display: flex;
    justify-content: flex-end;
    margin-right: 100px;
    text-decoration: none;
    color: #3498db;
}
.buttom{
    display: flex;
    margin: auto;
    margin-bottom: 20px;
    gap: 200px
      
}
.buttom1{
    width: 90px;
    height: 40px;
    background-color: white;
    border: 1px solid #3498db;
    color: #3498db;
    
}
.buttom2{
    width: 90px;
    height: 40px;
    background-color: #3498db<img width="200" alt="Captura de ecrã 2023-12-10 183626" src="https://github.com/Afonsina1/Formul-rio-HTML-CSS/assets/125184253/4b57a6eb-2487-464a-a582-58ec6d3aaca7">
<img width="200" alt="Captura de ecrã 2023-12-10 183626" src="https://github.com/Afonsina1/Formul-rio-HTML-CSS/assets/125184253/98167e4e-d95f-437e-b318-36a192e609b3">
;
    border: 1px solid#3498db;
    color: white;
    
}
