# Knime-Main-Position
Knime with main position machine learning

Rol-Main Projesi Aşamaları

#Başlangıç 
Main verisini buluyoruz


#Veriyi Anlamak 
Verileri inceliyoruz
rol-pozisyon asist  ve dakika başına minyon skoru tahmin ettirip öğretebiliriz

#Veriyi ve Modeli Hazırlamak
Algoritma taslağımız oluştuyoruz

POS,A,CSPM Support rölünün baskın özellikleri olduğu için bu veriler üzerinden işlemlerimizi gerçekleştireceğiz.

CSV Reader 
CONFIGURE Virgülle ayrılmış değerler dosyası

Colummn Filter 
CONFIGURE       öğrenmek istenilen verinin belirgin olması için support POS A  CSPM AND OTHER -- PLAYER TEAM SPLİT

X-Partitioner
CONFIGURE öğrentest çapraz doğrulama döngüsü

Decision Tree Learner
CONFIGURE  öğrenmesi gereken sütünü belirle

Decision Tree Predictor
tahmin

X-Aggregator
CONFIGURE  posa tahmin pos döngüden çıkıyoruz düzen

Scorer
CONFIGURE  yorumla

#Yapımın Bitmesi ve Yorumlanması
Knime ile uygulamayı yapıyor ve yorumluyoruz
