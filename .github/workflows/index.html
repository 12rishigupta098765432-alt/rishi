<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calculator App with History</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background: linear-gradient(135deg, #6366F1, #8B5CF6);
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }

        .app-container {
            display: flex;
            flex-direction: column;
            align-items: center;
            width: 100%;
            max-width: 1200px;
        }

        .app-title {
            color: white;
            font-size: 2.5rem;
            margin-bottom: 2rem;
            text-align: center;
            text-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
        }

        .calculator-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            width: 100%;
        }

        .calculator {
            background-color: #1F2937;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            padding: 20px;
            width: 350px;
        }

        .display {
            background-color: #374151;
            padding: 20px;
            border-radius: 12px;
            margin-bottom: 20px;
            text-align: right;
            min-height: 120px;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        .calculation {
            color: #9CA3AF;
            font-size: 1.2rem;
            min-height: 1.8rem;
            overflow-x: auto;
            white-space: nowrap;
        }

        .result {
            color: white;
            font-size: 2.5rem;
            font-weight: 500;
            overflow-x: auto;
            white-space: nowrap;
        }

        .buttons {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 12px;
        }

        .btn {
            border: none;
            padding: 16px;
            border-radius: 12px;
            font-size: 1.3rem;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.2s;
        }

        .btn:active {
            transform: scale(0.95);
        }

        .btn-number {
            background-color: #4B5563;
            color: white;
        }

        .btn-number:hover {
            background-color: #6B7280;
        }

        .btn-operator {
            background-color: #F59E0B;
            color: white;
        }

        .btn-operator:hover {
            background-color: #FBBF24;
        }

        .btn-special {
            background-color: #9CA3AF;
            color: #1F2937;
        }

        .btn-special:hover {
            background-color: #D1D5DB;
        }

        .btn-equals {
            background-color: #10B981;
            color: white;
        }

        .btn-equals:hover {
            background-color: #34D399;
        }

        .btn-clear {
            background-color: #EF4444;
            color: white;
        }

        .btn-clear:hover {
            background-color: #F87171;
        }

        .history-panel {
            background-color: #1F2937;
            border-radius: 16px;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
            padding: 20px;
            color: white;
            width: 350px;
            display: flex;
            flex-direction: column;
        }

        .history-title {
            font-size: 1.5rem;
            margin-bottom: 15px;
            text-align: center;
            color: #F59E0B;
        }

        .history-list {
            overflow-y: auto;
            max-height: 350px;
            margin-bottom: 15px;
            flex-grow: 1;
        }

        .history-item {
            padding: 12px 15px;
            margin-bottom: 10px;
            background-color: #374151;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.2s;
        }

        .history-item:hover {
            background-color: #4B5563;
        }

        .history-expression {
            color: #9CA3AF;
            font-size: 0.9rem;
            margin-bottom: 5px;
        }

        .history-result {
            color: white;
            font-size: 1.2rem;
            font-weight: 500;
        }

        .history-actions {
            display: flex;
            gap: 10px;
        }

        .history-btn {
            flex: 1;
            padding: 10px;
            border: none;
            border-radius: 8px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.2s;
        }

        .history-btn-clear {
            background-color: #EF4444;
            color: white;
        }

        .history-btn-clear:hover {
            background-color: #F87171;
        }

        .footer {
            color: white;
            margin-top: 2rem;
            text-align: center;
            opacity: 0.8;
        }

        @media (max-width: 768px) {
            .calculator-container {
                flex-direction: column;
                align-items: center;
            }

            .calculator, .history-panel {
                width: 100%;
                max-width: 350px;
            }
        }
    </style>
</head>
<body>
    <div class="app-container">
        <h1 class="app-title">Calculator with History</h1>
        
        <div class="calculator-container">
            <div class="calculator">
                <div class="display">
                    <div class="calculation" id="calculation">0</div>
                    <div class="result" id="result">0</div>
                </div>
                
                <div class="buttons">
                    <button class="btn btn-clear" onclick="clearAll()">C</button>
                    <button class="btn btn-special" onclick="backspace()">⌫</button>
                    <button class="btn btn-special" onclick="appendOperation('%')">%</button>
                    <button class="btn btn-operator" onclick="appendOperation('/')">/</button>
                    
                    <button class="btn btn-number" onclick="appendNumber('7')">7</button>
                    <button class="btn btn-number" onclick="appendNumber('8')">8</button>
                    <button class="btn btn-number" onclick="appendNumber('9')">9</button>
                    <button class="btn btn-operator" onclick="appendOperation('*')">×</button>
                    
                    <button class="btn btn-number" onclick="appendNumber('4')">4</button>
                    <button class="btn btn-number" onclick="appendNumber('5')">5</button>
                    <button class="btn btn-number" onclick="appendNumber('6')">6</button>
                    <button class="btn btn-operator" onclick="appendOperation('-')">-</button>
                    
                    <button class="btn btn-number" onclick="appendNumber('1')">1</button>
                    <button class="btn btn-number" onclick="appendNumber('2')">2</button>
                    <button class="btn btn-number" onclick="appendNumber('3')">3</button>
                    <button class="btn btn-operator" onclick="appendOperation('+')">+</button>
                    
                    <button class="btn btn-number" onclick="appendNumber('0')">0</button>
                    <button class="btn btn-number" onclick="appendNumber('.')">.</button>
                    <button class="btn btn-equals" onclick="calculate()" colspan="2">=</button>
                </div>
            </div>
            
            <div class="history-panel">
                <h2 class="history-title">Calculation History</h2>
                <div class="history-list" id="history-list">
                    <!-- History will be added here dynamically -->
                </div>
                <div class="history-actions">
                    <button class="history-btn history-btn-clear" onclick="clearHistory()">Clear History</button>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p>Your calculations are stored in the browser's localStorage</p>
        </div>
    </div>

    <script>
        // State management
        let currentInput = '0';
        let calculation = '';
        let shouldResetInput = false;
        let history = JSON.parse(localStorage.getItem('calculatorHistory')) || [];

        // DOM elements
        const resultElement = document.getElementById('result');
        const calculationElement = document.getElementById('calculation');
        const historyListElement = document.getElementById('history-list');

        // Initialize the calculator
        function initCalculator() {
            updateDisplay();
            renderHistory();
        }

        // Append a number to the current input
        function appendNumber(number) {
            if (currentInput === '0' || shouldResetInput) {
                currentInput = number;
                shouldResetInput = false;
            } else {
                currentInput += number;
            }
            updateDisplay();
        }

        // Append an operation
        function appendOperation(operation) {
            if (shouldResetInput) {
                calculation = resultElement.textContent + operation;
                shouldResetInput = false;
            } else {
                calculation += currentInput + operation;
                currentInput = '0';
            }
            updateDisplay();
        }

        // Calculate the result
        function calculate() {
            if (calculation === '' || shouldResetInput) return;
            
            try {
                calculation += currentInput;
                // Use Function constructor for safe evaluation
                const result = Function('return ' + calculation)();
                const roundedResult = parseFloat(result.toFixed(8)); // Avoid floating point errors
                
                // Add to history
                addToHistory(calculation, roundedResult);
                
                // Reset for next calculation
                currentInput = roundedResult.toString();
                calculation = '';
                shouldResetInput = true;
                updateDisplay();
            } catch (error) {
                resultElement.textContent = 'Error';
                setTimeout(() => {
                    clearAll();
                }, 1500);
            }
        }

        // Clear all inputs
        function clearAll() {
            currentInput = '0';
            calculation = '';
            shouldResetInput = false;
            updateDisplay();
        }

        // Backspace function
        function backspace() {
            if (currentInput.length > 1) {
                currentInput = currentInput.slice(0, -1);
            } else {
                currentInput = '0';
            }
            updateDisplay();
        }

        // Update the display
        function updateDisplay() {
            resultElement.textContent = currentInput;
            calculationElement.textContent = calculation;
        }

        // Add calculation to history
        function addToHistory(expression, result) {
            history.unshift({
                expression,
                result,
                timestamp: new Date().toLocaleString()
            });
            
            // Keep only last 20 calculations
            if (history.length > 20) {
                history.pop();
            }
            
            // Save to localStorage
            localStorage.setItem('calculatorHistory', JSON.stringify(history));
            
            // Update UI
            renderHistory();
        }

        // Render history list
        function renderHistory() {
            historyListElement.innerHTML = '';
            
            if (history.length === 0) {
                historyListElement.innerHTML = '<div class="history-item"><div class="history-result">No history yet</div></div>';
                return;
            }
            
            history.forEach((item, index) => {
                const historyItem = document.createElement('div');
                historyItem.className = 'history-item';
                historyItem.innerHTML = `
                    <div class="history-expression">${item.expression}</div>
                    <div class="history-result">${item.result}</div>
                    <div class="history-timestamp">${item.timestamp}</div>
                `;
                
                historyItem.addEventListener('click', () => {
                    calculation = item.expression.slice(0, -1);
                    currentInput = item.result.toString();
                    shouldResetInput = true;
                    updateDisplay();
                });
                
                historyListElement.appendChild(historyItem);
            });
        }

        // Clear history
        function clearHistory() {
            history = [];
            localStorage.removeItem('calculatorHistory');
            renderHistory();
        }

        // Initialize the calculator when the page loads
        window.onload = initCalculator;
    </script>
</body>
</html>
