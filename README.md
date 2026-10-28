# squad // Ceza & Saygınlık

Bu sürüm yalnızca Ceza & Saygınlık panelini içerir. Steam entegrasyonu, sesli oda bağlantısı, bağlantı listesi, duyuru ve push bildirim dosyaları kaldırılmıştır.

## Özellikler
- Siteyi ziyaret eden herkes üyeleri, kategorileri ve puanları görebilir.
- Yönetici GitHub token ile bağlanıp üye/kategori ekleyebilir.
- Yönetici her üye için kategori puanlarını `+` ve `−` ile değiştirebilir.
- Değişiklikler GitHub deposundaki `data/scoreboard.json` dosyasına kaydedilir.
- Arama ve sıralama.

## GitHub Pages kurulumu
1. ZIP içeriğini açın.
2. Dosyaları mevcut `TRlKeSeR03/squad-site` deposunun `main` dalına yükleyin; eski Steam/duyuru dosyalarını da silebilirsiniz.
3. GitHub'da Settings → Pages bölümünden Pages'in `main` dalından yayınlandığını doğrulayın.
4. Yönetici panelini açıp yalnızca yöneticilerin kullanacağı GitHub token'ını girin. Token, depodaki `data/scoreboard.json` dosyasını okuma ve yazma yetkisine sahip olmalıdır. Fine-grained token kullanıyorsanız yalnızca bu depoyu seçip Contents için Read and write izni verin.
5. Siteye herkes erişebilir; yazma işlemi token isteyen yönetici panelindedir.

## Güvenlik notu
GitHub token'ını kimseyle paylaşmayın. Ortak cihazlarda işiniz bitince “Bağlantıyı kes” kullanın. Daha yüksek güvenlik ve çok sayıda yönetici için sunucu tarafında kimlik doğrulama/veritabanı kullanılması önerilir. Puan kategorilerini davranış ve grup kuralları gibi uygun konular için kullanın.
