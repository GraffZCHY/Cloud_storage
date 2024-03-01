# My-cloud

### Attention
After pulling the project to the local location, you need to modify the configuration information

- `application.yml`：Modify data source information and email server information
- `config.DruidConfig`：Change the username and password for Druid login
- `utils.FtpUtil`：Modify the basic information of the FTP server
- `utils.MailUtils`：Modifying the sender's email on the email serve
- `resources.qqconnectconfig.properties`：Modify`app_ID`and `app_KEY`and `redirect_URI`

### Here's the translation of the main features of the project into English:

-User email registration, verification code validation, and user login.
-Integration of QQ third-party login to provide users with a convenient login channel.
-Allows the upload of temporary files that meet certain conditions without registering an account, but these are only valid for 4 hours.
-File management including upload, download, rename, delete, view statistics, and categorization.
-Folder management including creation, deletion, and renaming.
-File sharing, supporting sharing methods through links and QR codes.
-Differentiation between ordinary users and administrators, where administrators can modify the usage permissions and cloud storage capacity of ordinary users.

Here's the translation of the technology used in the project:

-Frontend
  HTML, CSS, JavaScript, jQuery
  Bootstrap and various plugins
-Backend
SpringBoot + MyBatis
  EhCache caching
  ThymeLeaf template engine
  Tencent QQ third-party login
  FTP utility class, QR code utility class
-Deployment
  Alibaba Cloud Light Application Server
  Docker environment
  FTP service
  MySQL database
-Links:


HOW TO LOAD IN WITH QQ(https://www.bilibili.com/video/av90710722)


HOW TO DEPLOY SPRINGBOOT APPLICATION(https://www.bilibili.com/video/av88690709)



