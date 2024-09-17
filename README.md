# TurkStudentCo-AlgoritmalarModuluOdevi

# Soru 1

  Başla
      İlk sayıyı kullanıcıdan al (a)
      İkinci sayıyı kullanıcıdan al (b)
      a ve b'yi topla ve sonucu (toplam) değişkenine ata
      toplam sonucunu ekrana yazdır
  Bitir

# SORU 2

  Başla
      toplam = 0
      a = 1
      Döngü başlat (a 1'den 100'e kadar):
          toplam = toplam + a
          a = a + 1
      Döngü bitir
      toplam sonucunu ekrana yazdır
  Bitir


# SORU 3
  Başla
    Kullanıcıdan bir sayı al (sayı)
    
    Eğer sayı <= 1 ise
        "Sayı asal değildir" yazdır
    Aksi halde
        i = 2
        asal = true
        
        Döngü başlat (i, 2'den sayının kareköküne kadar):
            Eğer sayı % i == 0 ise
                asal = false
                Döngüden çık
            i = i + 1
        Döngü bitir
        
        Eğer asal == true ise
            "Sayı asaldır" yazdır
        Aksi halde
            "Sayı asal değildir" yazdır
  Bitir
