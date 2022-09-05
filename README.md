# SAS-ile-Tahminleme-Projesi

SAS Studio kullanarak oluşturulan tahminleme peojesinde veriye erişim nasıl yapılır, veri setini inceleme, veriyi temizleme, veriyi analiz etme adımları gerçekleştirildi.
 
Projede kullanılan temel tahminleme modelleri ise Hierarchical Forecasting, Multistage Model, Naive Model, Non-seasonal Model, Panel Series Neural Network, Regression for Time Series, Retired Series, Seasonal Model, Stacked Model, Temporal Aggregation olmuştur.

SAS Studio uygulamasına veri seti yükleme ve veri üzerinde çalışma aşamalarında karşılaşılan hata çözümleri yapıldıktan sonra tahminleme modeli oluşturuldu.

![tahmin grafiği](https://user-images.githubusercontent.com/70209932/188399941-aff25a91-309a-4d02-b90a-5af378453327.jpg)

Oluşturulan projede görsel akış diyagramları kullanılarak aynı anda birden fazla model çalıştırılıp sonuçlara göre bir şampiyon model seçilir. Şampiyon model MAPE (Mean Absolute Percentage Error) değerinin en düşük olduğu modeldir. 

Bazı literatürlerde %10’un altında olan tahmin modelleri yüksek doğruluk derecesine sahip, %10 ve %20 arasında olan modeller doğru tahmin modelleri olarak sınıflandırılırken %50’nin üzerinde olan modeller ise yanlış ve hatalı olarak sınıflandırılmıştır. 

Projenin sonucuna seçilen şampiyon modelin MAPE değeri ise 81,0664 olarak bulunmuştur. En iyi model olmasına karşın %50’nin üzerinde olduğu model iyi bir tahmin vermeyecektir.

SAS Studio programı kullanılarak bir Hava Durumu Tahmin projesi gerçekleştirilmiştir.
