# QR.G.B.-ART 🎨🔬

**QR.G.B.-ART** — ваш прототип генератора художественных QR-кодов с элементами Generative Art, спектральной нормализацией и поддержкой многослойного кодирования.

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](https://opensource.org/licenses/MIT)
![Status: Science--Art](https://img.shields.io/badge/Status-Science--Art-brightgreen)

## 🌟 Концепция
Сайт ориентирован на технику **Spectral/Color Code**, связанную с исследованиями Михаила Кашкарова по спектральной нормализации для печати и светочувствительного искусства (Light-sensitive Art). 

### Ключевые функции:
* **Artistic QR:** Создание кодов с кастомными палитрами и градиентами (фиолетово-черные акценты), устойчивых к шуму.
* **SCI Multi-Layer:** Упаковка данных в три независимых цветовых канала (R, G, B) на базе модели **SCI**.
* **Visual Feedback:** Адаптивный интерфейс для тестирования читаемости кодов под разным освещением.

## 🛠 Технический стек
* **Canvas API:** Динамическая отрисовка слоев с наложением `lighten`.
* **Bradley Thresholding:** Алгоритм адаптивной бинаризации для стабильного сканирования физических поверхностей (холст, масло).
* **Lab-Color Space:** (В разработке) Расчет контраста по формуле ΔE для гарантированной читаемости.

## 🚀 Как пользоваться
1. Введите данные в поля **R**, **G** или **B**.
2. Получите стилизованный код, готовый к экспорту в PNG/SVG.
3. Используйте встроенный сканер для дешифровки спектральных слоев.

## 📖 Научная база
Проект является практической реализацией препринта:
> [Spectral Channel Integrity (SCI) Universal Model — Zenodo 18895764](https://zenodo.org/records/18895764)

## 👤 Автор / Researcher
**Михаил Кашкаров (Mykhailo Kashkarov)**
* [YouTube: Michael-RGB-ART](https://www.youtube.com/@Michael-RGB-ART)
* [Instagram: @mixailkashkarov](https://www.instagram.com/mixailkashkarov/)
* [X (Twitter): @MihailKashkarov](https://x.com/MihailKashkarov)

---
© 2026 QR.G.B.-ART | SCI Universal Model. Разработано для синхронизации цифрового кода и физической живописи.
