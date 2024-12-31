# Yangi qator

Ekranda yangi qator ochish uchun `\n` belgisidan foydalanishingiz mumkin:

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Assalamu aleykum!\n";
  cout << "Vaaleykum assalam!";
  return 0;
}
```

**Foydali:** Ketma-ket ikkita `\n` belgisi bo'sh qatorni yaratadi:

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Assalamu aleykum!\n\n";
  cout << "Vaaleykum assalam!";
  return 0;
}
```

Yangi qator qo'shishni yana bir yo'li `endl` manipulyatoridan foydalanish:

```cpp
#include <iostream>
using namespace std;

int main() {
  cout << "Assalamu aleykum!" << endl;
  cout << "Vaaleykum assalam!";
  return 0;
}
```

> `\n` va `endl` ikkalasi ham qatorni tugatish uchun qo'llanadi. Ammo, `\n` ko'proq ishlatiladi.
>
> ### \n o'zi nima?
>
> Yangi qator belgisi (\n) escape sequence (eskeyp-sikuens) deb ataladi. U kursor pozitsiyasini ekrandagi keyingi qator boshiga o'zgartirishga majbur qiladi. Bu yangi qator natijasini beradi.
>
> Boshqa maxsus tartiblarga misollar:
>
> <table>
>   <tr>
>    <th>Escape sequence</th>
>    <th>Tavsifi</th>
>   </tr>
>   <tr>
>    <td>\t</td>
>    <td>Gorizantal tab</td>
>   </tr>
>   <tr>
>    <td>\\</td>
>    <td>Chapga yotiq chiziq ya'ni bekslesh</td>
>   </tr>
>   <tr>
>    <td>\"</td>
>    <td>Qo'shtirnoq</td>
>   </tr>
> </table>
