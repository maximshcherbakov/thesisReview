"# thesisReview" 

# Шаблон для подготовки отзывов на автореферат в LaTeX.

## Общая информация

* Шаблон использует стилевой файл Lecture Notes in Computer Science (LNCS) http://www.springer.com/computer/lncs?SGWID=0-164-6-793341-0
* Кодировка tex файлов windows1251
* Пожалуйста, измените файл template.tex в соответствии с вашим стилем подготовки отзывов.

## Состав файлов

В template.tex вы задаете свой стиль отзыва в котором используются переменные, например \issue .

В preface.tex вы указываете информацию о диссертации: автор, тема, и т.д. (см. комментарии в файле)

В body.tex вы пишете содержательную часть отзыва.

_Вот здесь как раз и пишите значения переменных 
\newcommand{\issue}
{
%распознавания образов на изображениях, приведен исчерпывающий перечень различных имеющихся подходов, выделена специфика задачи. 
...
}_

В footer.tex вы указываете информацию о том, кто подписывает отзыв. 
