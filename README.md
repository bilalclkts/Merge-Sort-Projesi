[www.patika.dev](https://www.patika.dev/tr)
# Merge-Sort-Projesi 

[16,21,11,8,12,22] -> Merge Sort

## 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

- [16,21,11]          [8,12,22]
- [16,21] [11]        [8,12] [22]
- [16] [21] [11]      [8] [12] [22]

Bölme işleminden sonra birleştirme işlemine başlıyoruz.

- [16,21] [11]       [8,12] [22]
- [11,16,21]         [8,12,22]
- [8,11,12,16,21,22]

## 2.Big-O gösterimini yazınız.

O(n*log(n))
