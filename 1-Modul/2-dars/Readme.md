# Web Texnologiyalar
## Web texnologiyalar nima?
> * Biz har kuni foydalanadigan web saytlar, web dasturlarni ishlab chiqishda qo'llaniladigan va uni foydalanuvchiga yetkazib berishda ishlatiladigan dasturlarga web texnologiyalar deyiladi.
> > ![World-Wide-Web-Internet](assets/img/world-wide-web-internet.jpeg)
---------
> O'tiladigan mavzularimiz
1. [Internet](#Internet)
2. [Web ilovalarning arxitekturasi](#Web-ilovalarning-arxitekturasi)
3. [Protkollar](#Protokollar)
4. [IP, DOMEN, URL, HOSTING](#IP-Domen-URL-Hosting)
5. [DNS](#DNS)
6. [Web Server](#Web-Server)
---------
## Internet
> * Internet -ma'lumot almashinish tarmog'i
> * Internet -ko'plab qurilmalar(telefon, planshet, kompyuter)lar ulangan tarmoq
> # Internetga ulanish - ISP(Internet Service Provider)
> ![Internet Service Provider](assets/img/isp.jpg)
---------
## Web ilovalarning arxitekturasi
> ![Web ilovalarning arxitekturasi](assets/img/web-arxitektura.jpg)
---------
## Protokollar
> **Protokol** - ma'lumotlarni formatlash va qayta ishlash uchun standart qoidalar to'plamidir.
> * IP - Internet Protocol (Kompyuterdan kompyuterga ma'lumot o'tkazish uchun ishlatiladi)
> * TCP - Transmission Control Protocol (Kompyuterdagi dasturdan boshqa kompyuterdagi dasturga yuborish uchun ishlatiladi)
> * HTTP - Hypertext Transfer Protocol (Foydalanuvchi va Web Server o'rtasida HTML ma'lumotlarini almashinish uchun ishlatiladi)
> * TLC - Transport Layer Security (Internet orqali aloqa uchun ma'lumotlarni xavfsizligini ta'minlash uchun ishlatiladi)
> > ![Protokollar ishlash](assets/img/protokol.png)
---------
## IP, Domen, URL, Hosting
> ## IP nima?
> **IP(Internet Protokol)** - internet tarmog'idagi qurilmalarning takrorlanmas manzili hisoblanadi.
> > ![Internet Protocol](assets/img/ip-nima.jpg)
> ## Domen nima?
> **Domen** - web saytdan foydalanish uchun esda qoladigan, takrorlanmaydigan matn ko'rinishidagi manzil nomi hisoblanadi.
> > **Domenga misollar**
> > * [agron.uz](https://agron.uz)
> > * [webplaneta.uz](https://webplaneta.uz)
> > ## ![Domen haqida tushuncha](assets/img/domen.jpg)
> ## URL nima?
> **URL** - internetdagi ma'lumotlarning aniq manzili hisoblanadi.
> > ### Misol uchun `http://example.uz:8080/path/data.html?a=1&b=2#part1`
> > * http - protokol nomi
> > * example.uz - domen nomi
> > * 8080 - TCP port
> > * /path/data.html - fayl yo'li
> > * a=1&b=2 - so'rov parametrlari
> > * #part1 - xatcho'p(langar), sahifadagi joylashuv
> ## Hosting nima?
> **Hosting** - web saytlarni internetda joylashtirish uchun xizmat hisoblanadi
> > ![Hosting haqida tushuncha](assets/img/hosting.jpg)
> ### Hosting turlari (eng mashhur 3 tasi haqida)
> > 1. Shared hosting (Arzon)
> >   * Bitta serverda bir nechta web saytlar joylashishi mumkin, sizning saytingiz yonida yana bir nechta mijozlarning saytlari joylashgan bo'lishi mumkin
> > ![Shared-Hosting](assets/img/shared-hosting.jpg)
> > 2. VPS(*Virtual private server*) hosting (O'rtacha)
> >   * Bitta serverda bir nechta virtual serverlar hosil qilinadi, **Shared hosting**dan farqi siz uchun alohida virtual server yaratiladi unga faqat o'zingizni saytingizni joylashingiz mumkin.
> > ![Virtual Private Server](assets/img/VPS-hosting.jpg)
> > 3. Dedicated hosting (Qimmat)
> >   * Bitta server faqat bitta mijoz uchun ishlatiladi.
> > ![Dedicated Hosting](assets/img/Dedicated-hosting.jpg)
---------
## DNS
> ## DNS nima?
> **DNS(Domain Name Server)** - Domen nomlari tizimi (DNS) Domen nomlarini IP manzillarga o'girib beradi.
> > ![DNS haqida tushuncha](assets/img/DNS.jpg)
---------
## Web Server
> ## Web server nima?
> **Web Server** - Foydalanuvchidan kelayotgan so'rovlarni (HTTP so'rovlarni) qabul qilib, tegishli javobni yuboradigan dastur hisoblanadi.
> ### Bu dasturlarga misollar;
> > * Apache(HTTP Server)
> > * NGINX
> > * IIS \
> > > ![Web Server haqida](assets/img/web-server.png)
