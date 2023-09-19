# # Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portal diyebiliriz.
3. Neden bir branch oluşturuyoruz?
çalışılan projenin farklı versiyonlarına erişmemizi sağlar.ayrıca yaptığımız değişikliklerin yaptığımız çalışmayı bozmaması için kullanılır.
4. Pull Request'in amacı nedir?
branch da değiştirilen özelliklerin ve kodda tam olarak neyin değiştirildiğini anlamak için kullanılır.
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout komutu ile gitmek istediğimiz klasörün adını yazarak brach değişikliği yapabiliriz. git checkout 'main'
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch yerel depomu uzaktaki deponun içeriğine güncelle. git merge başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. git pull Proje ana dosyasındaki yaptığınız değişikliklerin bilgisayarınızdaki versiyonuna çekilmesini sağlar.
7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. 
8. Merge conflict'i nasıl çözeriz?
komutunu çalıştırarak git merge --abort birleştirmeyi iptal edin veya tüm birleştirme çakışmalarını çözerek komutunu çalıştırın git merge --continue.
