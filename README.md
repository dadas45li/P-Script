# P-Script

Özel boot script yapmak için servis


Boot sırasında başlatılacak olan bu servis p-start betiğini çalıştıracaktır. 

Servisi durdurmaya kalktığınızda ise p-stop çalışacaktır. 

Diğer betikler için kaynak kodu inceleyiniz...

#Kurulum
1-Kaynak kodu indirin

2- Boş bir dizine çıkartın

3- Lisans dosyasını ve bu belgeyi silin

4- dpkg -b çıkartılan_yol  komutunu vererek deb paketini oluşturun.

5- dpkg -i paket.deb komutu ile kurulumu gerçekleştirin.

6- Servis otomatik olarak etkinleşecektir.

Not:Çıkartılacak yolda boşluk karakteri olmamalıdır. ayrıca dpkg -b komutuna tam yolu girin "~", "./", "../" gibi karakterler kullanmayın.
