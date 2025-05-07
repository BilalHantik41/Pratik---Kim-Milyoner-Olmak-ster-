Kim Milyoner Olmak İster Konsol Uygulaması

Bu proje, C# ile yazılmış basit bir bilgi yarışması ("Who Wants to Be a Millionaire?") tarzı konsol uygulamasıdır. Kullanıcıya 3 adet iki seçenekli (A/B) soru sorulur; 2 doğru cevap verdiğinde kazanır, 2 yanlışta elenir.

Özellikler

Toplam 3 soru sorulur.

Her soru için sadece "A" veya "B" girişi kabul edilir; farklı bir girişte program hata mesajı verip sonlanır.

2 yanlış yaptığınızda yarışmadan elenirsiniz.

3 sorunun sonunda 2 veya daha fazla doğru verirseniz oyunu kazanırsınız.

Yanıtlar küçük/büyük harf duyarsızdır.

Gereksinimler

.NET Core SDK 3.1 veya daha üstü

Windows, macOS veya Linux ortamında çalışabilir

Kurulum ve Çalıştırma

Bu repoyu bilgisayarınıza klonlayın veya indirin.

Konsol/terminal açın ve proje klasörüne gidin.

cd KimMilyonerOlmakİster

Uygulamayı derleyip çalıştırın:

dotnet run

Ekrana gelen soruları takip edin ve "A" veya "B" ile yanıtlayın.

Kod Yapısı

Program.cs: Oyunun ana akışını içerir.

dogruSayisi ve yanlisSayisi değişkenleriyle cevapları sayar.

Her soruda geçerli giriş kontrolü (A/B) yapılır.

Yanıta göre sayılar güncellenir, elenme veya kazanma durumu kontrol edilir.

Geliştirme

Yeni sorular ve seçenekler eklemek için Program.cs dosyasındaki ilgili bölümleri güncelleyebilirsiniz.

Yanlış hakkı, soru sayısı gibi değerleri ihtiyaçlarınıza göre ayarlayabilirsiniz.
