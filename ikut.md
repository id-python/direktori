# Cara menambah data di direktori

## Jika belum pernah fork dan clone

- _fork_ [repositori](https://github.com/id-python/direktori/fork) (kamu akan memiliki repositori `username/direktori`)
- _clone_ repositori hasil _fork_ tersebut (ganti `username` dengan username kamu)

```
$ git clone https://github.com/username/direktori.git
```

## Jika sudah pernah fork dan clone

- tambahkan _upstream_ id-python/direktori di _clone_ direktori

```
$ git remote add upstream https://github.com/id-python/direktori.git
$ git fetch upstream
$ git rebase upstream/master
```

## Selanjutnya

- lakukan perubahan yang perlu
- ajukan _pull request_ melalui halaman [https://github.com/username/direktori/compare/id-python:master...master](https://github.com/username/direktori/compare/id-python:master...master) (ganti `username` dengan username kamu)
