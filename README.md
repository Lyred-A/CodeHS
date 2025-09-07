<!DOCTYPE html>
<html>
<head>
    <title>Calculator.IO</title>
    <link rel="stylesheet" href="style.css">
    <script src="java.js" defer></script>
</head>
<body>
<div class = "header">
Audit Calc</div>
    <div class="calc">
        <input id="readonly" readonly>
        <div id="grid-format">
            <button class="spcharacter" onclick="appendToCalculate('+')">+</button>
            <button class="spcharacter" onclick="appendToCalculate('*')">*</button>
            <button class="spcharacter" onclick="appendToCalculate('/')">/</button>
            <button class="spcharacter" onclick="appendToCalculate('-')">-</button>
            
            <button class="number" onclick="appendToCalculate('9')">9</button>
            <button class="number" onclick="appendToCalculate('8')">8</button>
            <button class="number" onclick="appendToCalculate('7')">7</button>
            <button class="number" onclick="appendToCalculate('6')">6</button>
            <button class="number" onclick="appendToCalculate('5')">5</button>
            <button class="number" onclick="appendToCalculate('4')">4</button>
            <button class="number" onclick="appendToCalculate('3')">3</button>
            <button class="number" onclick="appendToCalculate('2')">2</button>
            <button class="number" onclick="appendToCalculate('1')">1</button>
            <button class="number" onclick="appendToCalculate('0')">0</button>
            <button class="number" onclick="appendToCalculate('.')">.</button>
            <button class="number" onclick="appendToCalculate('00')">00</button>
            
            <button class="equal" onclick="Allclear()">AC</button>
            <button id="equal" onclick="calculate()">=</button>
        </div>
    </div>
    
    <button id = "black">Black Shade</button>
    <button id = "white">White Shade</button>
</body>
</html>
