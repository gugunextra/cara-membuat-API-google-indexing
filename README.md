# Cara Membuat Api Google Indexing
Cara Membuat Api Google Indexing

1. login ke https://console.cloud.google.com/projectcreate
2. Buat nama Project, misal : INDEXER2025
3. KLIK https://console.cloud.google.com/iam-admin/serviceaccounts , pilih project Anda.
4. Klik tanda + CREATE SERVICE ACCOUNT, kasih nama misalnya INDEXER2025, lalu klik CREATE CONTINUE ![image](https://github.com/gugunextra/cara-membuat-API-google-indexing/assets/73726019/6f21fbc8-3fe2-41e7-9b5e-ad164bfa5647)

5. Pilih Select a Role nya sebagai Owner, lalu klik Continue. lalu klik Done ![image](https://github.com/gugunextra/cara-membuat-API-google-indexing/assets/73726019/30b933ee-93b0-426e-adb6-3198f2d248fa)

6. Copy email nya, misal indexer2025@indexer2025-400203.iam.gserviceaccount.com karena nanti akan di gunakan lagi. Masih di setingan email ini, klik tanda titik tiga di samping kanan, lalu pilih Manage Keys. Pilih Create New Keys, pilih Json dan Save, maka akan terdownload secara otomatis. ![image](https://github.com/gugunextra/cara-membuat-API-google-indexing/assets/73726019/19037cb0-ae82-42e7-8b13-3076f8a17d87)
![image](https://github.com/gugunextra/cara-membuat-API-google-indexing/assets/73726019/f7fb1513-fbf3-4ddc-997c-00069f12a25e)

7. File yang terdownload otomatis itu dalam bentuk file json. Kamu bisa pindahkan ke folder favorit, misal di folder D.
8. Kamu juga bisa merename file json tersebut agar tidak terlalu panjang, misal service_account.json
9. Sekarang kita pergi ke https://console.cloud.google.com/apis/dashboard untuk mengaktifkan 2 API penting, yaitu API Google Console dan API google Web
10. Klik tanda + ENABLE APIS
11. Pada kolom pencarian ketik "Web Search Indexing API", lalu klik ENABLE.
12. Sekarang kita menuju ke Google Search Console https://search.google.com/search-console/ , kamu pilih website yang ingin di index, lalu pergi ke Settingan, pilih Pengguna dan Izin. Lalu kamu tambahkan email pada step 6 , misal indexer2025@indexer2025-400203.iam.gserviceaccount.com
13. Sekarang kamu buka aplikasi Software indexing nya, misal https://github.com/gugunextra/google-indexing-script.
