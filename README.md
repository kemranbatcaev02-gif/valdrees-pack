# 🛡️ Valdrees RolePlay — Minecraft Server Resource Pack

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.20%2B-5B8C32?style=for-the-badge&logo=minecraft&logoColor=white" alt="Minecraft Version" />
  <img src="https://img.shields.io/badge/Pack%20Format-Custom%20RP-2496ED?style=for-the-badge" alt="Resource Pack" />
  <img src="https://img.shields.io/badge/RolePlay-Police%20%26%20Government-E02424?style=for-the-badge" alt="RP Genre" />
  <img src="https://img.shields.io/badge/License-Proprietary-gray?style=for-the-badge" alt="License" />
</p>

<p align="center">
  Официальный ресурспак для сервера <b>Valdrees RP</b> в Minecraft.<br/>
  Включает фирменную айдентику, кастомные 3D-модели экипировки, уникальные бейджи рангов и шрифтовые глифы для создания глубокой ролевой атмосферы.
</p>

---

## ✨ Что входит в ресурспак

### 🎖️ Уникальные бейджи и ранги (Font Badges)
Кастомные графические иконки над головами и в чате для всех фракций и ролей сервера:
- 👑 **Руководство:** `owner`, `admin`, `chiefadmin`, `chieftech`, `tech`
- 🛡️ **Модерация и правопорядок:** `moder`, `police`
- 🌟 **Статусы сообщества:** `media`, `sponsor`, `veteran`, `default`

### 🔫 3D-модели предметов и экипировки
- ⛓️ **Наручники (`handcuffs`):** Кастомная модель и текстура для задержания нарушителей полицейскими.
- ⚡ **Электрошокер (`taser`):** Нелетальное спецсредство для силовых структур.
- 📐 Индивидуальные JSON-предикаты моделей под систему `CustomModelData`.

### 🎨 Серверный интерфейс и брендинг
- 🏛️ Фирменный логотип **Valdrees** (в высоком разрешении и компактной версии).
- 📜 Текстурные разделители (`divider_0`, `divider_1`, `divider_2`) для красивого оформления меню и табло.
- 💬 Слоган-текстуры и акцентные плашки для диалоговых окон.
- 🔤 Кастомный маппинг шрифтов Minecraft (`assets/minecraft/font/default.json`).

---

## 📥 Установка ресурспака

### Способ 1: Обычный клиент Minecraft (Java Edition)
1. Скачайте архив **`VALDREES.zip`** из этого репозитория (или раздела [Releases](https://github.com/kemranbatcaev02-gif/valdrees-pack/releases)).
2. Нажмите сочетание клавиш `Win + R`, введите `%appdata%\.minecraft\resourcepacks` и нажмите **Enter**.
3. Скопируйте файл `VALDREES.zip` в открывшуюся папку.
4. В игре откройте **Настройки → Наборы ресурсов** и перенесите **Valdrees Pack** в правую колонку (активные наборы).

### Способ 2: Сторонние лаунчеры (Prism / Modrinth / CurseForge / TLauncher)
- Перейдите в настройки нужного профиля игры → вкладка **Ресурспаки** (Resource Packs) → нажмите **Добавить** и выберите `VALDREES.zip`.

---

## 🗂️ Структура архива

```text
VALDREES.zip
├── pack.mcmeta                               # Метаданные ресурспака
├── pack.png                                  # Иконка набора в меню игры
└── assets/
    ├── minecraft/
    │   └── font/default.json                 # Переопределение глифов ванильного шрифта
    ├── valdre/
    │   ├── items/                            # Определения предметов (handcuffs, taser)
    │   └── models/item/                      # 3D JSON-модели кастомной экипировки
    └── valdrees/
        ├── font/                             # Шрифтовые раскладки (badge.json, icon.json, logo.json)
        └── textures/font/                    # Текстуры логотипов, разделителей и бейджей
            └── badge/                        # Текстуры рангов (admin, police, owner и др.)
```

---

## ⚙️ Требования и совместимость

- **Версия Minecraft:** 1.20+ (Java Edition)
- **Моды на оптику:** Рекомендуется наличие **OptiFine** или связки **Fabric + Sodium + CIT Resewn** для корректного отображения всех кастомных моделей и анимаций.

---

## 📜 Лицензия и копирайт

Все графические ассеты, модели и шрифты являются интеллектуальной собственностью проекта **Valdrees RP**. Использование ассетов на сторонних коммерческих серверах без согласования с автором запрещено.