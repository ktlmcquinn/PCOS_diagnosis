<h1>PCOS Analysis Project</h1>
<h2>Overview</h2>
This project focuses on analyzing data related to Polycystic Ovary Syndrome (PCOS), a common hormonal disorder affecting individuals of reproductive age. 
Through comprehensive data analysis and machine learning, the project aims to identify key factors contributing to PCOS and develop predictive models to diagnose the syndrome.

<h2>Objective</h2>
The main objective of this project is to leverage machine learning techniques to understand the complexities of PCOS and identify significant predictors of the syndrome. 
By doing so, we hope to contribute to the early detection and better management of PCOS.

<h2>Dataset</h2>
The dataset contains various features related to health, lifestyle, and clinical measurements of individuals with the target feature being whether on not PCOS is present in the individual. 
Key features include hormonal levels, ultrasound findings, and physical symptoms.

<h3>Features Overview</h3>
<h4>Clinical and Hormonal Features</h4>
<b>PCOS (Y/N):</b> Diagnosis of Polycystic Ovary Syndrome.<br>
<b>FSH(mIU/mL), LH(mIU/mL):</b> Follicle-stimulating hormone and Luteinizing hormone levels, respectively; hormonal imbalances can be indicative of PCOS.<br>
<b>TSH (mIU/L):</b> Thyroid-stimulating hormone level, indicating thyroid function which can be related to menstrual irregularities.<br>
<b>AMH(ng/mL):</b> Anti-Müllerian hormone level, often elevated in PCOS, reflecting the ovarian reserve.<br>
<b>PRL(ng/mL):</b> Prolactin level, which can be related to reproductive health issues.<br>
<b>Vit D3 (ng/mL):</b> Vitamin D level, as deficiencies have been linked to various health conditions, including PCOS.<br>
<b>PRG(ng/mL):</b> Progesterone level, important for menstrual cycle regulation.<br>
<b>RBS(mg/dl):</b> Random blood sugar, as insulin resistance is a common feature in PCOS.<br>
<b>I beta-HCG(mIU/mL), II beta-HCG(mIU/mL):</b> Human chorionic gonadotropin levels, relevant in pregnancy and can be measured in PCOS patients for various reasons.<br>
<h4>Physiological Measurements</h4>
<b>Age (yrs), Weight (Kg), Height(Cm), BMI:</b> Basic physiological measurements; BMI can indicate overweight/obesity, a risk factor for PCOS.<br>
<b>Blood Group:</b> Included for medical records, though not directly related to PCOS.<br>
<b>Pulse rate(bpm), RR (breaths/min):</b> Vital signs.<br>
<b>Hb(g/dl):</b> Hemoglobin level, indicating overall health status.<br>
<b>Hip(inch), Waist(inch), Waist:Hip Ratio:</b> Measurements related to body fat distribution, with central obesity being a risk factor for PCOS.<br>
<b>Endometrium (mm):</b> Endometrial thickness, which can be affected by menstrual cycle irregularities common in PCOS.<br>
<h4>Reproductive Health</h4>
<b>Cycle(R/I):</b> Regularity/Irregularity of menstrual cycle, a key symptom of PCOS.<br>
<b>Cycle length(days):</b> Duration of menstrual cycle, with variations often seen in PCOS.<br>
<b>Marriage Status (Yrs):</b> Could be relevant for studies on fertility and PCOS.<br>
<b>Pregnant(Y/N), No. of abortions:</b> Pregnancy history, as PCOS can affect fertility.<br>
<h4>Lifestyle and Symptoms</h4>
<b>Weight gain(Y/N), hair growth(Y/N), Skin darkening (Y/N), Hair loss(Y/N), Pimples(Y/N):</b> Symptoms associated with PCOS, such as weight gain, hirsutism, acanthosis nigricans (skin darkening), hair loss, and acne.<br>
<b>Fast food (Y/N), Reg.Exercise(Y/N):</b> Lifestyle factors that can influence PCOS symptoms and management.<br>
<b>BP _Systolic (mmHg), BP _Diastolic (mmHg):</b> Blood pressure measurements, as hypertension can be associated with PCOS.<br>
<h4>Ovarian Function</h4>
<b>Follicle No. (L), Follicle No. (R):</b> Number of follicles in the left and right ovaries, respectively; high numbers are indicative of PCOS.<br>
<b>Avg. F size (L) (mm), Avg. F size (R) (mm):</b> Average follicle size in the left and right ovaries, which can be relevant for assessing ovarian health and function.<br>


<h2>Methods</h2>

The analysis involves several key steps:

<b>Data Preprocessing:</b> Cleaning and preparing the data for analysis.<br>
<b>Feature Selection:</b> Using RFECV to identify the most significant predictors of PCOS.<br>
<b>Model Training:</b> Employing Logistic Regression to develop a predictive model.<br>
<b>Evaluation:</b> Assessing the model's performance through accuracy metrics and ROC curve analysis.<br>

<h2>Results</h2>
The project successfully identifies key predictors of PCOS and develops a logistic regression model with promising diagnostic capabilities. The model's performance is evaluated using accuracy scores and ROC curves, demonstrating its potential utility in clinical settings.

<h2>Tools and Technologies</h2>
- Pandas<br>
- NumPy<br>
- scikit-learn<br>
- Matplotlib<br>
- Seaborn<br>

<h2>Installation</h2>
To run this project, you will need Python and the above-mentioned libraries. You can install the dependencies via pip:

`pip install pandas numpy scikit-learn matplotlib seaborn`

<h2>Usage</h2>
To analyze the PCOS dataset and reproduce the findings, run the Jupyter notebooks in the repository. Ensure all data files are located in the appropriate directories as specified in the notebooks.

<h2>Contributing</h2>
Contributions to the project are welcome. Please feel free to fork the repository, make changes, and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

<h2>License</h2>
MIT
