TR - TÜRKÇE
Merhabalar, 
Çok uzun zamandır para piyasaların içerisindeyim ve bu süreçte çok şey öğrendim ve başarısız oldum ta ki Yapay zekanın bu kadar gelişmesine kadar. Daha önce python finans botları çok sefer denedim fakat çok fazla borsa ve yazılım gerekiyordu bazı kütüphaneler doğru düzgün çalışmıyordu. Excelden dashboard yapıp bazı indikatörleri ekleyip internetten bilgileri çekerek piyasa yönü belirlemeye çalıştım. 
Docker üzerinde kurduğum n8n ise bunların hepsini çok kolay bir şekilde sunuyor. 

![image](https://github.com/user-attachments/assets/57e1acbb-daf9-4b27-8f91-a183eecff7af)

Kısaca yaptğımı anlatacak olursam, Borsa İstanbul verilerini kısaltmasını girerek bunu kodumuzla filtreleyip basit bir garfiğini çizip GPT ile bize yazdırıyoruz. Ek olarak internetten hissenin haberlerini
yapay zeka içerisinde özetleyip bize veriyor.

GÜÇLÜ YÖNLERİ:
+ Fazla kod kullanmadan yerel bilgisayarda kullanabilmek ve değiştirebilmek.
+ Maliyetin oldukça düşük olması.
+ İnternetteki haberleri anında analiz içinde vermesi.

ZAYIF YÖNLERİ:
- GPT kullanıldığı için bir limitin olması ve ya ücret ödemek gerekmesi.
- Teknik analizlerin bulunmaması.

GELECEK İYİLEŞTİRME VE GÜNCELLEMELER
1- GPT yerine daha ucuz ve ya ücretsiz bir yapay zeka aracı ile bütün analizlerin yapılması.
2- Teknik analizlerin getirilmesi.
3- Kripto piyasası eklenmesi.
4- ABD borsası eklenmesi.
...

HEDEF:
Hedeflenen yer ise tam anlamıyla otomasyon ile piyasaların okunması alım satım fırsatları veren %10 üzerinde kar ettiren tam anlamıyla yapay zekaya bağlı bir finans botu geliştirmek.

KAYNAKÇALAR:
* Hisse verilerini çekmek için -> https://api.collectapi.com/economy/hisseSenedi 
* Grafik -> https://quickchart.io/chart/create
* Haberler için -> https://serpapi.com/users/sign_in

EN - ENGLISH
Hello,

I have been involved in financial markets for a long time, and throughout this journey, I have learned a lot and faced failures—until artificial intelligence advanced to this level. In the past, I tried Python-based finance bots multiple times, but they required too many exchanges and software, and some libraries didn’t work properly. I also attempted to create a dashboard in Excel, adding some indicators and pulling data from the internet to predict market trends. However, n8n, which I set up on Docker, makes all of this much easier.

![image](https://github.com/user-attachments/assets/57e1acbb-daf9-4b27-8f91-a183eecff7af)

Brief Overview of My Project, By entering a stock code from Borsa Istanbul, my system filters the data with a script, generates a simple chart, and uses GPT to interpret it. Additionally, it fetches and summarizes news related to the stock using AI.

Strengths:
+ Can be used and modified on a local computer with minimal coding.
+ Very low cost.
+ Instantly analyzes online news.

Weaknesses:
- Limited due to GPT usage or requires payment.
- Lacks technical analysis features.

Future Improvements & Updates:
1- Replacing GPT with a cheaper or free AI tool for full analysis.
2- Integrating technical analysis features.
3 - Adding the crypto market.
4- Adding the US stock market.
...

Goal:
The ultimate goal is to develop a fully automated AI-powered finance bot that analyzes markets and provides trading opportunities with over 10% profit potential.

Resources:
* Stock market data: -> https://api.collectapi.com/economy/hisseSenedi 
* Graph -> https://quickchart.io/chart/create
* News analysis -> https://serpapi.com/users/sign_in

