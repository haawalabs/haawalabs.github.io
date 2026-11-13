---
title: "Zip & Split: Support"
permalink: /zipsplit/support/
---

# Zip & Split: Support

Split big files into standard archives that open anywhere, right from Shortcuts.

Contact: [support@haawalabs.org](mailto:support@haawalabs.org). Please say your iPhone or iPad
model, iOS version and the Zip & Split version (from the App Store or TestFlight page).

## English

**How do I join the chunks on a computer?**
Put all chunks (`Pack.zip.001`, `Pack.zip.002`, …) in one folder. On Mac or Linux run
`cat Pack.zip.* > Pack.zip`, then open `Pack.zip`. On Windows run
`copy /b Pack.zip.001+Pack.zip.002 Pack.zip`. Or open the first chunk with 7-Zip (Windows), Keka
or The Unarchiver (Mac); they find the other chunks themselves.

**Which format should I pick?**
ZIP opens everywhere. TAR.GZ and TAR.XZ are common on Linux and compress more but need a tool on
Windows. 7Z compresses best and is the only format with a password.

**Why is 7Z or TAR.XZ slow on videos?**
They compress everything, including video that is already compressed. ZIP stores photos, videos
and audio as they are, so it's fastest.

**What chunk size should I use?**
18 MB by default, which fits the common 20–25 MB email attachment limits once email encoding adds
about a third. Check your provider's limit.

**Does compression continue if I leave the app?**
Yes. iOS shows a Live Activity with progress and a Cancel button. A very long job can still be
stopped by iOS if the device is low on power or memory; start it again with Compress Again.

**Can I use it from Shortcuts or Siri?**
Yes: the "Compress Files" action takes files and returns the archive chunks. Siri phrases:
"Compress with Zip & Split", "Zip with Zip & Split", "Split for email with Zip & Split".

**Do you see my files?**
No. Zip & Split doesn't send your files or data anywhere. Its only network use is Apple's StoreKit,
for purchases and restores. See the [privacy policy](/zipsplit/privacy/).

**The 7Z password is lost.**
It isn't stored anywhere, so we can't recover it.

**Known limits.** Zip & Split creates archives; it doesn't extract them. 7Z archives replace
characters outside the basic Unicode range in file names (such as emoji) with `_`. At most 999
chunks per archive.

## Українською

**Як склеїти частини на комп'ютері?**
Покладіть усі частини (`Pack.zip.001`, `Pack.zip.002`, …) в одну папку. На Mac чи Linux виконайте
`cat Pack.zip.* > Pack.zip` і відкрийте `Pack.zip`. У Windows:
`copy /b Pack.zip.001+Pack.zip.002 Pack.zip`. Або відкрийте першу частину в 7-Zip (Windows), Keka
чи The Unarchiver (Mac): вони самі знайдуть решту.

**Який формат обрати?**
ZIP відкривається всюди. TAR.GZ і TAR.XZ поширені в Linux, стискають сильніше, але у Windows
потрібен інструмент. 7Z стискає найкраще і лише він підтримує пароль.

**Чому 7Z або TAR.XZ повільні на відео?**
Вони стискають усе, навіть уже стиснене відео. ZIP зберігає фото, відео й аудіо як є, тому
найшвидший.

**Який розмір частини обрати?**
За замовчуванням 18 МБ: це вкладається в типові ліміти пошти 20–25 МБ з урахуванням того, що
кодування листа додає близько третини. Перевірте ліміт вашого провайдера.

**Чи триває стиснення, якщо вийти із застосунку?**
Так. iOS показує Live Activity з перебігом і кнопкою «Скасувати». Дуже довге завдання iOS усе ж
може зупинити за браку заряду чи пам'яті; запустіть знову через «Стиснути знову».

**Чи можна з Команд (Shortcuts) або Siri?**
Так: дія «Compress Files» приймає файли й повертає частини архіву. Фрази Siri: «Compress with
Zip & Split», «Zip with Zip & Split», «Split for email with Zip & Split».

**Ви бачите мої файли?**
Ні. Zip & Split нікуди не надсилає ваші файли чи дані. Мережу він використовує лише для Apple
StoreKit: для покупок і їх відновлення. Див. [політику конфіденційності](/zipsplit/privacy/).

**Я забув пароль до 7Z.**
Його ніде не збережено, тож відновити ми не можемо.

**Обмеження.** Zip & Split створює архіви, але не розпаковує їх. У 7Z символи поза базовим Unicode
в іменах файлів (наприклад, емодзі) замінюються на `_`. До 999 частин в архіві.
