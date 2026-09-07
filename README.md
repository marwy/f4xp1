# fuck_speed — Официальные релизы

> Высокопроизводительный безопасный мессенджер нового поколения (QUIC, Zero-Knowledge Protection, Terminal Noir UI).

---

## 📥 Скачать актуальную версию (v0.1.0-alpha)

| Версия | Ссылка | Размер | Описание |
|---|---|---|---|
| **Windows Установщик** | [⬇️ `fuck_speed_setup_v0.1.0-alpha_x86_64.exe`](https://github.com/marwy/fuckspeed_release/releases/latest/download/fuck_speed_setup_v0.1.0-alpha_x86_64.exe) | **16.47 MB** | Мастер установки, ярлыки, автозапуск (не требует прав администратора) |
| **Портативная версия** | [⬇️ `fuck_speed_portable_v0.1.0-alpha_x86_64.zip`](https://github.com/marwy/fuckspeed_release/releases/latest/download/fuck_speed_portable_v0.1.0-alpha_x86_64.zip) | **20.36 MB** | Распакуй и запусти (все данные и настройки изолированы в папке `portable_data/`) |

---

## ⚡ Бесшовное In-Place обновление
Клиент оснащен встроенной системой фонового автообновления:
1. При выходе новой версии клиент в фоне тихо скачивает оптимизированный zstd-пакет (`~16 МБ`).
2. Проверяет криптографическую подпись **Ed25519** и контрольные суммы **BLAKE3**.
3. В заголовке окна появляется зеленая кнопка **`[↑ v0.1.0-alpha]`**.
4. Нажмите на нее в удобный момент — приложение мгновенно перезапустится в обновленной версии.

---

## 🔐 Контрольные суммы (v0.1.0-alpha, сборка 101)

```text
b2bcfde79b931bfe1098f7f0c9c005dd2adedc99dc0d3a3b5edfaeabb83cbf4d *fuck_speed_setup_v0.1.0-alpha_x86_64.exe
b96e5ce3be99f3e6e4d3efcdcacca0ec0a7bfdf961838fa8d7a57ac0e6702f51 *fuck_speed_portable_v0.1.0-alpha_x86_64.zip
9030daa8c150afbb626cf14b3ea211820638cc4f7bdc92b20f23748c0bc6e6cf *fuck_speed.exe.zst
```

---

## 🛠️ Системные требования
- **ОС**: Windows 10 / Windows 11 (64-bit)
- **Архитектура**: x86-64 (поддержка SSE4.2 / AVX)
- **Графика**: Поддержка Vulkan / DirectX 12 / WebGPU (wgpu 30.0)

---
*Официальный канал релизов проекта fuck_speed.*
