[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/iGZu94G3)

# SİMPRA_HOMEWORK2

## Projeyi çalıştırmak için:
1. SimpraHomewroks.Apı -> appsettings.json -> MsSQL tanımlamasındaki ‘Server’ bilgisini kendiMsSQL server adı ile değiştiriniz. 
2. Package Manager Console -> Default Project -> SimpraHomework.Repository seçilir. 
3. Add-migration v1.1 veya EntityFramework6\Add-Migration initial komutu girilerek migration oluşturulur. 
4. Update-database komutu ile MsSQL’de ‘SimraHomework2Db’ ve tablo oluşturulur.



## Proje detay ve içerikleri: 
1. Projenin Database’i  MsSQL kullanılılarak geliştirildi.
2. Projenin backend’i ‘Web API’ projesi olup, NLayer Architecture yapısına uygun olarak dizayn edildi.
3. RESTAPI PRINCIPLES VE CRUD Operations kullanıldı. (Model kullanarak GetAll, GetById , Put , Post , Delete methodlarini icen bir controller implement edildi. )
4. Generic Repository Design Pattern ve Unit of Work Design Pattern uygulandı.(Where sartini implement edildi.)
5. Fluent  Validation ve AutoMapper kullanıldı.
6. CustomResponse ve Middleware kullanıldı.
7. Put ve Post apilerin de model validation hazirlandı.(StaffCreateRequestValidatior, StaffUpdateRequestValidator )
8. SOLID Prensipleri.

## Kullanılan Teknolojiler:
1. IDE : Visual Studio 2022
2.  DB: MsSQL
3.  Languages: C#
4.  Frameworks: .NET 6, ASP.NetCore, EntityFramework6, EFCore/SqlServer/, DependencyInjection Abstractions 
