​🏠 House Price Prediction (Advanced Pipeline)
​English
​This project delivers a highly accurate house price prediction model by following a professional 10-stage Data Science Pipeline:
​EDA: Deep analysis of features and correlations.
​Preprocessing: Encoding and outlier handling.
​Feature Engineering: Creating new variables to boost model "context".
​Imbalance Handling: Ensuring data consistency.
​Data Splitting: Strategic Train/Validation/Test splitting.
​Model Selection: Testing algorithms like Random Forest and XGBoost.
​Hyperparameter Tuning: Optimizing via Grid/Randomized Search.
​Advanced Evaluation: Using Confusion Matrix, F1-Score, and Precision-Recall.
​Model Persistence: Saving the final model and Scaler using joblib.
​Inference Pipeline: A ready-to-use script for new data predictions.
​العربية
​مشروع توقع أسعار البيوت مبني على مسار عمل احترافي (Pipeline) من 10 مراحل كما هو موضح في الصورة:
​استكشاف البيانات (EDA): تحليل العلاقات العميقة بين الميزات.
​معالجة البيانات: التعامل مع القيم المنحرفة (Outliers) والتشفير (Encoding).
​هندسة الميزات: إضافة ميزات جديدة لزيادة ذكاء الموديل.
​موازنة البيانات: ضمان استقرار البيانات وعدم انحيازها.
​تقسيم البيانات: فصل البيانات لمجموعات (تدريب واختبار) بشكل استراتيجي.
​اختيار النماذج: تجربة خوارزميات قوية مثل Random Forest و XGBoost.
​ضبط الأداء: الوصول لأفضل إعدادات للموديل (Tuning).
​التقييم الاحترافي: استخدام مقاييس دقيقة مثل F1-Score و Confusion Matrix.
​حفظ النموذج: توثيق وحفظ الموديل والـ Scaler باستخدام joblib.
​مرحلة التوقع: كود جاهز لاستقبال بيانات جديدة وإعطاء نتائج فورية


### 📊 Model Evaluation Summary

We evaluated the performance of our Regression model by comparing the **Actual Prices** versus the **Predicted Prices** on the test set.

#### **Actual vs. Predicted Price Analysis**
**بالعربية:** تحليل مقارنة الأسعار الفعلية بالأسعار المتوقعة.

![Model Prediction Evaluation](<   <img width="690" height="474" alt="Regression_Evaluation" src="https://github.com/user-attachments/assets/9c29f7a1-fbd6-4bc5-84c5-0dc837bb5a3e" />
  >)

​📈 Model Evaluation:
> Actual vs. Predicted Prices
>
​This scatter plot represents the final evaluation of our regression model. By comparing the Actual Prices against the Predicted Prices, we can observe:
​Model Accuracy: Most data points align closely with the dashed regression line, indicating a high correlation and low error rate.
​Reliability: The model consistently captures the pricing trends across different price ranges, confirming its readiness for real-world estimation.
>
​بالعربي

​مقارنة الأسعار الفعلية بالأسعار المتوقعة:
يوضح هذا الرسم البياني كفاءة النموذج النهائي؛ حيث تتقارب النقاط بشكل كبير مع خط التوقع، مما يؤكد دقة النموذج وقدرته العالية على التنبؤ بأسعار المنازل بشكل واقعي وموثوق.


​Tech Stack | التقنيات
​Python: Pandas, Scikit-learn, XGBoost, Joblib.
​By: Mohamed Belal
