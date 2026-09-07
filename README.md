# f4xp1 — Официальные релизы

> Высокопроизводительный безопасный мессенджер нового поколения (QUIC, Zero-Knowledge Protection, Terminal Noir UI).

---

## 📥 Скачать актуальную версию (v0.1.0-alpha)

| Версия | Ссылка | Размер | Описание |
|---|---|---|---|
| **Windows Установщик** | [⬇️ `fuck_speed_setup_v0.1.0-alpha_x86_64.exe`](https://github.com/marwy/f4xp1_release/releases/latest/download/fuck_speed_setup_v0.1.0-alpha_x86_64.exe) | **16.47 MB** | Мастер установки, ярлыки, автозапуск (не требует прав администратора) |
| **Портативная версия** | [⬇️ `fuck_speed_portable_v0.1.0-alpha_x86_64.zip`](https://github.com/marwy/f4xp1_release/releases/latest/download/fuck_speed_portable_v0.1.0-alpha_x86_64.zip) | **20.36 MB** | Распакуй и запусти (все данные и настройки изолированы в папке `portable_data/`) |

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
8b05c4b3519d1f99374222986cb9d872d4736e1b001395d9a0e0d4ecff5b5a4e *fuck_speed_setup_v0.1.0-alpha_x86_64.exe
5174192c9c6b923594de0e56e3a93e274d0ca71c458cbeaa3b6e474b0fcf64df *fuck_speed_portable_v0.1.0-alpha_x86_64.zip
9030daa8c150afbb626cf14b3ea211820638cc4f7bdc92b20f23748c0bc6e6cf *fuck_speed.exe.zst
```

---

## 🛠️ Системные требования
- **ОС**: Windows 10 / Windows 11 (64-bit)
- **Архитектура**: x86-64 (поддержка SSE4.2 / AVX)
- **Графика**: Поддержка Vulkan / DirectX 12 / WebGPU (wgpu 30.0)

---
*Официальный канал релизов проекта fuck_speed.*
