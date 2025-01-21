<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pesquisa no Google</title>
    <style>
        /* Estilo Global */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        h1 {
            font-size: 24px;
            color: #333;
            margin-bottom: 20px;
        }

        /* Contêiner principal */
        .search-container {
            text-align: center;
            background-color: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 400px;
        }

        /* Formulário de pesquisa */
        .search-form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .search-form input {
            width: 100%;
            padding: 12px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
            outline: none;
            transition: border-color 0.3s;
        }

        .search-form input:focus {
            border-color: #6366f1;
        }

        .search-form button {
            padding: 12px 20px;
            border: none;
            background-color: #6366f1;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .search-form button:hover {
            background-color: #4e53d2;
        }
    </style>
</head>
<body>
    <div class="search-container">
        <h1>Pesquisa no Google</h1>
        <form action="https://www.google.com/search" method="get" class="search-form">
            <input type="text" name="q" placeholder="Digite sua pesquisa..." required>
            <button type="submit">Pesquisar</button>
        </form>
    </div>
</body>
</html>
