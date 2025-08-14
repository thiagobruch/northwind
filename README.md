1 - Create a folder to store the data

2 - Save the docker-compose.yml file inside the folder and run "docker compose up -d"
It will create 2 Containers (northwind-db-1 and northwind-web-1)

3 - Go to folder ./html just created, create a subfolder (i.e. (./html/nw)

4 - Extract the content of the Northwind_App_With_Email.zip inside the subfolder

5 - Change the permissions with the command (chmod 777 -R .)

6 - Go to http://your-host:8087 click on continue and proceed with the install

7 - Open the Database using a DB Client (i.e. DBeaver).

8 - Restore the Database using the dump-Northwind.tar

The Northwind App with Email Field is ready to use
User/Pass admin/admin
