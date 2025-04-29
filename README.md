# Calculator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background: #f0f0f0;
        }
        .calculator {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
            width: 300px;
        }
        .display {
            width: 100%;
            height: 60px;
            background: #eeeeee;
            text-align: right;
            font-size: 28px;
            line-height: 60px;
            padding: 0 10px;
            margin-bottom: 20px;
            border-radius: 5px;
            overflow: hidden;
        }
        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            grid-gap: 10px;
        }
        .buttons button {
            height: 60px;
            font-size: 24px;
            border: none;
            background: #e0e0e0;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.2s;
        }
        .buttons button:hover {
            background: #d0d0d0;
        }
        .span-two {
            grid-column: span 2;
        }
        .span-two-rows {
            grid-row: span 2;
        }
    </style>
</head>
<body>

    <div class="calculator">
        <div id="display" class="display">0</div>

        <div class="buttons">
            <!-- Row 1 -->
            <button>C</button>
            <button>÷</button>
            <button>×</button>
            <button>⌫</button>

            <!-- Row 2 -->
            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button>-</button>

            <!-- Row 3 -->
            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button>+</button>

            <!-- Row 4 -->
            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button class="span-two-rows">=</button>

            <!-- Row 5 -->
            <button class="span-two">0</button>
            <button>.</button>
            <!-- Empty space handled because = button spans two rows -->
        </div>
    </div>

</body>
</html>