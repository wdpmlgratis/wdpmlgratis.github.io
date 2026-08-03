---
author: Sat Naing
pubDatetime: 2026-08-03T10:30:00.000Z
modDatetime: 2026-08-03T11:00:00.000Z
title: Contoh Artikel AstroPaper dengan 12 Field Frontmatter Lengkap
slug: contoh-artikel-astropaper-lengkap
featured: true
draft: true
tags:
  - tutorial
  - astropaper
  - sitepins
description: "Panduan praktis dan contoh pengisian untuk ke-12 field frontmatter
  bawaan AstroPaper yang terintegrasi dengan CMS Sitepins."
ogImage: "/assets/ChatGPT Image 2 Agu 2026, 10.59.33.png"
canonicalURL: "https://situs-anda.com/posts/contoh-artikel-astropaper-lengkap"
hideEditPost: false
timezone: "Asia/Jakarta"
---

## Daftar Isi

## Pendahuluan

Ini adalah artikel contoh (*dummy post*) yang dibuat khusus untuk membantu mendeteksi struktur skema di Sitepins secara otomatis. Di dalam file ini, seluruh konfigurasi metadata (*frontmatter*) yang berjumlah 12 buah telah diisi dengan nilai contoh yang valid sesuai standar AstroPaper [2.3.1].

## Mengapa Menggunakan File Ini?

Dengan menyimpan file ini ke dalam repositori Anda, Sitepins dapat secara instan mengenali seluruh field yang didukung oleh tema AstroPaper tanpa perlu Anda masukkan satu per satu secara manual [4.2.1, 5.2.1].

### Penjelasan Singkat Nilai Frontmatter:
- **`pubDatetime` & `modDatetime`**: Ditulis menggunakan standar ISO 8601 (misal: `2026-08-03T10:30:00Z`) [2.3.1].
- **`featured` & `draft` & `hideEditPost`**: Berupa nilai logika/boolean (`true` atau `false`) [2.3.1].
- **`tags`**: Ditulis dalam format daftar/array YAML [2.3.1].
- **`ogImage`**: Mengarah ke jalur absolut folder publik Anda [2.1.8, 2.3.1].

> [!TIP]
> Setelah Anda berhasil membuat skema di Sitepins menggunakan file ini, Anda bisa menghapus file ini dari repositori atau membiarkannya sebagai draf dengan mengubah nilai `draft` menjadi `true` [2.3.1].
