Öğrendiklerimi pekiştirmek için hava durumu tahmin modeli oluşturmaya çalıştım. İlk önce veriyi analiz ettim tarih verisini ayırarak işe başladım. Boş değerleri doldurdum. String özellikleri label encoding kullanarak int değerlere döndürdüm. Correlation değerlerini heatmap yardımı ile inceledim. Veriyi eğitmek için hazırladım.
Modelimi oluştururken k-fold ile cross validation kullanarak eğitimlerimi gerçekleştirdim. Kullandığım modeller: RandomForestClassifier, DecisionTreeClassifier.
