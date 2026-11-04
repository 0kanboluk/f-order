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
