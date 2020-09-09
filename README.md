# .gitignore-cheatsheet-indonesia

Merupakan contekan untuk menggunakan .gitignore berbahasa indonesia 

## Membuat file

Buat file bernama
`.gitignore` di root folder projek masing-masing

## Contoh Penggunaan

### Komentar
```
# ini merupakan komentar
```

### File
mengabaikan satu file
```
# nama file dan ekstensinya wajib ditulis
contoh.txt
```

mengabaikan banyak file dengan ekstensi yg sama
```
*.txt
```

mengabaikan satu file yg ada ditiap folder
```
**/contoh.txt
```

mengabaikan satu file yg ada didalam folder
```
node_modules/lodash/_arrayEachRight.js
```


### Folder
mengabaikan satu folder beserta isinya
```
node_modules/ `atau` /node_modules
```

mengabaikan folder yg ada didalam folder lainnya
```
node_modules/lodash `atau` node_modules/lodash/ `atau` /node_modules/lodash
```

mengabaikan semua yg ada didalam folder kecuali beberapa file
```
node_modules/lodash/*
!node_modules/lodash/_arrayEachRight.js
!node_modules/lodash/_arrayEach.js
...
```


## Ingin berkontribusi?
Pull requests sangat diperbolehkan tetapi keep it simple, bukan cheatsheet namanya kalau tidak simple :)

## Rujukan
https://git-scm.com/docs/gitignore
