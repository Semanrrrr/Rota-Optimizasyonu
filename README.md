# Rota-Optimizasyonu

#Sürücüsüz Metro Simülasyonu : İki istasyon arasındaki en hızlı ve en az aktarmalı rotayı bulan bir simülasyon.
#Python dilinde yazılmıştır.
#Collections ve heapq kütüphaneleri kullanılmıştır.
#BFS algoritması ile kuyruk/(queue) kullanılmıştır.

#=== Test Senaryoları ===
#1. AŞTİ'den OSB'ye:
#En az aktarmalı rota: AŞTİ -> Kızılay -> Kızılay -> Ulus -> Demetevler -> OSB
#En hızlı rota (25 dakika): AŞTİ -> Kızılay -> Kızılay -> Ulus -> Demetevler -> OSB

#2. Batıkent'ten Keçiören'e:
#En az aktarmalı rota: Batıkent -> Demetevler -> Gar -> Keçiören
#En hızlı rota (21 dakika): Batıkent -> Demetevler -> Gar -> Keçiören

#3. Keçiören'den AŞTİ'ye:
#En az aktarmalı rota: Keçiören -> Gar -> Gar -> Sıhhiye -> Kızılay -> AŞTİ
#En hızlı rota (19 dakika): Keçiören -> Gar -> Gar -> Sıhhiye -> Kızılay -> AŞTİ

#4. Kızılay'dan Demetevler'e :
#En az aktarmalı rota: Kızılay -> Ulus -> Demetevler -> Demetevler
#En hızlı rota (13 dakika): Kızılay -> Ulus -> Demetevler -> Demetevler

#5. Ulus'tan AŞTİ'ye   :
#En az aktarmalı rota: Ulus -> Kızılay -> Kızılay -> AŞTİ
#En hızlı rota (6 dakika): Ulus -> Kızılay -> Kızılay
