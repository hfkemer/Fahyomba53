\# FAHYOMBA - Görev Yönetim Sistemi



Modern görev yönetimi ve atama sistemi. Admin, Müdür ve Öğretmenlerin görevleri yönetebileceği platform.



\## Özellikler



✨ \*\*Görev Yönetimi\*\* - Müdürler tarafından görev oluşturma ve atama

✨ \*\*Öğretmen Rosteri\*\* - Global olarak görünür tüm öğretmen listesi

✨ \*\*Profil Fotoğrafı\*\* - JPG formatında profil resimleri yükleme

✨ \*\*Email Bildirimleri\*\* - Resend ile gerçek zamanlı bildirimler

✨ \*\*Admin Panel\*\* - Tüm kullanıcıları ve aktiviteleri izleme

✨ \*\*Şifre Sıfırlama\*\* - Admin tarafından güvenli şifre sıfırlama

✨ \*\*Kalıcı Veri\*\* - Supabase ile veritabanı yönetimi



\## Teknolojiler



\- \*\*Frontend\*\*: React 18 + TypeScript + Tailwind CSS

\- \*\*Backend\*\*: Supabase (PostgreSQL + Auth + Storage)

\- \*\*Email\*\*: Resend (ücretsiz transactional email)

\- \*\*Hosting\*\*: Netlify

\- \*\*Icons\*\*: Lucide React



\## Kurulum



```bash

\# Bağımlılıkları yükle

npm install



\# Geliştirme sunucusunu başlat

npm run dev



\# Production build yap

npm run build

```



\## Giriş Bilgileri



| Rol | Kullanıcı Adı | Şifre |

|-----|---|---|

| Admin | `hfkysd.53` | `admin2026` |

| Müdür | `yeb` | `531453` |

| Öğretmen | Kayıt yap | Şifre belirle |



\## Ortam Değişkenleri



`.env` dosyasında ayarla:



```

VITE\_SUPABASE\_URL=https://your-project.supabase.co

VITE\_SUPABASE\_ANON\_KEY=your-anon-key

```



\## Netlify Deployment



1\. GitHub repository'ni bağla

2\. Build command: `npm run build`

3\. Publish directory: `dist`

4\. Environment variables ekle



\## Resend Email Kurulumu



1\. https://resend.com adresinde hesap oluştur

2\. API key al

3\. Supabase Edge Functions secrets'e `RESEND\_API\_KEY` ekle



\## Lisans



Tüm hakları saklıdır © 2026



