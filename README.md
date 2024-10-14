# DDAandBresenhamAlgorithm_
# Çizgi Çizim Algoritmaları ile Ev Çizimi

Bu proje, iki farklı çizgi çizim algoritması kullanarak bir ev şekli çizmektedir: Digital Differential Analyzer (DDA) ve Bresenham algoritmaları. Proje, Python'da `matplotlib` kütüphanesini kullanarak grafiksel bir temsil oluşturur.

## Algoritmalar

### 1. DDA (Digital Differential Analyzer)
DDA algoritması, bir çizgi segmentini çizmek için kullanılan bir algoritmadır. X ve Y koordinatları arasındaki farkı kullanarak, belirli adım sayısı kadar nokta hesaplar ve bu noktaları çizer.

### 2. Bresenham Algoritması
Bresenham algoritması, yalnızca tam sayı hesaplamaları kullanarak bir çizgi çizen bir algoritmadır. Bu algoritma, daha yüksek verimlilik ve daha iyi bir performans sağlar.

## Kullanım

### Gerekli Kütüphaneler
Proje, `matplotlib` kütüphanesine ihtiyaç duyar. Eğer sisteminizde kurulu değilse, aşağıdaki komutla yükleyebilirsiniz:
```bash
pip install matplotlib
