 C# HotelProject.EntityLayer

	=> Concrete
		Tablolar


 Paketleri Y�kledik
	* Microsoft.EntityFrameworkCore
	* Microsoft.EntityFrameworkCore.Design
	* Microsoft.EntityFrameworkCore.SqlServer
	* Microsoft.EntityFrameworkCore.Tools


 Referans haritas� ��kartt�k 

	C# HotelProject.BusinessLayer
		* HotelProject.DataAccessLayer
		* HotelProject.EntityLayer

    C# HotelProject.AccessLayer
		* HotelProject.EntityLayer

    C# HotelProject.DtoLayer
		* HotelProject.EntityLayer

	C# HotelProject.WebApi
		* HotelProject.EntityLayer
		* HotelProject.DtoLayer
		* HotelProject.DataAccessLayer
		* HotelProject.BusinessLayer

 


 C# HotelProject.DataAccsessLayer

	=> Concrete
		Context.cs 
			Bu dosya DB ile ba�lant� kurmam�z� sa�lar.



* Kullan�c� ad� - �ifre
semih01 - 123456aA*


141.video 
Referance Loop Handling
services.AddControllers().AddNewtonsoftJson(options =>
            options.SerializerSettings.ReferenceLoopHandling = Newtonsoft.Json.ReferenceLoopHandling.Ignore);


projeyi github a g�nder.