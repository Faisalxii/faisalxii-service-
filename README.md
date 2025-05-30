<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Faisalxii | Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: ##3c7dee;
            text-align: center;
            padding: 50px;
        }
        nav {
            background-color:#3c7dee;
            padding: 15px;
            display: flex;
            justify-content: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background: white;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 5px solid #007bff;
        }
        h1 {
            color: #007bff;
            margin-bottom: 10px;
        }
        p {
            font-size: 18px;
            color: #555;
        }
        .btn {
            display: inline-block;
            background-color: #007bff;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
            transition: 0.3s;
        }
        .btn:hover {
            background-color: #0056b3;
        }
        .services {
            margin-top: 30px;
        }
        .service-box {
            background: #e3e3e3;
            padding: 20px;
            border-radius: 8px;
            margin: 10px;
            display: inline-block;
            width: 45%;
        }
        .contact-form {
            margin-top: 30px;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .submit-btn {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 10px;
            cursor: pointer;
            width: 100%;
        }
        .submit-btn:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <img src="your-image.jpg" alt="Faisalxii" class="profile-img">
        <h1>Welcome to Faisalxii's Portfolio</h1>
        <p>I am a professional web developer & designer.</p>
        <a href="#" class="btn">View Projects</a>
    </div>

    <div class="services">
        <h2>My Services</h2>
        <div class="service-box">
            <h3>Web Development</h3>
            <p>Modern & responsive websites built with HTML, CSS, JavaScript.</p>
        </div>
        <div class="service-box">
            <h3>Graphic Design</h3>
            <p>Creative logos, banners, and UI/UX designs.</p>
        </div>
    </div>

    <div class="container contact-form">
        <h2>Order Now</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea rows="4" placeholder="Describe your project..." required></textarea>
            <button type="submit" class="submit-btn">Send Request</button>
        </form>
    </div>

</body>
</html>
