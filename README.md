# Aygaz - Generative AI Kampı - Prompt Mühendisliğine Giriş (Global AI Hub) #


Yapay Zeka Komutlarıyla Bir Web Sitesi Oluşturma


## Proje İsterleri ##


**Portfolio / Galeri Web Sitesi**

Bu projede, yapay zeka araçlarını kullanarak ürettiğiniz görsel ve metinleri, yine bu araçlar yardımıyla geliştireceğiniz HTML
tabanlı bir web sitesinde sergilemeniz beklenmektedir.

**Örnek Araçlar**

**• Canva:** Görsel içeriklerin tasarlanması için kullanılabilecek bir platform.
**• DALL-E:** Yaratıcı görsel içeriklerin oluşturulması için kullanılabilecek bir yapay zeka modeli.
**• Artbreeder:** Fotoğraf ve görsellerin birleştirilmesi ve manipülasyonu ile yeni sanat eserleri üretmek için kullanılabilecek bir 
platform.
**• DeepDream:** Görsellerin halüsinasyon benzeri manipülasyonları için kullanılabilecek bir yapay zeka aracı.
**• Bard, CopyWrite, ChatGPT:** Metin içeriklerinin üretilmesi için kullanılabilecek yapay zeka tabanlı araçlar.

**Not:** ***Bu araçların kullanılması zorunlu değildir, fikir edindirmek için verilmiştir. Katılımcılar diledikleri GPT asistan(lar)ını kullanarak bu projeyi gerçekleştirebilir.***

1) **Web Sitesinin Yapay Zeka ile Oluşturulması:** Web sitesinin yapay zeka araçları kullanılarak prompt'larla oluşturulması ve bu 
prompt'ların proje klasöründe yer alması gerekmektedir.

**Not:** ***HTML&CSS gerekli ve yeterlidir, Javascript benzeri teknolojileri de opsiyonel olarak kullanabilirsiniz.***

2) **Yapay Zeka ile Oluşturulan İçerikler:** Proje içerisinde en az bir görsel ve bir içeriğin yapay zeka araçları ile oluşturulması 
zorunludur. Bu içeriklerin üretiminde kullanılan prompt'ların proje klasöründe yer alması gerekmektedir.

3) **Semantik Etiketlerin Kullanılması:** Web sitesinin HTML yapısında, semantik etiketlerin ***(header, main, nav, section, article, aside, footer)*** kullanılması beklenmektedir.

4) **Responsive Tasarım(Opsiyonel):** Oluşturulan web sitesi, farklı cihaz ve ekran boyutlarına uyumlu olmalıdır. Mobil, tablet ve 
masaüstü cihazlarda düzgün bir şekilde görüntülenmeli ve kullanıcı deneyimini artırmak için tasarımın her boyutta optimize edilmiş 
olması gerekmektedir.


## Proje Yapım Aşaması ##

Bu kampta yapım için verilen "Portfolyo" veya "Galeri" web sitesi seçenekleri arasından tercihimi "Portfolyo" web sitesinden yana 
kullandım. Konsept olarak, bir oyun tasarımcısının projelerine ve kendisi hakkında kısa bir bilgilendirme bölümüne yer verdiği web 
sitesi yapımını belirledim. 

Gerçek kişi ve kurumları yansıtmaması adına oluşturacağım web sitesi için bir de hayali bir karakter yaratmak istedim. Bunu oluştururken 
Gemini'ye şu promptu yazdım: 

"Bir oyun tasarımcısı için portfolyo sitesi oluşturuyorum. Bu sitenin sahibinin bir erkek olmasını istiyorum. Fakat random bir isim 
soyisim karar veremedim. Bana bir isim soyisim örneği verebilir misin? Eşsiz olursa sevinirim."

Ardından sunmuş olduğu seçenekler arasından "Deniz Kayra" kombinini seçtim.

HTML, CSS ve JavaScript kodlarından oluşan bu portfolyo web sitesinin yapımı için ChatGPT 3.5 üzerinden verdiğim ilk prompt şu oldu:

"Tasarım konusunda uzmanlaşmış, yaratıcı projeleriyle sektöründe öne çıkmış profesyonel bir FrontendDeveloperGPT'siniz. Sizden burada, 
bir Front-End Web Developer olarak hareket etmenizi istiyorum.

