# Data Science of Ramadan: Deep Mining of Lailatul Qadr with iQRa' Algorithm
Data Science of “Ramadan”: Deep Mining of Lailatul Qadr (Why it’s only in one day in Ramadan, and happens once every years? Because It’s the Sign Truth from Allah SWT) 

Authors:
1. Imam Cholissodin (imamcs@ub.ac.id), Faculty of Computer Science (Filkom), Universitas Brawijaya (UB), Corresponding Author ✔
2. Achmad Shampton (achsanmas@gmail.com), Pondok Pesantren Nurul Huda Salafiyah Syafi'iyah, Malang, Indonesia
3. Arief Andy Soebroto (ariefas@ub.ac.id), Faculty of Computer Science (Filkom), Universitas Brawijaya (UB)


----------start | (2022, Using Data by API or Scraping from our System): ------------------------------

Alhamdulillah, berdasarkan “Hasil rekap pengujian” Maka, In Syaa Allah suhu bumi saat Lailatul Qadr (LQ) rata-rata adalah ± 21.27 derajat celcius, yang artinya “udara tidak dingin atau tidak panas” = ± 21.27ᵒ C, yaitu pada tanggal 23 Ramadan 1443 H atau 24 April 2022. Kami mengimprovisasi dari nilai pencarian “udara tidak dingin atau tidak panas” dengan nilai batasan interval [15;25] sebagai kelanjutan dari percobaan pencarian sebelumnya (sebelum tahun 2022) yang menggunakan berbagai opsi interval yaitu:

opsi 1 >> for ii in range(15,40): # utk loop parameter suhu ideal bumi (t)=[15;40] dgn incrment 1

opsi 2 >> for ii in np.arange(15, 40.01, 0.01): # utk loop parameter suhu ideal bumi (t)=[15;40] dgn incrment 0.01

opsi 3 >> for ii in np.arange(10, 41, 1): # utk loop parameter suhu ideal bumi (t)=[10;40] dgn incrment 1

opsi 4 >> for ii in np.arange(19, 20, 1): # utk loop parameter suhu ideal bumi (t)=[19;20] dgn incrment 1

----------end | (2022, Using Data by API or Scraping from our System): ------------------------------


----------start | (before 2022, Using Data Form Kaggle): ------------------------------

Presentation:
![Data Science of “Ramadan”: Deep Mining of Lailatul Qadr v1](https://github.com/imamcs19/Data-Science-of-Ramadan---Deep-Mining-of-Lailatul-Qadr/blob/master/Data%20Science%20of%20Ramadan%20-%20Deep%20Mining%20of%20Lailatul%20Qadr.png)

![Data Science of “Ramadan”: Deep Mining of Lailatul Qadr v2](https://github.com/imamcs19/Data-Science-of-Ramadan---Deep-Mining-of-Lailatul-Qadr/blob/master/Data%20Science%20of%20Ramadan.png)

---------------------
Alhamdulillah, berdasarkan “Hasil rekap pengujian” Maka, In Syaa Allah suhu bumi saat Lailatul Qadr rata-rata adalah ± 19 derajat celcius, yang artinya “udara tidak dingin atau tidak panas” = ± 19ᵒ C.

----------end | (before 2022, Using Data Form Kaggle): ------------------------------

Umat Islam hanya ditunjukkan tanda-tanda kehadirannya. Di antara tanda-tanda datangnya Lailatul Qadar adalah ( https://islam.nu.or.id/post/read/13854/kapan-lailatul-qadar ): 
1. Pada hari itu matahari bersinar tidak terlalu panas dengan cuaca sangat sejuk, sebagaimana hadits riwayat Imam Muslim. 
2. Pada malam harinya langit nampak bersih, tidak nampak awan sedikit pun, suasana tenang dan sunyi, tidak dingin dan tidak panas. Hal ini berdasarkan riwayat, Imam Ahmad.

Dalam Mu'jam at- Thabari al-Kabir disebutkan bahwa Rasulullah SAW bersabda: "Malam Lailatul Qadar itu langit bersih, udara tidak dingin atau panas, langit tidak berawan, tidak ada hujan, bintang tidak nampak dan pada siang harinya matahari bersinar tidak begitu panas.“

In Syaa Allah, if We use Sufficient Features in Quality and Quantity, We will Find that Lailatul Qadr is a Unique Day.

Proving the Sign Truth of Islam with AI & Coding. Semoga Bermanfaat & Berkah. Aamiin YRA. :D
