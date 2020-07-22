# Titanic-Hayatta-Kalma-Tahmini

'titanic.csv' veri seti ile Jupyter Notebook üzerinde ;

- Gerekli kütüphanelerin import edilmesi
- Verilerin yüklenmesi
- Veri setindeki satır ve sütun bilgisi
- Veri setindeki istatistiki bilgilere ulaşma
- Hayatta kalabilenlerin sayısı
- Hayatta kalabilenlerin sayısını görselleştirme
- Veri setindeki 'who','sex','pclass','sibsp','parch','embarked' sütunların görselleştirmesi
- Cinsiyete göre hayatta kalma oranının hesaplanması
- Cinsiyet ve sınıfa göre hayatta kalanların görselleştirilmesi
- Her class'ın (sınıfın) hayatta kalma oranı ve görselleştirilmesi
- Yaş, sınıf ve cinsiyete göre hayatta kalma oranları
- Her sınıf için ödenen bilet fiyatı ve bunun görselleştirilmesi
- Veri setindeki değerler ve onların sayısı
- İhtiyacımız olmayan sütunların drop edilmesi ve eksik değerleri olan sütunların silinmesi
- Sütunların encode edilmesi
- Veri bilgisinden bağımsız 'X' ve bağımlı 'Y' değişkeninin split edilmesi
- Veri setini %80 train ve %20'sinin test için ayrılması
- Verilerin ölçeklendirilmesi
- Logistic Regression, k Neighbors, SVC Linear, SVC RBF, Gaussian Naive Bayes, Decision Tree ve Random Forest modellerinin kullanılması
- Tüm modellerin alınıp eğitilmesi
- Test verilerindeki tüm modellerin karmaşıklık matrisi ve Accuracy değerlerinin bulunması
- Feature ve Importance görselleştirilmesi
- En yüksek başarı oranına sahip modelin 'Random Forest Classifier' olması ve bu tahminlerinin yazdırılması
- Kendi yazmış olduğum değerler ile Random Forest Modeli ile hayatta kalıp kalamayacağımın tahmin edilmesi gerçekleştirilmiştir.

Veri Setindeki Sütunlar :
pclass: Yolcu Sınıfı (1 = 1'nci sınıf; 2 = 2'nci sınıf; 3 = 3'ncu sınıf)
survived: Hayatta Kalma (0 = Hayır; 1 = Evet)
name: Ad
sex: Cinsiyet
age: Yaş
sibsp: Gemideki kardeş/eş sayısı (örn: erkek kardeş, kız kardeş, üvey erkek kardeş, üvey kız kardeş)
parch: Gemideki ebeveyn/çocuk sayısı (örn: kız evlat, erkek evlat, üvey evlat)
fare: Yolcu ücreti (İngiliz Pound'u)
embarked: Bindiği Liman (C = Cherbourg; Q = Queenstown; S = Southampton)
adult_male: 18 yaşından büyük bir erkek mi ? (0 = Hayır, 1 = Evet)
deck: Geminin güvertesi
who: man (18+), woman (18+), child (<18)
alive: Yes, no
embarked_town: Gemiye binilen liman ( Cherbourg, Queenstown, Southampton)
class: Yolcu sınıfları (1st; 2nd; 3rd)
alone: 1= yanlız olan, 0= yanlız olmayan ( gemide en az 1 kardeş, eş, ebeveyn veya çocuk var)


