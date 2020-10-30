# Selamat!! Anda sekarang sudah di UTS Praktikum Level 4 (Level Terakhir)
Baca instruksi yang diberikan dengan baik.


## Kelas Diagram
![Image of UTS Level 4](http://api.puro.del.ac.id/v1/file/9bb555d1ff2501ee65aef9bf914f06cd)
>Update program anda pada level 3 sehingga sesuai dengan  kelas diagram di atas. 

>**Perhatikan bahwa, pada level 4 ini, sejumlah kelas berelasi dengan interface MyInterface.**

>**Untuk mendapatkan nilai sempurna pada level ini, konsentrasi menyesuaikan kode program pada level 3 sehingga mempunyai relasi dengan interface MyInterface seperti yang ditunjukkan pada kelas diagram di atas.**

## Rubrik Penilaian 
1. **[Poin 20]** test realisasi relasi antara kelas Rumah dan MyInterface.
	
	
	> Perintah test: 
	
	
		>gradle test --tests TestRumah.testInterfaceI

2. **[Poin 20]** test realisasi relasi antara kelas Alamat dan MyInterface.

	
	> Perintah test: 
	
	
		>gradle test --tests TestRumah.testInterfaceII

3. **[Poin 30]** test realisasi method clone() pada kelas Alamat 

	
	> Perintah test: 
	
	
		>gradle test --tests TestRumah.testCloneAlamat

4. **[Poin 30]** test realisasi method clone() pada kelas Rumah 

	
	> Perintah test: 
	
	
		>gradle test --tests TestRumah.testCloneRumah


**Catatan Penting:**
1. Anda hanya boleh mengubah kode program yang ada di src\main\java
1. **Semua kode program yang ada di src\test\java  tidak boleh diubah sama sekali!!** Jika anda ubah (akan terlihat pada history), maka nilai anda langsung 0.
1. Jangan memindah-mindahkan file, biarkan setiap file di folder di mana file tersebut berada sebelumnya.
1. Pada beberapa template program sudah disediakan method yang tidak boleh diubah. Maka jangan anda ubah!
