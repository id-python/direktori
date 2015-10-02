# Cara menambah data di direktori

Untuk yang belum pernah menggunakan git sebelumnya, bisa belajar dasar-dasar git melalui [tutorial git oleh Endy Muhardin] (https://github.com/endymuhardin/belajarGit)

## Jika belum pernah fork dan clone

- _fork_ [repositori](https://github.com/id-python/direktori/fork) (kamu akan memiliki repositori `username/direktori`)
- _clone_ repositori hasil _fork_ tersebut (ganti `username` dengan username kamu)

```
$ git clone git@github.com:username/direktori.git
```

## Jika sudah pernah fork dan clone

- tambahkan _upstream_ id-python/direktori di _clone_ direktori

```
$ git remote add upstream git@github.com:id-python/direktori.git
$ git fetch upstream
$ git rebase upstream/master
```

## Selanjutnya

- lakukan perubahan yang perlu
- `commit` dan `push` ke repositori `direktori` kamu.
- ajukan _pull request_ melalui halaman [https://github.com/username/direktori/compare/id-python:master...master](https://github.com/username/direktori/compare/id-python:master...master) (ganti `username` dengan username kamu)
