SciRec — Мікросервісна система персоналізованих рекомендацій наукових матеріалів
SciRec — це інтелектуальна система рекомендації наукових статей, яка поєднує декілька підходів машинного навчання для формування персоналізованих рекомендацій дослідникам та студентам.
Система реалізована як веб-застосунок на Python із використанням Flask та включає:
Content-Based Filtering (TF-IDF + Cosine Similarity)
Collaborative Filtering (SVD Matrix Factorization)
Knowledge Graph + PageRank
Hybrid Ensemble Recommendation Engine
Вбудований веб-інтерфейс
REST API для роботи з користувачами та рекомендаціями
Основні можливості
Управління користувачами
Створення профілів дослідників
Редагування профілів
Видалення користувачів
Збереження історії взаємодій
Каталог наукових статей
Генерація тестового набору з 200 наукових публікацій
Пошук за ключовими словами
Перегляд інформації про статті
Фільтрація за тегами
Персоналізовані рекомендації

Система використовує гібридний ансамбль з трьох моделей:

Content-Based	Аналіз змісту статей за допомогою TF-IDF
Collaborative Filtering	Пошук схожих користувачів через SVD
Knowledge Graph	Аналіз зв’язків між статтями та ключовими словами

Підсумкова рекомендація формується як зважена комбінація всіх моделей.

Використані технології
Backend
Python 3.9+
Flask
NumPy
SciPy
Scikit-Learn
Алгоритми ML
TF-IDF Vectorization
Cosine Similarity
Singular Value Decomposition (SVD)
PageRank
Maximum Marginal Relevance (MMR)
Frontend
HTML5
CSS3
JavaScript (Vanilla JS)
