---
author: Haikel
date: 2021-12-08 
title: "Migrasi Dari Visual Studio Code ke Neovim"
image: https://avatars.githubusercontent.com/u/77146709?v=4
draft: true
---

Tulisan Singkat: Migrasi Text Editor Utama Dari VScode ke Neovim

[Visual Studio Code](https://code.visualstudio.com/) adalah sebuah text editor yang menawarkan banyak fitur, tapi sayangnya tidak terlalu ramah kepada low devices. Karena laptop saya juga termasuk kelas low, jadi saya pun memutuskan untuk pindah ke [Neovim](https://neovim.io/). Tulisan ini adalah tentang pengalaman saya beralih dari VScode ke Neovim, jadi tidak ada tutorial untuk setup Neovim disini.

## Mengapa Neovim? 

Neovim itu fork dari [vim](https://www.vim.org/), dan menawarkan berbagai peningkatan dari vim. Kebetulan, sebelum full pindah ke Neovim, saya sudah memakai vim. Hanya saja vim nya saya pakai buat ngedit file sederhana saja, text editor utamanya ya tetep VScode.

Kalau mau install, sesuaikan saja dengan distronya. Disini saya pakai Artix, jadi tinggal ketik `yay -S neovim`.

Setelah pindah ke neovim, saya pun memutuskan untuk menggunakan konfigurasi yang ready atau siap pakai seperti [NvChad](https://github.com/NvChad/NvChad). Mengapa ga setup sendiri? Waktunya eui, kurang. Jadi mending ngambil yang udah siap aja. 

![nvchad](https://i.ibb.co/Jxg1H6n/neovim.png)

Saat memakai vim/neovim, dianjurkan untuk menggunakan **hjkl** ketimbang arrow keys, katanya karena biar jangkauan jari dengan huruf lain tidak terlalu jauh, misal kalo mau ke mode **insert**, kan deket tuh. Atau mode **visual** juga deket, sehingga hal ini membuatnya terasa lebih efisien ketimbang menggunakan tanda panah biasa.  

Tapi serius, hal ini memang agak susah. Seperti kebanyakan user lainnya yang baru pindah ke vim/neovim, saya udah kebiasaan pake navigasi panah atas bawah kanan kiri. But yeah, ini soal waktu aja sih. Lama-lama juga terbiasa. 

Untuk lebih lanjut mengenai mengapa penggunaan tanda panah di vim/neovim tidak dianjurkan, bisa dilihat [disini](https://superuser.com/questions/599150/why-arrow-keys-are-not-recommended-in-vim/599230)
