# Submit Form Homework
### TR
- İsim ve soyisim için input text alanları oluşturuldu.
```
İsim için:
 <input type="text" id="fname" name="fname" required>
 ```

- Cinsiyet seçimi için radio button oluşturuldu
```
<label for="gender">Cinsiyet</label> <br>
    <input type="radio" name="gender" id="gender" value="female">Kadın
    <input type="radio" name="gender" id="gender" value="male">Erkek
```

- Favori meyve seçimi için açılır menü oluşturuldu
```
<label for="fruit">Favori Meyve</label> <br>
    <select name="fruit" id="fruit">
        <option value="">Seçiniz..</option>
        <optgroup label="Meyveler">
            <option value="muz">Muz</option>
            <option value="erik">Erik</option>
            <option value="çilek">Çilek</option>
            <option value="armut">Armut</option>
        </optgroup>
    </select>
```

- E-posta adresi için input type email oluşturuldu
```
<input type="email" name="email" id="email" required>
```

- Şifre alanı için input type password oluşturuldu
```
<input type="password" name="password" id="password" required>
```

- Mesaj için textarea oluşturuldu ve "placeholder" kullanılarak içerisine kullanıcılar için ufak bilgi girildi.
```
<textarea name="message" id="message" cols="40" rows="5"
    placeholder="Mesajınızı buraya yazın."></textarea>
```

- Bilgileri göndermek için "button type submit" oluşturuldu
```
<button type="submit" value="Gönder">Gönder</button>
```
Form içerisinde gerekli bölümler doldurulduktan sonra gönder butonuna basıldığında geri bildirim mesajının bulunduğu succesinfo.html sayfasına yönlendirilir.
```
<form action="./succesinfo.html" method="get">
```


