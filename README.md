
# Uçuş Rötarları ve İptallerinin Analizi #

Amaç: Uçakların kalkış geçikmelerini tahmin etmektir.


Veri setinde 111006 satır ve 29 değişken bulunmaktadır. 2 havaalanından kalkan uçakların 2022 yılına ait ilk 6 aylık verisinden oluşur.

Değişken açıklamaları:

- year : Yıl - 2022 yılına ait verileri kapsar.
- month: Ay - 1. ve 6. aya ait verileri kapsar.
- day: Gün - 31 günü ifade eder.
- dep_time: Uçağın gerçekleşen kalkış zamanıdır. 
- sched_dep_time: Planlanan kalkış zamanı
- dep_delay: Kalkış gecikme süresi
- arr_time: Gerçekleşen varış zamanı
- sched_arr_time: Planlanan varış zamanı
- arr_delay: Varış gecikme süresi
- carrier: Hava yolu şirketinin kısaltması
- flight: uçuş numarası ?
- tailnum: Uçak kuyruk numarası
- origin: kalkış hava alanı kodu (SEA ve PDX)
- dest: varış hava alanı kodu (97 adet havaalanı bulunmaktadır)
- air_time: Uçuş süresi
- distance: Uçuş mesafesi
- hour: Saat
- Minute: Dakika
- airline: Havayolu şirketinin adı
- route: Uçuş rotası
- temp: Sıcaklık
- dewp: Çiy noktası sıcaklığı, bir hava kütlesinin içindeki su buharının yoğunlaşmaya başladığı sıcaklık.
- humid: Nemlilik
- wind_dir: Rüzgar yönü
- wind_speed: Rüzgar hızı
- wind_gust:  belirli bir zaman dilimindeki rüzgarın en yüksek hızını ifade eder
- precip: Yağış
- pressure: Hava basıncı
- visib: Görüş mesafesi





## Installation
```bash
pip install -r requirements.txt
```
    
## License

[MIT](https://choosealicense.com/licenses/mit/)

