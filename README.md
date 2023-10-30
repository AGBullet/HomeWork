# Приложение обнаруживает объекты, используя модель DETR (сквозное обнаружение объектов) с магистралью ResNet-50
Модель DETR представляет собой преобразователь кодер-декодер со сверточной основой. Для обнаружения объектов добавляются две головки поверх выходов декодера: линейный уровень для меток классов и MLP (многослойный персептрон) для ограничивающих рамок. Модель использует так называемые объектные запросы для обнаружения объектов на изображении. Каждый объектный запрос ищет конкретный объект на изображении. Для COCO количество запросов к объектам установлено равным 100.
