body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
        }
        h1 {
            color: #333;
        }
        #board {
            display: grid;
            grid-template-columns: repeat(3, 100px);
            grid-gap: 5px;
            background-color: #333;
            padding: 5px;
            border-radius: 10px;
        }
        .cell {
            width: 100px;
            height: 100px;
            background-color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            font-weight: bold;
            color: #333;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .cell:hover {
            background-color: #e0e0e0;
        }
        #status {
            margin-top: 20px;
            font-size: 24px;
            color: #333;
        }
        #reset {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 18px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        #reset:hover {
            background-color: #45a049;
        }
