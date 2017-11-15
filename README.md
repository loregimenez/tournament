------------
 TOURNAMENT
------------

This project is a database schema to store the game matches between players.
It's a Python module that uses the PostgreSQL database to keep track of players and matches in a game tournament.

It is needed a basic knowledge of Vagrant, Python and PSQL to run this project.

To be installed:
- Python v 2.7. Download: https://www.python.org/downloads/
- Vagrant. Download: https://www.vagrantup.com/downloads.html
- VirtualBox. Download: https://www.virtualbox.org/

To run the App:

1. Unzip de file
2. Open the terminal
3. Go to Vagrant directory: cd vagrant
4. Run the vagrant up command
5. Run the vagrant ssh command
6. Go to the project directory
7. Open up a new terminal
8. Run vagrant ssh
9. Type PSQL and hit enter
10. To set up the database: psql -f tournament.sql;
11. Type 'psql tournament' and hit enter
12. To see the database run \dt. It will print the database.
13. Go back to the original terminal
14. To test the program: python tournament_test.py

If it's done correctly, it should show a message "Success! All tests pass!"
