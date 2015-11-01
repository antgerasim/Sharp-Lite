This is an non-functional UPGRADE of Billy McCafferty's SharpLite reference architecure, to be runned on VISUAL STUDIO 2013 MVC4. 

TO OPEN SAMPLE PROJECT "MyStore":

1) CREATE EMPTY (MS SQL Server Express) DATABASE AND NAME IT "SharpLiteMyStore"
2) ADJUST CONNECTIONSTRINGS IN:
	- MyStore.Web/Web.config
	- Mystore.Tests/App.config
	
    <add name="MyStoreConnectionString" connectionString="Data Source=.\SQLEXPRESS;Initial Catalog=SharpLiteMyStore;Integrated Security=True" />
	 
3) Run CanGenerateDatabaseSchema() and copy the SQL commands as generated output from Resharper's UnitTestExplorer. Execute SQL commands on your Database (SharpLiteMyStore).

Attention: Templify sets the Project Url Port (http://localhost:55462/) for every generated project! Changes this to avoid clashes and confusions with other SharpLite projects. 
PUSH IT!

-----------------------------------

links:

http://www.codeproject.com/Articles/285158/Ssharparp-Lite-The-Basics

http://www.codeproject.com/Articles/13390/NHibernate-Best-Practices-with-ASP-NET-nd-Ed

http://devlicio.us/blogs/billy_mccafferty/archive/2012/08/02/greenfield-development-with-asp-net-mvc-amp-s-arp-lite-introduction.aspx

http://devlicio.us/blogs/billy_mccafferty/archive/2012/08/24/greenfield-development-with-asp-net-mvc-amp-s-arp-lite-day-1.aspx

http://devlicio.us/blogs/billy_mccafferty/archive/2012/10/12/greenfield-development-with-asp-net-mvc-amp-s-arp-lite-day-2.aspx

http://devlicio.us/blogs/billy_mccafferty/archive/2012/10/16/greenfield-development-with-asp-net-mvc-amp-s-arp-lite-day-3.aspx
