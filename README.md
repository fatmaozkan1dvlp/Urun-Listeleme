# 🧣 Vakko Şal/Eşarp Koleksiyonu Veritabanı Projesi (MVC Pattern)

> Bu repository, popüler bir şal/eşarp markası olan *Vakko'nun ürün kataloglarını simüle etmek ve bu verileri **Model-View-Controller (MVC)* mimarisi kullanarak yönetmek amacıyla geliştirdiğim bir öğrenme projesidir.

## 🌟 Proje Amacı

Bu proje, bir stajyer adayı olarak aşağıdaki kilit yetkinliklerimi pratik etmek ve sergilemek için hazırlanmıştır:

1.  *MVC Mimarisi Uygulaması:* Modern yazılım geliştirmede standart olan MVC desenini, bir veri listeleme ve yönetim uygulamasının omurgası olarak kullanmak.
    
2.  *Veritabanı Yönetimi:* Temel seviye bir veritabanını bir C# projesiyle entegre ederek *CRUD* (Create, Read, Update, Delete) operasyonlarının *R* (Read - Okuma) ve *L* (Listeleme) kısımlarını uygulamak.
3.  *Domain/İş Mantığı Modellemesi:* Gerçek bir ürün kataloğunun (Şal/Eşarp) özelliklerini (desen, renk, malzeme) yazılıma dökerek nesne yönelimli programlama (OOP) prensiplerini pekiştirmek.

## 💻 Teknolojiler

Bu projenin geliştirme sürecinde kullandığım temel teknolojiler ve kütüphaneler:

* Programlama Dili: C#
* Platform: .NET 
* Mimarisi: Model-View-Controller (MVC)
* Veri Depolama Simülasyonu: Basit C# Sınıfları ve SQL Server 
* IDE: Microsoft Visual Studio

## ⚙ Proje Yapısı ve Kapsam

Projenin temel olarak aşağıdaki modülleri veya işlevleri içermesi planlanmıştır:

### 1. Model Katmanı

* Scarf (Şal/Eşarp) sınıfı, Vakko ürünlerinin temel özelliklerini içerir.
* Bu katman, verilerin depolanma mantığını içerir.

### 2. Controller Katmanı

* Index(): Tüm şal/eşarp modellerini listeleyen ana aksiyon.
* Details(int id): Seçilen modelin detaylarını gösteren aksiyon.
* *Kapsam:* Şu an için odak, veriyi başarıyla *çekmek (Read)* ve *listelemektir*.

### 3. View Katmanı 

* Şal/Eşarp listesinin tablo veya kart görünümünde sunulması.
* Temel filtreleme/sıralama özelliklerinin basit HTML ile gösterilmesi