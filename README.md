# Воркшоп по базовому Reinforcement Learning (RL)

Добро пожаловать в репозиторий, посвящённый воркшопу по основам Reinforcement Learning (RL)! Здесь вы познакомитесь с ключевыми концепциями RL и получите практический опыт обучения RL-агента на примере Huggy.

---

## О чём этот воркшоп?

Этот воркшоп предназначен для тех, кто хочет понять основы Reinforcement Learning (обучения с подкреплением). Мы разберём ключевые концепции, алгоритмы и инструменты, которые помогут вам начать работу в этой области.

---

## Основные темы

### Теоретическая часть
1. **Кто такой агент?**
   - Агент — это сущность, которая взаимодействует с окружением, принимает решения и учится на основе обратной связи.

2. **Что такое окружение (Environment)?**
   - Окружение — это мир, в котором существует агент. Оно предоставляет агенту наблюдения и награды за его действия.

3. **Наблюдения (Observations)**
   - Данные, которые агент получает от окружения. Это может быть, например, изображение, координаты или другие сенсорные данные.

4. **Состояние (State)**
   - Текущее состояние окружения, которое агент использует для принятия решений.

5. **Действия (Actions)**
   - Набор действий, которые агент может выполнить в окружении.

6. **Политика (Policy)**
   - Стратегия, которую использует агент для выбора действий на основе текущего состояния.

7. **Методы, основанные на политике (Policy-based Methods, Policy Gradient)**
   - Алгоритмы, которые напрямую оптимизируют политику агента.

8. **Методы, основанные на ценности (Value-based Methods)**
   - Алгоритмы, которые обучают агента, оценивая ценность состояний и действий.

9. **Actor-Critic (PPO)**
   - Гибридный подход, сочетающий Policy-based и Value-based методы. Пример: Proximal Policy Optimization (PPO).

10. **Q-Learning**
    - Алгоритм, который обучает агента находить оптимальную стратегию через оценку Q-функции.

11. **Глубинное Q-обучение (Deep Q-Learning)**
    - Расширение Q-Learning с использованием нейронных сетей для работы с большими пространствами состояний.

12. **Model-based RL**
    - Подход, при котором агент строит модель окружения для планирования действий.

13. **Оффлайн vs. Онлайн обучение (Offline vs. Online Reinforcement Learning)**
    - Оффлайн обучение: агент обучается на заранее собранных данных.
    - Онлайн обучение: агент обучается в реальном времени, взаимодействуя с окружением.

14. **Обучение с подражанием (Imitation Learning)**
    - Агент учится, имитируя поведение эксперта.

15. **Доступные симуляторы для обучения простейших RL-агентов**
    - Симуляторы для обучения агентов в средах "AI vs Environment" и "AI vs AI":
      - [Unity ML-Agents](https://github.com/Unity-Technologies/ml-agents)
      - [OpenAI Gym](https://www.gymlibrary.dev/)
      - [Stable-Baselines3](https://stable-baselines3.readthedocs.io/)

16. **Литература и курсы для дальнейшего обучения**
    - Книги:
      - "Reinforcement Learning: An Introduction" by Richard S. Sutton and Andrew G. Barto.
    - Курсы:
      - [Deep Reinforcement Learning Course by Hugging Face](https://huggingface.co/deep-rl-course)
      - [CS234: Reinforcement Learning (Stanford)](http://web.stanford.edu/class/cs234/)

## Как начать?

1. Клонируйте репозиторий:
   ```bash
   git clone <git-link>