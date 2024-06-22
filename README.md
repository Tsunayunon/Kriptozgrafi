# Kriptozgrafi

### Proje Açıklaması
Bu proje, kullanıcıların çeşitli şifreleme türlerini (simetrik, asimetrik ve hibrit) kullanarak mesajları şifreleyip çözmelerine olanak tanıyan bir şifreleme uygulamasıdır. Uygulama, kullanıcı yönetimi ve şifreleme yönetimi özelliklerini içerir.

### Dosya ve Klasör Yapısı
- `asymmetric.py`: Asimetrik şifreleme ve çözme fonksiyonlarını içerir.
- `symmetric.py`: Simetrik şifreleme ve çözme fonksiyonlarını içerir.
- `hybrid.py`: Hibrit şifreleme ve çözme fonksiyonlarını içerir.
- `database.py`: Kullanıcı ve şifreleme bilgilerini saklamak ve yönetmek için veritabanı fonksiyonlarını içerir.
- `main.py`: Kullanıcı arayüzü ve uygulamanın ana fonksiyonlarını içerir.

### Kullanılan Kütüphaneler
- `cryptography`: Asimetrik ve hibrit şifreleme işlemleri için kullanılır.
- `pycryptodome`: Simetrik şifreleme işlemleri için kullanılır.
- `tkinter`: Kullanıcı arayüzü oluşturmak için kullanılır.
- `csv`: Veritabanı işlemleri için kullanılır.
- `os`: Dosya ve klasör işlemleri için kullanılır.
- `logging`: Hata ve işlem takibi için kullanılır.

### Better Comments Uzantısı
Proje kodunda daha iyi yorumlar yazmak için Better Comments uzantısı kullanılmıştır. Bu uzantı, kodun anlaşılabilirliğini artırmak için farklı türde yorumlar yapmanıza olanak tanır.

- **Ad**: Better Comments
- **Kimlik**: aaron-bond.better-comments
- **Açıklama**: Kod yorumlamanızı uyarılar, bilgi amaçlı notlar, TODO'lar ve daha fazlasıyla geliştirir!
- **Sürüm**: 3.0.2
- **Yayımcı**: Aaron Bond
- **VS Market bağlantısı**: [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

### Kurulum ve Çalıştırma
1. Proje dosyalarını indirin ve bir dizine çıkarın.
2. Gerekli Python kütüphanelerini yükleyin:
   ```bash
   pip install cryptography pycryptodome
   ```
3. `main.py` dosyasını çalıştırarak uygulamayı başlatın:
   ```bash
   python main.py
   ```

### Kullanım
- **Kayıt Olma**: Yeni kullanıcı oluşturabilir ve kayıt olabilirsiniz.
- **Giriş Yapma**: Mevcut kullanıcı ile giriş yapabilirsiniz.
- **Mesaj Şifreleme**: Farklı şifreleme türlerini kullanarak mesajları şifreleyebilirsiniz.
- **Mesaj Deşifre Etme**: Daha önce şifrelenmiş mesajları çözebilirsiniz.
- **Kullanıcı Yönetimi**: Admin paneli üzerinden kullanıcıları yönetebilirsiniz.

### Yazarlar ve Katkıda Bulunanlar
- [Adınız] - Proje Geliştiricisi

Herhangi bir sorun veya geri bildiriminiz için lütfen bizimle iletişime geçin.

### Lisans
Bu proje MIT Lisansı ile lisanslanmıştır - daha fazla bilgi için `LICENSE` dosyasına bakınız.

Bu README dosyası, projenin genel yapısını, kullanılan kütüphaneleri ve temel kullanım talimatlarını içermektedir. Projeyi geliştiren ve katkıda bulunanlar için teşekkür ederiz.