Web sitesi tasarımlarıyla adından sık sık söz ettiren, şirketlerin arayıp da bulamadığı yeteneğe sahip tam donanımlı bir web sitesi 
oluşturma uzmanısınız.

Oyunlara karakter tasarımlarıyla ve oyun yapımıyla ilgilenen deneyimli bir oyun tasarımcısı, sizden kendisi için görsellerin ve görsel 
efektlerin ön plana çıktığı bir portfolyo sitesi hazırlamanızı istedi. Siz bu web sitesini kodlayacaksınız. Kodlarken; HTML5, CSS3 ve 
JavaScript teknolojilerini kullanacaksınız. Oluşturduğun web sitesi mobil uyumlu ve duyarlı olmalıdır.

Ayrıca düzen ve stil açısından site, yapısında kullanılan teknolojilerin en üst sürümlerini içermelidir.

HTML, CSS ve JavaScript kodlarını ayrı çıktılar olarak vermen çok önemlidir.

Ayrıca sayfa içeriğindeki başlıklara dahili bağlantılar içeren bir gezinme menüsü de eklemelisiniz.

Yazdığınız kodların hiçbirine bir açıklama satırı eklemeyin.

Her şeyi anlıyor musunu? Tüm gereklilikleri anladıysanız lütfen evet, anlamadıysanız lütfen hayır yanıtını verir misiniz?"


Bu prompt sonrasında almış olduğum olumlu yanıtın ardından projenin amacını içeren şu promptu yazdım:

**Prompt (ChatGPT 3.5) :**
"AMACINIZ:
Web sitesi bir oyun tasarımcısının 4 adet oyun çalışmasını içeren bir portfolyo sitesi olmalıdır. Web sitesinde, "Semantic HTML" 
tag'lerinin yani "header, nav, main, article, figure, p, section, aside, footer" tag'lerinin yer almasını istiyoruz. Bana bu web 
sitesini oluşturmamda yardımcı olabilir misin? Eğer cevabınız evetse istenilen özelleştirmeler için size detay vermek istiyoruz."

**Gelen Cevap:** "Evet, kesinlikle size yardımcı olabilirim. Lütfen istediğiniz özelleştirmeleri detaylı olarak belirtin, böylece web 
sitesini istediğiniz şekilde oluşturabilirim."

Bunun üzerine Gemini'ye dönüp bu sefer oyun isimlerine karar verme konusunda aşağıda yer alan promptları kullandım:

1) Cyberpunk 2077 isimli bir oyun için benzer bir isim önerisinde bulunabilir misin? (1. oyun için 'Neo-Tokyo' önerisi seçildi.)
2) "ghost of tsushima" isimli bir oyun için benzer bir isim önerisinde bulunabilir misin? (2. oyun için 'Reikon no Shima' önerisi seçildi.)
3) Valorant, League of Legends tarzında içerisinde birden fazla karakterlerin yer aldığı benzersiz bir oyun ismi istiyorum. (3. oyun için 
   'Stars of Chaos' önerisi seçildi.)

**Prompt (ChatGPT 3.5) :**
"Deniz Kayra" isimli oyun tasarımcımız;
1- "Neo-Tokyo"
2- "Reikon no Shima"
3- "Stars of Chaos"
4- "Master League" 
isimlerine sahip 4 adet oyun projesinde yer almıştır. Bu 4 oyunun ilk ikisinde tek bir ana karakter, diğer ikisinde ise üç adet 
seçilebilir karakter yer almaktadır. 

Sitenin giriş sayfasının arka planında belli süre aralıklarıyla, görev almış olduğu oyun projelerinin görselleri geçiş yapsın 
istiyorum. Görsel gelsin, sonra soluklaşıp koyulaşarak diğer görsele geçsin.

