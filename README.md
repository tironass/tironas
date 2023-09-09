# *Tironas* (2.1/4)

![icon](https://github.com/tironass/tironas/assets/143009717/e059a824-b48a-4987-9949-14f9ff2b88d0)

**Kurulum**

apt update&upgrade

apt install python3-requests python3-colorama python3-psutil

pip install PyGithub

git clone https://github.com/tironass/tironas.git

cd tironas

pip3 install -r requirements.txt

python3 tironas.py

**Discord Botuna Ayarlama**

Bot'un çalışabilmesi için 'Privileged Gateway Intents' seçeneklerinin hepsinin aktif olması gerekmektedir.

**Token bulma:**

1- Tarayıcıdan bot olarak kullanacağınız Discord hesabına giriniz.<br>
2- Tarayıcı konsolunu açınız.<br>
3- Ağ trafiği izleme bölümüne geliniz.<br>
4- Konsolu kapatmadan, Discord'da bu oturum boyunca tıklamadığınız bir sohbete tıklayınız.<br>
5- Sonu *messages?limit=50* ile biten isteğe tıklayınız.<br>
6- İsteğin *Header* kısmındaki *Authorization* değeri sizin token'ınızdır.<br>
7- Bu token'ı *discord-selfbot-tironas.py*'de *token* kısmına yazınız. (str olarak)<br>

**Chat Id Bulma:**

1- Bot hesabı ile mesajlaşacağınız kendi orijinal hesabınızdan bot'a bir tane mesaj atınız.<br>
2- Tarayıcıda Discord'u açın ve bot hesabına giriş yapınız, ardından gerçek hesabınızın üzerine tıklayın.<br>
3- Url'deki *@me*'den sonraki sayı sizin sohbet id'nizdir.<br>
4- Bu id'yi *discord-selfbot-tironas.py*'de *chat_id* kısmına yazınız. (int olarak)<br><br>
**Not:** Eğer bot'u Discord sunucusunda kullanacaksanız, *channels*'dan sonra gelen, taksim ile ayrılmış iki sayıdan ikincisi sohbet id'nizdir.
