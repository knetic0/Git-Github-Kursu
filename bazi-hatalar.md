# <center>Bazı Hatalar</center>

> **Eğer Push işlemlerinde hata alıyorsanız ya da Push işlemlerinde sistem sizden şifre istiyorsa aşağıdakı adımlarla bu sorunları ortadan kaldırabilirsiniz.**

<img src="img/ssh-keygenimg/fpush.png" />

> **Adımları teker teker ve dikkatli bir şekilde uygulayınız.**

> **Öncelikle ```ssh-keygen``` komutu ile SSH Anahtarımızı oluşturalım.**

<img src="img/ssh-keygenimg/ssh-keygen.png" />

> **Bu komuttan 3 adet soru sorulacaktır. Enter'a basarak bu soruları geçelim. Sonunda bu çıktıyı almalıyız.**

<img src="img/ssh-keygenimg/filedir.png" />

> **Kırmızı kutu içerisinde bulunan dosya yolunu kopyalayalım ve ```cat``` komutu ile içeriğine erişim sağlayalım.**

<img src="img/ssh-keygenimg/cat.png">

> **Uzun bir çıktı alıcaz. Bu çıktıyı kopyalayalım ve Githubımıza girelim. ```Settings > SSH and GPG Keys > New SSH Keys``` kısmına gelelim.**

<img src="img/ssh-keygenimg/settings.png" />

<img src="img/ssh-keygenimg/sshkeysadd.png" />

<img src="img/ssh-keygenimg/copy.png" />

> **Title kısmını, Key Type ve Key kısmını görüntüdeki gibi doldurduktan sonra ```Add SSH Key``` butonuna basalım. Sonuç şöyle olmalı;**

<img src="img/ssh-keygenimg/son.png" />