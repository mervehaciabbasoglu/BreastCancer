Breast Cancer | [Merve Hacıabbasoğlu]

Bu proje, meme kanseri teşhisini desteklemek amacıyla geliştirilmiş bir makine öğrenmesi uygulamasıdır. Wisconsin Meme Kanseri veri seti kullanılarak oluşturulmuş modeller, kullanıcıların meme kanseri teşhisi için doğruluk oranı ve skor gibi geribildirimler almasını sağlar.

Dataset ve Model Dosyası

Veri seti, Kaggle'dan (https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data) indirilmiştir ve Google Drive'da saklanmaktadır. Proje betikleri bu veri setini kullanarak eğitim ve test işlemlerini gerçekleştirmektedir.

Veri Setinin Kullanımı

•	data_preparation.py: Bu Python betiği, meme kanseri veri setini işleyerek eğitim ve test için verileri hazırlar.

•	neural_network_model.py: Bu betik, hazırlanan veri seti üzerinde bir derin öğrenme modeli (Neural Network) eğitir ve meme kanseri teşhisi için bir model oluşturur.

•	naive_bayes_model.py: Bu betik, Gaussian Naive Bayes algoritması ile bir model eğitir ve meme kanseri teşhisinde kullanılacak olan bir sınıflandırıcı oluşturur.

•	model_evaluation.py: Bu betik, eğitilen modelleri test verisi üzerinde değerlendirir ve performanslarını raporlar.

•	dataset/: Meme kanseri veri setinin işlendiği ve saklandığı klasör.

•	models/: Eğitilmiş modellerin (model.h5, naive_bayes_model.pkl) kaydedildiği klasör.

Kullanım

1.	Veri Hazırlığı:
o	data_preparation.py betiğini çalıştırarak meme kanseri veri setini işleyin ve eğitim/test setlerine ayırın.

2.	Model Eğitimi:
o	Derin Öğrenme Modeli: neural_network_model.py betiğini çalıştırarak derin öğrenme modelini eğitin.

o	Naive Bayes Modeli: naive_bayes_model.py betiğini çalıştırarak Naive Bayes modelini eğitin.

3.	Model Değerlendirme:
o	model_evaluation.py betiğini çalıştırarak her iki modelin performansını test edin ve doğruluk oranını, kaybı ve diğer metrikleri inceleyin.

Gereksinimler

Bu projeyi çalıştırmak için aşağıdaki Python kütüphanelerine ihtiyacınız olacak:

•	Python 3.x

•	TensorFlow

•	Keras

•	scikit-learn

•	Matplotlib

•	Pandas

•	NumPy

Gerekli kütüphaneleri aşağıdaki komutla yükleyebilirsiniz:
pip install tensorflow keras scikit-learn matplotlib pandas numpy

