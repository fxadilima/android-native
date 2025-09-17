# Packages For Android-x86_64

Direktori ini berisi prebuilt packages untuk android-x86_64, umumnya dicompile berdasarkan android-35,
tetapi bisa digunakan untuk android-36.

Paket baru bernama `baklava-vendor-0.1.tar.xz` dimaksudkan sebagai base bagi kita untuk membangun program-program
selanjutnya. Di situ sudah ada setidaknya 2 paket yang hampir selalu dipakai, yaitu ncurses dan readline, dan juga
`GNU Bash 5.3`, dimaksudkan untuk android, tidak memakai Glibc.

Paket `vendor` ini bisa di-uncompress di direktori mana pun, tetapi pastikan untuk membuat symlink terkait, supaya
tetap bisa diakses dari `system-wide`, lakukan perintah berikut sebagai root (atau memakai sudo):

```bash
ln -sv $PWD/vendor /
```


