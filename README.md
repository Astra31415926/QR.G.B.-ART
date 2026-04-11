# QR.G.B.-ART 🎨🔬

![Preview](QRGB_PRO%20540х540.png)

**QR.G.B.-ART** — прототип генератора художніх QR-кодів з елементами Generative Art, спектральною нормалізацією та підтримкою багатошарового кодування.

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
![Status: Science--Art](https://img.shields.io/badge/Status-Science--Art-brightgreen)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18895764.svg)](https://zenodo.org/records/18895764)
[![Behance](https://img.shields.io/badge/Behance-Case--Study-blue)](https://www.behance.net/gallery/247424185)

## 🌟 Концепція
Проєкт орієнтований на техніку **Spectral/Color Code**, засновану на дослідженнях Михайла Кашкарова зі спектральної нормалізації для фізичного друку та світлочутливого мистецтва (Light-sensitive Art). 

### Ключові функції:
* **Artistic QR:** Створення кодів із кастомними палітрами та градієнтами (фіолетово-чорні акценти), стійких до візуального шуму.
* **Multi-Layer Encoding:** Упаковка незалежних даних у три колірні канали (R, G, B) на базі моделі **цілісності спектральних каналів**.
* **Visual Feedback:** Інструментарій для тестування зчитування кодів під різним спектральним освітленням.

## 📖 Наукова база
Проєкт реалізує модель **Spectral Channel Integrity (цілісність спектральних каналів)**:

> **Spectral Channel Integrity Universal Model**
> DOI: [10.5281/zenodo.18895764](https://doi.org/10.5281/zenodo.18895764)

Система аналізує відбивну здатність пігментів і синхронізує рівні яскравості каналів, що дозволяє використовувати фізичні поверхні (полотно, олія) як стабільні носії даних.

## 🛠 Технічний стек
* **Canvas API:** Динамічне малювання шарів із накладенням `lighten`.
* **Bradley Thresholding:** Алгоритм адаптивної бінаризації для стабільного сканування текстурованих поверхонь.
* **Lab-Color Space:** Розрахунок колірного контрасту ΔE для автоматичної верифікації зчитування.

## 🚀 Швидкий старт
Проєкт доступний онлайн: [https://astra31415926.github.io/QRGB-Spectral-Encoding/](https://astra31415926.github.io/QRGB-Spectral-Encoding/)

1. Введіть дані в поля **R**, **G** або **B**.
2. Експортуйте стилізований код у PNG для друку або цифрового використання.
3. Використовуйте вбудований сканер для дешифрування шарів через камеру смартфона.

## 👤 Автор / Researcher
**Михайло Кашкаров (Mykhailo Kashkarov)**
Science-Art дослідник, творець моделі цілісності спектральних каналів.

* 📱 **[Behance: Case Study & Presentation](https://www.behance.net/gallery/247424185)**
* [YouTube: Michael-RGB-ART](https://www.youtube.com/@Michael-RGB-ART)
* [Instagram: @mixailkashkarov](https://www.instagram.com/mixailkashkarov/)
* [Medium: @Bakminsterfuler](https://medium.com/@Bakminsterfuler)
* [Zenodo Profile](https://zenodo.org/records/18895764)

---
© 2026 QR.G.B.-ART | Модель цілісності спектральних каналів. Розроблено для синхронізації цифрового коду та фізичного живопису.
