
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Akshita Choudhary's Portfolio</title>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #007bff;
            padding: 50px 0;
            color: white;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        h2 {
            margin-top: 30px;
            font-size: 2rem;
            border-bottom: 2px solid #007bff;
            padding-bottom: 10px;
        }

        .list-group-item {
            background-color: #ffffff;
            border: none;
            border-bottom: 1px solid #e0e0e0;
        }

        .list-group-item:hover {
            background-color: #f1f1f1;
        }

        .card {
            border: 1px solid #007bff;
            border-radius: 8px;
            transition: transform 0.2s;
        }

        .card:hover {
            transform: scale(1.05);
        }

        footer {
            background-color: #f8f9fa;
            padding: 15px 0;
            border-top: 1px solid #e0e0e0;
        }

        footer p {
            margin: 0;
        }

        .container {
            margin-top: 30px;
            margin-bottom: 30px;
        }

        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }

            h2 {
                font-size: 1.5rem;
            }
        }
    </style>
</head>
<body>
    <header class="text-center">
        <h1>Akshita Choudhary</h1>
        <p>B.Tech in Computer Science Engineering</p>
        <p>KIET, Ghaziabad</p>
    </header>

    <section class="container my-5">
        <h2>Skills</h2>
        <ul class="list-group">
            <li class="list-group-item">Programming (C Language)</li>
            <li class="list-group-item">HTML, CSS, Bootstrap</li>
            <li class="list-group-item">JavaScript(Basics)</li>
            <li class="list-group-item">3D Design (AutoDesk Inventor)</li>
        </ul>
    </section>

    <section class="container my-5">
        <h2>Languages</h2>
        <ul class="list-group">
            <li class="list-group-item">Hindi</li>
            <li class="list-group-item">English</li>
            <li class="list-group-item">German</li>
        </ul>
    </section>

    <section class="container my-5">
        <h2>Projects</h2>
        <div class="card mb-3">
            <div class="card-body">
                <h5 class="card-title">Home Workout Website</h5>
                <p class="card-text">A platform for people to do home exercises and workouts.</p>
            </div>
        </div>
        <div class="card mb-3">
            <div class="card-body">
                <h5 class="card-title">To-Do list</h5>
                <p class="card-text">A project showcasing a to do list for selection options.</p>
            </div>
        </div>
    </section>

    <footer class="text-center">
        <p>E-MAIL : akshita.2428cse1570@kiet.edu</p>
        <p>Contact : 7078884564</p>
    </footer>


</body>
</html>
