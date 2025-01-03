# Levenshtein Algorithm

Bu proje, iki metin arasındaki **Levenshtein Mesafesi**'ni hesaplamak için yazılmış bir uygulamadır. Levenshtein Mesafesi, iki metin arasındaki en küçük düzenleme sayısını (ekleme, silme, değiştirme) hesaplayan bir algoritmadır. Program ayrıca, kullanıcıya matrisin basılıp basılmayacağını belirleme seçeneği sunar.

## İçindekiler
- [Proje Açıklaması](#proje-açıklaması)
- [Kurulum ve Derleme](#kurulum-ve-derleme)
- [Kullanım](#kullanım)
- [Argümanlar](#argümanlar)
- [Dosya Yapısı](#dosya-yapısı)

## Proje Açıklaması

Bu proje, iki cümleyi karşılaştırmak ve Levenshtein Mesafesi'ni hesaplamak için geliştirilmiştir. Program, kullanıcının verdiği iki cümleyi kıyaslar ve bunlar arasındaki minimum düzenlemeleri hesaplar.

Ayrıca, kullanıcıya isteğe bağlı olarak hesaplanan matrisin ekranda yazdırılmasını sağlama imkanı da sunulur. Bu matris, her iki metnin karakterleri arasındaki tüm dönüşüm adımlarını gösterir.

## Kurulum ve Derleme

Proje, **Makefile** kullanarak derlenebilir. Aşağıdaki adımları takip ederek projeyi derleyebilir ve çalıştırabilirsiniz.

### 1. Bağımlılıklar
- C derleyicisi (örneğin GCC veya Clang)
- Make

### 2. Derleme Adımları

Proje klasörünü açın ve terminal üzerinden aşağıdaki komutları sırasıyla girin:



# Levenshtein Mesafesi Programı

Bu program, Levenshtein mesafesini hesaplayan bir algoritmayı uygular. İki kelime ya da cümle arasındaki düzenleme mesafesini bulmak için tasarlanmıştır. Program, birinci ve ikinci argüman olarak girilen iki kelimeyi karşılaştırır. Üçüncü bir argüman olarak, karşılaştırma sırasında kullanılan matrisin yazdırılıp yazdırılmayacağı belirlenebilir.

---

## **Klasör Yapısı**

main/
├── bin/
│   ├── MacOS/                # MacOS için çalıştırılabilir dosyalar
│   └── Windows/              # Windows için çalıştırılabilir dosyalar
├── src/                      # Kaynak kodları ve Makefile
│   ├── main.c
│   ├── levenshtein.c
│   ├── print_matrix.c
│   └── Makefile
├── README.md                 # Proje açıklaması (bu dosya)