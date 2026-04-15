# mrp-motor-uretim
Excel tabanlı 4 seviyeli BOM ve MRP modeli — lot sizing (EOQ/FOQ/L4L), güvenlik stoku ve yeniden sipariş noktası hesabı | Otomotiv / Motor Üretimi
Motor Üretim MRP Modeli

Bu proje, Endüstri Mühendisliği lisans eğitimi kapsamında gerçekleştirilen staj hazırlık çalışmamının bir parçasıdır. Şirket gizliliği sebebiyle bazı bilgiler değiştirilmiştir.

Proje Hakkında
Motor üretimi için Malzeme İhtiyaç Planlaması (MRP) modeli geliştirilmiştir. Model, gerçek bir üretim ortamını simüle edecek şekilde tasarlanmış olup SAP PP modülünde uygulanan MRP mantığını Excel ortamında yansıtmaktadır.
İçerik
DosyaAçıklamaMRP_Motor_Uretim.xlsx6 sekmeli MRP modeli
Excel Sekmeleri
Sekmeİçerik1_BOM4 seviyeli, 29 parçalı motor ürün ağacı2_MPS_Talep12 haftalık Master Production Schedule3_MRP_HesaplamaNet ihtiyaç, lot sizing, planlı sipariş çizelgesi4_Lot_SizingL4L / FOQ / POQ / EOQ yöntem karşılaştırması5_Güvenlik_StokuSS = Z × σ_d × √LT formülü ile ROP hesabı6_Özet_DashboardKPI paneli ve kritik parça uyarı tablosu
Kullanılan Yöntemler

BOM Patlatma — 4 seviyeli ürün ağacı üzerinden net ihtiyaç hesabı
Lot Sizing — Sabit Sipariş Miktarı (FOQ), Ekonomik Sipariş Miktarı (EOQ), Dönemlik Sipariş (POQ), Lot-for-Lot (L4L)
Güvenlik Stoku — Z skoru ve talep değişkenliğine dayalı istatistiksel hesaplama
Yeniden Sipariş Noktası (ROP) — Temin süresi ve ortalama talep bazlı

Temel Bulgular

Toplam 29 parça, 4 üretim seviyesi
En kritik temin süresi: Enjektör (F-001) — 5 hafta
EOQ hesabı: sipariş maliyeti 500₺, elde tutma maliyeti 2₺/adet/hafta
%95 hizmet seviyesi için Z = 1.65

Kullanılan Araçlar

Microsoft Excel
