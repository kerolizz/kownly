<!DOCTYPE html>
<html>
<head>
    <title>Pic of Your Smile</title>
    <style>
        body {
            text-align: center;
            background-color: #fdeff2;
            font-family: Arial, sans-serif;
        }

        h1 {
            color: #ff69b4;
        }

        p {
            font-size: 18px;
            color: #333333;
            line-height: 1.5;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #ff69b4;
            color: #ffffff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <h1>Pic of Your Smile</h1>
    <p>She had one of those smiles for a smiles—</p>
    <p>a smile you can't help but smile when smiled.</p>
    <p>Can or cannot.....???</p>
    <button onclick="submitPetition('yes')">Yesszzz &#x1F618;</button>
    <button onclick="submitPetition('no')">No &#x1F624;</button>

    <script>
        function submitPetition(response) {
            if (response === 'yes') {
                alert("Makasih soooo much \uD83D\uDE18");
            } else if (response === 'no') {
                alert("Select siottt \uD83D\uDE24");
            }
        }
    </script>
</body>
</html>
