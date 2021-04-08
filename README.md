# TXT3456   
Формат текстовых символов разной длины   

1) Формат текстовых символов TXT3   
Размер символа 8 бит (2^3), включает в себя только обозначение самого текстового символа

2) Формат текстовых символов TXT4   
Размер символа 16 бит (2^4), включает в себя:   
0...7 бит - обозначение самого текстового символа, размером 8 бит
8...15 бит- обозначение режима отображения текстового символа:
-- 0й бит для обозначения регистра:              нижний регистр (=0) или верхний регистр (=1)
-- 1й бит для обозначения выделения:             без выделения (=0) или жирный (=1)
-- 2й бит для обозначения стиля:                 без курсива (=0) или курсив (=1)
-- 3й бит для обозначения подчеркивания:         без подчеркивания (=0) или с подчеркиванием (=1)
-- 4й бит для обозначения зачеркивания:          без зачеркивания (=0) или с зачеркиванием (=1)
-- 5й бит для обозначения шрифта:                обычный (=0) или заглавный (=1)
-- 6й и 7й биты для обозначения цвет символа:    обычный (=00) или GYR (зеленый=01, желтый=10, красный=11)


