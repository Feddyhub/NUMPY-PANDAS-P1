Odevde cvs dosyasi Kaggle'a yukleme sikintisi oldugu icin odevi 2 part PDF olarak paylastim. (kaggle to colab to PDF)

Kullandigim Kaynaklar ve Linkleri                                                 2020280014@ogr.deu.edu.tr     
1-Matplotlib documents
2-Numpy Documents                                                                                         Murat Ferhat Derya -Veri Madenciligi
Kaggle tutorial
gitHUB data set
3-Youtube 
4-chatGPT
5-Medium Cheet Sheets

linkler:
https://matplotlib.org/stable/plot_types/index.html
https://numpy.org/doc/1.24/reference/random/generated/numpy.random.randint.html
https://www.youtube.com/watch?v=5Gp_RCcZoh4&t=160s&ab_channel=Hasan%C3%87a%C4%9Fr%C4%B1G%C3%BCng%C3%B6r
https://github.com/mwaskom/seaborn-data/blob/master/mpg.csv
https://www.kaggle.com/code/dansbecker/finding-your-files-in-kaggle-kernels
https://ibb.co/mR9CR4T
https://www.youtube.com/watch?v=feDJkDaNuOk&ab_channel=RegenerativeToday
https://startupsventurecapital.com/essential-cheat-sheets-for-machine-learning-and-deep-learning-researchers-efb6a8ebd2e5
https://www.youtube.com/watch?v=Wemra5t1Ws4&ab_channel=RandomUploads

1-Oncelikle ders oncesinde de numpy pandas ve sklearn kutuphanelerini bildigimden dolayi kucuk bir goz gezdirme ardindan ilk kodlari kendim yaptim.
matplotlib grafikleri bilmedigimden dolayi dokumantasyondan bar grafiginin parametrelerini bulup kopyaladim.
2-veri yukleme olayi kaggle'da zor oldugu icin mpg datasetini githubdan bulup bilgisayara yuklemek suretiyle kaggle notebook'uma verileri cektim.
verileri genelde seaborn ile gorsellestirdim ve belki farkli korelasyonlar bulabilirim diye cogu pair'leri sns ile gorsellestirdim
sklearn kutuphanelerini documents'inden bakip import ettim. fit,score,X_train,y_train gibi bazi essential kaliplari bilmemin cok avantaji oldu.
Devaminda elimdeki istenen verileri reshape(-1,1) komutu ile sutunlara verirerk ve pd pandas ile data framee cevirdikten sonra train testleri fit ettikten sonra
en son istenen bir girdiyi =[[13.35.3500]] gibi liste sonrasinda df haline cevirip y_predict'in cevabini buldum.
