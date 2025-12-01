# BKM Tekstil - Kurumsal Web Projesi

Bu proje, **BKM Tekstil** için geliştirilmiş; modern, hızlı ve tamamen duyarlı (responsive) bir kurumsal web sitesidir. React ve Vite altyapısı kullanılarak oluşturulmuş olup, Tailwind CSS ile stillendirilmiştir.

## 🚀 Özellikler

*   **Modern Arayüz:** Kullanıcı dostu ve estetik tasarım.
*   **Responsive Tasarım:** Mobil, tablet ve masaüstü cihazlarla tam uyumlu.
*   **Kurumsal Sayfalar:** Hakkımızda, Vizyon & Misyon, Kalite Politikaları.
*   **Ürün ve Marka Tanıtımı:** Ürün kategorileri ve marka vitrinleri.
*   **Medya Galerisi:** Fotoğraf ve video galerileri.
*   **İletişim Formu:** EmailJS entegrasyonu ile çalışan geri bildirim formu.
*   **Yasal Bilgilendirme:** KVKK ve Çerez politikaları sayfaları.
*   **SEO Dostu:** Temiz kod yapısı ve hızlı yükleme süreleri.

## 🛠️ Kullanılan Teknolojiler

Bu projede aşağıdaki teknolojiler ve kütüphaneler kullanılmıştır:

*   **[React](https://react.dev/):** Kullanıcı arayüzü kütüphanesi.
*   **[Vite](https://vitejs.dev/):** Hızlı geliştirme ve derleme aracı.
*   **[Tailwind CSS](https://tailwindcss.com/):** Utility-first CSS framework'ü.
*   **[React Router DOM](https://reactrouter.com/):** Sayfa yönlendirmeleri ve navigasyon.
*   **[Lucide React](https://lucide.dev/):** Modern ve hafif ikon seti.
*   **[EmailJS](https://www.emailjs.com/):** Sunucu gerektirmeden mail gönderme servisi.

## ⚙️ Kurulum ve Çalıştırma

Projeyi yerel ortamınızda çalıştırmak için aşağıdaki adımları izleyin:

### 1. Ön Gereksinimler
Bilgisayarınızda [Node.js](https://nodejs.org/) (v16 veya üzeri) yüklü olmalıdır.

### 2. Projeyi İndirme
Projeyi bilgisayarınıza klonlayın veya indirin:
```bash
git clone https://github.com/kullaniciadi/bkm-tekstil.git
cd BKM_Tekstil
```

### 3. Bağımlılıkları Yükleme
Gerekli paketleri yüklemek için terminalde şu komutu çalıştırın:
```bash
npm install
```

### 4. Projeyi Başlatma
Geliştirme sunucusunu başlatmak için:
```bash
npm run dev
```
Komutu çalıştırdıktan sonra tarayıcınızda **http://localhost:3000** (veya terminalde belirtilen port) adresine giderek siteyi görüntüleyebilirsiniz.

## 📂 Proje Yapısı

```
BKM_Tekstil/
├── public/              # Statik dosyalar (resimler, logolar, videolar)
│   ├── arkaplan/
│   ├── logo/
│   ├── slayt/
│   └── video/
├── src/
│   ├── components/      # Tekrar kullanılabilir bileşenler (Header, Footer, vb.)
│   ├── pages/           # Sayfa tasarımları (AboutPage, ContactPage, vb.)
│   ├── services/        # API ve servis entegrasyonları (emailService.js)
│   ├── App.jsx          # Ana uygulama bileşeni ve route tanımları
│   ├── main.jsx         # Uygulamanın giriş noktası
│   └── index.css        # Global stiller ve Tailwind tanımları
├── index.html           # Ana HTML dosyası
├── package.json         # Proje bağımlılıkları ve scriptler
├── tailwind.config.js   # Tailwind CSS konfigürasyonu
└── vite.config.ts       # Vite konfigürasyonu
```

## 📜 Mevcut Scriptler

`package.json` dosyasında tanımlı komutlar:

*   `npm run dev`: Geliştirme sunucusunu başlatır (Hızlı yenileme özellikli).
*   `npm run build`: Projeyi canlı ortam (production) için derler `dist` klasörüne çıkarır.
*   `npm run preview`: Derlenmiş projeyi yerel olarak önizlemenizi sağlar.
*   `npm run lint`: Kod standartlarını kontrol eder (ESLint).

## 🚀 Canlıya Alma (Deployment)

Projeyi GitHub Pages, Vercel veya Netlify gibi platformlarda yayınlamak için:

1.  `npm run build` komutunu çalıştırın.
2.  Oluşan `dist` klasörünün içeriğini sunucunuza yükleyin.

## 📞 İletişim

Herhangi bir soru veya öneriniz için proje yetkilisi ile iletişime geçebilirsiniz.

---
*BKM Tekstil © 2025 - Tüm Hakları Saklıdır.*

