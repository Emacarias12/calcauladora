html> <html> <head> <title>HTML Calculator</title> <style> body { font-family: Arial, sans-serif; }
#calculator { margin: 0 auto; width: 200px; height: 300px; border: 2px solid #ccc; padding: 15px; display: grid; grid-template-columns: repeat(4, 1fr); grid-gap: 5px; }
button { width: 100%; height: 100%; border: none; font-size: 24px; cursor: pointer; }
button:hover { background-color: #f2f2f2; }
button:active { background-color: #e6e6e6; }
.clear, .equals { grid-column: span 2; background-color: #ff6347; color: #fff; }
.clear:hover, .equals:hover { background-color: #ff4d30; }
.clear:active, .equals:active { background-color: #ff3f21; }
.display { grid-column: span 4; background-color: #f9f9f9; text-align: right; padding: 25px 10px; font-size: 28px; } </style>
</head> <body> <div id="calculator"> <div class="display">0</div> <button>7</button> <button>8</button> <button>9</button> <button>/</button> <button>4</button> <button>5</button> <button>6</button> <button>*</button> <button>1</button> <button>2</button> <button>3

