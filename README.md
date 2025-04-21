<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мои статьи</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #121212; /* Тёмный фон */
            /* Для фонового изображения раскомментируй: */
            /* background-image: url('https://example.com/background.jpg'); */
            background-size: cover;
            color: #ffffff;
        }
        h1 {
            text-align: center;
            color: #00b7eb; /* Голубой заголовок */
            margin-bottom: 20px;
            animation: fadeIn 1s ease-in;
        }
        .article-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .article-card {
            background: #1e1e1e; /* Тёмные карточки */
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            width: 100%;
            max-width: 300px;
            overflow: hidden;
            text-decoration: none;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            animation: slideUp 0.5s ease forwards;
            opacity: 0;
            animation-delay: calc(0.1s * var(--index));
        }
        .article-card:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0,0,0,0.3);
        }
        .article-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }
        .article-card h3 {
            margin: 10px;
            font-size: 18px;
            color: #ffffff;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <h1>The Limited Club</h1>
    <div class="article-container">
        <!-- Статья 1 -->
        <a href="[https://telegra.ph/Статья-1](https://telegra.ph/Kak-podnyat-kachestvo-trafika-v-gemblinge-neskolko-prakticheskih-mehanik-04-09)" class="article-card" style="--index: 1;">
            <img src="[https://via.placeholder.com/300x200.png?text=Preview+1](https://i.postimg.cc/qvFS6T6t/image.jpg)" alt="Статья 1">
            <h3>Как поднять качество трафика в гемблинге: несколько практических механик</h3>
        </a>
        <!-- Статья 2 -->
        <a href="https://telegra.ph/Статья-2" class="article-card" style="--index: 2;">
            <img src="https://via.placeholder.com/300x200.png?text=Preview+2" alt="Статья 2">
            <h3>Статья 2 тут будет </h3>
        </a>
        <!-- Добавь свои статьи в таком же формате -->
    </div>
</body>
</html>
