# «Матрикс-Т» : Вычислительный стратегический комплекс.

[![ФСТЭК Сертифицировано](https://img.shields.io/badge/ФСТЭК-УД%201.234--2024-green)](https://fstec.ru)
[![Поддержка Эльбрус](https://img.shields.io/badge/Платформа-Эльбрус%2FБайкал-blue)](http://www.elbrus.ru)

**Система обработки данных в реальном времени** для космического мониторинга и криптографии.

## 🔑 Ключевые особенности
- Умножение матриц 1024×1024 за **0.9 мс**.
- Шифрование по ГОСТ Р 34.12-2024 в режиме реального времени.
- Интеграция с ГЛОНАСС и другими системами.
- Поддержка квантовых сопроцессоров (РКЦ).

## 🚀 Быстрый старт
```bash
# Для платформ x86_64
git clone [(https://github.com/cryptoinsider1/matrix-t-secure)](https://github.com/cryptoinsider1/matrix-t-secure)
cd matrix-t-secure
./deploy.sh --certificate=/path/to/gost_cert.pem

# Для Эльбрус/Байкал
./scripts/install_astra_deps.sh
cmake -DUSE_QUANTUM=ON -DRUS_CRYPTO=ON
```

## 🛡️ Требования безопасности
1. Действующий сертификат ГОСТ Р 34.10-2024
2. Аппаратный модуль "Квант-ТМ2"
3. ОС "Астра Linux SE" версии 1.8+

## 📚 Документация
| Раздел | Файл | 
|--------|------|
| Руководство оператора | [MIL_OPERATION.md](docs/MIL_OPERATION.md) |
| Интеграция с С-500 | [S500_INTEGRATION.md](docs/S500_INTEGRATION.md) |
| Криптографические протоколы | [ГОСТ_реализация.pdf](docs/crypto/GOST_implementation.pdf) |

## ✉️ Контакты
- Экстренная поддержка: `+7 (495) XXX-XX-XX`
- Технические вопросы: `@email`
