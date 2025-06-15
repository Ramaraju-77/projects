<!DOCTYPE html>
<html lang="en">
<head>
    <Style>
.container {
     width: 100; 
    height:100vh ;
    background:rgb(8, 8, 8);
    display:flex;
    align-items: center;
    justify-content:"center";
   
}
.calculator {
    background:rgb(125, 197, 233);
    padding:20px;
    border-radius:20px;
     margin-left: 42%;
}
.calculator form input{
    border:0;
    outline:0;
    width:40px;
    height:40px;
    border-radius:10px;
    box-shadow:-8px -8px 15px rgb(4, 64, 72),5px 5px 15px rgb(10, 30, 71);
    background: transparent;
    font-size:20px;
    color:#ffffff;
    cursor:pointer;
    margin:10px;
}
form .display{
    display: flex;
    justify-content: flex-end;
    margin: 20px 0;
}
form .display input{
    text-align: right;
    flex:1;
    font-size:45px;
    box-shadow:none;
}
form input.equal{
    width:103px;
}
    </Style>
    <title>Simple Calculator</title>
</head>
<body>
    <div class="container">
        <div class="calculator">
            <form>
                <div class="display">
                    <input type="text" name="display" >
                </div>
                <div>
                    <input type="button" value="AC" onclick="display.value =' '">
                    <input type="button" value="DE" onclick="display.value = display.value.toString().slice">
                    <input type="button" value="." onclick="display.value +='.'">
                    <input type="button" value="/" onclick="display.value +='/'"> 
                 </div>
                 <div>
                    <input type="button" value="7" onclick="display.value +='7'">
                    <input type="button" value="8" onclick="display.value +='8'">
                    <input type="button" value="9" onclick="display.value +='9'">
                    <input type="button" value="*"  onclick="display.value +='*'"> 
                 </div>
                 <div>
                    <input type="button" value="4" onclick="display.value +='4'">
                    <input type="button" value="5" onclick="display.value +='5'">
                    <input type="button" value="6" onclick="display.value +='6'">
                    <input type="button" value="-" onclick="display.value +='-'"> 
                 </div>
                 <div>
                    <input type="button" value="1" onclick="display.value +='1'">
                    <input type="button" value="2" onclick="display.value +='2'">
                    <input type="button" value="3" onclick="display.value +='3'">
                    <input type="button" value="+" onclick="display.value +='+'"> 
                 </div>
                 <div>
                    <input type="button" value="00" onclick="display.value +='00'">
                    <input type="button" value="0" onclick="display.value +='0'">
                    <input type="button" class="equal" value="=" onclick="display.value =eval(display.value)"> 
                 </div>
                 
                 
                 
                 
            </form>
            
        </div>
    </div>
</body>
</html>
