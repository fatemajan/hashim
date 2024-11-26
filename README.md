# hashim
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Friendship Form</title>
    <link rel="stylesheet" href="HTML Form.css"> <!-- Ensure you have this CSS file -->
</head>

<body>
    <div class="container">
        <section>
            <h1>Friendship Form</h1>
            <form
                onsubmit="window.location.href='https://drive.google.com/file/d/1rWLE8fKZcLfgqdW1jL5k1qVG4XDdVWOW/view?usp=drivesdk'; return false;">
                <div>
                    <label>First Name:
                        <input type="text" required>
                    </label>
                </div>
                <div>
                    <label>Last Name:
                        <input type="text" required>
                    </label>
                </div>
                <div>
                    <label>Gender:
                        <select name="gender" required>
                            <option value="male">Male</option>
                            <option value="female">Female</option>
                        </select>
                    </label>
                </div>
                <div>
                    <label>Contact Number:
                        <input type="text" required>
                    </label>
                </div>
                <div>
                    <label>Date of Birth:
                        <input type="date" required>
                    </label>
                </div>
                <div>
                    <label>Best Friend:
                        <input type="text" required>
                    </label>
                </div>
                <div>
                    <label>What motivated you to select this friend in your life?
                        <textarea required></textarea>
                    </label>
                </div>
                <button type="submit">Submit</button>
            </form>
        </section>
    </div>
</body>

</html>

Style sheet
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}

.container {
    width: 100%;
    max-width: 600px;
    padding: 20px;
    background-color: #ffffff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

h1 {
    text-align: center;
    margin-bottom: 20px;
    color: #333;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    display: flex;
    flex-direction: column;
    margin-bottom: 15px;
    font-weight: bold;
    color: #333;
}

input[type="text"],
input[type="date"],
input[type="email"],
input[type="password"],
input[type="number"],
select,

input[type="text"]:focus,
input[type="date"]:focus,
input[type="email"]:focus,
input[type="password"]:focus,
input[type="number"]:focus,
select:focus,
textarea:focus {
    border-color: #0077cc;
    outline: none;
}


button {
    padding: 10px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #0077cc;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    margin-top: 10px;
    transition: background-color 0.3s ease;
}

button:hover {
    background-color: #005fa3;
}

div {
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

div>label {
    flex: 1 1 45%;
}