Sitenin üst kısmında yer alacak navbar'da "portfolyo" sekmesi adı altında görselli ve açıklamalı detaylarıyla birlikte yapmış olduğu 
4 projeyi, "hakkımda" sekmesi adı altında kısa ve öz şekilde hazırlanmış kendisini tanıtan bir yazıyı (eğitim bilgileri, yetenekler, 
kullandığı teknolojiler), "iletişim" sekmesi adı altında ise "BANA ULAŞIN" başlıklı bir iletişim formu istiyoruz. Navbar da şeffaf 
olsun, sitenin arka planı geçişlerle birlikte gözükebilsin. Büyük harflerle "DENİZ KAYRA" şeklinde bir başlık olsun, üstünde de küçük 
ama okunabilir harflerle "Benzersiz Tasarımlar Arayanların Adresi..." yazsın. İsminin altında da küçük bir açıklama olarak "Oyun ve 
karakter tasarımında uzmanlaşan, deneyimli bir bağımsız oyun tasarımcısıyım..." yazsın. Ardında sayfayı aşağı doğru kaydırdığımızda 
"PORTFOLYOM" başlıklı kısım gelsin. Bu kısmın altında oyunlar sıralanacak. Oyunlar sıralanırken bulunmuş olduğu kısmın sol tarafında 
oyunun görseli sağ tarafında ise oyunun açıklaması yazsın. Aşağı doğru kaydırdıkça bir üstteki oyunun görseli soluklaşsın.

Sayfanın en altında da "BAŞA DÖN" yazısı ve ok işaretinin yer aldığı bir buton olsun. Bu butona basıldığında sayfanın en üstüne çıkalım."

Cevap: "Anladım. İstenilen özellikler doğrultusunda bir tasarım yapacağım. İşe başlamadan önce, her bir oyun projesi için kullanılacak 
görsellerin ve ilgili açıklamaların bir listesini hazırlamanız gerekecek. Ayrıca iletişim formu için hangi alanların bulunmasını 
istediğinizi de belirtmeniz gerekecek. Bu bilgileri sağlarsanız, tasarımı oluşturmaya başlayabilirim."

Bu cevap üzerine Gemini'ye dönüp oyunların açıklamalarıyla ilgili şu promptları yazdım:
1) Neo-Tokyo isimli bir oyunum var. Bu oyun Cyberpunk 2077 oyunundaki gibi bir evrende yer alıyor. Bunu tanımlayacak kısa bir açıklama yazısı yazar mısın?
2) Reikon no Shima isimli bir oyunum var. Bu oyun Ghost of Tsushima oyunundaki gibi bir evrende yer alıyor. Bunu tanımlayacak kısa bir açıklama yazısı yazar mısın?
3) Stars of Chaos isimli bir oyunum var. Bu oyun Valorant, League of Legends benzeri oyunlardaki gibi bir evrende yer alıyor. Bunu tanımlayacak kısa bir açıklama yazısı yazar mısın?
4) Master League isimli bir oyunum var. Bu oyun Kerbal Space Program, Mass Effect 2, No Man's Sky, Observation, Outer Wilds, Star Conflict,
Star Trek Online, Star Wars: Squadrons, The Outer Worlds, Universe Sandbox 2 benzeri oyunlardaki gibi bir evrende yer alıyor. Bunu tanımlayacak kısa bir açıklama yazısı yazar mısın?

**Prompt (ChatGPT 3.5) :** 
"Kullanılacak görselleri yerleştireceğiniz tag'leri boş bırakırsanız ben oralara sonradan görselleri yerleştirebilirim. 

Oyunlarla ilgili açıklamalar ise şöyle:
1 - Neo-Tokyo: Neon ışıklı gökdelenlerin gölgelerinde, yakuza çeteleri, teknolojiyle yozlaşmış şirketler ve sokak samurayları
karanlık bir güç mücadelesine girmiş durumda. Bu distopik megakentte hayatta kalmak için her şey mübah.

2 - Reikon no Shima: Sisle kaplı dağların ve gizemli tapınakların gölgesinde, unutulmaz bir maceraya adım atmaya hazır olun. 
Ruhlar Adası'nın efsaneleri kulağınıza fısıldayacak, sizi geçmişin savaşlarına ve kayıp kahramanların hikayelerine sürükleyecek.

3 - Start of Chaos: Farklı yeteneklere sahip karakterlerin beceri dansında kaybolmak, stratejinin ve reflekslerin bir araya
geldiği savaşın coşkusunu yaşamak için hazır mısınız? Her köşesi gizem ve heyecan fısıldayan kaotik bir evrene adım atın.

4 - Master League: Uzayın sonsuzluğuna açılan bir kapıdan içeri adım atmaya, yıldızların arasında kendi kaderinizi çizmeye hazır 
mısınız? Master League, sizi uzayın gizemli ve heyecan verici dünyasına davet ediyor.

