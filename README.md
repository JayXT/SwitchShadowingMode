# SwitchShadowingMode

## EN

A simple GNU/Linux shell script to redirect in real-time microphone input to headphones and thus hear both your voice and system audio at the same time. This is especially useful for monitoring your continuous shadowing of a language parent during pronunciation training on [Refold Stage 3B](https://t.me/RefoldUA/184) or later.

### Dependencies
- PipeWire + WirePlumber

### Preparation
1. Copy the script to any directory under PATH.
2. Make the script executable.
3. Assign a shortcut in your DE or WM configuration to call the script, e.g. `Super+Shift+S`.

### Usage
1. When the shadowing mode needs to be activated, press the respective shortcut once.
2. When the shadowing mode needs to be deactivated, press the shortcut once more.

### Notes
- It's important to avoid using the script with speakers as a default output device to avoid audio feedback. Earbuds or ideally headphones should be used.
- The script was tested against Debian 13 XFCE.

## UK

Простий скрипт оболонки для GNU/Linux, що дозволяє перенаправляти в режимі реального часу сигнал з мікрофона на навушники і таким чином чути водночас ваш голос та системне аудіо. Це особливо корисно для моніторингу вашого безперервного наслідування мови батька впродовж тренування вимови на [Refold Стадії 3Б](https://telegra.ph/S3B3-Trenuvannya-vimovi-10-16) чи пізніше.

### Залежності
- PipeWire + WirePlumber

### Підготовка
1. Скопіюйте скрипт у будь-який каталог, що входить до змінної PATH.
2. Надайте скрипту права на виконання.
3. У налаштуваннях вашого середовища робочого столу (DE) або віконного менеджера (WM) призначте комбінацію клавіш для запуску скрипта, наприклад `Super+Shift+S`.

### Використання
1. Щоб увімкнути режим наслідування мови, натисніть відповідну комбінацію клавіш один раз.
2. Щоб вимкнути режим наслідування мови, натисніть цю комбінацію клавіш ще раз.

### Примітки
- Важливо не використовувати скрипт, якщо динаміки обрані як пристрій виводу за замовчуванням, щоб уникнути зворотного аудіо зв’язку. Слід використовувати навушники-вкладиші або, в ідеалі, накладні навушники.
- Скрипт було протестовано на Debian 13 XFCE.
