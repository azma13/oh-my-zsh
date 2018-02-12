# **Tentang Zsh**

## **1. Penjelasan singkat tentang Shell dan Zsh**
Shell, dalam komputer adalah salah satu jenis program asli sistem operasi (seringnya merupakan program yang terpisah dari inti sistem operasi) yang menyediakan komunikasi langsung antara pengguna dan sistem operasi.

Zsh merupakan salah satu jenis shell yang populer digunakan pada terminal linux. Zsh memiliki kelebihan dibandingkan dengan bash shell salah satunya yaitu adanya fitur **cd autocomplete** yaitu ketika kita mengetikkan perintah **cd** dan menekan tombol **tab** maka direktori yang ada akan autocomplete.

## **2. Instalasi Zsh**
Pada OS Mac, Zsh sudah terinstall secara default. Install zsh and zsh-completions using Homebrew:
```
$ brew install zsh zsh-completions
```
## **3. Penjelasan mengenai Oh My Zsh**
Robby Russel mengembangkan **Oh My Zsh**, yaitu sebuah framework untuk konfigurasi Zsh. Dengan Oh My Zsh, terminal yang menjalankan Zsh menjadi lebih keren karena dilengkapi dengan functions, helpers, plugins, dan themes. 

## **4. Cara instalasi Oh My Zsh**
Instalasi Oh-my-zsh dapat dilakukan dengan me-running command berikut pada terminal.
```
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

## **5. Mengganti tema Zsh menggunakan oh-my-Zsh**
untuk mengganti tema oh-my-zsh menggunakan

```
$ nano ~/.zshrc
```
Lalu cari tulisan **ZSH_THEME=”tema-yg-diinginkan”**

untuk langsung melihat perubahan tampilannya menggunakan
```
$ source ~/.zshrc
```
## **6. Fitur-fitur Zsh**
beberapa fitur zsh
1.  Tab completion on `cd`
```
cd <TAB>
```
2.  Memendekkan perintah `ls`
tidak perlu menulis panjang command, cukup di tab maka zsh akan melengkapi
misalnya:
```
ls /u/l/dtra<TAB>
```

    maka zsh akan melengkapi menjadi

```
ls /usrl/ib/dtrace/
```
3.  Zsh dapat mengubah tampilan shell / tema

4.  The `autopushd` command helps you do `popd` after you use `cd` to go back to your previous directory
5.  Menyediakan perintah yang lebih singkat / alias. Contoh :`ls -liah` cukup ditulis `ll`
