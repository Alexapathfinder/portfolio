# Projects 
В данном репозитории находятся проекты, защищенные в процессе обучения на курсе "Специалист по Data Science" сервиса онлайн-образования Яндекс.Практикум, такие как:

## Классификация комментариев на позитивные и негативные
  Обучение моделей определять эмоциональную окраску твитов.
  В проекте использованы:
  - WordNetLemmatizer, 
  - TfidfVectorizer,
  - модель BERT; 
  - RandomForestClassifier
  - LogisticRegression.
  
  
## Прогноз, уйдет ли клиент из банка
  По собранным в датафрейме признакам прогнозируется, останется ли человек клиентом банка или уйдет в ближайшем будущем.
  В проекте использованы:
  - средства визуализации посредством библиотек seaborn и matplotlib, 
  - техники прямого и порядкового кодирования: One-Hot Encoding и Ordinal Encoding, 
  - масштабирование признаков: StandardScaler, 
  - техники борьбы с дисбалансом классов: upsampling и downsampling, 
  - модели RandomForestClassifier, DecisionTreeClassifier и LogisticRegression.
  

## Прогноз объема заказов такси на следующий час
  Работа с временными рядами.
  В проекте выполнены:
  - ресемплирование данных по 1 часу
  - визуализации при помощи библиотек seaborn и matplotlib
  - высчитано скользящее среднее и скользящее стандартное отклонение для стационарности ряда
  - осуществлен подбор гиперпараметров при помощи GridSearchCV
  - обучены модели LinearRegression и RandomForestRegressor


## Предсказание рыночной стоимости авто
  Предполагается, что клиент выставляет б/у авто на сайте, а модель подсказывает ориентировочную стоимость автомобиля.
  В проекте использованы:
  - CatBoostRegressor
  - LinearRegression
  - GridSearchCV
  - LGBMRegressor
  - визуализация seaborn и matplotlib
  Также в проекте проведена работа с большим количеством пропусков
  


## Анализ спроса клиентов на авиабилеты в города, где проходят крупные культурные мероприятия
  Работа с БД sql. Выдвигается гипотеза, что в среднем цена авиабилета в города, где в это время проводятся мероприятия схожа с ценой в любое иное время. Проводится статистический анализ данных.
  В проекте использованы:
  - средства sql
  - библиотеки визуализации matplotlib и seaborn
  - scipy.stats для анализа данных
  - визуализация seaborn и matplotlib


## Выявление региона, где добыча нефтепродуктов принесет максимальную прибыль
  Даны несколько датафреймов. Каждый датафрейм содержит информацию по одной из областей освоения. Необходимо проанализировать данные, рассчитать прибыль и возможные риски; выявить наиболее благоприятный для освоения регион.
  В проекте использованы:
  - train_test_split
  - LinearRegression
  - mean_squared_error
  - stats
  - средства визуализации посредством библиотек seaborn и matplotlib


## Защита персональных данных клиентов компании
  Даны персональные данные. Необходимо создать такой метод преобразования данных, чтобы по ним было затруднительно воссоздать личные данные клиентов.
  В проекте использованы:
  - numpy
  - StandardScaler
  - scipy.spatial.distance
  - визуализация seaborn и matplotlib
  - создан класс LinearRegression
  
  
## Предсказание показателя восстановления золота из сырья
  Даны несколько датафреймов, в которых находится информация об уровне концентрации металлов на разных этапах очистки сырья от примесей. Необходимо определить, какой объем золота компания получит после финальной очистки продукта.
  В проекте использованы:
  - StandardScaler
  - cross_val_score
  - GridSearchCV
  - make_scorer
  - LinearRegression
  - RandomForestRegressor
  - DecisionTreeRegressor
  - scipy.stats
  - визуализация seaborn и matplotlib


## Предсказание ориентировочного возраста по фото
  В файле собран ряд фотографий. Необходимо обучить модели распознавать возраст изображенного лица по данным фотографии.
  В проекте использованы:
  - Sequential
  - Conv2D, Flatten, Dense, AvgPool2D
  - Adam
  - ImageDataGenerator
  - GlobalAveragePooling2D
  - ResNet50
  - визуализация seaborn и matplotlib
