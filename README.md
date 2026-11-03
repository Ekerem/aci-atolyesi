# Açı Atölyesi

5. sınıf Matematik, 3. Tema (Geometrik Şekiller) açı kazanımları için çizim uygulaması
(MAT.5.3.1, MAT.5.3.3, MAT.5.3.4).

## Ne yapar?
- **Işın, doğru parçası, doğru** çizilir; ışın ve doğruların sonsuzluğu uçlarındaki okla gösterilir. Uç noktalar otomatik harflendirilir (A, B, C…).
- **Çember**: merkezden dışarı sürükleyerek çizilir; çemberin üzerine ve kesişimlerine noktalar yapışır, merkezden çizilen yarıçaplar arasındaki merkez açı otomatik gösterilir.
- **Kesiştir**: bir kesişim yerine ya da sırayla iki şekle dokunulur; kesişim noktası adlandırılır ve şekiller hareket edince onlarla birlikte hareket eder.
- **Ad değiştirme**: Taşı modunda bir noktaya ya da harfine dokunup (her modda çift tıklayıp) yeni adı yazın.
- **Dikme ve Paralel**: önce bir çizgiye, sonra yerleştirilecek noktaya dokunulur; dikme ya da paralel otomatik çizilir.
- Kesişen çizgiler arasındaki **açılar otomatik gösterilir**; **eş açılar aynı renktedir**, dik açılar kare işaretlidir.
- **Dereceleri Gizle**: renkler kalır, sayılar gizlenir; öğrenciler açıölçerle kendileri ölçer.
- **Saydam açıölçer**: ✥ ile taşınır, ⇔ ile büyütülür/küçültülür, ⟳ ile döndürülür. Merkezi noktalara, tabanı çizgilere yapışır.
  Açıölçerin merkezinden başlayan çizimler tam derece ile çizilir (canlı derece göstergesi).
- **Taşı**: noktayı sürükleyerek açıyı değiştirin, çizgiyi sürükleyerek kaydırın. **Sil**, **Geri Al**, **Temizle**.
- **Yakınlaştırma**: fare tekerleği, iki parmakla sıkıştırma ya da sol alttaki −, 100%, + düğmeleri. Taşı modunda boş alanı sürükleyince (veya iki parmakla) sayfa kayar.
- 🔄 **Güncelle** butonu, sağ altta "Made by Us" imzası, çevrimdışı çalışma (`sw.js`).

## Bağlantılar
- Web: https://ekerem.github.io/aci-atolyesi/
- APK: https://github.com/ekerem/aci-atolyesi/releases/latest

## Kurulum
1. `ekerem` geçen yerleri (index.html, version.json, capacitor.config.json, README.md) GitHub kullanıcı adınızla değiştirin.
2. Depoyu `aci-atolyesi` adıyla oluşturup dosyaları `main` dalına gönderin. Settings → Pages → Source: **GitHub Actions**.
3. APK, `version.json` içindeki sürüm değişip `main` dalına gönderildiğinde otomatik derlenir ve o sürümün release kaydına eklenir.

## Yeni sürüm
`index.html` içindeki `APP_VERSION` ve `version.json` birlikte artırılıp `main` dalına gönderilir; etiket ve release otomatik oluşur.
