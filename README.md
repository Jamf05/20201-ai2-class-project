# Clasificación de emociónes usando NLP

**Autores: Jorge Andres Mogotocoro Fajardo, Elkin Darío Fernández Celis**

<div align='center'>
<img width='100%' src='https://res.cloudinary.com/jamf05/image/upload/v1599341642/random-uploads/ntflbp455om2yhvsafbm.jpg'>
</div>

**Objetivo: Clasificar oraciones etiquetadas con un sentimiento usando NLP.**

- **Dataset**: El conjunto de datos empleado se basa en el tratamiento de 6 conjuntos de datos organizados de la siguiente manera:
  - **emotions-dataset-for-nlp** [[++](https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp)]: Contiene 20000 registros organizados en dos columnas una para el texto y otra para uno de 6 sentimientos (surprise, love, anger, joy, sadness y fear).
  - **WASSA-2017 Shared Task on Emotion Intensity** [[++](http://saifmohammad.com/WebPages/EmotionIntensity-SharedTask.html)]: Contiene 3960 registros organizados en tres columnas, una para el texto, otra para una de 4 sentimientos (anger, joy, sadness y fear) y otra para la intensidad de la emoción.
  - **nlp-text-emotion** [[++](https://github.com/lukasgarbas/nlp-text-emotion)]: Contiene 11327 registros organizados en dos columnas una para el texto y otra para uno de 5 sentimientos (neutral, anger, joy, sadness y fear).
  - **simbig2016-facebook-reactions** [[++](https://github.com/rgap/simbig2016-facebook-reactions)]: Contiene 4160 registros provenientes de la API de facebook de los que se tomaron en cuenta los campos "description","fb_love", "fb_haha", "fb_wow", "fb_angry", "fb_sad".
  - **Facebook Reactions** [[++](https://www.kaggle.com/johanabrahamsson/facebook-reactions)]: Contiene 81099 registros provenientes de la API de facebook de los que se tomaron en cuenta los campos "description","fb_love", "fb_haha", "fb_wow", "fb_angry", "fb_sad".
  - **2012-2016 Facebook Posts** [[++](https://data.world/martinchek/2012-2016-facebook-posts)] Contiene 9 conjuntos de datos provenientes de la API de facebook sobre publicaciones de diferentes cadenas de televisión y medios de comunicacion, se tomaron en cuenta los campos "description","fb_love", "fb_haha", "fb_wow", "fb_angry", "fb_sad".

- **Algoritmos utilizados**: LSTM y GRU

([code](https://github.com/Jamf05/20201-ai2-class-project)) ([video](https://youtu.be/pgi9X9bHW7U)) ([poster](https://drive.google.com/file/d/10ehfCDI85QPabk88-JYTdykXzKQzBhHG/view?usp=sharing)) [(+info](https://github.com/Jamf05))
