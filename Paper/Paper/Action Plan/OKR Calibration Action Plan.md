**Problem Definition**

- Terlalu banyak hal hal yang didevelop itu repo yang shared ketimbang repo yang owned sehingga definisi improvement semakin membingungkan
	- Kornel: **Focused on we have owned for now**
		- paper-workflow
			- Workflow yang suka ilang ilangan
		- paper-tax
		- paper-bimasakti
		- paper-signing
		- 
- Perubahan kultur yang semakin dinamis dan berubah seperti yang awalnya itu menganggap bahwa OKR itu secara team tapi sekarang penilaiannya menjadi individu
	- Kornel: Ngobrol sama Yoedi
	- Waktu meeting yang harusnya limited (5 jam per sprint) ternyata banyak banget (harus interview terus)
		- Kornel: Definitely we are hiring banyak, dan emang harus bisa dibagi waktunya dan jangan khawatir bahwa pasti akan dilihat sama management
- Improvement itu masih belum clear goalsnya apa (termasuk dari gue, yang dimana management itu butuhnya yang clearnya seperti apa?)
	- Kornel: as straightforward as, problem apa dan kita bisa solve apa? Thinking process untuk problem awareness ini yang harusnya bisa ditingkatkan
- Ada assumption bahwa management itu tidak melihat secara case by case basis dan terlihat menyamaratakan OKR goals ini dari 1 BU ke BU yang lain, padahal MLE itu adalah special case yang tidak begitu priviledge untuk mendapatkan slot time buat improvement (mengingat kita masih banyak yang harus dikejar dalam hal fitur, cuma bukan berarti tim product ga mau)
	- Kornel: Kalau ada improvement, tetep perlu diassess bahwa untuk alokasi. Dibutuhkan untuk RFC terlebih dahulu.
- Achievement burning ticket not 100%
	- Gangguan tengah sprint
	- Overestimating / Underestimate (estimation still pain points)
	- Outside Meetings (meetings AFAIK should be 5 hours per sprint allocated for the developers)
	- (it's on me) seldom doing the split task (if the task is too big)

**Suggestion**

- Perlu dimasukin angka-angkanya dulu (Kornel)
	- Angka rating setiap orang
- **First and foremost we need to maintain coding standard**, hopefully this can be also applied on the shared repository as well
	- [Use SOLID principle](https://forreya.medium.com/the-solid-principles-writing-scalable-maintainable-code-13040ada3bca) - Need Sony to made the RFC and share with everybody
		- Strict PR Review
		- Separate code for any changes that MLE used if it's on the same flow (separating ownership) if possible
		- Use inline comments if any to made the communication clearer
	- Focus on visibility & monitoring effort while development
		- Adding to New Relic Dashboard - Using Pulumi
		- Kibana still unreliable while being hit by multiple services at once, often down
- Achieving H1 OKR
	- 3rd point improvement
		- Need to make a clear definition of what defines as "reliability improvement that matters"
	- Need to modify the report to include the changes since latest shake up ONLY (if applicable)
	- On call itu juga musti dijadikan gimana agar lebih managable
- Sandbox

