<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>Final</title>
    <style>
        /* Style général */
        body {
            background-color: #e0f7fa; /* Bleu très clair */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            color: #00509e;
        }

        h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .buttons {
            display: flex;
            gap: 20px;
        }

        button {
            background-color: #00509e;
            color: white;
            border: none;
            border-radius: 5px;
            padding: 10px 20px;
            font-size: 1.2em;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        button:hover {
            background-color: #003f7e;
        }
    </style>
</head>
<body>
    <h1>Bonjour</h1>
    <div class="buttons">
        <button onclick="alert('Sign Up sélectionné')">Sign Up</button>
        <button onclick="alert('Sign In sélectionné')">Sign In</button>
    </div>
</body>
</html>
