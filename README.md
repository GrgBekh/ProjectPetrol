# ProjectPetrol


Data_preprocessing отвечает за обработку первоначальных кривых las
Dataset_init создает тренировочную и тестовую выборку
Model_architecture посвящен построению модели и просмотру результатов
Side_testing - Dip test и оценка работы кластеризации

LasCurvesRaw - необработанные данные логгирования скважин
LasCurves - соответственно обработанные
DatasetForPetroCNN - различные csvшки
logs - логи tensorboard


lasio выкатил обновление и теперь нельзя обрезать датафреймы для записи в лог
скважины, установите пожалуйста не последнюю версию lasio, или запустите в google
colab.

Если вы не хотите обучать модель, она и ее веса сохранены в этом репозитории
GPU отключен на случай если нет среды с GPU

Хорошего дня!
