# Module_5.-
УСЛОВИЯ

Вы работаете в компании, которая занимается продажей автомобилей с пробегом в Москве. 

Основная задача компании и её менеджеров — максимально быстро находить выгодные предложения (проще говоря, купить ниже рынка, а продать дороже рынка). 

Руководство компании просит вашу команду создать модель, которая будет предсказывать стоимость автомобиля по его характеристикам.

Если такая модель будет работать хорошо, то вы сможете быстро выявлять выгодные предложения (когда желаемая цена продавца ниже предсказанной рыночной цены). 
Это значительно ускорит работу менеджеров и повысит прибыль компании.

ПРОБЛЕМА

Только вот незадача: исторически сложилось, что компания изначально не собирала данные. 
Есть только небольшой датасет с историей продаж за короткий период, которого для обучения модели будет явно мало. 
Его мы будем использовать для теста, остальное придется собрать самим.

В качестве тренировочного датасета был использова датасет по ссылке: https://www.kaggle.com/mikhailpustovalov/autoru-all-used-car-offers-as-of-17032021

В качестве моделей были использованы: linear regression, ridge regression, randomforestregressor, catboost, DecisionTreeRegressor и BaggingRegressor
Лучше всего сработали BaggingRegressor и randomforestregressor

В датасет было добавлено порядка 70 новых признаков, проведена очистка и предобработка данных

Что можно сделать лучше: подучить парсинг, была проблема со сбором данных, при попытки их выгрузить ломалась кодировка.
