# Knime-Main-Position
Knime with main position machine learning

Rol-Main Projesi Aşamaları

Başlangıç 
Main verisini buluyoruz


Veriyi Anlamak 
Verileri inceliyoruz player datayı seç nedenini anlat
rol-pozisyon asist  ve dakika başına minyon skoru tahmin ettirip öğretebiliriz

Veriyi Hazırlamak
Algoritma taslağımız oluştuyoruz
POS,A,CSPM SUPPORTUN BELİRGİN ÖZELLİKLERİ
CONF read csv Virgülle ayrılmış değerler dosyası
CONF -filtre öğrenmek istenilen verinin belirgin olması için support
POS A  CSPM AND OTHER -- PLAYER TEAM SPLİT
CONF -partitioner -öğrentest çapraz doğrulama döngüsü
Biz bu veri setinin bir kısmı ile modelimizi eğitmek, bir kısmı ile eğittiğimiz modelimizin başarısını değerlendirmek istiyoruz. Basit yaklaşım; %75’ini eğitim için, %25’ini de test için ayırmaktır.
CONF- learner öğrenmesi gereken sütünü belirle
 -predictor tahmin
CONF -aggregator posa tahmin pos döngüden çıkıyoruz düzen
CONF -scor yorumla
Model Hazırlamak 
Knime ile uygulamayı yapıyor ve yorumluyoruz
