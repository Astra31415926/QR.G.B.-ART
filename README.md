# QR.G.B.-ART 🎨🔬

![Preview](screenshot.png)

**QR.G.B.-ART** — прототип генератора художественных QR-кодов с элементами Generative Art, спектральной нормализацией и поддержкой многослойного кодирования.

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
![Status: Science--Art](https://img.shields.io/badge/Status-Science--Art-brightgreen)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18895764.svg)](https://zenodo.org/records/18895764)

## 🌟 Концепция
Проект ориентирован на технику **Spectral/Color Code**, основанную на исследованиях Михаила Кашкарова по спектральной нормализации для физической печати и светочувствительного искусства (Light-sensitive Art). 

### Ключевые функции:
* **Artistic QR:** Создание кодов с кастомными палитрами и градиентами (фиолетово-черные акценты), устойчивых к визуальному шуму.
* **SCI Multi-Layer:** Упаковка независимых данных в три цветовых канала (R, G, B) на базе модели **SCI**.
* **Visual Feedback:** Инструментарий для тестирования читаемости кодов под разным спектральным освещением.

## 📖 Научная база
Проект реализует **Spectral Channel Integrity (SCI)** модель:

> **Spectral Channel Integrity (SCI) Universal Model**
> DOI: [10.5281/zenodo.18895764](https://doi.org/10.5281/zenodo.18895764)

Система анализирует отражательную способность пигментов и синхронизирует уровни яркости каналов, что позволяет использовать физические поверхности (холст, масло) как стабильные носители данных.

## 🛠 Технический стек
* **Canvas API:** Динамическая отрисовка слоев с наложением `lighten`.
* **Bradley Thresholding:** Алгоритм адаптивной бинаризации для стабильного сканирования текстурированных поверхностей.
* **Lab-Color Space:** Расчет цветового контраста ΔE для автоматической верификации читаемости.

## 🚀 Быстрый старт
Проект доступен онлайн: [https://astra31415926.github.io/QRGB-Spectral-Encoding/](https://astra31415926.github.io/QRGB-Spectral-Encoding/)

1. Введите данные в поля **R**, **G** или **B**.
2. Экспортируйте стилизованный код в PNG для печати или цифрового использования.
3. Используйте встроенный сканер для дешифровки слоев через камеру смартфона.

## 👤 Автор / Researcher
**Михаил Кашкаров (Mykhailo Kashkarov)**
Science-Art исследователь, создатель модели SCI.

* [YouTube: Michael-RGB-ART](https://www.youtube.com/@Michael-RGB-ART)
* [Instagram: @mixailkashkarov](https://www.instagram.com/mixailkashkarov/)
* [Medium: @Bakminsterfuler](https://medium.com/@Bakminsterfuler)
* [Zenodo Profile](https://zenodo.org/records/18895764)

---
© 2026 QR.G.B.-ART | SCI Universal Model. Разработано для синхронизации цифрового кода и физической живописи.
