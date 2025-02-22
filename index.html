<!DOCTYPE html>
<html lang="en">
<head>
    <title>Dynamic Application</title>
    
    <style> 
        body {
            background-color: rgb(3, 165, 165);
            padding: 20px;
            font-family: Arial, sans-serif;
        }
        .container {
            display: flex;
            flex-direction: column;
            gap: 25px;
            align-items: center;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        .button-group {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: nowrap;
            align-items: center;
            width: 100%;
        }
        .color-section {
            background-color: rgba(255, 255, 255, 0.3);
            padding: 20px;
            border-radius: 8px;
            width: 100%;
            max-width: 500px;
        }
        .color-picker {
            display: flex;
            gap: 15px;
            align-items: center;
            width: 100%;
            justify-content: center;
        }
        button {
            padding: 10px 20px;
            border-radius: 6px;
            border: none;
            cursor: pointer;
            background-color: #ffffff;
            min-width: 120px;
            position: relative; /* Fix: Prevents movement */
            top: 0;
            left: 0;
        }
        button:hover {
            background-color: #f0f0f0;
        }
        #Click {
            background-color: #4CAF50;
            color: yellow;
            font-size: 1.1em;
            padding: 12px 24px;
        }
        input[type="text"], input[type="color"] {
            padding: 8px;
            border-radius: 6px;
            border: 1px solid #ddd;
        }
        input[type="color"] {
            width: 60px;
            height: 40px;
            padding: 2px;
            cursor: pointer;
        }
        .error-message {
            color: #ff3333;
            font-size: 14px;
            margin-top: 10px;
            text-align: center;
            display: none;
            font-weight: 500;
            padding: 8px;
            background-color: rgba(255, 0, 0, 0.1);
            border-radius: 4px;
        }
        #text {
            font-size: 18px;
            margin: 20px 0;
            text-align: center;
            color: #333;
        }
        #colorInput {
            min-width: 150px;
        }
        .apply-button {
            background-color: #4CAF50;
            color: white;
        }
        .apply-button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body onload="showWelcomeMessage()">
    <div class="container">
        <div class="button-group">
            <button onclick="alert('Hello! Are you aware that coding is so easy in this generation!')">Click me</button>
            <button id="Click">Internal Javascript</button>
            <button onClick="toggleText()">Change Text</button>
        </div>

        <p id="text">This is the first HTML, CSS and Javascript fusion</p>
        
        <div class="color-section">
            <div class="color-picker">
                <input type="color" id="colorPickerInput" value="#00FFFF" onchange="handleColorPicker()">
                <input type="text" id="colorInput" placeholder="Enter color name (e.g. red)" onkeyup="handleTextInput(event)">
                <button onclick="applyColor()" class="apply-button">Apply Color</button>
            </div>
            <div id="errorMessage" class="error-message"></div>
        </div>
    </div>
    
    <script>
        function showWelcomeMessage() {
            alert("Hi, Welcome! I am Tetricia Teopista. Please click OK to continue.");
        }

        const originalText = document.getElementById('text').innerHTML;
        let isOriginalText = true;

        function isValidColor(color) {
            const tempElement = document.createElement('div');
            tempElement.style.backgroundColor = color;
            return tempElement.style.backgroundColor !== '';
        }

        function showError(message) {
            const errorElement = document.getElementById('errorMessage');
            errorElement.textContent = message;
            errorElement.style.display = 'block';
            setTimeout(() => {
                errorElement.style.display = 'none';
            }, 3000);
        }

        function handleColorPicker() {
            const color = document.getElementById('colorPickerInput').value;
            document.body.style.backgroundColor = color;
            document.getElementById('colorInput').value = color;
        }

        function handleTextInput(event) {
            if (event.key === 'Enter') {
                applyColor();
            }
        }

        function applyColor() {
            const colorInput = document.getElementById('colorInput');
            const color = colorInput.value.trim();

            if (!color) {
                showError('Please enter a color name or code');
                return;
            }

            if (!isValidColor(color)) {
                showError('Color does not exit. Please enter a valid color name or code (e.g. red, #FF0000)');
                return;
            }

            document.body.style.backgroundColor = color;
            try {
                const tempElement = document.createElement('div');
                tempElement.style.backgroundColor = color;
                const computedColor = getComputedStyle(tempElement).backgroundColor;
                const hexColor = rgbToHex(computedColor);
                document.getElementById('colorPickerInput').value = hexColor;
            } catch (error) {
                console.log('Color conversion error:', error);
            }
        }

        function rgbToHex(rgb) {
            if (rgb.startsWith('rgb')) {
                const rgbValues = rgb.match(/\d+/g);
                if (rgbValues && rgbValues.length === 3) {
                    const r = parseInt(rgbValues[0]);
                    const g = parseInt(rgbValues[1]);
                    const b = parseInt(rgbValues[2]);
                    return '#' + ((1 << 24) + (r << 16) + (g << 8) + b).toString(16).slice(1);
                }
            }
            return '#000000'; 
        }

        function toggleText() {
            const textElement = document.getElementById('text');
            if (isOriginalText) {
                textElement.innerHTML = 'I am testing inline Javascript';
            } else {
                textElement.innerHTML = originalText;
            }
            isOriginalText = !isOriginalText;
        }

        document.getElementById("Click").onclick = function() {
            alert("Button was Clicked.");
        }
        document.getElementById("Click").onmouseover = function() {
            document.getElementById("Click").style.color = "red";
        }
        document.getElementById("Click").onmouseout = function() {
            document.getElementById("Click").style.color = "yellow";
        }
    </script>
</body>
</html>
