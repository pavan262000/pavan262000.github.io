<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centered Column with Image Cards</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .card {
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
            border-radius: 10px;
            text-align: center;
            margin: 10px;
        }

        .image-block img {
            max-width: 100%;
            height: auto;
        }

        .label {
            font-size: 18px;
            color: #333;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="card">
            <div class="image-block">
                <img src="image1.jpg" alt="Image 1">
                <div class="label">Label 1</div>
            </div>
        </div>
        <div class="card">
            <div class="image-block">
                <img src="image2.jpg" alt="Image 2">
                <div class="label">Label 2</div>
            </div>
        </div>
        <div class="card">
            <div class="image-block">
                <img src="image3.jpg" alt="Image 3">
                <div class="label">Label 3</div>
            </div>
        </div>
    </div>
</body>
</html>
