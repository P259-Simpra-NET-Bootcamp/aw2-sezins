
#SİMPRA_HOMEWORK2

Projeyi ayağa kaldırmak için:1. SimpraHomewroks.Apı -> appsettings.json -> MsSQL tanımlamasındaki ‘Server’ bilgisini kendiMsSQL server adı ile değiştiriniz. 
2. Package Manager Console -> Default Project -> SimpraHomework.Repository seçilir. 
3. Add-migration v1.1 veya EntityFramework6\Add-Migration initial komutu girilerek migration oluşturulur. 
4. Update-database komutu ile MsSQL’de ‘SimraHomework2Db’ ve tablo oluşturulur.



##Proje detay ve içerikleri: 
Projenin Database’i  MsSQL kullanılılarak geliştirildi.
Projenin backend’i ‘Web API’ projesi olup, NLayer Architecture yapısına uygun olarak dizayn edildi.
RESTAPI PRINCIPLES VE CRUD Operations kullanıldı. (Model kullanarak GetAll, GetById , Put , Post , Delete methodlarini icen bir controller implement edildi. )
Generic Repository Design Pattern ve Unit of Work Design Pattern uygulandı.(Where sartini implement edildi.)
Fluent  Validation ve AutoMapper kullanıldı.
CustomResponse ve Middleware kullanıldı.
Put ve Post apilerin de model validation hazirlandı.(StaffCreateRequestValidatior, StaffUpdateRequestValidator )

##SOLID Prensipleri.

Kullanılan Teknolojiler: IDE : Visual Studio 2022 DB: MsSQL Languages: C#, Frameworks: .NET 6, ASP.NetCore, 
EntityFramework6, EFCore/SqlServer/, DependencyInjection Abstractions 
