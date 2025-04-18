# 👋 Привет, я Виталий Григорьев

## Обо мне:
Специализируюсь на нейросетях и машинном обучении.  
Люблю сложные задачи, работаю с данными, моделями и их внедрением.  
Всегда открыт к новым вызовам и коллаборациям!  

**🔧 Технологии**: Python, PyTorch/TensorFlow, NLP/CV, классические ML. 

**🧠 Изучаю**: Deep Q Learning, GA + RL, архитектуры GAN 

**📫 Связаться со мной**: [telegram](https://t.me/grigorev21), [e-mail](vitek21sme@gmail.com)

---  


                    
## **Мои проекты:**

### [1. RAG-система](https://github.com/vi21g/RAG_witcher_wiki) :

**Описание**: RAG-система для поиска ответов в вики-базе по вселенной «Ведьмака»

**Стек**: `LlamaIndex`, `OpenAI`, `Arize Phoenix`, `Knowledge Maps`, `Jupyter Notebook`

**Особенности**: Защита от галлюцинаций через трейсинг запросов (Arize Phoenix), оптимизация поиска за счёт декомпозиции запросов (Knowledge Maps), готовое решение для работы с узкоспециализированными данными (например, lore вселенной).


### [2. Классификация текста: трансформеры vs классические ML](https://github.com/vi21g/classic_ml_vs_transformers) :  

**Описание**: Сравнительный анализ эффективности трансформерных моделей (DistilBERT) и классических методов (Logistic Regression, XGBoost, SVM) в задаче бинарной классификации русскоязычных текстов.  

**Стек**:  
`Transformers` (Hugging Face), `Scikit-learn`, `Pandas`, `NLTK`, `Google Colab`, `Jupyter Notebook`  

**Особенности**:  
- Работа в виде построения гипотез и исследования
- Подробный разбор влияния **балансировки классов** на качество предсказаний (прирост F1-score на 7-8% для минорного класса)  
- Готовые решения для **предобработки текста** (нормализация, исправление опечаток)  
- Интерактивный **Colab-ноутбук** с воспроизводимыми экспериментами


### [3. Генетический алгоритм для обучения агентов в Gym](https://github.com/vi21g/gym_genetic_algorithm) :

**Описание**: Обучение RL-агентов с помощью генетического алгоритма в средах Gym (CartPole, LunarLander, BipedalWalker) с использованием transfer learning между схожими средами.

**Стек**: `gymnasium`, `numpy`, `Jupyter Notebook`, `генетические алгоритмы`

**Особенности**:
- Перенос весов между дискретными средами (CartPole → LunarLander) для ускоренного обучения
- Ранняя остановка для BipedalWalker при достижении целевого результата (300+ баллов)
- Гибкая система мутаций (MUTATION_RATE) и селекции (NSURV) в генетическом алгоритме
- Видеодемонстрации работы обученных агентов в каждом окружении


### [4. Кластеризация клиентов торгового центра](https://github.com/vi21g/clustering) :  

**Описание**: Сравнение методов кластеризации (K-means и Deep Embedded Clustering) для сегментации клиентов по данным о возрасте, доходе и покупательской активности.  

**Стек**:  `Scikit-learn` (KMeans), `TensorFlow/Keras` (DEC), `Pandas`, `Matplotlib/Seaborn`, `Jupyter Notebook`  

**Особенности**:  
- Подробный **анализ оптимального числа кластеров** (метод локтя, silhouette score)  
- Сравнение **классического (K-means)** и **нейросетевого (DEC)** подходов  
- Готовые **визуализации распределения кластеров** в 2D/3D  
- Тестирование **устойчивости** кластеризации к random_state  

**Ключевой вывод**:  
DEC эффективен для задач с неочевидной структурой данных, но требует больше вычислительных ресурсов. K-means остается «золотым стандартом» для быстрого анализа.


### [5. Telegram-бот](https://github.com/vi21g/tgBot) :

**Описание**: Бот в виде викторины: вопрос-ответ с определенной базой знаний. Сохраняет результат по мере прохождения квиза.

**Стек**: `aiogram`, `aiosqlite`

**Особенности**: Асинхронная архитектур для высокой отзывчивости, лёгкая и быстрая база данных на основе SQLite


### [6. Классические ML модели в бинарной классификации](https://github.com/vi21g/sklearn-models)

**Описание**: Бинарная классификация текстовых постов Reddit на тему депрессии. Реализована на классических ML-алгоритмах из библиотеки **scikit-learn**

**Стек**: `scikit-learn (sklearn)`, `classic ML`, `Depression: Reddit Dataset`

**Особенности**: Сравнение эффективности разных алгоритмов sklearn на текстовых данных, готовый pipeline для бинарной классификации


