---
title: Menghapus Outliers dengan pandas 
tags: [Python, Pandas, EDA]
style: fill
color: primary
description: cara paling mudah buat hapus dan mendeteksi outlier.
---

Source: [ichi.pro](https://ichi.pro/id/menghapus-pencilan-dari-data-menggunakan-python-dan-pandas-180001119792428)

Menghapus Outliers dari data menggunakan Python dan Pandas.

## Outliers

Diagram kotak yang menampilkan rentang median dan antar-kuartil adalah cara yang baik untuk memvisualisasikan distribusi, terutama jika datanya berisi pencilan. Arti dari berbagai aspek plot kotak dapat dijelaskan sebagai berikut -

{% include elements/figure.html image="https://github.com/sipedia/sipedia.github.io/raw/master/docs/_data/1.png" caption="Several years ago we were definitely in the room on the right but we’ve moved a lot closer to the room on the left." %}

## Definisi Fungsi
Fungsi generate () di bawah (diambil dari Stack Overflow) akan menghasilkan daftar float dengan median tertentu yang berisi outlier (nilai jauh dari median) yang dapat kita gunakan untuk menjelajahi konsep.
Fungsi generate () telah dimodifikasi dari https://stackoverflow.com/questions/55351782/how-should-i-generate-outliers-randomly

