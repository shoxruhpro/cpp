# Izohlar

Izohlar kodni ta'riflash va uni o'qishga oson qilish uchun ishlatiladi. Undan boshqa kodni sinab ko'rilayotganda, hozirgi kodni ishlamaydigan qilib turishda foydalanish ham mumkin. Izohlar 2 turga bo'linadi: bir-qatorli va ko'p-qatorli.

## Bir-qatorli izohlar

Bir-qatorli izoh ikkita slesh (`//`) bilan boshlanadi.

`//` bilan boshlangan joydan qator oxirigacha bo'lgan matnni kompilyator e'tiborsiz qoldiradi (bajarilmaydi).

Quyidagi misolda bir-qatorli izoh kod qatoridan oldin yozilgan:

```cpp
// Bu izoh
cout << "Alhamdulillah!";
```

Quyidagi misolda bir-qatorli izoh kod qatori oxiridan yozilgan:

```cpp
cout << "Alhamdulillah!"; // Bu izoh
```

## Ko'p-qatorli izohlar

Ko'p-qatorli izohlar `/*` bilan boshlanib, `*/` bilan tugaydi.

`/*` va `*/` orasidagi har qanday matnni kompilyator e'tiborsiz qoldiradi.

```cpp
/* Quyidagi kod Alhamdulillah! matnini
ekranga chop etadi va bu juda ajoyib */
cout << "Alhamdulillah!";
```

> ### Bir yoki ko'p-qatorli izohlar?
>
> Qaysi birini ishlatish o'zingizga havola. Odatda qisqa izohlar uchun `//` ishlatiladi, uzunlari uchun esa `/* */`
