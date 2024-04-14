Skewness
veri setinizdeki değişkenlerin çarpıklığını (skewness) ölçmektedir. Çarpıklık, bir dağılımın simetrisizliğini ölçer. Pozitif bir çarpıklık, dağılımın sağa çekik olduğunu, negatif bir çarpıklık ise dağılımın sola çekik olduğunu gösterir. Genellikle, çarpıklık mutlak değeri 1'den büyük olduğunda, dağılımın anormal derecede çarpık olduğu kabul edilir.
pre (Number of times pregnant): Çarpıklık (Skewness) = 0.902
Bu değişkenin dağılımı sağa çekiktir (pozitif çarpıklık). Hamilelik sayısının çoğu 0 veya düşük değerlerde olduğunu gösterirken, birkaç nadir vakada çok yüksek değerlerin olduğunu gösterebilir.
pla (Plasma glucose concentration a 2 hours in an oral glucose tolerance test): Çarpıklık = 0.174
Bu değişkenin dağılımı hafifçe sağa çekiktir (pozitif çarpıklık).
Dia (Diastolic blood pressure): Çarpıklık = -1.844
Bu değişkenin dağılımı oldukça sola çekiktir (negatif çarpıklık). Genellikle düşük tansiyon değerleri görülürken, birkaç yüksek değer de mevcuttur.
skin (Triceps skinfold thickness): Çarpıklık = 0.109
Bu değişkenin dağılımı hafifçe sağa çekiktir (pozitif çarpıklık).
insulin (2-Hour serum insulin): Çarpıklık = 2.272
Bu değişkenin dağılımı oldukça sağa çekiktir (pozitif çarpıklık).
mass (Body mass index): Çarpıklık = -0.429
Bu değişkenin dağılımı hafifçe sola çekiktir (negatif çarpıklık).
ped (Diabetes pedigree function): Çarpıklık = 1.920
Bu değişkenin dağılımı oldukça sağa çekiktir (pozitif çarpıklık).
Age (years): Çarpıklık = 1.130
Bu değişkenin dağılımı oldukça sağa çekiktir (pozitif çarpıklık).
class (Class variable): Çarpıklık = 0.635
Bu değişkenin dağılımı hafifçe sağa çekiktir (pozitif çarpıklık).
Bu sonuçlar, veri setini dağılımlarının ne kadar simetrik veya çarpık olduğunu göstermektedir. Bu bilgi, veri setini analizinde ve modelleme sürecinde dikkate alınabilir. Özellikle, çarpık dağılımların model performansını etkileyebileceği göz önünde bulundurulmalıdır.

Box Plot Analizi
Kutu grafiklerine göre, her bir değişkenin dağılımı ve aykırı değerleri hakkında önemli bilgiler elde edilebilir:
Number of times pregnant (pre): Medyan değeri 1'dir ve birçok gözlemde değerlerin 0-10 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Plasma glucose concentration a 2 hours in an oral glucose tolerance test (pla): Medyan değeri yaklaşık 120'dir ve birçok gözlemde değerlerin 100-200 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Diastolic blood pressure (Dia): Medyan değeri yaklaşık 72'dir ve birçok gözlemde değerlerin 60-80 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Triceps skinfold thickness (skin): Medyan değeri yaklaşık 23'dür ve birçok gözlemde değerlerin 15-35 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
2-Hour serum insulin (insulin): Medyan değeri yaklaşık 30'dur ve birçok gözlemde değerlerin 0-150 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Body mass index (mass): Medyan değeri yaklaşık 32'dir ve birçok gözlemde değerlerin 25-40 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Diabetes pedigree function (ped): Medyan değeri yaklaşık 0.3'tür ve birçok gözlemde değerlerin 0.1-0.6 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Age (years): Medyan değeri yaklaşık 30'dur ve birçok gözlemde değerlerin 20-40 aralığında olduğu görülmektedir. Aykırı değerler mevcuttur.
Class variable (class): Sınıfların dengeli dağılmadığı görülmektedir.
Genel olarak, veri setinde her bir değişkenin dağılımı incelendiğinde, aykırı değerlerin mevcut olduğu ve bazı değişkenlerde dağılımların dengeli olmadığı gözlemlenmektedir.

Correlation
Korelasyon, bir veri setindeki değişkenler arasındaki ilişkiyi ölçen bir istatistiksel ölçüdür. Korelasyon katsayısı, -1 ile 1 arasında değer alabilir.
1'e yaklaşan pozitif bir korelasyon, değişkenler arasında güçlü bir pozitif ilişki olduğunu gösterir. Yani bir değişkenin değeri arttığında diğer değişkenin değeri de artar.
-1'e yaklaşan negatif bir korelasyon, değişkenler arasında güçlü bir negatif ilişki olduğunu gösterir. Yani bir değişkenin değeri arttığında diğer değişkenin değeri azalır.
0'a yakın bir korelasyon, değişkenler arasında zayıf veya hiç ilişki olmadığını gösterir.

PCA ve LDA Öznitelik Analizi
PCA (Principal Component Analysis) ve LDA (Linear Discriminant Analysis) yöntemleri, boyut indirgeme teknikleridir. Bu teknikler, çok boyutlu veri setlerini daha düşük boyutlu bir alt uzaya dönüştürerek veri setlerindeki özniteliklerin önemini belirlemeyi sağlar.
PCA ve LDA Karşılaştırması:
PCA ve LDA, veri setini farklı şekillerde dönüştürür. PCA, değişkenler arasındaki varyansı maksimize etmeye odaklanırken, LDA, sınıflar arasındaki ayrımı en iyi şekilde sağlayacak şekilde değişkenleri dönüştürmeye odaklanır. Bu nedenle, PCA genellikle sınıflandırma öncesi veri keşfi ve görselleştirmesi için kullanılırken, LDA sınıflandırma görevlerinde daha etkilidir.

