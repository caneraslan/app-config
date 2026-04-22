# App Config Manager ⚙️

Bu depo, geliştirmiş olduğum **English Learn With Words** mobil uygulamasının dinamik yapılandırma dosyalarını ve uygulama içi kontrol mekanizmalarını barındırır. Uygulamanın ayarlarını merkezi bir noktadan yönetmek ve güncellemeleri kontrol etmek amacıyla oluşturulmuştur.

---

## ✨ İşlevler

* **Remote Config:** Uygulama içerisindeki belirli parametreleri (dil seçenekleri, API uç noktaları vb.) uygulama markete yeni bir sürüm çıkmadan güncelleyebilme.
* **Sürüm Kontrolü (Version Check):** Uygulamanın en güncel sürüm bilgilerini tutarak kullanıcıları zorunlu veya önerilen güncellemelere yönlendirme.
* **Dinamik İçerik Yönetimi:** Uygulama içi duyurular veya kelime listeleri gibi değişken verilerin merkezi yönetimi.

---

## 🛠️ Teknik Detaylar

* **Merkezi Yönetim:** Ayarlar JSON formatında tutulmakta olup, uygulama çalışma zamanında (runtime) bu verileri çekerek kendini yapılandırır.
* **Modüler Yapı:** Farklı ortamlar (development, production) için kolayca genişletilebilir yapı.
* **Bakım Kolaylığı:** Kod değişikliği gerektirmeyen parametre güncellemeleri sayesinde hızlı müdahale imkanı.

---

## 📂 İçerik

* `config.json` (veya ilgili dosyalar): Uygulamanın davranışını belirleyen anahtar-değer çiftleri.
* `version.json`: Uygulama sürüm takibi ve güncelleme tetikleyicileri.

---

## 🚀 Entegrasyon

Bu yapılandırma merkezi, **React Native (Expo)** ile geliştirilen mobil uygulama ile entegre çalışacak şekilde tasarlanmıştır. Uygulama her açılışta veya belirli aralıklarla bu repo üzerinden güncel konfigürasyonu kontrol eder.

---

## 📫 İletişim

Caner ASLAN - [caneraslanm@gmail.com](mailto:caneraslanm@gmail.com)
