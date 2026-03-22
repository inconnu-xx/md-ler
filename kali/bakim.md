SIK KULLANIMDA HER GÜN, DEĞİLSE İKİ GÜNDE BİR
sudo apt update = apt paket yöneticisi. update paket listelerini kontrol eder. 

HAFTADA BİR
sudo apt update && sudo apt upgrade -y = upgrade yüklü paketlerin yeni sürümünü kurar. -y evet sorularını otomatik gecer. && ilk komut basarılıysa ikincisini calistirir.

AYLIK DERİN TEMİZLİK VE BÜYÜK UPDATE
sudo apt update && sudo apt full-upgrade -y = full upgrade gerekirse paket sil ve yenisini kur.
suda apt autoremove -y = autoremove gereksiz bağımlılıkları siler.
sudo apt autoclean = indirilen eski paket cache'lerini siler.

YILLIK BÜYÜK SÜRÜM GEÇİŞİ
sudo apt update && sudo apt full-upgrade -y sonra:
sudo reboot


UYGULAMA İNDİRMEDEN ÖNCE
sudo apt update















