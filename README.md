# Kali Linux Mac address changer 'tool' ( English )
- Mac address renewal/changing tool.
 
---
 
### What's a MAC Address and how do I find it?

- Just like each house has it's own postal address, every device connected on a network
has a Media Access Control (MAC) address, that uniquely identifies it. The MAC address is tied to the Network Interface Controller (NIC), a subcomponent of the larger device. The NIC is where you make your physical connection to the network, by plugging in an Ethernet cable or connecting to a WiFi signal.

### What does a MAC address look like?

- The MAC address is a 12 digit hexadecimal number that is most often displayed with a colon or hypen separating every two digits (an sixed), making it easier to read.

> Example:

```console

 A MAC address of 2c549188c9e3 is typically
 displayed as 2C:54:91:88:C9:E3 or 2c-54-91-88-c9-e3.

```
---

### Can a device have more than one MAC address?

- Yes. For each network interface in your device, there is a unique MAC address associated with it. So if your laptop has both an Ethernet port and Wi-Fi built-in, you will see two MAC addresses in the system configuration.

### How do I find my MAC address?

- In general, you will find MAC addresses in the system settings, general information, or network settings/status of your device. Occasionally, the MAC address is printed on a label affixed to the bottom of a device.

It is important to note that manufacturers sometimes use different names to describe the MAC address, such as Hardware ID, Physical Address, Wireless ID, Wi-Fi Address, etc.


#### For Windows Computers

1. Press Start + R on your keyboard
2. In the Run window, type in cmd and click OK
3. At the command prompt, type ipconfig /all and hit Enter
4. The MAC address for each interface will be listed as Physical Address
5. For wired interfaces, look for the term Ethernet or Gigabit in the name or description
6. For wireless interfaces, look for the terms Wireless or Wi-Fi in the name or description

#### For Mac Computers

1. Open System Preferences
2. Click on the Network icon
3. Select the interface you wish to use, then click Advanced...
4. The MAC address is listed under the Hardware tab

---

# Tested On 

 Sr. | Operating System | Version | Virtual Box | VM Ware | Network Type |
--- | --- | --- | --- | --- | --- |
1 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img> | 2021.2 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">|<img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1"> |<img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |
2 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2021.1 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1"> | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1"> | <img algin="center" src="https://badgen.net/badge/Network/NAT/brown">  |
3 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2020.4 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">|<img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |
4 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2019.4 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |
5 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2018.4 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |

---

# Kali Linux Mac address yenileme/değiştirme 'aracı' ( Turkish )

- Mac adresi yenileme/değiştirme aracı.

---

### MAC Adresi nedir ve onu nasıl bulabilirim?

- Her evin kendi posta adresi olduğu gibi, bir ağa bağlı her bir cihazında
benzersiz bir şekilde tanımlayan bir Medya Erişim Kontrolü (MAC) adresine sahiptir. MAC adresi, daha büyük aygıtın bir alt bileşeni olan Ağ Arayüzü Denetleyicisine (NIC) bağlıdır. NIC, bir Ethernet kablosu takarak veya bir WiFi sinyaline bağlanarak ağa fiziksel bağlantınızı yaptığınız yerdir.

### MAC adresi neye benzer?

- MAC adresi, çoğunlukla iki haneden (altılı) ayrılan iki nokta üst üste veya kısa çizgi ile görüntülenen, okumayı kolaylaştıran 12 basamaklı bir onaltılık sayıdır.

> Örnek:

```console

  2c549188c9e3 MAC adresi tipik olarak 2C:54:91:88:C9:E3 
  veya 2c-54-91-88-c9-e3 olarak görüntülenebilir.

```
---

### Bir cihazın birden fazla MAC adresi olabilir mi?

- Evet. Cihazınızdaki her ağ arayüzü için, onunla ilişkilendirilmiş benzersiz bir MAC adresi vardır. Bu nedenle, dizüstü bilgisayarınızda hem Ethernet bağlantı noktası hem de yerleşik Wi-Fi varsa, sistem yapılandırmasında iki MAC adresi görürsünüz.

### MAC adresimi nasıl bulurum?

- Genel olarak MAC adreslerini cihazınızın sistem ayarlarında, genel bilgilerde veya ağ ayarlarında/durumunda bulabilirsiniz. Bazen MAC adresi, aygıtın altına yapıştırılmış bir etikete yazdırılır.

Unutmamanız gereken şey; Üreticilerin bazen MAC adresini tanımlamak için Donanım Kimliği, Fiziksel Adres, Kablosuz Kimlik, Wi-Fi Adresi vb. gibi farklı adlar kullanabildiğidir.

#### Windows Bilgisayarlar için

1. Klavyenizde Başlat + R tuşlarına basın
2. Çalıştır penceresinde cmd yazın ve Tamam'a tıklayın.
3. Komut isteminde ipconfig /all yazın ve Enter'a basın
4. Her arabirimin MAC adresi Fiziksel Adres olarak listelenecektir.
5. Kablolu arabirimler için ad veya açıklamada Ethernet veya Gigabit terimini arayın.
6. Kablosuz arabirimler için ad veya açıklamada Kablosuz veya Wi-Fi terimlerini arayın.

#### Mac Bilgisayarlar için

1. Sistem Tercihlerini Açın
2. Ağ simgesine tıklayın
3. Kullanmak istediğiniz arayüzü seçin, ardından Gelişmiş...'e tıklayın.
4. MAC adresi Donanım sekmesi altında listelenir

---
# Test Edildi

 Sr. | İşletim Sistemi | Versiyon | Virtual Box | VM Ware | Network Tipi |
--- | --- | --- | --- | --- | --- |
1 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img> | 2021.2 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">|<img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1"> |<img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |
2 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2021.1 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1"> | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1"> | <img algin="center" src="https://badgen.net/badge/Network/NAT/brown">  |
3 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2020.4 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">|<img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |
4 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2019.4 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |
5 | <img align="center" src="https://img.icons8.com/color/25/000000/kali-linux.png"> Kali Linux</img > | 2018.4 | <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/github/status/micromatch/micromatch/4.0.1">| <img algin="center" src="https://badgen.net/badge/Network/NAT/brown"> |

