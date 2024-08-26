```html
<!DOCTYPE html>
<html lang="tr">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASP.NET MVC Proje Açıklaması</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 800px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }

        p {
            margin-bottom: 15px;
            color: #555;
        }

        code {
            background: #eee;
            padding: 2px 5px;
            border-radius: 4px;
            font-size: 14px;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>ASP.NET MVC Proje Açıklaması</h1>
        <p>Visual Studio editörü üzerinden <strong>ASP.Net Web Application (.NET Framework)</strong> seçerek projeyi
            <strong>MVC</strong> formatında oluşturalım.</p>

        <p>Daha sonra yapacağımız ilk iş, <code>App_Data</code> klasörüne sağ tıklayarak <code>Add New Item</code>
            diyerek <strong>SQL Server Database</strong> oluşturmaktır.</p>

        <p>Oluşturduğumuz veritabanının içine, projemizdeki tabloları ekleyip veri tabanımızı oluşturuyoruz.</p>

        <p>Ardından <code>Model</code> klasöründen <code>Add New Item</code> diyerek yeni bir <strong>ADO.NET
                EntityFramework</strong> oluşturuyoruz. Database olarak, bilgisayarımızdaki SQL Server Management Studio
            IDE'sini veya Visual Studio içinde oluşturduğumuz veritabanını seçebiliyoruz. Ben, doğrudan oluşturduğumuz
            veritabanını seçtim.</p>

        <p>Böylelikle <code>Model</code> klasöründe model yapımız oluştu. Artık <code>Controller</code> kısmına
            geçebiliriz.</p>

        <p><code>Controllers</code> klasörüne yeni bir <strong>Controller</strong> ekliyoruz (<code>Add
                Controller</code>). Daha sonra çıkan ekranda <strong>MVC 5 Controller with views, using Entity
                Framework</strong> seçeneğini seçiyoruz.</p>

        <p><em>Burada "MVC 5 Controller Empty" seçeneğini seçip tüm sorguları kendimiz de yazabilirdik; ancak seçtiğimiz
                diğer seçenek, bu işlemleri otomatik olarak tablomuzdan yapıyor olacak.</em></p>

        <p>Daha sonra <strong>Model Class</strong>'tan oluşturduğumuz modeli seçiyoruz ve <strong>DataContext
                Class</strong>'tan da oluşturduğumuz <code>databaseEntities</code>'i seçiyoruz.</p>

        <p>Proje bu haliyle çalışır durumda oluyor. Tarayıcıda çalıştırıp çeşitli işlemleri artık yapabiliriz.</p>
    </div>
</body>

</html>
```
