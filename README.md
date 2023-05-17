
# SİMPRA_HOMEWORK2

Projeyi ayağa kaldırmak için:
1. SimpraHomewroks.Apı -> appsettings.json -> MsSQL tanımlamasındaki ‘Server’ bilgisini kendiMsSQL server adı ile değiştiriniz. 
2. Package Manager Console -> Default Project -> SimpraHomework.Repository seçilir. 
3. Add-migration v1.1 veya EntityFramework6\Add-Migration initial komutu girilerek migration oluşturulur. 
4. Update-database komutu ile MsSQL’de ‘SimraHomework2Db’ ve tablo oluşturulur.



## Proje detay ve içerikleri: 
1.Projenin Database’i  MsSQL kullanılılarak geliştirildi.
2.Projenin backend’i ‘Web API’ projesi olup, NLayer Architecture yapısına uygun olarak dizayn edildi.
3.RESTAPI PRINCIPLES VE CRUD Operations kullanıldı. (Model kullanarak GetAll, GetById , Put , Post , Delete methodlarini icen bir controller implement edildi. )
4.Generic Repository Design Pattern ve Unit of Work Design Pattern uygulandı.(Where sartini implement edildi.)
5.Fluent  Validation ve AutoMapper kullanıldı.
6.CustomResponse ve Middleware kullanıldı.
7.Put ve Post apilerin de model validation hazirlandı.(StaffCreateRequestValidatior, StaffUpdateRequestValidator )
8.SOLID Prensipleri.

## Kullanılan Teknolojiler: IDE : Visual Studio 2022 DB: MsSQL Languages: C#, Frameworks: .NET 6, ASP.NetCore, 
EntityFramework6, EFCore/SqlServer/, DependencyInjection Abstractions 
