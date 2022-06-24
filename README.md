# U-net-segmentation_human_body
Bu modelde kaggle üzerinden indirilen insan vücudu ve bu vücudların maskeleri eğitilerek, insan vucudunu tanıyan bir segmentasyon modeli geliştirilmiştir.

Data set("https://www.kaggle.com/datasets/tapakah68/segmentation-full-body-mads-dataset")

Colab üzerinde geliştirilen model sırası ile
    -İndirilen verilerin csv formatına dönüştürülüp boyutlarının eşlenmesi
    -Hazırlanan csv dosyasının u-net segmentation kulanılarak eğilmesi
    -Eğitilen modelin tahmin celli
    -Maskesiz bir insan vücudu eklendiğinde maske görüntüsünün alınması
olarak tüm celler bulunmaktadır.

Ek olarak modelde kullanılan metric değerler, bach_generatorler import edilmek üzere dosyalar kısmına eklenmiştir.

Emeği geçenler :{U-net-segmentation_human_body,
Ahmet NARMANLI:'https://github.com/narmanliahmet',
Emrah Doğuer  :'https://github.com/Emrhdgr',
Yıl:2022}

@
