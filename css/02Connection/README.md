# Подключение стилей к документу
## 1 способ:  
Атрибут style="" внутри открывающего тэга  
Этот атрибут применяется ко всему контенту внутри тэга, даже если внутри него есть еще тэги(как в примере тэг b, слово def бужет выделено жирным красным цветом)  
Этот способ не очень хорош, поскольку при его использовании можно подключить 1-2 стиля  

## 2 способ
Тэг style внутри тэга head.  
В нем прописываем тэг, в котором находится контент, который нам хочется украсить. После контента идут фигурные скобки, внутри которых прописываем стилизацию(через ;)  

## 3 способ
Наиболее правильным вариантом было бы "вынести" все стили в отдельный файл отдельно от HTML. Создадим файл с расширением .css. Внутри него пишем такой же код, как и в тэге style из предыдущего способа. После чего нам необходимо подключить этот css файл с помощью тэга link внутри head, в атрибут href вставляем путь до нашего css файла.