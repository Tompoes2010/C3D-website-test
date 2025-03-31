<!DOCTYPE html>
<html lang="nl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C3D - Gepersonaliseerde Sleutelhangers</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        h1 {
            color: #333;
        }
        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        form {
            display: flex;
            flex-direction: column;
        }
        input, textarea, button {
            margin: 10px 0;
            padding: 10px;
            font-size: 16px;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welkom bij C3D</h1>
        <p>Bestel hier je gepersonaliseerde 3D-geprinte sleutelhanger!</p>
        <form action="https://formspree.io/f/your-form-id" method="POST">
            <input type="text" name="naam" placeholder="Jouw naam" required>
            <input type="email" name="email" placeholder="Jouw e-mail" required>
            <textarea name="beschrijving" placeholder="Beschrijf jouw ontwerp" required></textarea>
            <button type="submit">Bestel</button>
        </form>
    </div>
</body>
</html>
