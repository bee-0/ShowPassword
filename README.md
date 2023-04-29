# ShowPassword


Disini saya akan menjelaskan bagaimana membuat Show password dengan javascript.
silakan melihat [Demo](https://bee-0.github.io/ShowPassword/)

kode ini sudah dilengkapi dengan antar muka yang responsive 
```
gh repo clone bee-0/ShowPassword
```

### Penjelasan

ShowPassword bekerja dengan cara, mengubah tipe input dari elemen password
```html
<input type="password" />
```
"password" menjadi "text" dan sebaliknya .


### bekerja dengan cara!

- Mengambil referensi elemen input  password dan elemen icon dengan mengunakan 
```javascript
document.getElementById()

document.querySelector()
```

- Ketika pengguna mengeklik elemen icon 
```html
 onclick="showPassword()
```
akan dijalankan dan akan memeriksa jenis tipe input password 



Jika tipe input password saat ini adalah "password", maka akan mengubahny menjadi "text"  akan mengganti icon yang menunjukan mata terlihat   &  sebaliknya

📍 Semoga bermanfaat 


