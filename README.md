<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>School Hub</title>
    <!-- Tailwind CSS CDN for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 1rem;
            text-align: center;
        }
        .container {
            background-color: #ffffff;
            border-radius: 1rem;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
            padding: 2.5rem;
            width: 100%;
            max-width: 400px;
        }
        .btn {
            display: block;
            width: 100%;
            padding: 1rem;
            border-radius: 0.75rem;
            font-weight: 600;
            cursor: pointer;
            transition: background-color 0.2s, transform 0.1s;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            text-decoration: none; /* For links */
            color: white;
            font-size: 1.125rem;
        }
        .btn-school {
            background-color: #3b82f6; /* Blue */
            margin-bottom: 1.5rem;
        }
        .btn-school:hover {
            background-color: #2563eb;
            transform: translateY(-1px);
        }
        .btn-student {
            background-color: #10b981; /* Green */
        }
        .btn-student:hover {
            background-color: #059669;
            transform: translateY(-1px);
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="text-3xl font-bold text-gray-800 mb-8">Welcome to the School Hub! 📚</h1>
        <a href="school.html" class="btn btn-school">I'm a School Admin 🧑‍🏫</a>
        <a href="student.html" class="btn btn-student">I'm a Student 🧑‍🎓</a>
    </div>
</body>
</html>

