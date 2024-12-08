<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Street Level Esports</title>
    <link rel="stylesheet" href="style.css"> <!-- Link to your CSS file -->
</head>
<body>
    <header>
        <h1>Welcome to Street Level Esports</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#tournaments">Tournaments</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Join Our Esports Tournaments</h2>
        <p>Compete in exciting tournaments and win amazing prizes at Street Level Esports!</p>
    </section>

    <section id="tournaments">
        <h2>Upcoming Tournaments</h2>
        <ul>
            <li>Tournament 1 - Date - Entry Fee: $10</li>
            <li>Tournament 2 - Date - Entry Fee: $15</li>
            <!-- Add more tournaments here -->
        </ul>
        <form action="payment_gateway_link" method="POST">
            <label for="tournament">Select Tournament</label>
            <select name="tournament" id="tournament">
                <option value="tournament1">Tournament 1</option>
                <option value="tournament2">Tournament 2</option>
                <!-- Add more options here -->
            </select>
            <label for="payment">Payment</label>
            <input type="number" name="payment" placeholder="Enter Amount" required>
            <button type="submit">Join Tournament</button>
        </form>
    </section>

    <section id="contact">
        <h2>Contact Street Level Esports</h2>
        <form action="contact_form_submission_url" method="POST">
            <label for="name">Name</label>
            <input type="text" name="name" id="name" required>
            <label for="email">Email</label>
            <input type="email" name="email" id="email" required>
            <label for="message">Message</label>
            <textarea name="message" id="message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Street Level Esports. All rights reserved.</p>
    </footer>
</body>
</html>
