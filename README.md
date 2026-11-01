# Açı Atölyesi

5. sınıf Matematik, 3. Tema (Geometrik Şekiller) açı kazanımları için çizim uygulaması
(MAT.5.3.1, MAT.5.3.3, MAT.5.3.4).

## Ne yapar?
- **Işın, doğru parçası, doğru** çizilir; uç noktalar otomatik harflendirilir (A, B, C…).
- Kesişen çizgiler arasındaki **açılar otomatik gösterilir**; **eş açılar aynı renktedir**, dik açılar kare işaretlidir.
- **Dereceleri Gizle**: renkler kalır, sayılar gizlenir; öğrenciler açıölçerle kendileri ölçer.
- **Saydam açıölçer**: ✥ ile taşınır, ⇔ ile büyütülür/küçültülür, ⟳ ile döndürülür. Merkezi noktalara, tabanı çizgilere yapışır.
  Açıölçerin merkezinden başlayan çizimler tam derece ile çizilir (canlı derece göstergesi).
- **Taşı**: noktayı sürükleyerek açıyı değiştirin, çizgiyi sürükleyerek kaydırın. **Sil**, **Geri Al**, **Temizle**.
- 🔄 **Güncelle** butonu, sağ altta "Made by Us" imzası, çevrimdışı çalışma (`sw.js`).

## Bağlantılar
- Web: https://ekerem.github.io/aci-atolyesi/
- APK: https://github.com/ekerem/aci-atolyesi/releases/latest

## Kurulum
1. `ekerem` geçen yerleri (index.html, version.json, capacitor.config.json, README.md) GitHub kullanıcı adınızla değiştirin.
2. Depoyu `aci-atolyesi` adıyla oluşturup dosyaları `main` dalına gönderin. Settings → Pages → Source: **GitHub Actions**.
3. APK için `v1.0.0` etiketiyle release oluşturun; APK iş akışı derleyip release'e ekler.

## Yeni sürüm
`index.html` içindeki `APP_VERSION` ve `version.json` birlikte artırılır, yeni etiket (`v1.0.1`) ile release açılır.
