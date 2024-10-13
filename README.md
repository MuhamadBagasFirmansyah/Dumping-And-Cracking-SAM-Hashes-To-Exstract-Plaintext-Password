# Dumping And Cracking SAM Hashes To Exstract Plaintext Password

## 1.	Yang pertama mendowload semua file pada link berikut. Setelah itu ekstrak semua filenya.
•	Table Vista free
https://sourceforge.net/projects/ophcrack/files/tables/Vista%20free/tables_vista_free.zip/download
•	PwDump7
https://github.com/Seabreg/pwdump
•	Ophcrack
https://ophcrack.sourceforge.io/download.php?type=ophcrack
![image](https://github.com/user-attachments/assets/1315c728-2ef3-43dd-b388-a471eb19b646)


## 2.	Langkah selanjutnya kita akan mengambil file hashes yang berisi username dan password user.
•	Buka CMD sebagai admin

![image](https://github.com/user-attachments/assets/bb5a766e-c662-4046-8c98-0ab6222277ac)

•	Ketik wmic useraccount get username,id

![image](https://github.com/user-attachments/assets/d5fed0f4-71ab-40bd-a6c2-320f7a855402)

•	Selanjutnya pada cmd buka folder pwdump7

![image](https://github.com/user-attachments/assets/3eccbec7-d6a3-4dd4-8737-747f9d0d2835)

•	Jalankan pwdump7.exe untuk melakukan hashes

![image](https://github.com/user-attachments/assets/5cd177af-05ff-44f7-b48e-fa601899cf64)

•	Selanjutnya akan memindahkan hasil dari pwdump7 tadi ke dalam bentuk txt

![image](https://github.com/user-attachments/assets/3a3e79b0-a1b6-49d2-a904-6591a1f7b758)

•	Berikut isi file hashes.txt nya


![image](https://github.com/user-attachments/assets/448c7b1f-fcce-42c5-81bd-e4f51802d8a0)

## 3.	Langkah selanjutnya yaitu melakukan crack file hasehes.txt menggunakan tools ophcrack 

![image](https://github.com/user-attachments/assets/2a622ea1-af7c-43d2-9311-8d3f4cb601e0)

•	Sebelum itu terlebih dahulu menginstal table pada ophcrack dengan cara berikut
•	Buka Tables

![image](https://github.com/user-attachments/assets/b6cdb348-6c6c-4369-86ad-e3c80baa0a31)

•	Pilih Vista free dan klik install

![image](https://github.com/user-attachments/assets/0889cb53-d56c-4338-953c-a8db65471769)

•	Setelah itu pilih direktori dimana file vista free di ekstrak

![image](https://github.com/user-attachments/assets/7014a9a3-aa8b-41b4-9fc3-ad4ae528e028)

•	Setelah itu akan keluar table2 dari vista free

![image](https://github.com/user-attachments/assets/994f5eb2-c5b0-412b-b695-d3afe7b66fdd)

•	Selanjutnya akan memindahkan file hashes ke ophcrack dengan cara pilih load dan pilih PWDUMP file


![image](https://github.com/user-attachments/assets/4588a58a-379d-44ce-826b-b2c87b853b3a)

•	Selanjutnya pilih file hashes nya.

![image](https://github.com/user-attachments/assets/ed215bb3-4a9b-46e3-b7e2-0284745fccc8)

•	Maka akan muncul nama user beserta hashesnya.

![image](https://github.com/user-attachments/assets/1d466eeb-279c-44a1-b94c-cd027fc179a3)

•	Selanjutnya click Crack dan tunggu Progress nya sampai selesai.

![image](https://github.com/user-attachments/assets/371b7d9f-6865-4009-a152-3fec98b0d33a)

•	Setelah proses selesai maka pada LM Pwd 1 dan 2 akan keluar password daris usernya.

![image](https://github.com/user-attachments/assets/814f603b-2c72-48f3-8e8a-6ab6aca99790)

Pada percobaan diatas kenapa not found mungkin karena sistem protection pada windows sudah makin bagus. Jadi untuk model hacking ini tidak akan bisa. Dan juga mungkin pada library tables nya kurang karena menggunakan yang free.

