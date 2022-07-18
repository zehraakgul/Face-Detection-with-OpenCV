# Face-Detection-with-OpenCV
Face applications with OpenCV and Dlib library.
# OpenCV ile Yüz algılama işlemleri

Adım 1) Yüz algılama işlemleri:

 OpenCv, dlib, Numpy kütüphaneleri kullanılarak yüz filtre ve yüz algılama uygulaması gerçekleştirildi. Yüz algılama ve filtre işlemleri için dosyalarda da bulunan 'haarcascade_frontalface_alt.xml' ve "shape_predictor_68_face_landmarks.dat" (Bu dosyayı sıkıştırılmış dosyadan çıkarmanız gerekmektedir. [Buraya tıklayarak indirebilirsiniz]( https://github.com/davisking/dlib-models/blob/master/shape_predictor_68_face_landmarks.dat.bz2)) adlı dosyalar kullanılmıştır. 5’i örnek resimler olacak şekilde toplamda 10 adet resim üzerinde çalışılıp resimler üzerinde uygulamalar gerçekleştirildi. Kullanılan resimler şu şekildedir:
 ![](https://github.com/zehraakgul/Face-Detection-with-OpenCV/blob/main/resimler/Test.png)
 
 Adım 2) Dudak Rengi işlemleri: 
 
  Dudak renklerini kullanıcı Trackbar kullanarak resimlerdeki gibi her bir resim için ayı anda dudak rengi uygulanıyor (Kırmızı, yeşil, mor ve sarı)
  
  * Kırmızı renk uygulanmış:
  
  ![](https://github.com/zehraakgul/Face-Detection-with-OpenCV/blob/main/resimler/kirmizidudak.png)
  
  * Yeşil renk uygulanmış:
  
  ![](https://github.com/zehraakgul/Face-Detection-with-OpenCV/blob/main/resimler/yesildudak.png)
  
  * Sarı renk uygulanmış:
  
  ![](https://github.com/zehraakgul/Face-Detection-with-OpenCV/blob/main/resimler/saridudak.png)
  
  * Mor renk uygulanmış:
  
  ![](https://github.com/zehraakgul/Face-Detection-with-OpenCV/blob/main/resimler/mordudak.png)
 
 Adım 3) Belirlenen bir Filtre uygulanması:
 
 Kullanıcı tüm resimlere şapka eklemek (Şapka ekleme filtresi seçildi) için trackbar’ı 0’dan 1’e çekerek ekleme işlemini gerçekleştirebilir.
 
 ![](https://github.com/zehraakgul/Face-Detection-with-OpenCV/blob/main/resimler/sapkaeklenmis.png)
 
