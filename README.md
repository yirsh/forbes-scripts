# Convert Mag+ to Adobe DPS

Скрипты для помощи в переносе документов с платформы Mag+ на Adobe DPS,
работают под CS6, почти всё работает под CC2017

mag2adps/mag2adps_01.jsx - выполняет приведение mag+ объектов к объектам ADPS, 
результат сохраняет в папке обрабатываемого файла с префиксом _objConv_ ,
не обрабатывает на 100% возможные сочетания mag+ объектов, упрощена обработка настроек видео, джамплинков

Resize/magResize_FF.jsx - изменяет размеры документа, 
результат сохраняет в папке обрабатываемого файла с префиксом _DPS_ 

Resize/magResize_onlyW.jsx - изменяет только ширину и поля документа, 
результат сохраняет в папке обрабатываемого файла с префиксом _DPS_ 
(если вылетает, magResize_FF.jsx, то используем magResize_onlyW.jsx, высоту ставим вручную)

