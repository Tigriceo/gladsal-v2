# Scroll Variants For Client Review

Ниже ссылки на один и тот же сайт с разными вариантами поведения скролла.
Задача заказчика: открыть каждый вариант и выбрать 1-2 лучших по ощущениям.

Тестовый сайт: https://tigriceo.github.io/gladsal-v2/

## Как оценивать

1. Насколько скролл комфортный в обычной прокрутке.
2. Нет ли ощущения, что сайт слишком медленный.
3. Нет ли резких пролетов на быстрых движениях колесом.
4. Как ощущается переход между секциями.

---

## Варианты 1-4 (базовые профили)

1. Default (контрольный):
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=slow

2. Soft (чуть мягче):
https://tigriceo.github.io/gladsal-v2/?lenisConfig=soft&lenisPreset=slow

3. Strict (максимально контролируемый):
https://tigriceo.github.io/gladsal-v2/?lenisConfig=strict&lenisPreset=slow

4. Glide (чуть более динамичный):
https://tigriceo.github.io/gladsal-v2/?lenisConfig=glide&lenisPreset=slow

---

## Варианты 5-8 (сбалансированные)

5. Balanced на default:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=balanced

6. Balanced на soft:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=soft&lenisPreset=balanced

7. Balanced на strict:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=strict&lenisPreset=balanced

8. Balanced на glide:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=glide&lenisPreset=balanced

---

## Варианты 9-12 (точечная настройка для мыши)

9. Мягкий и спокойный:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=slow&lenisClamp=92&lenisDesktopLerp=0.062&lenisDesktopWheelMultiplier=0.58

10. Контролируемый без пролетов:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=slow&lenisClamp=88&lenisDesktopLerp=0.056&lenisDesktopWheelMultiplier=0.52&lenisSpikeThreshold=140&lenisSpikeMultiplier=0.78

11. Более живой, но стабильный:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=slow&lenisClamp=108&lenisDesktopLerp=0.07&lenisDesktopWheelMultiplier=0.64&lenisSpikeThreshold=170&lenisSpikeMultiplier=0.86

12. Умеренно динамичный:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=glide&lenisPreset=balanced&lenisClamp=108&lenisDesktopLerp=0.074&lenisDesktopWheelMultiplier=0.66

---

## Варианты 13-16 (trackpad сценарии)

13. Trackpad базовый:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=slow&trackpadTuning=1

14. Trackpad мягче:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=soft&lenisPreset=slow&trackpadTuning=1&lenisTrackpadClamp=126&lenisTrackpadMultiplier=0.72

15. Trackpad более быстрый:
https://tigriceo.github.io/gladsal-v2/?lenisConfig=glide&lenisPreset=balanced&trackpadTuning=1&lenisTrackpadClamp=148&lenisTrackpadMultiplier=0.84

16. Trackpad tuning выключен (для сравнения):
https://tigriceo.github.io/gladsal-v2/?lenisConfig=default&lenisPreset=slow&trackpadTuning=0

---

## Быстрый выбор для заказчика

Если нужно выбрать быстро, сначала посмотреть только эти 4:

- Вариант 1 (контрольный)
- Вариант 2 (мягче)
- Вариант 3 (строже)
- Вариант 11 (живой, но стабильный)

