<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>التخليص الجمركي</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Tajawal', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            background-color: #00264d;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
            padding: 10px 15px;
            display: block;
        }
        nav ul li a:hover {
            background-color: #0055a5;
            border-radius: 5px;
        }
        main {
            padding: 20px;
        }
        section {
            background: white;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        .form-container {
            width: 50%;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: right;
        }
        .form-container input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .form-container button {
            background-color: #004080;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .form-container button:hover {
            background-color: #0055a5;
        }
    </style>
</head>
<body>
    <header>
        <h1>مرحبًا بك في موقع التخليص الجمركي</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">الرئيسية</a></li>
            <li><a href="register.html" target="_self"">إنشاء حساب</a></li>
            <li><a href="account.html">إدارة الحساب</a></li>
        </ul>
    </nav>
    <main>
        <section>
            <h2>معلومات عن التخليص الجمركي</h2>
            <p>هنا يمكنك معرفة كل شيء عن إجراءات التخليص الجمركي والخدمات التي نقدمها.</p>
        </section>
        <section class="form-container">
            <h2>إنشاء حساب</h2>
            <form action="#" method="post">
                <label for="username">اسم الحساب:</label>
                <input type="text" id="username" name="username" required>
                
                <label for="email">البريد الإلكتروني:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="password">كلمة المرور:</label>
                <input type="password" id="password" name="password" required>
                
                <label for="confirm-password">تأكيد كلمة المرور:</label>
                <input type="password" id="confirm-password" name="confirm-password" required>
                
                <button type="submit">تسجيل</button>
            </form>
        </section>
    </main>
</body>
</html>
