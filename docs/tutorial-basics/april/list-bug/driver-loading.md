---
sidebar_position: 1
---

# Trip driver loading

Ketika driver membuka trip,terjadi loading terus menerus dan trip tidak bisa dibuka, Hal tersebut terjadi dikarenakan data `itemTmp` yang dikirim customer tidak sesuai atau berbeda dengan data yang diterima oleh aplikasi driver

Data yang dikirim customer merupakan type data `FLOAT` sedangkan aplikasi driver menerima data dengan type `INT`

Data tersebut merupakan hasil dari Order planning Customer

<img src={require('@site/static/img/bug/muter2.png').default} />
<img src={require('@site/static/img/bug/suhu.png').default} />

## Time

### Bug

- 4 April 2024

### Solved

- 25 April 2024

## Impact

Driver tidak bisa memulai trip

## Temporary Solution

Cancel orderan dan bikin yang baru tanpa order planning
