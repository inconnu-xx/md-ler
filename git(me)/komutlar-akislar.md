KOMUTLAR

git init = bir klasörü git projesine cevirir. versiyon takibi baslar
git clone = bir porjeyi githubdan veya baska sunucudan pc ye indirir. projenin tüm gecmisi de gelir
git status = projede ne değiştiğini gösterir (hangi dosya değisti, hangisi commite hazır, hangisi yeni)
git add = değisen dosyaları staging alanına koyar. (yani bu dosya commite girecek demis olunur)
git commit = staging de ki degisiklikleri proje gecmisine kaydeder
git push = pc deki commitleri github gibi uzak repoya gönderir
git pull = uzak repodaki yeni değisiklikleri pc ya ceker
git fetch = remote de ki değisiklikleri indirir ama projeye uygulamaz, sadece bilgiyi alır
git branch = projede bulunan branchleri listeler veya yeni branch olusturur
git checkout = branch değistirmeyi sağlar
git switch = yeni git sürümlerinde branch değistirmak icin kullanılan daha sade komut
git merge = bir branchi baska branch ile değistirir
git log = commit gecmisini gösterir
git diff = dosyalarda yapılan değisiklikleri satır satır gösterir
git stash = yarım kalan değisiklikleri gecici olarak saklar



AKIŞ ÖRNEKLERİ

örn 1: yeni proje baslatmak
--proje klasörünü oluşturdun ve terminali actın
git init = proje dosyasının icinde git takibi icin gizli bir git klasörü olusturursun
--kodları yazdın ve dosyaların oluştu
git add . = tüm değişiklikleri staging alanına koyar ve commite hazırlar
git commit -m "ilk commit" = proje gecmisi kaydedilir ve ilk version oluşmuş olur



örn 2: githuba proje yüklemek
--yerelde commit atıldı, sunucuya yüklenecek
git remote add origin repo_adresi = repoyu bagladın
git push -u origin main = projeyi githuba gönderdin



örn 3: var olan projeyi pc ye yüklemek
git clone repo_adresi = proje iner, commit gecmisi iner, remote bağlantısı kurulur
artık proje pcde dir



örn 4: normal geliştirme akısı
--projeyi indirdin ve kod yazdın
git status = değisiklikleri kontrol edersin. git sana hangi dosyaların değistiğini söyler
git add . = commite hazırlarsın
git commit -m "login sistemi eklendi" = commit atarsın
git push = githuba gönderirsin
