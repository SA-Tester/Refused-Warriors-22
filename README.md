# Refused-Warriors-22

# Deploying the Application in your local machine
1. Install latest python version from https://www.python.org/downloads/
2. Install tensorflow, numpy, matplotlib, wordcloud, newspaper, PIL, skimage, mysql.connector and flask modules using pip<br>
<ul>
  <li>Intall Tnesorflow - pip install tensorflow</li>
  <li>Install Numpy - pip install numpy</li>
  <li>Install Matplotlib - pip install matplotlib</li>
  ... and so on
</ul>

3. Install mysql server using https://www.mysql.com/downloads/
4. Restore the DB structure in DB folder to your machine
<ul>
  <li>Enter to mysql console: mysql -u[username] -p[password]</li>
  <li>Create a database named MarsImagery: create database MarsImagery;</li>
  <li>Exit from the mysql console: quit</li>
  <li>Restore the .sql file: mysql -u[username] -p[password] MarsImagery < [local path to backupfile]</li>
</ul>
