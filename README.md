# rock-paper-scissors-CNN
A Convolutional Neural Network (CNN) to classify Rock-Paper-Scissors images using TensorFlow and Keras.

# Rock-Paper-Scissors CNN Classifier

A Convolutional Network (CNN) built with TensorFlow and Keras to classify Rock-Paper-Scissors images. This project demonstrates end-to-end image processing, from Exploratory Data Analysis (EDA) to model training.

---

## Dataset Overview
* **Total Images:** 2,188 balanced images.
* **Classes:** 3 categories (Rock, Paper, and Scissors).

## Key Features
* **Exploratory Data Analysis (EDA):** Verifying and visualizing sample images randomly using `matplotlib`.
* **Data Augmentation:** Utilizing `ImageDataGenerator` for rescaling, random rotations, shifts, and zooms to prevent overfitting.
* **CNN Architecture:** Implemented via `tf.keras.models.Sequential` consisting of `Conv2D`, `MaxPooling2D`, `Flatten`, and `Dense` layers with a `softmax` activation function for the final 3-class output.

---

# تشخیص بازی سنگ-کاغذ-قیچی با شبکه عصبی CNN

یک پروژه دسته‌بندی تصاویر با استفاده از شبکه عصبی پیچشی (CNN) که با TensorFlow و Keras پیاده‌سازی شده است. این پروژه فرآیند کامل پردازش تصویر را از تحلیل اولیه تا آموزش مدل پوشش می‌دهد.

---

## مشخصات دیتاست
* **تعداد کل تصاویر:** ۲۱۸۸ تصویر کاملاً متعادل (Balanced).
* **کلاس‌ها:** ۳ دسته (سنگ، کاغذ و قیچی).

## ویژگی‌های اصلی پروژه
* **تحلیل اولیه داده‌ها (EDA):** بررسی هوشمند و نمایش نمونه تصاویر تصادفی با استفاده از `matplotlib`.
* **افزایش تنوع داده‌ها (Data Augmentation):** استفاده از `ImageDataGenerator` برای نرمال‌سازی پیکسل‌ها، چرخش، جابجایی و زوم تصافی جهت جلوگیری از بیش‌برازش (Overfitting).
* **معماری شبکه (CNN):** پیاده‌سازی مدل با `Sequential` شامل لایه‌های استخراج ویژگی (`Conv2D` و `MaxPooling2D`) و لایه‌های متراکم نهایی با تابع فعال‌سازی `softmax`.
