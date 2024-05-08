## Reflection

### 1.2

![capture result](image.png)
"hey hey" akan tercetak sebelum "howdy!" dan "done!" karena bagian "hey hey" berada di luar fungsi async. Proses eksekusi tetap berlanjut dan mencetak "hey hey" sementara fungsi async masih menunggu hasil dari future-nya.






