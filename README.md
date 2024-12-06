(https://scontent-iad3-1.xx.fbcdn.net/v/t31.0-8/12045296_896994067005023_5505146103193104549_o.jpg?oh=4afd029c1486604d29f672d76becb8bc&oe=5921F70A " Warehouse inventory system ")

1. Download the latest version with git (`git clone https://github.com/Dawndroid/warehouse-inventory-system.git`)

2. Import/load oswa_inv.sql into your mysql database. This should set up the basic structure of the database system.

3. Modify the includes/config.php and change the variables to match your host, database, username and passwords.

4. Change all Folder permission inside uploads folder either add them to group call `www` if available or `777`.

5. Then logging by typing **username** and **password**:


   Administrator        | Special User           | Default User
   ---------------------| -----------------------| -------------------
   **Username** : admin | **Username** : special | **Username** : user
   **Password** : admin | **Password** : special | **Password** : user