# Araştırma Soruları

Artık yeni iş yerindeki ilk görevini gerçekleştirmek için hazırsın! Kullandığımız araçları biraz daha iyi anlama zamanı. Yapman istenilen şey, bu dokümanı güncelleyerek, aşağıdaki soruları soruları cevaplaman. Böylece Git yapısına biraz daha aşina olmaya başlayacaksın.

Soruları cevaplarken takıldığın yerlerde [GitHub docs](https://docs.github.com/en)'u kullanabilirsin. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak _zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçecek_.

![READ THE DOCS](https://github.com/Workintech/FSWeb-S1G1-Projesi-Web-Development-Projesi-icin-Git/blob/main/read-the-docs-wit.gif?raw=true)

Eğer aradığın soruların cevapları GitHub docs'ta yoksa, Google'lama becerileriniz size yardımcı olacak. Google'ı iyi kullanabilmek de aslında büyük bir dikkat ve çalışma gerektiriyor. Zamanla bu konuda da daha iyileştiğini göreceksin :)

## Sorular

1. Git nedir?
Git açık kaynak dağıtılmış sürüm sistemidir.
2. Git ile GitHub arasında ne fark var?
Git projenin sürüm geçmişini yönetmek ve lokal cihazda kullanmak için kullanilır.GitHub ise projenin uzaktaki sunucularda depolamak, işbirliği yapmak ve paylaşmak için kullanılır. 
3. Neden bir branch oluşturuyoruz?
Branch projenin ana kod tabanından ayrılmasını sağlar bu sayede aynı projede birden fazla kişi eş zamanlı geliştirme ve düzeltme yapabilir.
4. Pull Request'in amacı nedir?
Pull request, branch üzerinde yapılan değişikliklerin projeye merge edilmek istendiğinde kullanılır. Projeye merge edilmeden önce herkese açık olup gerekli incelemeler ve kontroller yapılabilir. 
5. Bir Branchten diğerine geçmek için kullandığın KOMUT nedir? Mesela `isim-soyisim` branch'inde çalıştığını hayal et ve main branch'ine geçmek istiyorsun, ne yaparsın?
git checkout main yazarak geçiş yaparım.

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
git fetch repositoryden çalışmayı çeker ancak düzenleme düzenleme yapmaz. git merge farklı branchleri birleştirmek için kullanılır. git pull ise git fetch ve git merge komutlarının birleşmiş halidir. 
7. Merge conflict nedir?
Farklı branchlerin aynı dosyada aynı satırda çakışmasıdır.
8. Merge conflict'i nasıl çözeriz?
Çakışan bölümler düzenlenerek çözülür. 