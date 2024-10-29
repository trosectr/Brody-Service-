# Brody-Service-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brody's Neighborhood Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        main {
            padding: 1em 2em;
        }
        .section {
            margin-bottom: 2em;
        }
        h2 {
            color: #333;
        }
        form {
            background-color: #e2e2e2;
            padding: 1em;
            border-radius: 5px;
        }
        .form-group {
            margin-bottom: 1em;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5em;
        }
        .form-group input {
            padding: 0.5em;
            width: 100%;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 0.7em 1.5em;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

<header>
    <h1>Brody's Neighborhood Services</h1>
    <p>Helping neighbors with snow shoveling and trash day services</p>
</header>

<main>
    <section class="section" id="about">
        <h2>About Brody</h2>
        <p>Hi, I'm Brody! I'm 10 years old and love helping my neighbors keep their driveways clear and their trash cans in order. My dad helps me run my business, and I'm excited to offer reliable and friendly services right in our community.</p>
    </section>

    <section class="section" id="services">
        <h2>Services & Pricing</h2>
        <ul>
            <li><strong>Snow Shoveling:</strong> $25 per job</li>
            <li><strong>Trash Can Service:</strong> $4 per week - I’ll bring your trash cans to the street on trash day and put them back afterward!</li>
        </ul>
    </section>

    <section class="section" id="sign-up">
        <h2>Sign Up for Services</h2>
        <form>
            <div class="form-group">
                <label for="name">Full Name</label>
                <input type="text" id="name" name="name" required>
            </div>
            <div class="form-group">
                <label for="address">Address</label>
                <input type="text" id="address" name="address" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
            </div>
            <div class="form-group">
                <label for="service">Choose Service</label>
                <select id="service" name="service" required>
                    <option value="snow_shoveling">Snow Shoveling - $25</option>
                    <option value="trash_service">Trash Can Service - $4/week</option>
                </select>
            </div>
            <button type="submit">Sign Up</button>
        </form>
    </section>
</main>

</body>
</html>
