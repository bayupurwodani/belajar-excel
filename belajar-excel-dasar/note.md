### Cara membuat warna selang seling pada sel di dalam tabel

- Cara Umum :
  - tandai seluruh tabel
  - Masuk ke tab **Home** pilih **Conditional Formatting**
  - Pilih **New Rule**
  - Di dalam **New Rule** pilih **> Use a formula to determine which cells to format**
  - Isikan rumus **=ISODD(ROW())** atau rumus **=ISEVEN(ROW())** di dalam kolom **Format values where this formula is true**
  - Selanjutnya klik **Format** dan masuk ke tab **Fill** dan pilih **Warna** yang kalian inginkan dan klik _Ok_
  - Terakhir klik **Ok**.

_'Catatan:_ rumus **=ISODD(ROW())** ini hanya memberikan warna ke hasil yang **Genap** dari awal sel di tandai, sedangkan ketika ingin hasil yang **Ganjil** gunakan rumur **=ISEVEN(ROW())**.
