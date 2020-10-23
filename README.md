## Tchekhov's letters
Проект выполнен **Машей Ершовой** в рамках курса "Автоматической обработки языка" НИУ ВШЭ
### Корпус
Составлен из 331 письма (81459 словоформ) из переписки А. П. Чехова и О. Л. Книппер, опубликованной на сайте [http://apchekhov.ru](http://apchekhov.ru).
Корпус собирается [этой тетрадкой](https://github.com/ershovamary/NLP_third/blob/master/Project/NLP_Project_crawler.ipynb).
### Поиск
По корпусу можно искать:
* точное вхождение;
  > Например: "дусик"
* слово по лемме;
  > Например: актрисуля
* по форме слова и тэгам OpenCorpora;
  > Например: люблю+INFN
* комбинации из таких токенов.
  > Например: собака ADJF ADJF
  
Поиск осуществляется по тэгам pymorphy3 с помощью [этой программы](https://github.com/ershovamary/NLP_third/blob/master/Project/NLP_Project_search_better.ipynb).

#### POS-тэги OpenCorpora
| Тэг | Значение | Пример |
|:----:|:-------:|:------|
|NOUN|имя существительное|собака|
|ADJF|имя прилагательное (полное)|дорогой, мой|
|ADJS|имя прилагательное (краткое)|здоров|
|COMP|компаратив|лучше|
|VERB|глагол (личная форма)|люблю|
|INFN|глагол (инфинитив)|любить|
|PRTF|причастие (полное)|взволнованный|
|PRTS|причастие (краткое)|напечатан|
|GRND|деепричастие|судя|
|NUMR|числительное|два, мало|
|ADVB|наречие|лениво|
|NPRO|местоимение-существительное|ты|
|PRED|предикатив|надо, нельзя|
|PREP|предлог|за|
|CONJ|союз|а|
|PRCL|частица|вот|
|INTJ|междометие|ах, бррр|

#### Обратная связь
[telegram](https://t.me/ershovamary)

![](https://proza.ru/pics/2011/04/29/470.jpg)
