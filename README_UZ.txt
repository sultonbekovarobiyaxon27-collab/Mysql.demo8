MYSQL DEMO — O'ZBEKCHA QO'LLANMA

Loyiha fayllari tayyor. Ishlatish tartibi:
1) TiDB Cloud'da Starter klaster yarating.
2) SQL Editor'da jadval.sql faylidagi kodni ishga tushiring.
3) Connect bo'limidan HOST, PORT, USERNAME va parolni oling.
4) GitHub repository yarating va ushbu papka ICHIDAGI fayllarni yuklang.
5) Netlify'da GitHub repository'ni import qilib deploy qiling.
6) Netlify Project configuration > Environment variables bo'limida quyidagi kalitlarni yarating:
   DB_HOST, DB_PORT, DB_USER, DB_PASS, DB_NAME
   Qiymatlarni TiDB Connect ma'lumotlaridan kiriting; DB_NAME=test.
   DB_PASS maxfiy (secret) qiymat sifatida belgilang.
7) Environment variables kiritilgach, Netlify'da qayta deploy qiling.
8) Saytni ochib ism saqlashni sinang.

MUHIM: DB_PASS parolini index.html yoki GitHub kodiga yozmang va hech kimga yubormang.
Bu loyiha fayllari tayyor holatda, lekin akkaunt ochish, TiDB klaster yaratish,
parol kiritish va Netlify deploy amallarini egasining o'zi bajarishi kerak.
