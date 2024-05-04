# Advanced Programming - Module 10
#### Reyhan Zada Virgiwibowo - 2206081723 - Advanced Programming C

### 1.2 Understanding how it works
![Screenshot 1.2](static\images\1.2.png)

Berdasarkan screenshot dari hasil eksekusi, dapat dilihat bahwa statement "hey hey" muncul terlebih dahulu sebelum "howdy!" dan "done!". Hal ini terjadi karena print statement "hey hey" berada di luar asynchronous task dan masuk ke main thread. Dengan demikian, program akan menjalankan sesuai baris terlebih dahulu, menjalankan print statement "hey hey", kemudian executor dari asynchronous task baru akan di-run.