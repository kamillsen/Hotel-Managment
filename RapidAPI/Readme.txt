 C# HotelProject.EntityLayer

	=> Concrete
		Tablolar


 Paketleri Yükledik
	* Microsoft.EntityFrameworkCore
	* Microsoft.EntityFrameworkCore.Design
	* Microsoft.EntityFrameworkCore.SqlServer
	* Microsoft.EntityFrameworkCore.Tools


 Referans haritasý çýkarttýk 

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
			Bu dosya DB ile baðlantý kurmamýzý saðlar.



* Kullanýcý adý - þifre
semih01 - 123456aA*


141.video 
Referance Loop Handling
services.AddControllers().AddNewtonsoftJson(options =>
            options.SerializerSettings.ReferenceLoopHandling = Newtonsoft.Json.ReferenceLoopHandling.Ignore);
