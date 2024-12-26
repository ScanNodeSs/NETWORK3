# NETWORK3
![image](https://github.com/user-attachments/assets/df2f0e41-9104-467a-a9d9-25bd8d08912c)


1.KAYIT

Öncelikle Aşağıdaki linkten kayıt olmanız gerekiyor
Önemli not:Eğer hazli hazırda pc den node çalışıyorsa ona eklenti yapılamıyor yeni bir hesapla giriş yapmanız gerekiyor 
her node için bir hesap bir node şeklinde oluyor.

LİNK:https://account.network3.ai/register_page?rc=31ba2ff4

2.KURULUM

En düşük sunucu kiralayıp terminali açıyoruz ve aşağıdaki kodları giriniz

Daha sonra kurulum yapacak bir yerde y/n diye soracak y basınız

Bir süre sonra size key verecek =(eşittir) dahil o kodu bir yere kayıt ediniz





```shell
cd
sudo apt update
sudo apt install wireguard


wget https://network3.io/ubuntu-node-v2.1.0.tar

tar -xf ubuntu-node-v2.1.0.tar

sudo apt-get install net-tools

/sbin/ifconfig eth0 up
cd ubuntu-node
sudo bash manager.sh up
sudo bash manager.sh key
```
Eğer anahtarı(key) sogrulamak istiyorsanız aşağıdaki koduy giriniz
```shell
sudo bash manager.sh key
```
3.TARAYICIDA KURULUM

Aşağıdaki yere ipadresi yazan yeri silip sunucunuzun ip adresini yazınız ve başka hiç bir şey değiştirmeden hepsini kopyalayınız

ve tarayıcınıza yapıştırınız 

Lütfen uygulamaya e-mail ve şifrenizle giriş yapınız.Aksi durumda key girme kutucuğu gözükmeyecektir

Link:https://account.network3.ai/main?o=IPadresi:8080

aşağıdaki gibi bir ekran gelecek sol tarafta node connected yazan yerde +(artı) işaretine basınız ve açılan kutucuğa key giriniz

Bir müddet sonra puanlar gelmeye başlayacak 

Ayrıca wallet entagrasoynuda geldi sol veya eth cüzdanı bağlayın

Öneri:okex wallet sol veya eth cüzdanı import edip bağlayabilirsiniz

Henüz güncelleme gelmediğinden puanlar görünmeyebilir

![image](https://github.com/user-attachments/assets/3e26c626-1079-41ff-8658-926086f1badb)




CoreNode ekibine teşekkürler.

