
این پروژه مربوط به **سؤال سایت Quera به آدرس [https://quera.org/problemset/254932](https://quera.org/problemset/254932)** است که هدف آن **طبقه‌بندی جملات متنی** با استفاده از روش‌های **یادگیری ماشین (Machine Learning)** و **یادگیری عمیق (Deep Learning)** می‌باشد.  

در این پروژه مراحل زیر انجام شده است:

1. **پیش‌پردازش داده‌ها (Preprocessing)**  
   - پاک‌سازی داده‌ها (حذف نویز، علائم نگارشی، کلمات توقف و غیره)  
   - تحلیل اکتشافی داده‌ها (EDA) برای بررسی توزیع کلاس‌ها و ویژگی‌ها  

2. **بالانس داده‌ها**  
   - به دلیل نامتوازن بودن داده‌ها، از روش‌های oversampling و undersampling برای ایجاد تعادل بین کلاس‌ها استفاده شد.  

3. **مدل‌سازی با یادگیری ماشین (Machine Learning)**  
   - ادغام و پاک‌سازی متن‌ها  
   - تبدیل متن‌ها به ویژگی عددی با استفاده از **TF-IDF Vectorization**  
   - آموزش مدل‌های مختلف از جمله Logistic Regression، Random Forest، و XGBoost  
   - دستیابی به **دقت (Accuracy) حدود 80٪**

4. **مدل‌سازی با یادگیری عمیق (Deep Learning)**  
   - استفاده از embedding و لایه‌های شبکه عصبی (Dense و LSTM) برای تحلیل معنایی جملات  
   - دستیابی به دقت مشابه در حدود **80٪**
.

📎 لینک پروژه در Google Colab:  
[Google Colab Notebook](https://colab.research.google.com/drive/1_hM70Hauy-SRjYVbBWttB43-MtP92vw3)

---

## 🇬🇧 Description (English)

This project is based on **the Quera NLP Challenge** available at [https://quera.org/problemset/254932](https://quera.org/problemset/254932).  
The goal is to **classify text sentences** using both **Machine Learning** and **Deep Learning** techniques.

### Project Steps

1. **Data Preprocessing**  
   - Text cleaning (removing noise, punctuation, and stopwords)  
   - Exploratory Data Analysis (EDA) to understand class distribution and text patterns  

2. **Data Balancing**  
   - Used sampling techniques to balance the dataset and reduce class bias  

3. **Machine Learning Approach**  
   - Combined and cleaned the text corpus  
   - Applied **TF-IDF vectorization** to convert text into numerical features  
   - Trained models such as Logistic Regression, Random Forest, and XGBoost  
   - Achieved an **accuracy of around 80%**

4. **Deep Learning Approach**  
   - Used embeddings and neural network layers (Dense / LSTM) for semantic analysis  
   - Achieved similar performance with **~80% accuracy**

📎 Google Colab Notebook:  
[Google Colab Link](https://colab.research.google.com/drive/1_hM70Hauy-SRjYVbBWttB43-MtP92vw3)
