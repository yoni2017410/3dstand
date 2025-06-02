<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ברוכים הבאים</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            text-align: center;
            direction: rtl;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #ddd;
            padding: 10px;
            margin-top: 20px;
        }
        form {
            max-width: 400px;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 4px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>ברוכים הבאים לאתר של יונתן ושל כרמל</h1>
    </header>
    <main>
        <h2>תוכן ראשי</h2>
        <p>פה תוכלו לקנות מה שבא לכם עד 10 סנטימטר בתלת מימד ולבוא לאסוף .</p>

        <h2>צור קשר</h2>
        <form enctype="multipart/form-data" method="post">
            <label for="name">שם:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">אימייל:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">הודעה:</label>
            <textarea id="message" name="message" rows="4" required></textarea>

            <label for="stlFile">העלה קובץ STL:</label>
            <input type="file" id="stlFile" name="stlFile" accept=".stl" required>

            <button type="submit">שלח</button>
        </form>
    </main>
    <footer>
        <p>כל הזכויות שמורות &copy; 2025</p>
    </footer>
</body>
</html>
