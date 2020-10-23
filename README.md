## Tchekhov's letters
 Проект выполнен **Машей Ершовой** в рамках курса "Автоматической обработки языка" НИУ ВШЭ
### Корпус
Составлен из 331 письма (81459 словоформ) из переписки А. П. Чехова и О. Л. Книппер, опубликованной на сайте [http://apchekhov.ru](http://apchekhov.ru).
Корпус собирается [этой тетрадкой](https://github.com/ershovamary/NLP_third/edit/master/NLP_Project_crawler.ipynb).
### Поиск
По корпусу можно искать:
* точное вхождение;
  > Например: "дусик"
* слова по лемме и тэгам OpenCorpora
  > Например: любить+INFN
* комбинации из таких токенов.
  > Например: собака ADJF
  
Поиск осуществляется по тэгам pymorphy3 с помощью [этой программы](https://github.com/ershovamary/NLP_third/edit/master/NLP_Project_search_better.ipynb).

#### POS-тэги OpenCorpora
