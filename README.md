# Kitaplık Projesi

Bu proje, kitapları yönetmek için kullanılan basit bir Windows Forms uygulamasıdır. Uygulama, Microsoft Access veritabanı ile entegre çalışarak kitapları listeleme, ekleme, silme, güncelleme ve arama işlemlerini gerçekleştirmektedir.

## Özellikler

- **Kitap Listeleme:** Veritabanındaki tüm kitapları `DataGridView` üzerinde listeleme.
- **Kitap Ekleme:** Yeni kitapları sisteme ekleme.
- **Kitap Silme:** Var olan kitapları sistemden silme.
- **Kitap Güncelleme:** Var olan kitapların bilgilerini güncelleme.
- **Kitap Arama:** Kitap adı ile arama yaparak belirli kitapları bulma.

## Gereksinimler

- .NET Framework 4.0 veya daha yeni bir sürüm.
- Microsoft Access Database Engine (ACE.OLEDB) 12.0.

## Kullanım

1. Uygulamayı başlatın.
2. Kitapları listelemek için `Listele` butonuna tıklayın.
3. Yeni kitap eklemek için `Kaydet` butonuna tıklayın.
4. Kitapları silmek için seçili bir kitabı seçin ve `Sil` butonuna tıklayın.
5. Kitap bilgilerini güncellemek için seçili kitabı düzenleyin ve `Güncelle` butonuna tıklayın.
6. Kitapları aramak için arama kutusuna kitap adını yazın ve `Ara` veya `Bul` butonuna tıklayın.

## Kod Açıklaması

- **Form1.cs:** Ana formu ve veritabanı işlemlerini içerir. Kitapları listeleme, ekleme, silme, güncelleme ve arama işlemlerini sağlar.
- **OleDbConnection:** Microsoft Access veritabanı ile bağlantı sağlar.
- **OleDbCommand:** SQL komutlarını çalıştırır.
- **DataGridView:** Kitap verilerini tablo şeklinde gösterir.
