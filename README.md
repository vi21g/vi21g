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


### [2. Генетический алгоритм для обучения агентов в Gym](https://github.com/vi21g/gym_genetic_algorithm) :

**Описание**: Обучение RL-агентов с помощью генетического алгоритма в средах Gym (CartPole, LunarLander, BipedalWalker) с использованием transfer learning между схожими средами.

**Стек**: `gymnasium`, `numpy`, `Jupyter Notebook`, `генетические алгоритмы`

**Особенности**:
- Перенос весов между дискретными средами (CartPole → LunarLander) для ускоренного обучения
- Ранняя остановка для BipedalWalker при достижении целевого результата (300+ баллов)
- Гибкая система мутаций (MUTATION_RATE) и селекции (NSURV) в генетическом алгоритме
- Видеодемонстрации работы обученных агентов в каждом окружении


### [3. Telegram-бот](https://github.com/vi21g/tgBot) :

**Описание**: Бот в виде викторины: вопрос-ответ с определенной базой знаний. Сохраняет результат по мере прохождения квиза.

**Стек**: `aiogram`, `aiosqlite`

**Особенности**: Асинхронная архитектур для высокой отзывчивости, лёгкая и быстрая база данных на основе SQLite


### [4. Классические ML модели в бинарной классификации](https://github.com/vi21g/sklearn-models)

**Описание**: Бинарная классификация текстовых постов Reddit на тему депрессии. Реализована на классических ML-алгоритмах из библиотеки **scikit-learn**

**Стек**: `scikit-learn (sklearn)`, `classic ML`, `Depression: Reddit Dataset`

**Особенности**: Сравнение эффективности разных алгоритмов sklearn на текстовых данных, готовый pipeline для бинарной классификации


