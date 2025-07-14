


![image](https://github.com/user-attachments/assets/4b1b06a6-75a3-4734-9c40-642072fa2451)


Katmanlı Mimari kullanılarak clean code prensiplerine uygun yapı tasarlandı. Kullanıcı arayüzünde kategori bazlı ürün listeleme, filtreleme ve satın alma simülasyonu, admin panelinde ürün, kategori ve kullanıcı yönetimi, CRUD işlemleri ve Bootstrap 5 ile duyarlı (responsive) ve modern tasarım entegre edildi.

(A structure was designed in accordance with clean code principles using Layered Architecture. Category-based product listing, filtering and purchasing simulation in the user interface, product, category and user management in the admin panel, CRUD operations and responsive and modern design were integrated with Bootstrap 5.)


## Kullanılan Teknolojiler

ASP.NET Core MVC -	Web uygulama çatısı

Entity Framework Core -	ORM ve veri erişim katmanı

SQLite / SQL Server -	Veritabanı

Razor Pages -	View katmanı

Bootstrap -	Responsive arayüz tasarımı

## Özellikler

Ürün listeleme ve detay sayfası

 Kullanıcı ve admin girişi

 Kategori filtreleme

 Admin paneli üzerinden:
 
   A. Ürün oluşturma, düzenleme ve silme
   
   B. Kategori yönetimi
   
  Entity Framework Core ile veritabanı işlemleri
  
  Razor View ile sayfa yapısı

  Veritabanı desteği (SQL Server, SQLite)


  ```
git clone https://github.com/erenmulkoglu96/store-app-aspnet-core-mvc.git

```

## Project Commands
```csharp
dotnet new sln -o Store
dotnet new --list
dotnet new web -f net6.0 --output StoreApp
dotnet sln .\Store\ add .\Store\StoreApp\
dotnet sln .\Store list
```

## Package Management
```csharp
dotnet add package <packagename> --version 6.0.0
dotnet add Microsoft.EntityFramework.Core --version 6.0.0
dotnet add Microsoft.EntityFramework.Core.Sqlite --version 6.0.0
dotnet add Microsoft.EntityFramework.Core.Design --version 6.0.0
dotnet list package
```

## dotnet Tool
```csharp
dotnet tool list
dotnet tool list -g
```

## Migrations
```csharp
dotnet ef migrations add <name>
dotnet ef database update
```

```sqlite
.help
.show
.system cls
.system dir
.mode list
.mode box
SELECT * FROM Products;
```
