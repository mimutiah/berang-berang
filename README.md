# Banking Marketing Targets Project

## Project Overview
This project by <b>Berang-Berang Consulting</b> aims to enhance the effectiveness of marketing campaigns for a bank. Our analysis utilizes the <b>"Banking Marketing Targets"</b> dataset to develop predictive models that identify potential customers likely to subscribe, thus enabling more targeted and cost-efficient marketing strategies.

## Repository Contents
<b>banking_train.xlsx</b>: Training dataset for model development.

<b>banking_test.xlsx</b>: Test dataset for model evaluation.

<b>Stage_1_FinPro_W.ipynb</b>: Jupyter Notebook containing the Exploratory Data Analysis (EDA), Pre-processing, and Outlier Handling.


## Getting Started
### Prerequisites
Ensure you have Python installed along with the following libraries:
<ul>
<li>Pandas</li>
<li>Numpy</li>
<li>Scikit-learn</li>
<li>Matplotlib</li>
<li>Seaborn</li>
</ul>


### Installation
Clone the repository and install the required Python packages:


```
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

### Running the Program
<ol>
<li>Open the Jupyter Notebook:</li>

  ```
jupyter notebook Stage_1_FinPro_W.ipynb

  ```

<li>Execute the cells sequentially to perform EDA, data pre-processing, and model training.</li>
</ol>

## Using the Program
<b>EDA</b>: Explore data distributions and relationships between features.

<b>Pre-processing</b>: Clean and prepare the data for modeling by handling outliers and normalizing data.

<b>Model Training</b>: Train the predictive model using the training dataset.

<b>Evaluation</b>: Assess the model's performance on the test dataset.




## References
Pandas Documentation: <https://pandas.pydata.org>

NumPy Documentation: <https://numpy.org/doc/>

Scikit-learn Documentation: <https://scikit-learn.org>

Matplotlib Documentation: <https://matplotlib.org/stable/index.html>

Seaborn Documentation: <https://seaborn.pydata.org/>


## Contributors
<b>Project Manager</b>: Manages the project workflow and client communications.

<b>Data Engineer</b>: Responsible for data collection, storage, and preliminary processing.

<b>Data Analyst</b>: Analyzes data to extract meaningful insights for business decisions.

<b>Data Scientist</b>: Develops and deploys machine learning models to solve the client's problem.


## Business Insights
<b>Bagaimana Umur Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Lansia cenderung lebih tertarik pada deposito karena keamanan finansial dan prioritas konsumsi yang berfokus pada kenyamanan, sedangkan kelompok usia muda kurang tertarik akibat ketidakpastian ekonomi.


<b>Bagaimana Pekerjaan Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Kemampuan menabung dan kondisi ekonomi yang berbeda berdasarkan jenis pekerjaan mempengaruhi kecenderungan pelanggan dalam melakukan deposit, dengan kategori seperti Student, Retired, dan Unemployed menunjukkan persentase yang lebih tinggi karena stabilitas atau perencanaan keuangan masa depan, sementara pekerja Blue-collar dan Services kurang mampu menabung karena penghasilan rendah dan biaya hidup yang tinggi.


<b>Bagaimana Status Pernikahan Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Status pernikahan mempengaruhi kecenderungan untuk melakukan deposit, dengan individu single cenderung menyisihkan lebih banyak uang untuk deposit karena memiliki tanggungan yang lebih sedikit, sedangkan yang menikah memiliki persentase yang lebih rendah akibat tanggung jawab finansial lebih besar, dan yang bercerai memiliki persentase terendah mungkin karena dampak finansial perceraian.


<b>Bagaimana Default, Housing & Loan Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Kecenderungan pelanggan dalam melakukan deposit dipengaruhi oleh status kredit mereka, dimana hanya pelanggan tanpa tunggakan yang memiliki deposit, sedangkan keberadaan pinjaman housing atau personal tidak secara signifikan mempengaruhi peluang mereka untuk memiliki deposit, menunjukkan bahwa keberadaan aset atau pinjaman tidak terlalu mempengaruhi keputusan untuk menabung dalam bentuk deposit.


<b>Bagaimana Contact Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Metode komunikasi berpengaruh terhadap kecenderungan pelanggan dalam melakukan deposit, dengan cellular lebih efektif dibandingkan telephone, mungkin karena kemudahan akses dan fleksibilitasnya yang lebih besar dalam menjangkau pelanggan di berbagai situasi, sehingga meningkatkan peluang persetujuan deposit.


<b>Bagaimana Month Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Kemungkinan pelanggan melakukan deposit bervariasi berdasarkan bulan, dengan Maret menunjukkan efektivitas tertinggi, diikuti oleh Oktober dan September yang juga memiliki tingkat keberhasilan yang signifikan, sedangkan Mei menunjukkan performa terendah, mengindikasikan perlunya strategi yang lebih agresif atau pendekatan yang berbeda untuk meningkatkan hasil pada bulan tersebut.


<b>Apakah Hari Dalam Seminggu Mempengaruhi Kecenderungan Pelanggan dalam Melakukan Deposit?</b>

Hari dalam seminggu mempengaruhi kecenderungan pelanggan dalam melakukan deposit, dengan Kamis menunjukkan persentase deposit paling tinggi, sementara Senin memiliki persentase terendah, menunjukkan bahwa konsumen mungkin lebih aktif secara finansial dan nyaman melakukan deposit di pertengahan minggu dibandingkan dengan awal atau akhir minggu.