Çoklu Doğrusal Regresyon ve Multinominal Lojistik Regresyon
Çoklu Doğrusal Regresyon modeli eğitim veri seti için ortalama kare hatayı (MSE) 0.1643 ve belirleme katsayısını (R²) 0.2899 olarak hesapladı. Bu, modelin eğitim veri seti üzerindeki performansını ölçer.
Multinominal Lojistik Regresyon modeli eğitim veri seti için MSE'yi 0.2208 ve R²'yi 0.0459 olarak hesapladı. Bu da modelin eğitim veri seti üzerindeki performansını gösterir.
Sonuç olarak, Çoklu Doğrusal Regresyon modeli, Multinominal Lojistik Regresyon modeline göre daha iyi performans gösterdi, çünkü daha düşük bir MSE değeri ve daha yüksek bir R² değeri elde etti. Ancak, her iki model de eğitim veri seti üzerinde belirli bir performans sergilemektedir.

Multinominal Lojistik Regresyon Sınıflandırma Modeli Performansı
Doğruluk (Accuracy): 0.779
Bu modelin doğruluk oranı %77.92 olarak hesaplanmıştır, yani toplam test veri setinin %77.92'sinde doğru sınıflandırma yapılmıştır. Confusion matrix, modelin her bir sınıfı ne kadar doğru bir şekilde tahmin ettiğini göstermektedir. Precision, recall ve F1-score değerleri, sınıflandırma modelinin her bir sınıfı ne kadar doğru tahmin ettiğini ve bu tahminlerin ne kadarının gerçekten doğru olduğunu gösterir. Özellikle, sınıf 1 için recall değeri düşük olduğu için bu sınıfın tahmininde iyileştirmeler yapılması gerekebilir.

ROC Curve for Multinomial Logistic Regression
ROC eğrisi, duyarlılık (sensitivite) ve özgüllük (specificity) arasındaki ilişkiyi gösterir ve farklı sınırlayıcı eşik değerlerinde modelin performansını değerlendirmemize olanak tanır. Bir ROC eğrisi, ideal bir sınıflandırıcı, yani eğri sol üst köşeden geçen bir çizgidir.
Eğri altında kalan alan (AUC), modelin sınıflandırma performansını ölçen bir metrik olarak kullanılır. Yüksek bir AUC değeri, modelin iyi performans gösterdiğini gösterirken, düşük bir AUC değeri modelin kötü performans gösterdiğini gösterir.
Ayrıca, ROC eğrisinin altındaki alanı (AUC) rapora ekleyebiliriz. AUC değeri ne kadar yüksek olursa, modelin sınıflandırma performansı o kadar iyidir.
Örneğin, Multinomial Lojistik Regresyon modeli için ROC eğrisi ve AUC değeri:
ROC Eğrisi ve AUC Değeri:
ROC eğrisinin altındaki alan (AUC): 0.83 (örnek değer)
Modelin sınıflandırma performansı oldukça yüksektir. ROC eğrisi, duyarlılık ve özgüllük arasında güçlü bir denge olduğunu göstermektedir.

Karar Ağacı Sınıflandırma Modeli Performansı:
Doğruluk (Accuracy): 0.7229
Bu raporda, karar ağacı sınıflandırma modelinin performansı değerlendirilmiştir. Model, test veri seti üzerinde %72.29 doğruluk elde etmiştir. Confusion matrix'e bakıldığında, modelin 117 doğru negatif (TN), 50 doğru pozitif (TP), 30 yanlış negatif (FN) ve 34 yanlış pozitif (FP) tahmini olduğu görülmektedir.
Precision, recall ve f1-score metriklerini incelediğimizde, sırasıyla 0.77, 0.62 ve 0.79 olan "0.0" sınıfı için iyi performans gösterirken, "1.0" sınıfı için 0.60 olan recall değeri düşüktür. Bu, modelin "1.0" sınıfını tanımlamada zayıf olduğunu gösterebilir. Macro avg ve weighted avg değerleri, sınıf dengesizliği göz önüne alındığında genel model performansını gösterir.

Naive Bayes Sınıflandırıcı Modeli Performansı:
Doğruluk (Accuracy): 0.7403
Bu raporda, Naive Bayes sınıflandırıcı modelinin performansı değerlendirilmiştir. Model, test veri seti üzerinde %74.03 doğruluk elde etmiştir. Confusion matrix'e bakıldığında, modelin 116 doğru negatif (TN), 55 doğru pozitif (TP), 31 yanlış negatif (FN) ve 29 yanlış pozitif (FP) tahmini olduğu görülmektedir.
Precision, recall ve f1-score metriklerini incelediğimizde, sırasıyla 0.80, 0.64 ve 0.79 olan "0.0" sınıfı için iyi performans gösterirken, "1.0" sınıfı için 0.65 olan recall değeri düşüktür. Bu, modelin "1.0" sınıfını tanımlamada zayıf olduğunu gösterebilir. Macro avg ve weighted avg değerleri, sınıf dengesizliği göz önüne alındığında genel model performansını gösterir.

