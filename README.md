# Project_Capstone_Hacktiv8

1. Title project : Menganalisis Faktor Seorang Nasabah yang Melakukan Berlangganan Deposit atau Tidak
   
2. Project overview :
   
3. Raw dataset link : https://www.kaggle.com/datasets/krantiswalke/bankfullcsv
  
4. Insight & findings :
a. Ketidakseimbangan Data Target: Dataset sangat tidak seimbang, dengan jumlah nasabah yang tidak berlangganan jauh lebih banyak dibandingkan yang berlangganan. Ini adalah temuan penting yang sudah Anda tangani dengan SMOTE.
b. Distribusi Berlangganan berdasarkan Pekerjaan: Terlihat bahwa beberapa pekerjaan seperti "management", "technician", "blue-collar", dan "admin." memiliki jumlah nasabah yang signifikan, baik yang berlangganan maupun tidak. Proporsi nasabah yang berlangganan juga bervariasi antar jenis pekerjaan, di mana "management" memiliki proporsi tertinggi di antara yang berlangganan, diikuti oleh "technician" dan "blue-collar".
c. Distribusi Berlangganan berdasarkan Status Pernikahan: Nasabah dengan status "married" memiliki jumlah terbanyak, baik yang berlangganan maupun tidak. Namun, proporsi nasabah "single" yang berlangganan relatif lebih tinggi dibandingkan "married" dan "divorced".
d. Distribusi Berlangganan berdasarkan Pendidikan: Nasabah dengan pendidikan "secondary" adalah yang paling banyak, diikuti oleh "tertiary" dan "primary". Proporsi nasabah "tertiary" yang berlangganan sedikit lebih tinggi dibandingkan "secondary" dan "primary".
e. Distribusi Berlangganan berdasarkan Kepemilikan Pinjaman Rumah: Nasabah yang tidak memiliki pinjaman rumah ("no") memiliki jumlah yang lebih banyak berlangganan dibandingkan yang memiliki ("yes"). Ini menunjukkan bahwa memiliki pinjaman rumah mungkin menjadi faktor yang sedikit mengurangi kemungkinan berlangganan.
f. Distribusi Berlangganan berdasarkan Jenis Kontak: Mayoritas nasabah dihubungi melalui "cellular", dan proporsi nasabah yang berlangganan dari kontak "cellular" jauh lebih tinggi dibandingkan "telephone".
g. Durasi Kontak sebagai Faktor Penting: Analisis fitur numerik menunjukkan bahwa "duration" (durasi kontak terakhir) memiliki perbedaan distribusi yang jelas antara nasabah yang berlangganan dan tidak berlangganan. Nasabah yang berlangganan cenderung memiliki durasi kontak yang lebih lama, yang juga terlihat dari nilai mean dan median yang lebih tinggi pada kelompok 'yes'. Korelasi heatmap juga menunjukkan korelasi positif yang cukup kuat antara 'duration' dan 'y'.

5. AI support explanation : 
