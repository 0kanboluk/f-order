# f-order
a dormitory football reservation mobile application

## Proje Hakkında
Yurtlardaki halı saha organizasyonlarının geleneksel WhatsApp grupları üzerinden yürütülmesinin yarattığı iletişim kopukluklarını, anlık yedek oyuncu bulma zorluğunu ve maça gelmeyenlerin (no-show) yarattığı adaletsizliği çözen mobil uygulamadır. Sistem; saat bazlı rezervasyon, takım kurma, 14 asil / 2 yedek kuralı, anlık iletişim portali ve güvene dayalı ban mekanizması sunar.

## Takım Üyeleri ve Alanları
* **Okan Bölük (Takım Kaptanı):** Core Booking Engine (Takvim, State Yönetimi ve Rezervasyon)
* **Yahya:** Real-Time Communications (Supabase Broadcast ile Geçici Sohbet Odaları)
* **Katryna:** Identity, Trust & Ban System (Kayıt, P2P Şikayet Doğrulaması ve Yaptırım)

## Teknoloji Yığını
* **Frontend / İstemci:** Flutter (iOS & Android)
* **Backend (BaaS) & Veritabanı:** Supabase (PostgreSQL, Auth)
* **Gerçek Zamanlı Veri:** Supabase Realtime (WebSocket)

## Geliştirici Ortamı Kurulumu
1. Depoyu klonlayın: `git clone https://github.com/0kanboluk/yurt-saha.git`
2. Proje dizinine geçiş yapın: `cd yurt-saha`
3. Flutter bağımlılıklarını indirin: `flutter pub get`
4. `.env.example` dosyasını `.env` olarak kopyalayıp Supabase `URL` ve `ANON_KEY` bilgilerinizi girin.
5. Uygulamayı başlatın: `flutter run`
