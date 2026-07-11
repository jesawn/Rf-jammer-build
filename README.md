# 📡 RF Jammer для Flipper Zero / RF Jammer for Flipper Zero

**Готовый `.fap` плагин для глушения сигналов. Собрано из исходников RocketGod специально для прошивки Momentum.**

**Ready-to-use `.fap` plugin for signal jamming. Compiled from RocketGod's source code specifically for Momentum firmware.**

---

## 🚀 Установка и использование / Installation & Usage

1. Скачай файл `jammer_app.fap` из раздела **Releases**.
2. Скопируй его в папку `apps` на SD-карте Flipper Zero.
3. Запусти через меню приложений.
4. Выбери нужную частоту и режим.

1. Download `jammer_app.fap` from the **Releases** section.
2. Copy it to the `apps` folder on your Flipper Zero SD card.
3. Launch from the apps menu.
4. Select the desired frequency and mode.

---

## 📡 Как это работает / How it works

**(Русский)**
Плагин генерирует мощный сигнал на выбранной частоте, который "забивает" эфир и мешает приёмникам распознавать реальные данные. Подходит для тестирования устройств на частотах 433 МГц и 868 МГц.

**(English)**
The plugin generates a powerful signal on the selected frequency, "jamming" the airwaves and preventing receivers from recognizing real data. Suitable for testing devices at 433 MHz and 868 MHz frequencies.

---

## ⚙️ Режимы работы / Operation Modes

| Режим / Mode | Описание / Description (RU) | Description (EN) |
| :--- | :--- | :--- |
| **OOK 650 kHz** | Передаёт непрерывный сигнал `0xFF`, который полностью "забивает" эфир. | Transmits a continuous `0xFF` signal, completely jamming the airwaves. |
| **2FSK 2.38 kHz** | Использует узкую полосу и точную модуляцию для запутывания демодуляторов. | Uses narrow bandwidth and precise modulation to confuse demodulators. |
| **MSK 99.97 Kb/s** | Генерирует случайный шум, имитирующий высокоскоростную цифровую связь. | Generates random noise that simulates high-speed digital communication. |
| **Шум / Noise** | Создаёт естественные помехи, которые сложно отфильтровать. | Creates natural interference that is hard to filter out. |

---

## ⚠️ Важное предупреждение / Important Warning

**Только для образовательных целей!** В реальной жизни использование глушилок запрещено законом и может привести к серьёзным последствиям.

**For educational purposes only!** In real life, using jammers is illegal and can lead to serious consequences.

---

## 👨‍💻 Исходный код и автор / Source Code & Original Author

Оригинальный проект и исходный код: **RocketGod-git/flipper-zero-rf-jammer**.  
Этот репозиторий содержит готовую сборку (`.fap`) для тех, кто не хочет компилировать самостоятельно.

Original project and source code: **RocketGod-git/flipper-zero-rf-jammer**.  
This repository contains a pre-built (`.fap`) version for those who don't want to compile it themselves.

---

Built and shared by **@jesawn**