İletişim formunda;
Adı,
Soyadı,
E-posta*
Konu
Başlıklarının olduğu ve "Bana mesaj bırakın..." ifadesinin yer aldığı bir text-box yer alsın. En altında da "Gönder" butonu olsun."

**Cevap:** "Anladım. Şimdi tasarımı oluşturmak için işe koyulacağım. İşlem tamamlandığında size kodları sunacağım. Başlamadan önce son 
bir sorum olacak: İletişim formunda "Konu" alanı için belirli bir liste mi istiyorsunuz, yoksa kullanıcıların serbestçe bir konu 
belirlemesine izin mi vermek istiyorsunuz?" 

**Prompt (ChatGPT 3.5) :** "İletişim formunda "Konu" alanı için kullanıcılar serbestçe bir konu belirleyebilsin, kendi konu başlığını 
kendisi yazsın."

**Prompt (ChatGPT 3.5) :**
"Sitenin header kısmının arka planında bilgisayarımda yer alan "_c5396954-6f88-4a67-8701-a4d3d0391791.jfif" isimli görsel yer alacak.

Neo-Tokyo isimli oyun için bilgisayarımda yer alan "_32b1dc9a-4072-452d-a150-f4690fb0f9cd.jfif" isimli görsel kullanılsın.

Reikon no Shima isimli oyun için bilgisayarımda yer alan "_3040f8fb-f509-4fc4-bf9a-3c20113e844f.jfif" isimli görsel kullanılsın.

Start of Chaos isimli oyun için bilgisayarımda yer alan "_f3d2e720-f318-4f8d-9b5a-40cb2e05dbe3.jfif" isimli görsel kullanılsın.

Master League isimli oyun için bilgisayarımda yer alan "_b89a9bb7-c489-49ab-ab5f-402fb7582512.jfif" isimli görsel kullanılsın.

Bu güncellemeler doğrultusunda kodları yeniden oluşturabilir misin? 
Ayrıca oyun tanımlamalarını da yazmamışsın, onları ekler misin?"

**Prompt (ChatGPT 3.5) :** "Görsel çok fazla zoomlanmış bir şekilde geldi. Bunu web sayfası görünümüne nasıl sığdırabilirim. Gerekise 
sağ ve sol tarafa siyah bölümler ekleyebilirsin. Görselin orijinal boyutu 1024 x 1024"

**Prompt (ChatGPT 3.5) :** "Başlıkta yer alan yazılar gözü yormayacak şekilde farklı fontlarda olsun."

**Prompt (ChatGPT 3.5) :** "Arial'den daha güzel bir font bulabilirsin.."

**Prompt (ChatGPT 3.5) :** 
"Benzersiz Tasarımlar Arayanların Adresi...
DENİZ KAYRA yazılarını italic ve arka planla uyumlu bir renkte,
Oyun ve karakter tasarımında uzmanlaşan, deneyimli bir bağımsız oyun tasarımcısıyım... yazısını italic ve rengini beyaz yapalım"

**Prompt (ChatGPT 3.5) :** "Portfolyo başlığı ve Açıklama yazıları da görsellerin başlangıç ve bitişleri ile aynı hizada olsun"

**Prompt (ChatGPT 3.5) :** "Bu şekilde sadece oyunların başlıkları sayfaya ortalandı. Ben bu şekilde istemiyorum. Görsellerin başladığı 
yerden başlasın. Yani şu anda görseller sayfaya ortalı bir şekilde bulunuyor. yazıların da sayfanın kenarlarında görsellerle aynı 
eşitlikte boşluk bırakacak şekilde yer almasını istiyorum."

**Prompt (ChatGPT 3.5) :** "Her görseli ayrı ayrı 12 cm x 12 cm boyutunda bir kutucuk içerisine alabilir misin"

**Prompt (ChatGPT 3.5) :** "Görsellerin köşelerini ve bulunduğu kısmın kutucuk köşelerini yuvarlatmanı istiyorum"

**Prompt (ChatGPT 3.5) :** "Başlıkları ve Açıklama yazılarının fontlarını daha büyük yazmak istiyorum."

**Prompt (ChatGPT 3.5) :** "Açıklama yazılarının sayfanın solunda da aynı hizada bitmesini istiyorum. Word dosyasındaki "yasla" komutu gibi."

**Prompt (ChatGPT 3.5) :** "Açıklama ve oyun başlıklarının fontlarını biraz daha büyütmek istiyorum. Özellikle oyun başlığının."

