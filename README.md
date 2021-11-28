# Veri Setinizi Yolov5 Formatına Dönüştürün!

<img height="350" src="/images/yolo.png"/>

### Bu Repo da Neler Var?

- Xml Formatındaki Veri Setini .Txt Formatına Çevirme
- Xml Formatındaki Dosyaları Silme
- Veri Setinizi Yolov5 Formatına Göre Bölme
- Veri Setini Train,Test ve Val Şekilde Bölme
- Veri Setini %80,%10,%10 Ayırma

Örnek Format: 
```
datasets/ 

      images/
    
          train
            img_000.jpg
            ...
            img_999.jpg 
            
          val
           img_000.jpg
           ...
           img_999.jpg 
           
      labels/
          
          train
            img_000.txt
            ...
            img_999.txt 

          val
            img_000.txt
            ...
            img_999.txt
```









