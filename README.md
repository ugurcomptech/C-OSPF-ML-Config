# Cisco OSPF Routing MultiLayer Switch Konfigürasyonu

Bu ağ tasarımında, MultiLayer Switch (Çok Katmanlı Anahtar) kullanılmış ve dinamik bir routing yapılandırması oluşturmak için OSPF (Open Shortest Path First) Routing Protokolü tercih edilmiştir. Bu yapı, ağın daha etkili ve yönetilebilir olmasına yardımcı olur. Aşağıda, OSPF Routing ve MultiLayer Switch yapılandırmasını daha ayrıntılı bir şekilde açıklayan kaynaklara ulaşabilirsiniz:


## Router ML Arası Bağlantı

MultiLayer ile Router arasında bağlantı yapmak istiyorsanız VLAN oluşturmanıza gerek yok aşağıda ki kodu MultiLayer Switche yazarsanız normal IP adresi yazabilirsiniz.

```
Switch(config)#interface fastEthernet 0/2 // yapılandırmak istediğiniz port
Switch(config-if)#no switchport
Switch(config-if)#ip address 1.1.1.1 255.0.0.0 // IP adresi
```


## OSPF Routing Nasıl Yapılır?

Bu kaynak, OSPF'nin temel konseptlerini ve Cisco cihazlarında nasıl yapılandırılacağını ayrıntılı bir şekilde açıklar. Ayrıca, farklı senaryolara uyarlanabilen adım adım yönergeler sunar.

**[OSPF Routing Nasıl Yapılandırılır?](https://github.com/ugurcomptech/Cisco-OSPF-Routing)**



## MultiLayer Switch Nasıl Yapılandırılır?

Bu kaynak, MultiLayer Switch yapılandırmasının temel unsurlarını kapsar ve Cisco ağınıza entegre etmek için gereken adımları adım adım açıklar. MultiLayer Switch kullanmanın avantajlarını ve uygulama örneklerini içerir.

**[MultiLayer Switch Nasıl Yapılandırılır?](https://github.com/ugurcomptech/Cisco-MULTILAYER-Switch-Config)**


## Bilgilendirme

Bu kaynaklar, Cisco ağınızı daha etkili bir şekilde yapılandırmanıza yardımcı olacaktır. İhtiyacınıza göre bu kaynaklara göz atabilir ve ağınızın performansını ve yönetilebilirliğini artırmak için gerekli bilgilere ulaşabilirsiniz.

## Ağ Tasarımı

![image](https://github.com/ugurcomptech/C-OSPF-ML-Config/assets/133202238/c1aee2b6-1335-4cbd-bf20-58e93b30e312)