**Prompt (ChatGPT 3.5) :** "Görseller arasındaki boşlukları biraz arttıralım"

**Prompt (ChatGPT 3.5) :** "PORTFOLYOM yazısı en üstteki görselden biraz daha ayrışsın"

**Prompt (ChatGPT 3.5) :** "Bu yazı fontlarını sevmedim. İnternet üzerinden bir yazı fontu da kullanabiliriz. Örneğin Google Fonts'ta 
güzel fontlar var. Bu projeye uyumlu olabilecek olanları ekler misin?"

**Cevap :** "Tabii, Google Fonts'tan uygun bir yazı tipi seçelim. Önerileriniz var mı? Hangi tarzda bir font tercih edersiniz? Örneğin, 
daha modern, şık, klasik veya gösterişli bir font arıyor musunuz?"

**Prompt (ChatGPT 3.5) :** "Evet. Daha modern, şık ve gösterişli bir font arıyorum"

**Cevap :** "Anladım, o zaman "Montserrat" adlı bir Google Font'u kullanabiliriz. Bu font, modern ve şık bir görünüme sahiptir. Ayrıca 
görsellerinizle uyumlu olacaktır. Kodlarınıza ekleyelim:"

**Prompt (ChatGPT 3.5) :** "Header kısmında yer alan arka planın biraz daha puslu görünmesini istiyorum."

**Prompt (ChatGPT 3.5) :** "Böyle olunca yazılar da bulanıklaştı. Yazılar bulanıklaşmasın"

**Prompt (ChatGPT 3.5) :** "Arka plan değişmiyor. Blurlu hali güzeldi aslında ama yazılar okunmuyordu."

**Prompt (ChatGPT 3.5) :** "NAVBAR'daki yazıların arasını biraz açar mısın?"

**Prompt (ChatGPT 3.5) :** "Aralarına çizgi koyabilir misin?"

**Prompt (ChatGPT 3.5) :** "Her portfolyo-item'in içerisindeki divlere kendi görsellerine uygun renklerde bir arka plan rengi ve 
yazılara da arka plana uygun bir yazı rengi vermek istiyorum."

**Prompt (ChatGPT 3.5) :** "Sayfanın en altında yer alan "Başa Dön" butonuna bastıktan sonra yavaş yavaş yukarı çıkmasını istiyorum. 
Bunu nasıl yapabiliriz?"

**Prompt (ChatGPT 3.5) :** "NAVBAR'da yer alan HAKKIMDA kısmına geçelim. Burası için şöyle bir şey istiyorum:
HAKKIMDA yazısına tıklandığında yavaş bir geçiş efektiyle "DENİZ KAYRA" başlıklı bir sayfaya yönlendirsin. Ama bu sayfanın 
üstünde navbar yine aynı özelliklerle gözüksün."

**Prompt (ChatGPT 3.5) :** "Başka bir sayfaya yönlendirmesin de Oyunlar listelendikten sonra oyunların altına listelensin"

**Prompt (ChatGPT 3.5) :** "Şimdi senden giriş sayfasının alt kısmına bir hakkımda bölümü eklemeni istiyorum. NAVBAR'da yer alan 
HAKKIMDA butonuna tıklandığında sayfanın altında, oyunlardan sonra gelen 'HAKKIMDA' başlıklı hakkımda bölümüne gitsin."

**Prompt (ChatGPT 3.5) :** "Bu section tagleri arasında görsel sayfanın sağında yazılar ise solunda olsun istiyorum. Bunu yapan 
HTML ve CSS kodlarını yazar mısın?"

**Prompt (ChatGPT 3.5) :** "Sayfanın en altına İLETİŞİM başlığı adı altında bir form koymak istiyorum. Bunun HTML ve CSS kodları 
nasıl olmalıdır?"

**Prompt (ChatGPT 3.5) :** "ADI, SOYADI, E-POSTA, KONU ve Bana Mesaj Bırakın isimli bir text-box olmasını istiyorum. Bunun kodlarını 
yazar mısın?"

**Prompt (ChatGPT 3.5) :** "CSS kodlarını da yazar mısın? kutucuklar şeffaf olsun"

**Prompt (ChatGPT 3.5) :** "Tüm alanları doldurması zorunlu olsun"

