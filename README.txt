Repository ini berisikan mengenai final project yang kelompok Lord Analyst kerjakan.
Dataset yang kita dapatkan bernama 'AutoInsurance.csv' yang dapat kita unduh di kaggle (https://www.kaggle.com/ranja7/vehicle-insurance-customer-data)
Isi dataset berisikan data para nasabah asuransi di suatu perusahaan asuransi mobil di Negara Amerika Serikat sekitar tahun 2011 silam.
Final project ini terdiri dari beberapa file notebook beserta file-file tambahan lainnya seperti dataset dan hasil runing beberapa model ML.

==================================================================================
1.Business_Problem_and_Data_Understanding.ipynb

Notebook ini berisikan latar belakang dari pengerjaan final project ini dan business problem yang dapat kita temuka dari dataset yang kita miliki. Penjelasan mengenai
setiap kolom yang ada di dalam dataset pun dijabarkan berdasarkan domain knowledge di bidang asuransi.

==================================================================================
2.DataCleaning_and_DataPreprocessing.ipynb

Notebook ini berisikan mengenai langkah-langkah yang kita lakukan untuk "membersihkan" data agar dapat kita analisis lebih lanjut. Adapun proses data preprocessing yang kita lakukan
untuk menyiapkan data agar dapat digunakan kedalam model ML yang akan kita buat pada tahap selanjutnya.

==================================================================================
3.Analytical_Approach_and_Model.ipynb

Notebook ini terdiri dari 3 bagian :
	3.1 	Pertama adalah EDA untuk menganalisis data lebih lanjut menggunakan data yang sudah kita bersihka sebelumnya. Hasil EDA akan menjelaskan beberapa
		insight bisnis yang bisa kita dapatkan dari mengeksplorasi data secara lebih mendalam.
	3.2 	Kedua adalah model ML untuk dapat memprediksi jumlah premi perbulan calon nasabah baru menggunakan fitur-fitur yang bisa kita kumpulkan dari para calon 		nasabah baru.
	3.3	Ketiga adalah model ML untuk dapat memprediksi jumlah total klaim asuransi calon nasabah baru agar kita dapat melakukan klasifikasi terhadap calon nasabah
		yang berpeluang mempunyai total klaim asuransi yang tinggi di masa depan.

==================================================================================
4.Conclusion_and_Recommendation.ipynb

Notebook ini berisi mengenai kesimpulan dari apa yang sudah kita kerjakan sebelumnya dan dampak bisnis bagi pihak perusahaan yang tentunya akan menguntungkan perusahaan dan juga terdapat
rekomendasi mengenai project ini baik rekomendasi terhadap model ML yang kita buat maupun rekomendasi bagi perusahaan untuk mencapai goals dari perusahaan itu sendiri.

==================================================================================
MonthlyPremiumAuto.sav (file berukuran besar, tidak bisa disubmit tapi dapat di download di notebook "3.Analytical_Approach_and_Model.ipynb" > Save Model)

Model ML untuk penentuan jumlah premi perbulan calon nasabah baru dalam format file .sav yang sudah menggunakan parameter terbaik dan skor error terkecil.

==================================================================================
TotalClaimAmount.sav

Model ML untuk penentuan jumlah total klaim asuransi calon nasabah baru dalam format file .sav yang sudah menggunakan parameter terbaik dan skor error terkecil.

==================================================================================
AutoInsurance.csv

Dataset original yang didapatkan dari kaggle untuk kebutuhan project ini.

==================================================================================
RandomCV_Result_MonthlyPremiumAuto.csv

Dataset dalam bentuk .csv yang berisikan hasil runing dari RandomizedSearchCV dalam penentuan model ML jumlah premi auto.
File ini disertakan karena pada saat hyperparameter tuning model random forest untuk penentuan jumlah premi, proses runing 
randomizedcv pada fitting model berjalan sangat lama sekitar 1 jam. Maka dari itu kami menyimpan hasil randomcv tersebut kedalam bentuk csv
yang dapat kita load dataframenya menggunakan code yang ada di dalam notebook "3.Analytical_Approach_and_Model.ipynb" untuk memberikan opsi kepada para
pembaca yang menginginkan hasilnya keluar lebih cepat.

==================================================================================

Sekian penjelasan singkat mengenai isi repository ini, terimakasih.



Lord Analyst.
