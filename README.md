# Звіт до роботи
## Тема: Тестування програм
### Мета роботи: Cтворити декілька Python файлів для роботи
---
### Виконання роботи
- Результати виконання завдання *14*;
    1. Розробив Савка Віталій
    1..
- вставлені рисунки (скріншоти екрана або фотографії виконаного завдання у зошиті);
- ![Screenshot_8](https://user-images.githubusercontent.com/111871895/202234838-f386fbc6-5a62-48c7-b56a-dd1546cc47dc.png)

> 

![alt text](https://github.com/BobasB/it_college/raw/main/reports/pictures/logo-lit.jpg "ІТ Коледж")

- Код /и:
- class Figure:
    def __init__(self, type, length) -> None:
        assert length > 0, "Довжина має бути більшою за 0!"
        assert type in ["квадрат", "прямокутник", "трикутник"], "Дозволені фігури: квадрат, прямокутник, трикутник"
        self.type = type
        self.length = length

#a = Figure("трапеція", 12)
#b = Figure("квадрат", 0)
c = Figure("квадрат", 1)
class Figure:
    FIGURES = ["квадрат", "прямокутник", "трикутник"]
    def __init__(self, type, length) -> None:
        assert length > 0, "Довжина має бути більшою за 0!"
        assert type in self.FIGURES, "Дозволені фігури: квадрат, прямокутник, трикутник"
        self.type = type
        self.length = length

    @property
    def get_figure_type(self):
        return self.type

    @property
    def get_figure_length(self):
        return self.type # робимо помилку
```python
def simple_function_example():
    pass
```
```text
<< SOME text HERE >>
```

- результати виконання індивідуального завдання (якщо такі є);

### Висновок: 
> у висновку потрібно відповісти на запитання:
- :question: Що зроблено в роботі;
- Протестував юніт тести з використання бібліотеки PyTest
- :question: Чи досягнуто мети роботи;
- Ні
- :question: Які нові знання отримано;
-  Процес перевірки правильності роботи програм, їх функцій та поведінки при різних умовах роботи шляхом створення штучних ситуацій або сценаріїв.
- :question: Чи вдалось відповісти на всі питання задані в ході роботи;
- Ні
- :question: Чи вдалося виконати всі завдання;
- Ні
- :question: Чи виникли складності у виконанні завдання;
- Так
- :question: Чи подобається такий формат здачі роботи (Feedback);
- Так
- :question: Побажання для покращення (Suggestions);
- Так
---
