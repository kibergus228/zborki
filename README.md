<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centered Cards</title>
    <link rel="stylesheet" type="text/css" href="stail.css">
</head>
<body>
    <stail>
        body {
    background-image: url('./завантаження.jpg');
    background-size: cover;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.container {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.card {
    width: 250px;
    padding: 20px;
    background-color: rgba(173, 216, 230, 0.8);
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    text-align: center;
}

.card img {
    width: 100%;
    border-radius: 4px;
    margin-bottom: 10px;
}

.btn {
    background-color: #007BFF;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.btn:hover {
    background-color: #0056b3;
}
    </stail>
    <div class="container">
        <div class="card">
            <img src="./завантаження (2).jpg" alt="Winter Forest">
            <div class="info">
                <h2>Ліс</h2>
                <p>Зимовий ліс</p>
                <a href="https://drive.google.com/drive/folders/17YPgeyZAfQeU2t1QJuY_hhgETOhHUheQ?usp=sharing">
                    <button class="btn">скачати</button>
                </a>
            </div>
        </div>
        
        <div class="card">
            <img src="./завантаження (2).jpg" alt="Winter Forest">
            <div class="info">
                <h2>Ліс</h2>
                <p>Зимовий ліс</p>
                <a href="https://drive.google.com/drive/folders/17YPgeyZAfQeU2t1QJuY_hhgETOhHUheQ?usp=sharing">
                    <button class="btn">скачати</button>
                </a>
            </div>
        </div>
        
        <div class="card">
            <img src="./завантаження (2).jpg" alt="Winter Forest">
            <div class="info">
                <h2>Ліс</h2>
                <p>Зимовий ліс</p>
                <a href="https://drive.google.com/drive/folders/17YPgeyZAfQeU2t1QJuY_hhgETOhHUheQ?usp=sharing">
                    <button class="btn">скачати</button>
                </a>
            </div>
        </div>
    </div>
</body>
</html>

