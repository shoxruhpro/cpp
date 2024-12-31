# Sintaksis

Oldingi mavzularda quyidagi kodga bir necha marta duch keldingiz. Keling, uni har bir bo'lagini o'rganib chiqamiz:

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Bismillah!";
  return 0;
}
```

## Endi tushuntiramiz

**1-qator:** `#include <iostream>` - bu sarlavha fayl. Uning yordamida kompilyator kerakli kutubxonalardan kerakli xususiyatlarni olishi mumkin. Ushbu sarlavha fayl yordamida esa `cout` kabi kiritish/chiqarish amallarini dasturimizda qo'llay olamiz.

**2-qator**: `using namespace std` - bu standart kutubxona neymspeysini bizning dasturga qo'shadi. Ya'ni biz standart kutubxonadagi obyekt va o'zgaruvchi nomlaridan foydalanishimiz mumkinligini bildiradi.

> Kutubxonalar - bu oldindan kompilyatsiya qilib qo'yilgan kodlar bo'lib, ularni sarlavha fayllar yordamida o'z kodimizga qo'shib foydalanishimiz mumkin. Sarlavha fayllar kutubxonadagi barcha narsalar haqida ma'lumotni o'zida saqlashi mumkin.
>
> Agar 1-2-qatorlardagi kod sizga baribir tushunarsiz bo'lsa, hechqisi yo'q. Shunchaki u (deyarli) barcha C++ dasturlarda bo'lishi kerakligini esingizda saqlang. Keyinchalik bu mavzuga yana qaytishingiz mumkin.

**3-qator:** bo'sh qator. C++ bo'sh joyga e'tibor bermaydi. Lekin biz undan kodni o'qishga oson qilishda foydalanamiz.

**4-qator:** C++ dasturida doim paydo bo'ladigan yana bir narsa - bu `main()`. Bu funksiya deyiladi. O'z nomi bilan aytib turganidek - asosiy funksiya. Jingalak qavslar `{}` uning tanasi bo'lib, ichidagi kod dastur ishga tushirilgan vaqtda birinchi bo'lib ishlaydi.

> Funksiyalar alohida mavzu bo'lib, darslar davomida keladi. Undan oldin bir nechta mavzularni o'zlashtirishimiz zarur.

**5-qator:** `cout` (o'qilishi: "si-aut") - bu obyekt bo'lib, _kiritish operatori_ (`<<`) bilan birga matnni ekranga chiqarish/chop etish uchun ishlatiladi.

> **Esda tuting:**
>
> C++ tilidagi har bir ko'rsatma nuqtali-vergul bilan tugaydi ;
>
> Asosiy funksiyani bunday ham yozish mumkin:
>
> ```cpp
> int main(){cout << "Bismillah!";return 0;}
> ```
>
> Kompilyator bo'sh joylarni e'tiborga olmaydi. Shunday bo'lsada, kodni alohida qatorlarga ajratish uni o'qishga oson qiladi.

**6-qator:** `return 0` - dastur o'z ishini bexato bajarib bo'lganini bildiradi va asosiy funksiyani to'xtatadi.

**7-qator:** asosiy funksiyaning tanasini yopish uchun yopuvchi jingalak qavs `}` qo'yishni esdan chiqarmang.

## Neymspeysni qoldirib ketish

Siz ba'zi C++ dasturlarni standart kutubxona neymspeysisiz ishlashini ko'rishingiz mumkin. `using namespace std` qatori qoldirib ketilishi mumkin. Unda biz ushbu kutubxonadan kelgan barcha narsalar oldidan `std` kalitso'zi, ketidan `::` operatorini ishlatishimizga to'g'ri keladi.

```cpp
#include <iostream>

int main() {
  std::cout << "Alhamdulillah!";
  return 0;
}
```

> Standart kutubxona neymspeysini ishlatasizmi yoki yo'q - o'zingizga havola.
