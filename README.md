# St10448886-PROG5121_POE_Part2
PROG5121 POE Part 2

QuickChat is a Java desktop app that lets a user register, log in, and send messages using simple pop-up windows (JOptionPane). The program is made of three main parts:

Login – Handles user registration and checks if the username (must have an underscore and max 5 characters), password (at least 8 characters, one capital, one number, one special character), and cellphone number (must start with +27 and be 13 digits) are valid.

Message – Lets you send messages after logging in. It generates a unique 10-digit message ID, checks recipient phone numbers, creates a message hash, and gives you the choice to send, disregard, or store the message in a messages.json file. It also keeps track of how many messages you’ve sent in the current session.

Main – Runs the app. First, it welcomes you, helps you register and log in, and then shows you a menu where you can send messages, view a placeholder for message history (coming soon), or quit the app.

In short, after registering and logging in, you can send messages, track how many you’ve sent, and store them in a file. It’s a basic but functional app, useful for practicing Java input handling, validation, and file storage.
