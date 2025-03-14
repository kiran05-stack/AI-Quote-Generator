<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Quote Generator</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; padding: 50px; }
        #quote-box { font-size: 24px; margin-top: 20px; }
        button { padding: 10px 20px; font-size: 16px; }
    </style>
</head>
<body>
    <h1>AI-Powered Quote Generator</h1>
    <div id="quote-box">Click below to get a quote</div>
    <button onclick="generateQuote()">Generate Quote</button>
    
    <script>
        const quotes = [
            "Believe in yourself!",
            "Keep pushing forward!",
            "Your potential is limitless!",
            "Success comes to those who work hard!"
        ];

        function generateQuote() {
            const randomIndex = Math.floor(Math.random() * quotes.length);
            document.getElementById("quote-box").innerText = quotes[randomIndex];
        }
    </script>
</body>
</html>
