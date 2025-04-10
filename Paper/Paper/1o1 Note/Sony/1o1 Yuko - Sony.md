**Kerjaan masih bisa banyak yang diimprove**
* Banyak repo legacy yang ibarat kata yang belum terstruktur codenya
* Taati quality ketimbang delivery
	* Principal programming contoh **solid principle** 0 besar
		* 1 function bisa berratus line
		* Belum ada dependency version
		* Unit testing dulu baru mutation testing baru nanti ada automation
	* Langkah awal adalah document secara flow per repository
		* Routes yang dipakai yang mana dan tujuannya apa
		* API Contract per route harus diimplement
			* Orang baru tidak tahu UInya dimana
			* Masih bingung ownership dimana = shared repo
	* Ownershipnya tidak jelas contoh casenya tim payment

Action Plan:
- Owned Repository
	- Merubah design pattern = factory design
	- Kapan bisa kita execute
- Shared Repository
	- Knowledge untuk apa yang si repo ini kerjakan
	- Modenya harus bisa extend tanpa nyentuh yang lama
- Coba ngerefactor ketika ada momentnya
	- Contoh ketika ada bug terjadi


**Delivery VS Quality**

**Automatic Dependency Injection**

Happyness 7
- Kerjaan mostly CRUD - belum merasa tertantang
	- Suka explore hal baru yang dimana bisa direuse sama tim lain
	- Contoh tokped: contributor PDK yang dimana meningkatkan productivity semua tim engineer
	- Suka meremind engineer mengenai principle
	- Principle engineer

**Feedback ke Yuko**
- Udah saatnya gue mulai nerapin principle yang dibilangin dan mulai terjun dibeberapa task
- Nothing much tapi improve di bagian detailing
	- Contoh bikin playbook, coba bikin lebih detail aja