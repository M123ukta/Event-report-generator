# Setup Instructions

1. Import the database:
   - Open phpMyAdmin
   - Create a new database
   - Import database/mydatabase.sql

2. Update connect.php with your local DB credentials:
   $conn = new mysqli("localhost", "root", "", "mydatabase");