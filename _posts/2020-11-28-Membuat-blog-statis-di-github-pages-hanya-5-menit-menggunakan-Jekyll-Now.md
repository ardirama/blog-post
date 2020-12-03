---
layout: post
title: Membuat blog statis di github-pages hanya 5 menit menggunakan Jekyll Now 
---


Penjelasan Tentang Jekyll Now adalah sebuah SSG (static site generator) yang biasanya digunakan untuk membuat blog yang hostingnya di github pages. Dengan ini kamu tidak perlu susah-susah untuk membuat blog di Jekyll ini konsepnya menggunakan markdown untuk membuat post atau halaman blog.

![Jekyll Now Theme Screenshot]({{ site.baseurl }}/images/jekyll-now-theme-screenshot.jpg "Jekyll Now Theme Screenshot")

## Intro

Sebenarnya anda juga bisa melihat quick start nya di web resminya tetapi banyak dari kalian yang belum paham bahasa inggris jadi saya tulis lah blog ini. Di atas adalah contoh blog yang di generate sebelum di setup , anda akan mendapatkan tampilan default dari Jekyll Now .Oke Langsung saja ke stepnya buka github [Jekyll-Now](https://github.com/barryclark/jekyll-now)

## Step 1

![Step 1]({{ site.baseurl }}/images/step1.gif "Step 1")

**Pertama** , kalian fork terlebih dahulu repository dari jekyll disini saya mengira bahwa anda sudah memiliki akun github atau sudah melakukan login dengan akun anda.

## Step 2

![_config.yml]({{ site.baseurl }}/images/config.png "_config.yml")
Jika sudah memfork kemudian kita custom view agar bisa tampil dan bisa diakses.

> Disini ada beberapa tahapan yang harus kita lakukan 

> 1. cari menu settings pada repository ini lalu klik
> 2. edit nama repository ini dengan nama username github ditambah domain nya `yourgithubusername.github.io` lalu rename
> 3. jika sudah ,scroll ke bawah terdapat section Github Pages di source pilih branch master lalu pilih folder root kemudian save

Tunggu beberapa saat , kemudian buka tab baru dan ketik [yourusernamegithub.github.io].
Blog anda sudah siap ...

## Step 3 <Membuat Post Pertama Kita>

![_config.yml]({{ site.baseurl }}/images/config.png)

Settingan blog terdapat di file _config.yml 
> 1. Edit nama pada argument name: ganti dengan nama / nick kalian 
> 2. Edit kolom description: tambahkan bio apapun seperti di instagram
> 3. Edit avatar atau gambar pada kolom avatar: ini untuk gambar profile anda

Edit `/_posts/2014-3-3-Hello-World.md` Untuk gaya halaman bisa merefrensikan dari[Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) buat kreasimu.

![First Post]({{ site.baseurl }}/images/first-post.png "First Post")

Diatas adalah gaya penulisan markdown yang digunakan pada jekyll-now.


Baiklah , Sampai disini saya akhiri dan saya ucapkan terimakasih karena sudah membaca blog kecil ini. Ada pertanyaan bisa hubungi kontak saya atau comment dibawah!!

