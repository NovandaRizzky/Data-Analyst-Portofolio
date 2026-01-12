This repository contains the code used in the article:  
Comparison of SMOTE and ADASYN in Optimizing Random Forest Model for Imbalanced Financial Ratio Bankruptcy Prediction (Jurnal Teknoinfo, 2025)  
Paper Link : https://publikasi.teknokrat.ac.id/index.php/teknoinfo/article/view/1056  
## Ringkasan Projek  
Projek ini berfokus pada peningkatan model _machine learning_ pada data kebangkrutan perusahaan yang tidak seimbang. Data yang digunakan dapat diakses pada kaggle dengan judul "Company Bankruptcy Prediction" yang berisikan variabel-variabel keuangan. Variabel target yaitu Bankruptcy? yang bernilai 1 dan 0 mengindikasikan bahwa perusahaan tersebut bangkrut atau tidak. Dimana 1 adalah perusahaan yang bangkrut dan 0 adalah perusahaan yang tidak bangkrut. Permasalahan pada data ini yaitu jumlah perusahaan yang bangkrut jauh lebih sedikit dibandingkan dengan perusahaan yang bangkrut. Hal tersebut membuat model _machine learning_ menjadi lebih sulit untuk memprediksi perusahaan yang bangkrut dibandingkan perusahaan yang tidak bangkrut. Untuk memperbaiki hal ini, Saya ingin meningkatkan model menjadi lebih baik dalam memprediksi perusahaan yang bangkrut dengan teknik SMOTE dan ADASYN.  
## Permasalahan  
Model _machine learning_ lebih sulit memprediksi perusahaan yang bangkrut dikarenakan data tidak seimbang.  
## Metodologi  
- Data _cleaning_ dan _preprocessing_
- ADE (Analisis Data Eksploratif)
- Menangani data tidak seimbang menggunakan SMOTE dan ADASYN
- Membuat model dengan _Random Forest_
- Evaluasi model
## Dataset  
Dataset dapat diakses pada _website_ kaggle berikut https://www.kaggle.com/datasets/fedesoriano/company-bankruptcy-prediction atau dapat didownload pada folder data yang sudah disediakan.  
## Hasil  
Hasil yang saya temukan yaitu SMOTE dan ADASYN berhasil meningkatkan performa model terutama pada nilai _F1-Score_ yang artinya model lebih seimbang dalam memprediksi perusahaan yang bangkrut, walaupun menurunkan akurasi model secara keseluruhan.  
## Kesimpulan  
SMOTE secara keseluruhan lebih baik dibandingkan ADASYN secara keseluruhan dalam memprediksi kebangkrutan perusahaan menggunakan rasio keuangan pada data yang tidak seimbang.  
## Perbaikan yang Dapat Ditingkatkan  
- Model dapat dilakukan _hyperparameter tuning_
- Dapat menggunakan teknik _oversampling_ yang lain seperti Borderline-SMOTE, SVM-SMOTE, dan KMeans-SMOTE. Atau dapat menggunakan teknik _resampling_ yang tidak bergantung pada interpolasi seperti _Generative Adversarial Network_ (GAN) atau alternatif lainnya seperti _undersampling_ dan _cost-sensitive learning_.
- Variabel yang digunakan selain rasio keuangan dapat dikombinasikan dengan variabel keuangan yang relevan seperti total aset, laba, maupun variabel keuangan lainnya.

## Author
Novanda Rizky Ramadhana
