# Login-Page
A basic registration Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ShubhTravels.com</title>
    <link rel="stylesheet" href="style.css">
    <style>/* style.css */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

body {
    background: linear-gradient(135deg, #74ebd5, #ACB6E5);
    min-height: 100vh;
    padding: 40px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
}

/* Header Styling */
header {
    text-align: center;
    margin-bottom: 40px;
}

header h1 {
    font-size: 3rem;
    font-weight: bold;
    color: #ffffff;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.4);
}

header h1 span {
    color: #ffe600;
}

header p {
    font-size: 1.2rem;
    color: #fefefe;
    margin-top: 10px;
    font-style: italic;
}

/* Form Styling */
form {
    background-color: white;
    padding: 30px 40px;
    border-radius: 15px;
    box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);
    width: 100%;
    max-width: 500px;
}

form div {
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: bold;
    color: #333;
}

input[type="text"],
input[type="number"],
input[type="email"],
textarea {
    width: 100%;
    padding: 12px 15px;
    border: 1px solid #ccc;
    border-radius: 10px;
    transition: 0.3s;
    font-size: 1rem;
    background-color: #f9f9f9;
}

input:focus,
textarea:focus {
    border-color: #6a82fb;
    outline: none;
    background-color: #fff;
    box-shadow: 0 0 0 3px rgba(106, 130, 251, 0.2);
}

textarea {
    resize: vertical;
    min-height: 80px;
}

button {
    padding: 12px 20px;
    background: linear-gradient(to right, #6a82fb, #fc5c7d);
    border: none;
    border-radius: 10px;
    color: white;
    font-weight: bold;
    font-size: 1rem;
    cursor: pointer;
    transition: background 0.3s ease;
    width: 100%;
}

button:hover {
    background: linear-gradient(to right, #5a69e5, #f74268);
}

/* Responsive tweaks */
@media (max-width: 600px) {
    form {
        padding: 25px 20px;
    }

    input, textarea, button {
        font-size: 0.95rem;
    }

    header h1 {
        font-size: 2.3rem;
    }

    header p {
        font-size: 1rem;
    }
}
</style>
</head>
<body>
    <header>
        <h1>ShubhTravels<span>.com</span></h1>
        <p>Your gateway to unforgettable journeys</p>
    </header>

    <form action="">
        <div>
            <label for="name">Name</label>
            <input id="name" type="text" placeholder="Enter Your Name">
        </div>
        <div>
            <label for="age">Age</label>
            <input id="age" type="number" placeholder="Enter Your Age">
        </div>
        <div>
            <label for="Email">Email</label>
            <input id="Email" type="email" placeholder="Enter a valid Email">
        </div>
        <div>
            <label for="Contact">Contact number</label>
            <input id="Contact" type="number" placeholder="Enter Your Contact number">
        </div>
        <div>
            <label for="Address">Address</label>
            <textarea name="Address" id="Address" placeholder="Enter your full address here..."></textarea>
        </div>
        <div>
            <button type="submit">Submit</button>
        </div>
    </form>
</body>
</html>
