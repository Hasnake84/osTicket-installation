<img width="884" alt="image" src="https://github.com/Hasnake84/osTicket-installation/assets/114637978/d2f9aa9f-77cf-4e39-8897-ec6f6ee9f69a">

# osTicket-installation
## Installation Steps
  -  Enable CGI and Common HTTP Features in Windows IIS (Internet Information Services)
     
     Control Panel > Programs > Turn Windows features on or off

     <a href="https://imgur.com/zMd0C33"><img src="https://i.imgur.com//zMd0C33.png" title="source: imgur.com" /></a>

  -  Install PHP Manager for IIS (Rewrite Module)
  -  Create a directory on C:\PHP
  - From the installation files unzip the contents into C:\PHP
  - Install Visual C++ Redistributable from  VC_redist.x86.exe
  - Register PHP from within IIS
  - Reload IIS (Open IIS, Stop and Start the server)

     <a href="https://imgur.com/EJjQH05"><img src="https://i.imgur.com//EJjQH05.png" title="source: imgur.com" /></a>

  - Install MySQL Server
    Typical Setup > Launch Configuration Wizard > Standard Configuration 
 

  - # Install osTicket v1.15.8
      - Download osTicket from the Installation Files Folder
      - Extract and copy upload folder to c:\inetpub\wwwroot
      - Within c:\inetpub\wwwroot, Rename upload to osTicket

     <a href="https://imgur.com/2SCxdKd"><img src="https://i.imgur.com//2SCxdKd.png" title="source: imgur.com" /></a>
   - Sites > Default > osTicket > “Browse *:80”

     <a href="https://imgur.com/4GvM9Zw"><img src="https://i.imgur.com//4GvM9Zw.png" title="source: imgur.com" /></a>
  - Rename: ost-config.php
     - From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
     - To: C:\inetpub\wwwroot\osTicket\include\ost-config.php
 - Install HeidiSQL
   - Open Heidi SQL
   - New session, root/Password
   - Connect to the session
   - Create a database called “osTicket”
   - Continue Setting up osticket in the browser
     - MySQL Database: osTicket
     - MySQL Username: root
     - MySQL Password: Password
     - “Install Now”










