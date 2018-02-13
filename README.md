## 1. Penjelasan Singkat Mengenai Shell dan Zsh
```
Shell adalah program (penterjemah perintah) yang menjembatani user dengan sistem operasi dalam hal ini kernel (inti sistem operasi), umumnya shell menyediakan prompt sebagai user interface, tempat dimana user mengetikkan perintah-perintah yang diinginkan baik berupa perintah internal shell (internal command), ataupun perintah eksekusi suatu file progam (eksternal command), selain itu shell memungkinkan user menyusun sekumpulan perintah pada sebuah atau beberapa file untuk dieksekusi sebagai program.
```
```
Zsh adalah sebuah powerful shell yang interaktif dan kompatibel dengan semua command (perintah) di bash. Kelebihan Zsh dibanding bash adalah efesinsi; tab completion yang lebih baik dibanding bash; dukungan syntax-highlighting; fitur globbing; array handling; dan bisa dikostumisasi secara menyeluruh (Fully customisable).
```

## 2. Cara Instalasi Zsh
Buka terminal, lalu ketikkan :
```
$ sudo apt-get install zsh
```

## 3. Penjelasan Singkat Mengenai Oh My Zsh
```
Oh My Zsh adalah framework open source, community-driven untuk mengelola konfigurasi zsh Anda.
```

## 4. Cara Install Oh My ZSH
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## 5. Cara Menggati Tema Zsh (Menggunakan Oh My Zsh)
* Buka file .zshrc
```
nano .zshrc
```
* Jika file sudah terbuka cari script berikut :
```
# time that oh-my-zsh is loaded.
ZSH_THEME="<nama tema>"
```
*  Isi nama tema yang diinginkan. Daftar tema dapat dilihat [disini](https://github.com/robbyrussell/oh-my-zsh/wiki/themes)
* Simpan file .zshrc
* Jalankan dengan :
```
source .zshrc
```

## 6. Fitur - Fitur Zsh yang tidak tersedia di Bash
## Auto-correct
pada zsh terdapat auto-correct
![auto-correct](https://qph.ec.quoracdn.net/main-qimg-d45a5c5abf52584a62a147e4df0bbd82.webp "Logo Title Text 1")

## Auto-complete
pada zsh terdapat auto-complete dengan cara tekan tombol **tab**

## Expand Variable
ketik
``` 
$ Path
```
kemudian tekan **tab**
maka akan menghasilkan 
```
/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin
```
 ## Extended gobbling
 ```
 ls *(                                                                   1 ↵
%  -- device files
)  -- end of qualifiers
*  -- executable plain files
+  -- + command name
-  -- follow symlinks toggle
.  -- plain files
/  -- directories
:  -- modifier
=  -- sockets
@  -- symbolic links
A  -- group-readable
D  -- glob dots
E  -- group-executable
F  -- non-empty directories
 ```

## Autopush Command
 autopushd command pada zsh membuat 
 ```
 cd
 ```
 bisa langsung kembali ke direktori sebelumnya

## Tema
 zsh menyediakan berbagai tema yang bisa diubah oleh pengguna

## Alias 
 menyediakan perintah yang lebih singkat. Contoh :
 ```
ls -liah Menjadi ls -ll
 ```