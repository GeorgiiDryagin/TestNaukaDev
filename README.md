# TestNaukaDev
SQLServer_UserDataViewer

Для взаимодействия приложения с вашим сервером и его клиентом, необходимо в файле App.config изменить строку 10, которая выглядит так:
<add name="DBConnectionString" connectionString="Data Source=LAPTOP-RACCOON\SVR; Initial Catalog=TestNauka; Integrated Security=True" providerName="System.Data.SqlClient"/>
В этой строке вместо LAPTOP-RACCOON\SVR необходимо указать имя вашего сервера, а вместо "System.Data.SqlClient" - имя вашего клиента связи с сервером.


In order for the app to interact with your server and its client, you need to change line 10 in the App.config file, which looks like this:
<add name="DBConnectionString" connectionString="Data Source=LAPTOP-RACCOON\SVR; Initial Catalog=TestNauka; Integrated Security=True" providerName="System.Data.SqlClient"/>
In this line, instead of LAPTOP-RACCOON\SVR, you must specify the name of your server, and instead of "System.Data.SqlClient" - the name of your server connection client.
