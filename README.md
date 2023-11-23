# Kasus pemilihan smartphone dengan menggunakan MOP
## Tujuan optimisasi pemilihan smartphone adalah untuk mendefinisikan fungsi tujuan dan fungsi kendala yang sesuai dengan preferensi dan batasan yang umum dalam pemilihan smartphone.

**Deskripsi Masalah:**
Seorang konsumen berniat membeli smartphone baru dan dihadapkan pada berbagai pilihan. Kriteria utama konsumen adalah kualitas kamera (f1) dan durasi baterai (f2). Selain itu, ada beberapa kendala atau batasan yang harus diperhatikan, seperti dana budget maksimum yang tersedia.


**Fungsi Tujuan (Objective Functions):**
1. f_1 (x): Kualitas Kamera
   - Misalnya, f_1 (x) = Resolusi Kamera
   - Tujuannya adalah memaksimalkan kualitas kamera.

2. f_2 (x): Durasi Baterai
   - Misalnya, f_2 (x) = Durasi Baterai
   - Tujuannya adalah memaksimalkan durasi baterai.

**Fungsi Kendala (Constraint Functions):**
1. g_1(x): Batasan Budget
   - g_1 (x) = Harga Smartphone
   - Smartphone yang dipilih tidak boleh melebihi budget yang dimiliki.

**Fungsi Objektif**

f_1 (x) = x1^1
f_2 (x) = x2^2

**Fungsi constraint**
x1^2 + X2^2 <= 1000

**Tujuan Keseluruhan:**
Maksimalkan kualitas kamera f_1(x) dan durasi baterai f_2(x) sambil memenuhi batasan budget g_1(x).

**Pareto Front:**
Solusi optimal adalah yang berada di Pareto front, yaitu solusi-solusi yang tidak dapat ditingkatkan pada satu objektif tanpa mengorbankan yang lain. Dalam konteks ini, ini bisa menjadi kombinasi smartphone yang memberikan trade-off optimal antara kualitas kamera dan durasi baterai sesuai dengan batasan yang ada.

**HASIL**
f1_arch: Nilai negatif menunjukkan bahwa jumlah kamera pada smartphone cenderung lebih rendah. Nilai yang lebih kecil menandakan jumlah kamera yang lebih banyak. Setiap elemen dalam array mewakili jumlah kamera untuk satu solusi dalam himpunan Pareto-optimal.

f2_arch: Nilai yang lebih besar menunjukkan besar baterai yang lebih besar. Oleh karena itu, semakin besar nilai dalam array f2_arch, semakin besar besar baterai yang dimiliki oleh smartphone dalam himpunan Pareto-optimal.