**Prompt (ChatGPT 3.5) :** "Oyunların açıklama yazılarının altın o oyuna ait çıkış yılı, oyun türü, platformlar ve projedeki görev 
bilgisi yer alsın istiyorum. Bu bilgiler alt alta yer alsın. Çıkış yılı yazısından sonra araya navbardaki gibi bir çizgi koyup 
tarih bilgisini eklemeni istiyorum. Aynı şekilde diğer bilgiler için de bu araya çizgi koyma geçerli olsun. çıkış yılı, oyun 
türü, platformlar ve projedeki görev yazıları bold olurken karşılıkları normal olsun "

**Prompt (ChatGPT 3.5) :** "Bir web sitesi tarayıcıda açıldığında tarayıcının üst kısmında sitenin adının yanında küçük bir icon 
bulunuyor. Bunu kendi web siteme nasıl ekleyebilirim?"

**Prompt (ChatGPT 3.5) :** "Linkini verdiğim görseli projenin HTML kısmına favicon olarak ekleyen kodu verir misin?"


Oyunların görselleri oluşturulurken "Microsoft Copilot" isimli yapay zeka aracının "Designer" kısmı kullanılmıştır. Bu aşamada 
her oyun için aşağıdaki promptlar yazılmıştır:

1) I have a game called Neo-Tokyo. The description of this game is as follows: In the shadows of neon-lit skyscrapers, yakuza 
gangs, technologically corrupt corporations and street samurai are engaged in a dark power struggle. In this dystopian megacity, 
anything is possible to survive. Can you design me a game visual that fits this description?

2) I have a game called Reikon no Shima. The description of this game is as follows: In the shadow of mist-covered mountains and 
mysterious temples, get ready to embark on an unforgettable adventure. The legends of the Isle of Souls will whisper in your ear, 
dragging you into the battles of the past and the stories of lost heroes. Can you design me a game visual that fits this description?

3) I have a game called Start of Chaos. The description of this game is as follows: Are you ready to get lost in the skill dance 
of characters with different abilities, to experience the euphoria of war where strategy and reflexes come together? Step into a 
chaotic universe where every corner whispers mystery and excitement. Can you design me a game visual that fits this description?

4) I have a game called Master League. The description of this game is as follows: Are you ready to step through a door to the 
infinity of space and draw your own destiny among the stars? Master League invites you to the mysterious and exciting world of space. Can you design me a game visual that fits this description? (with spaceships)


Sitenin başlık kısmında kullanılan arka plan görseli yine "Microsoft Copilot" isimli yapay zeka aracının "Designer" bölümü 
kullanılarak hazırlanmıştır. Şu prompt kullanılmıştır:
"Can you draw a background for a game designer's portfolio site? Let it be a futuristic design."


Hakkımda kısmında kullanılan logo tasarımı yine "Microsoft Copilot" isimli yapay zeka aracının "Designer" bölümü kullanılarak 
hazırlanmıştır. Şu prompt kullanılmıştır: 
"Can you create a creative logo with your initials for a professional game designer named "Deniz Kayra"?"

## Değerlendirmeler ##

**Global AI Hub'ın "Aygaz - Generative AI Kampı - Prompt Mühendisliğine Giriş" isimli düzenlemiş olduğu bu etkinlik kapsamında hazırlanan bu projede 'Google Gemini', 'ChatGPT 3.5' ve 'Microsoft Copilot' kullanılmıştır. Efektif olması açısından görsellerin promptları İngilizce olarak verilmiştir.**

**Bu proje bana, yapay zeka araçlarının biz yazılım geliştiricilerine ne kadar çok fayda sağladığını ve yaratıcılık konusunda ne kadar başarılı olduklarını bir kez daha göstermiştir. Şu an için onlarla promptlar aracılığıyla açık ve net bir şekilde konuşarak onları doğru bir şekilde yönlendirerek istediğimiz çıktıları elde edebilmekteyiz. Tabi eksik olduğu noktalar da mutlaka var. Bu noktalardan kaynaklı projenin hazırlanma aşamasında zaman zaman zorluklar da yaşatmış olup gerekli aşamalarda müdahalelerde bulunulmuştur.**

**Eksponansiyel bir hızla ilerleyen bu sektördeki gelişmeleri yakından takip edip bana en faydalı olacak şekilde kullanmaya devam edeceğim...**