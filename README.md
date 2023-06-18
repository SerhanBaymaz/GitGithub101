# GitGithub101

# Basic TERMINAL commands

`ls` : list        bulunduğun klasördeki dosyaları listeler

`ls -a`         gizli klasörleri de listeler.

`cd file_name:` ChangeDirectory    `cd Desktop`    

`cd..`  bir önceki dizine götürür  

`mkdir` :    klasör oluşturur.      `mkdir deneme`

`touch` :  dosya oluşturur.     `touch abc.txt`

`Ctrl+Shift  c||v` teriminalde kopyala yapıştır işlemleri yapar.

`pwd` : o anki konumunuzu söyler.



# GIT nedir

![GitNedir](https://github.com/SerhanBaymaz/GitGithub101/assets/102352030/40d9656a-30b1-48e5-8905-7ebb9e87e1cb)



# GIT terimleri

**Commit:** Oyunlardaki kayıt noktalarına benzer. Geri dönmek için kaydettiğimiz yer.

**Status:** Dosyanın durumunu gösterir.

**Init:** Klasörde Git'i etkinleştirir (Git başlatıcı).

**Index veya Staging:** Henüz kaydedilmemiş, ancak kaydedilmeyi bekleyen değişikliklerin bulunduğu bölüm.

**Hash:** Commitlerin (kayıt noktalarının) benzersiz tanımlayıcısı.

**Head:** Geçerli commit'i veya geçerli branch'ı ifade eder.

**Master:** Git'teki varsayılan branch. Depo başlatıldığında oluşturulur.

**Stash:** Gizlemek veya saklamak anlamına gelir. git stash pop ile gizlemeden çıkarılır ve değişiklikler uygulanır.

**Detached:** HEAD'in doğrudan bir commit'e, bir branch'a değil işaret ettiği durumu ifade eder.

**Git Reset:** Commitleri geri almak veya iptal etmek için kullanılır.

**Git Reset --hard:** Depoyu belirli bir commit'e sıfırlar, o commit'ten sonraki tüm değişiklikleri siler.



## Git kısaca 3 bölümden oluşur.

![git1](https://github.com/SerhanBaymaz/GitGithub101/assets/102352030/6b0465c0-3478-494e-b77c-0173e498eba1)


`git add ornek.txt`    :  Dosyayı çalışma klasöründen index’e atar. sahneye çıkarıyor ama repoya atmadı. Commit atılmasını bekliyor.(stage/index)

`git commit -m “savepoint için oluşturulan mesaj”`

`git commit ornek.txt` Dosyayı sahneden(index) alıp commit oluşturur.

`.`    NOKTA tüm dosyalar anlamına gelir

`git log` commitlerin kayıtlarını detaylı gösterir.

`git log --oneline` commitlerin kayıtlarını tek satırda gösterir.
