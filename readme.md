# Lirik Lagu Generator
`Lirik Lagu Generator` merupakan aplikasi AI yang dapat membuat lirik lagu bahasa indonesia menggunakan deep learning. Pada project ini saya menggunakan dataset hasil [scrapping](https://github.com/share424/lyric-scrapper) dari beberapa situs penyedia lirik lagu.

## Dataset
Dataset dapat didownload [disini](https://github.com/share424/lyric-scrapper/releases/download/1/lyric_bahasa.json)

## Pretrain Model
Pretrain model dapat didownload [disini](https://github.com/share424/lyric-scrapper/releases/download/1/checkpoint.h5)

## Video Tutorial
Video tutorial cara pembuatanya dapat dilihat [disini](https://youtu.be/7IaEfd1ze2I)

## Contoh Hasil
```python
beam_search("<start> disaat ku menyendiri")

###
Generated output:

disaat ku menyendiri , kau rasakan hatiku 
kan selalu ada untukmu , kamu bilang padaku , 
kau rasakan hatiku selalu mencari 
kau rasakan aku mencari , kau rasakan aku bahagia 
kau rasakan aku mencari , mencari dirimu 
reff 
kau bilang diriku , kau yang selalu ada di hidupku 
tak perlu kamu bilang , kau tak pernah katakan 
jangan bilang bilang sayang 
kau bilang bilang cinta 
repeat reff
###
```