# ALgoritma-enkripsi

## Enkripsi

**Input**: Kpublik = (e, N), plain text (M)
**Output**: cipher text (C)
1. for i ← 0 to PanjangPlaintext － 1 do
2. Konversi Mi ke nilai desimal
3. Ci ← (Mi)e mod N
4. end for
5. Return C


## Dekprisi

**Input**: Kprivat = (d, N), cipher text (C)
**Output**: plain text (M)
1. for i ← 0 to PanjangCiphertext － 1 do
2. Mi ← (Ci)d mod N
3. Konversi nilai Mi ke karakter
4. end for
5. Return M
