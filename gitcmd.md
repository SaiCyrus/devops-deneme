# Git El Kitapçığı

---

## Bölüm 1: Git Kurulumu ve Başlangıç

### Git Versiyonunu Kontrol Etmek

```
git --version
```
Bilgisayarında Git’in kurulu olup olmadığını kontrol eder.

Yeni Bir Klasör Oluşturup Git Deposu Başlatmak
```
mkdir proje-adi
cd proje-adi
git init
```
Yeni klasör açar, içine girer ve o klasörü Git deposu haline getirirsin.

# Bölüm 2: Dosya Takibi ve Commit İşlemleri
Dosya Durumunu Kontrol Etmek
```
git status
```
Değişiklikleri ve sahnelenmiş dosyaları gösterir.

Dosya Eklemek (Staging Area)
```
git add dosya-adi
```
Dosyayı commit için hazırlar.

Commit Yapmak
```
git commit -m "Commit mesajı"
```
Değişiklikleri kaydeder, mesaj yazılır.

# Bölüm 3: Branch (Dal) Yönetimi
Yeni Branch Oluşturmak
```
git branch yeni-branch
```
Branch’a Geçmek
```
git checkout yeni-branch
```
Yeni Branch Oluşturup Geçmek (Tek Komut)
```
git checkout -b yeni-branch
```
Branch’ları Listelemek
```
git branch
```
Branch’ları Birleştirmek (Merge)
```
git checkout master
git merge yeni-branch
```
Branch Silmek
```
git branch -d yeni-branch
```
# Bölüm 4: Uzak Depo (Remote Repository) İşlemleri
Uzak Depo Ekleme
```
git remote add origin https://github.com/kullaniciadi/repo-adi.git
```
Değişiklikleri Uzak Depoya Göndermek (Push)
```
git push -u origin master
```
Uzak Depodan Güncel Değişiklikleri Çekmek (Pull)
```
git pull origin master
```
# Bölüm 5: Değişiklikleri Görüntüleme ve Geri Alma
Değişiklikleri Satır Satır Görüntüleme
```
git diff
```
Commit Geçmişini Görüntüleme
```
git log
```

# Bölüm 6: İpuçları ve En İyi Uygulamalar
1. Sık sık commit yap! Her küçük değişiklik kaybolmasın.
2. Anlamlı commit mesajları yaz! Gelecekte ne yaptığını hatırlamak için önemli.
3. Branch kullan! Yeni özellikleri ana koddan ayrı geliştir.
4. Push ve pull komutlarını düzenli kullan! Çalışmanı yedekle ve güncel tut.
