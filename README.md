# Lezzetli Tarifler

Mobil uyumlu, Türkçe tarif keşif sitesi. Ana sayfa, tarif kategorileri, arama ve filtreleme, tarif detayları, Recipe/Website yapılandırılmış verisi ve tarayıcıda çalışan basit içerik yönetimi içerir.

## Başlangıç

Projeyi GitHub Pages ile yayınlayabilir veya `index.html` dosyasını bir web sunucusunda servis edebilirsiniz. Derleme adımı ya da bağımlılık kurulumu gerekmez.

## Özellikler

- Responsive, mobil öncelikli arayüz ve Türkçe içerik
- Kategori filtreleri ve tarif/malzeme araması
- Adım adım tarif detayları, malzeme listeleri ve porsiyon bilgileri
- Başlık ve açıklama meta etiketleri, Open Graph ve JSON-LD `WebSite` / `Recipe` şemaları
- Yönetim panelinden tarif ekleme, düzenleme ve silme
- Yönetim paneli verileri `localStorage` üzerinde saklanır

## Yönetim paneli hakkında

Bu repo, backend gerektirmeyen statik bir prototiptir. Tarif yönetimi yalnızca aynı tarayıcıda saklanır; gerçek çok kullanıcılı yönetim, kalıcı merkezi depolama ve kimlik doğrulama sağlamaz. Üretim ortamında yönetim panelini güvenli bir API/veritabanı ve kimlik doğrulama katmanına bağlayın.

## Yayınlama

GitHub deposunda **Settings → Pages** bölümünden `main` dalının kök dizinini seçerek GitHub Pages'i etkinleştirin. Özel alan adı kullanıyorsanız site adresini sitemap ve canonical URL yapılandırmasına ekleyin.
