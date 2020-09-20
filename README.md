# Gerçek Zamanlı Sudoku Çözücü Program

### Github Adresi

https://github.com/Grup1-Python-Egitimi/PythonSudokuSolver

### Grubu oluşturan öğretmenlerin listesi

Mehmet Öztürk, Halil İbrahim Kocagöz, Mehmet Kotan, Ahmet Kaynak

# Sudoku Çözücü Analiz Raporu

### Kısa Özet

Klasik sudoku problemlerine çözüm üretmenin yanında derin öğrenme kütüphanelerini kullanarak gerçek zamanlı sudoku çözen program.

### Problem Tanımı

Sudoku problemlerinin çözümüne gerçek zamanlı olarak ulaşıp cevapları kontrol edebilme amacıyla yapılmıştır. Gazetelerde, dergilerde çıkan sudoku bulmacalarını çözümünü program vasıtası ile yapmak için bulmacadaki verileri(sayıları-boşlukları) girmek gerekiyordu, derin öğrenme tabanlı bilgisayarlı görü yöntemi ile ise bunun fotoğrafını çekmek yeterli oluyor.

### Analiz Süreci

Yazılımın üretilme sürecinde Python&#39;ın os, math, random modülleri, numerik işlemler için numpy ve scipy, görüntü işleme ve tanımlama işlemleri için tensorflow, keras derin öğrenme kütüphaneleri ve opencv kullanılmıştır. Github üzerinde ortak çalışma imkanı bulan proje üyeleri geliştirme ortamı için Visual Studio Code ve Pycharm kullanmışlardır.

1.
#### İhtiyaç Analizi

Sudoku problemlerinin çözümüne anında ulaşarak bulmacaların kontrolünü kolaylaştırmak ve sudoku bulmacalarını daha eğlenceli hale getirmek.

1.
#### İçerik Analizi

Projenin içeriğinde klasik sudoku çözücü programlarına ek olarak derin öğrenme kütüphanelerini kullanarak bu bulmacaya doğrudan, gerçek zamanlı olarak ulaşma imkanı sağlamaktadır.

1.
#### Durum Ortam Analizi

Yazılım gerçekleştirilmesinde sudoku bulmacalarının görüntü ayarları için opencv kütüphanesi kullanılırken, modelleme ve eğitim için tensorflow ve keras derin öğrenme kütüphaneleri kullanıldı.

1.
#### Kullanıcı Analizi

Github üzerinden kullanılıma açılan uygulamamızın sudoku çözümü Python bilgisi yeterli olanlar için anlaşılır düzeydedir. Gerekli olanlar yerlerde yorum satırları kullanılmıştır.

# Sudoku Çözücü Tasarım Raporu

### Kısa Özet

Proje tasarım sürecinde sudoku çözümüne ek olarak gerçek zamanlı sudoku çözücü eklenmiştir. Bunlar mobil uygulama üzerinde ayrı butonlar(menüler) şeklinde ilerleyen zamanlarda eklenecektir.

## Veri Tasarımı

Uygulamamızda veritabanı kullanılmamıştır ama ilerleyen zamanlarda başka bir mobil uygulamanın içerisine veya web tabanlı sisteme dahil edilebilir.

## Ara yüz Tasarımı

Konsol üzerinden çalışan uygulamamız için web üzerinden veya mobil uygulama üzerinden çalışan arayüzü yapılacaktır.

## Kod Tasarımı

![](RackMultipart20200920-4-14qd4nt_html_19b3a9f82120ca7.png)

## Zaman Çizelgesi

Proje gruplarının netleşmesinden sonra proje fikir aşaması bir hafta sürdü. Uygulamamız öncelikle sadece sudoku çözümü için tasarlandı, bu aşama 3 gün sürdü. Uygulamaya gerçek zamanlı çözücü ekleme fikrinden sonra, görüntü işleme ve derin öğrenme kütüphanelerinin eklenmesi ise bir hafta sürdü.

# Sudoku Çözücü Gerçekleştirme Raporu

## Karşılaşılan Sorunlar ve Uygulanan Çözümler

Sudoku çözümü için çekilen bazı fotoğraflarda sorun yaşanabilmektedir. Bunun için sistemin evrişimsel sinir ağları kullanarak eğitilmesi gerekmektedir ama sudoku fotoğraflarının toplanması ve etiketleme işlemlerinden sonra eğitim sürecinin proje zaman çizelgesine uymayacağından şu an için vazgeçilmiştir. Ayrıca sudoku bulmacalarının farklı versiyonları için de ayrı çözümler üretmek gerekmektedir.

## Proje Bileşenleri ve Görevleri

Sudoku İmages = Çözümlenecek sudoku bulmacalarının toplandığı klasör

Digit Recognition = Gerçek zamanlı çözüm için modellemenin yapıldığı yer

Sudoku Solver = Sudoku bulmaca çözücü

Realtime Sudoku Solver = Gerçek zamanlı sudoku bulmaca çözücü

## Github Yükleme Süreci

Kendi ideleri üzerinden çalışan üyelerimiz projeyi daha sonra bir proje üyemiz tarafından uygulamanın son halini github üzerinde paylaşmıştır. Ayrıca üyeler kendi github hesapları üzerinden projeyi fork etmiştir.

# Sudoku Çözücü Test Raporu

## Karşılaşılan Sorunlar ve Uygulanan Çözümler

Projemiz doğru açı ve ışık altında çekilen fotoğraflarda stabil bir şekilde çalışmaktadır. Uygulamanın mobil üzerinde gerçek zamanlı çalışabilmesi ve kamera kalitesi, doğru ışık ve doğru açı gibi etkenlerden olabildiğince uzaklaşabilmesi proje zaman çizelgesine uymamaktadır.
