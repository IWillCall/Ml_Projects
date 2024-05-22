### Опис проекту
У ході проекту я провів порівняння більше ніж 20 методів балансування класів для моделей логістичної регресії та дерева рішень. Також провів тюнінг гіперпараметрів моделі та оцінку параметрів за допомогою SHAP. 

В [Oversampling_methods_comparison](./Oversampling_methods_comparison.ipynb) задокументовано порівняння oversampling підходу до балансування класів.

В [Undexsampling_methods_comparison](./Undersampling_methods_comparison.ipynb) задокументовано порівняння undersampling підходу до балансування класів.

В кожному з блокнотів у висновках я виклав свої міркування щодо отриманих результатів.

### Джерело даних
Дані взяти з Kaggle:
[https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data](https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease/data)

Самі дані походять зі щорічного опитування CDC (Центр Контролю та Попередження Захворювань). У ході навчання моделі використано дані за 2022 рік, без відсутніх значень, всього близько 246 тис. записів та 39 змінних.
