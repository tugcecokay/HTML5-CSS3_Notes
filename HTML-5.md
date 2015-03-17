###YENİ ETİKETLER VE ANLAMSAL WEB

####HTML5 ile gelen yeni medya etiketleri;
 	 <audio>
 	 <video>
 	 <source>
	 <embed>
	 <track>
 	 

 - **audio:**
	 Ses ve müzik dosyalarının çalmasını sağlayana etikettir. MP3,WAV ve Ogg formatlarını desteklemektedir.
		 	
	<audio src ="ses.mp3" controls>	Tarayıcınız audio etiketini desteklemiyor.</audio>

 -  **video:**
 Video dosylarının çalmasını sağlar. MP4, WebM ve Ogg formatlarını desteklemektedir.
		 
		 <video widht ="320" height="240" controls src="video.mp4">
 		Tarayıcınız video etiketini desteklemiyor.</video>
 -  **source:**
Audio veya video gibi etiketlerin içerisinde kullanılır.Amacı aynı dosyanın farklı formatlarını listleyip desteklediği formatı seçmesini sağlamaktır.
 	
	 	<audio controls>
 		<source src="ses.ogg" type="audio/ogg">
 		<source src="ses.mp3" type="audio/mpeg"></audio>
 - **embed:**
 Harici bir uygulamanın ve ya bir eklentinin web sayfasına gömülmesini sağlar. Genişlik ve yükseklik özellikleri ile ekrandaki boyutu düzenlenebilir.
	 	
	 	<embed src="helloworld.swf"> Bu örnek swf dosyasının web sayfasının içine gömülmesini sağlıyor.
 - **track:**
  Audio ve video etiketleri içerisinde yer alıp ilgili dosyaları çalarken o dosya ile ilgili yazıların çıkmasını sağlar.
	 	
	 	<video widht="320" height="240" controls>
 		<source src="film.mp4" type="video/mp4">
 		<source src="film.ogg" type="video/ogg">
 		<track src="altyazi.vtt" kind ="subtitles" srclang="en" label="English">
 		<track src="altyazi.vtt" kind ="subtitles" srclang="tr" label="Türkçe"></video>

 	###Yapısal Etiketler

 - **header**  web sayfasının başlığını ve içindeki bazı bölümlerin başlıklarını yazmak için kullanılır.İçerik hakkında bazı bilgiler(yazar adı,yayınlanma zamanı vb.). Bir sayfada birden fazla header etiketi kullanılabilir.
	
 - **article** 'i en iyi emsil eden yazı türleri forum yazıları,blog yazıları,yorumlar... Kendi başına olabilir ve birden fazla olabilir.
 - **section** bir bölümü tanımlamak için kullanılır. Farklı konulardaki yazıları gruplamak veya bir yazı içinde farklı bölümler oluşturmak için kullanılır.
 -  **aside** ana unsur ile ilgili bilhi veren bölümdür ve kenar çubuğu(sidebar) olarak sayfada yer alır.
 -  **nav** aynı sayfa içerisinde başka bölümler ulaşmak veya başka sayfalara bağlantı vermek için kullanılır. Menü elemanıdır.
 -  **figure** kendi içerisinde resim,fotoğraf,diyagram vb. görsel elemanları içerir. ***figcaption*** ise figure etiketi içerisinde yer alır ve görsel ile ilgili kısa bilgi verir. 
 -  **footer** bulunduğu bölüm veya sayfa hakkında altbilgi içerir.

***Not:***  Bu etiketler aslında isim farklılığından çok yeni bir şey katmamıştır sadece anlam kazandırmaktadır. Bu yüzden yapısal etiketler div gibi davranırlar. CSS ile konumlarını ve genişliklerini yinegeliştiricinin ayarlaması gerekir. Eğer bu etiketleri desteklemeyen bir yazıcı kullanıyorsanız CSS olarak aşağıdaki tanımı yapmanız işinizi görecektir.
		article, section, aside, hgroup, nav, footer, figure, figcaption{ 
			display:block;
		}

###Yapısal Olmayan Etiketler

 - **bdi** bir yazının(Türkçe) içinde farklı yönde yazı (Arapça) olduğunda onu ayırmak için kullanılır.
	
 - **details** ve **summary** ayrıntı bilgi vermek için kullanılır.
	
