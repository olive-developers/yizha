# yizha

1. install postgres, if you are using wsl this instruction will work for you: https://docs.microsoft.com/en-us/windows/wsl/tutorials/wsl-database

2. Create a new role in the postgres database:
  2.1 run: sudo service postgresql start
  2.2 run: sudo -u postgres psql
  2.3 run: create role your_name with createdb login password 'password';
(write \q to exit)

3. Change the username and password in the config/database.yml file

4. run: sudo apt install postgresql-contrib libpq-dev 

5. run: bin/setup
