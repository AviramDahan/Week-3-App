# Weight Tracker App - Web Application

* The application source code available for download in this Github repository: https://github.com/sela-rhinops/bootcamp-app.

* 2 Ubuntu Servers: 
1. Database: Configure the database server (postgresql)
2. Application: Configure the web server (install prerequisites)

* Creating a Web Application Register Using Okta (application uses Okta for authentication)

* Deploy the application (developed on nodejs)

* application keeps running even if any of the servers is restarted (PM2 Setup)

![image](https://user-images.githubusercontent.com/89352211/139874527-1bc47c56-2668-43f4-bdb3-1d97aa8b92d7.png)

# Web Application

Project Visual Studio 19:

Project settings

* ASP.NET Core Web App template
* .NET 5
* NuGet Packages: Newtonsoft.Json

# Rebuild Solution + Publish To Folder 
![image](https://imgur.com/WCqKjsd.png)

# Website On Your Microsoft Machine

* Add IIS to your windows server
* Create a new IIS application pool
* Create website (use port 5100 and your new application pool)
* Copy your website to your windows server
* Browse to “http://localhost:5100/” from your microsoft machine
