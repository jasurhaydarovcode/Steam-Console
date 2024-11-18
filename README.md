<img align="right" width="100" src="https://cdn.freebiesupply.com/images/large/2x/steam-logo-transparent.png" alt="Steam logo"/>
<h1>Steam Console Codes</h1>

### Copyright reserved! by [jasurhaydarovcode](https://github.com/jasurhaydarovcode)

# 1. Steam Clientni ochish uchun:
Agar Steam'ni komanda satridan ochmoqchi bo'lsangiz, quyidagi kodni ishlating:
```perl
steam://open/console
```

# 2. Game o'rnatish (Install):
O'yinlarni Steam orqali komanda satridan o'rnatish uchun quyidagi koddan foydalaning:
```arduino
steam://install/[AppID]
```
[AppID] o'yinning Steam'dagi identifikator raqami bo'lib, uni Steam'dan topishingiz mumkin. Masalan, "Counter-Strike: Global Offensive" o'yini uchun AppID 730.

# 3. Game boshlash (Launch):
O'yinni komanda satridan ishga tushirish uchun quyidagi koddan foydalaning:
```arduino
steam://run/[AppID]
```

# 4. O'yin qo'shish (Add non-Steam game):
Agar Steam'ga Steam-dan tashqari o'yin qo'shmoqchi bo'lsangiz, quyidagi kodni ishlatishingiz mumkin:
```
steam://add/[path_to_game_executable]
```

# 5. Steam Libraryni tekshirish (Verify game files):
O'yin fayllarini tekshirish uchun quyidagi kodni ishlatishingiz mumkin:
```
steam://validate/[AppID]
```

# 6. Steam'ni yangilash:
Agar Steam'ni komanda satridan yangilamoqchi bo'lsangiz:
```
steam://update
```

# 7. Steam Serverga ulanib, konsolga o'tish:
Agar siz Steam serverining konsoliga o'tmoqchi bo'lsangiz:
```
steam://connect/[ip_address]
```

# 8. Tizimni to'xtatish (Shutdown):
Agar Steam dasturini to'xtatmoqchi bo'lsangiz:
```
steam://shutdown
```

---

# 1. Steamni yangilashni boshlash (Update Steam):
Steam'ni avtomatik yangilashni boshlash uchun quyidagi komandani ishlating:
```
steam://update
```

# 2. Steam'ni o'chirish (Shutdown Steam):
Steam dasturini to'xtatish va o'chirish uchun:
```
steam://shutdown
```

# 3. Sizning Steam hisobingizga kirish (Login):
Agar Steam hisobingizga kirishni xohlasangiz, quyidagi kodni ishlating:
```
steam://login/[username]/[password]
```

# 4. Sizning hisobingizdan chiqish (Logout):
Steam hisobingizdan chiqish uchun quyidagi komandani ishlating:
```
steam://logout
```

# 5. Steam'ni Offline rejimga o'tkazish:
Steam'ni oflayn rejimga o'tkazish uchun:
```
steam://offline
```

# 6. Steamni Onlayn rejimga o'tkazish:
Steam'ni onlayn rejimga qaytarish:
```
steam://online
```

# 7. Steam o'yinlarini va yuklamalarni ko'rish:
Yuklamalarni va o'yinlarni ko'rish uchun quyidagi komanda mavjud:
```
steam://downloads
```

# 8. O'yin haqida ma'lumot olish (Show game details):
O'yin haqida ma'lumot olish uchun:
```
steam://details/[AppID]
```

# 9. Steamdagi do'stlar ro'yxatini ko'rish (Friends List):
Steam do'stlaringiz ro'yxatini ko'rish uchun:
```
steam://friends
```

# 10. Mavjud Steam o'yinlarining holatini tekshirish:
O'yinlarning holatini (masalan, yuklanayotgan yoki o'rnatilgan) tekshirish uchun:
```
steam://apps/[AppID]/status
```

# 11. Steam Update Tarixi (Update History):
Agar Steam yangilanish tarixini ko'rishni xohlasangiz:
```
steam://updates
```

# 12. Steam uchun maxsus parametrlar (Steam Parameters):
Steam'ni maxsus sozlamalar bilan ishga tushirish uchun quyidagi komandalardan foydalanishingiz mumkin:
- Steam'ni administrator sifatida ishga tushirish:
    ```
       steam://run/steam://admin
    ```
- Steamni ma'lum bir o'yin bilan ishga tushirish:
    ```
    steam://run/[AppID]
    ```

### Copyright reserved! by [jasurhaydarovcode](https://github.com/jasurhaydarovcode)