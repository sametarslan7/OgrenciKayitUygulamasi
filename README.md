# ASP.NET MVC Proje Açıklaması

Visual Studio editörü üzerinden **ASP.Net Web Application (.NET Framework)** seçerek projeyi **MVC** formatında oluşturun.

---

Daha sonra yapacağınız ilk iş, `App_Data` klasörüne sağ tıklayarak `Add New Item` diyerek **SQL Server Database** oluşturmaktır.

Oluşturduğunuz veritabanının içine, projenizdeki tabloları ekleyip veri tabanınızı oluşturun.

Ardından, `Model` klasöründen `Add New Item` diyerek yeni bir **ADO.NET EntityFramework** oluşturun. Database olarak, bilgisayarınızdaki SQL Server Management Studio IDE'sini veya Visual Studio içinde oluşturduğunuz veritabanını seçebilirsiniz. Ben, doğrudan oluşturduğumuz veritabanını seçtim.

Bu işlemle, `Model` klasöründe model yapınız oluşmuş olacak. Artık `Controller` kısmına geçebilirsiniz.

---

`Controllers` klasörüne yeni bir **Controller** ekleyin (`Add Controller`). Daha sonra çıkan ekranda **MVC 5 Controller with views, using Entity Framework** seçeneğini seçin.

> **Not:** Burada "MVC 5 Controller Empty" seçeneğini seçip tüm sorguları kendiniz de yazabilirsiniz; ancak seçtiğimiz diğer seçenek, bu işlemleri otomatik olarak tablomuzdan yapacaktır.

Sonrasında, **Model Class**'tan oluşturduğunuz modeli seçin ve **DataContext Class**'tan da oluşturduğunuz `databaseEntities`'i seçin.

Proje bu haliyle çalışır durumda olacak. Tarayıcıda çalıştırıp çeşitli işlemleri artık yapabilirsiniz.
