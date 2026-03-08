<!--
  ╔══════════════════════════════════════════════════════════╗
  ║              WEBGUIDE.DEV — BANNER HEADER                ║
  ╚══════════════════════════════════════════════════════════╝
-->
<div align="center">
<table width="100%" style="border:0;background:#1a1a2e;border-radius:12px"><tr><td align="center" style="padding:32px 24px 24px">

<h1>🌐 WebGuide — Комплексний Гайд з HTML & CSS</h1>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#html-блоки)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#css--як-організовано-стилі)
[![Responsive](https://img.shields.io/badge/RESPONSIVE-4CAF50?style=for-the-badge&logo=googlechrome&logoColor=white)](#-поради-та-фішки)
[![License](https://img.shields.io/badge/LICENSE-grey?style=for-the-badge)](LICENSE)
[![MIT](https://img.shields.io/badge/MIT-b3a696?style=for-the-badge)](#)

<br/>

**Професійна документація веб-розробки з інтерактивним навігаційним меню та красивим теплим дизайном**

<br/>

[🌟 Основні Особливості](#-огляд-проєкту) • [🚀 Швидкий Старт](#-швидкий-старт) • [📚 Документація](#-html-блоки) • [🎨 Дизайн](#️-кольорова-палітра)

</td></tr></table>

<br/>

| 🏗️ HTML блоків | 🎨 CSS секцій | ⚡ JS функцій | 📄 Файлів |
|:-:|:-:|:-:|:-:|
| **9** | **12** | **10** | **3** |

</div>

---

## 📋 Зміст

- [🌱 Огляд проєкту](#-огляд-проєкту)
- [📁 Структура файлів](#-структура-файлів)
- [🏗️ HTML Блоки](#️-html-блоки)
- [🎨 CSS — як організовано стилі](#-css--як-організовано-стилі)
- [⚡ JavaScript](#-javascript)
- [🖌️ Кольорова палітра](#️-кольорова-палітра)
- [💡 Поради та фішки](#-поради-та-фішки)
- [🚀 Швидкий старт](#-швидкий-старт)
- [📬 Контакти](#-контакти)

---

## 🌱 Огляд проєкту

**WebGuide.dev** — інтерактивна документація-гайд, яка крок за кроком показує як зібрати повноцінний лендинг з нуля. Кожен блок подається у форматі **HTML поруч із CSS** — щоб бачити зв'язок між розміткою і стилем.

### Що всередині

| Модуль | Опис |
|--------|------|
| 🏗️ **9 HTML-блоків** | Header, Hero, Features, Content, Two-Column, Cards, CTA, FAQ, Footer |
| 🎨 **Дизайн-система** | 6 кольорів, 3 рівні шрифтів, Golden Ratio відступи |
| ⚡ **Vanilla JS** | Без фреймворків — чистий браузерний JavaScript |
| 📱 **Адаптивність** | `@media` breakpoints, Grid і Flex переходять в 1 колонку |
| 📖 **Коментарі** | Кожен рядок коду пояснено прямо у файлі |

> 💡 **Підхід гайду:** Спочатку структура — потім стиль. Кожна HTML-секція має свій CSS-блок поруч. Це допомагає розуміти не просто «як виглядає», а «чому виглядає саме так».

---

## 📁 Структура файлів

<!--
  ╔══════════════════════════════════════════╗
  ║           СТРУКТУРА ПРОЄКТУ              ║
  ╚══════════════════════════════════════════╝
-->
<table width="100%" style="border:0;background:#161b22;border-radius:10px"><tr><td style="padding:20px 28px">

```
project/
├── 📄 index.html       ← точка входу, весь HTML розмічений тут
├── 🎨 styles.css       ← всі стилі, від reset до @media
├── ⚙️  script.js        ← інтерактивність та DOM-логіка
└── 📖 README.md        ← цей файл
```

</td></tr></table>

### Як відкрити

**Варіант 1 — просто в браузері:**
```bash
# Просто відкрий index.html у будь-якому браузері
open index.html
```

**Варіант 2 — Live Server (рекомендовано):**
```bash
# Встанови розширення Live Server у VS Code
# Правий клік на index.html → "Open with Live Server"
# Файл автоматично оновлюється при кожному збереженні
```

**Варіант 3 — клонування репо:**
```bash
git clone https://github.com/webguide-dev/webguide.git
cd webguide
open index.html
```

---

## 🏗️ HTML Блоки

Файл `index.html` розбитий на **9 семантичних секцій**. Кожна позначена коментарем для швидкого пошуку (`Ctrl+F`):

```html
<!-- ═══════════════════════════════════════
     НАЗВА БЛОКУ
════════════════════════════════════════ -->
```

### Перелік блоків

| # | Блок | Тег | Опис |
|---|------|-----|------|
| 1 | **Header / Навігація** | `<header>` | Sticky, логотип + `<nav>`, якорі до секцій |
| 2 | **Hero секція** | `<section>` | Grid 2 колонки: текст + зображення, h1, CTA кнопки |
| 3 | **Features картки** | `<section>` | Grid з 3 карток, іконка + заголовок + опис, hover |
| 4 | **Content 2-Col** | `<section>` | CSS Grid: зліва зображення, справа текст зі списком |
| 5 | **Two-Column Items** | `<section>` | Flexbox items: іконка + текст поруч |
| 6 | **Info Cards** | `<section>` | Grid 4 картки, overlay-текст при hover |
| 7 | **CTA секція** | `<section>` | Повноширокий блок, темний фон, велика кнопка |
| 8 | **FAQ акордеон** | `<section>` | JS toggle, `classList.toggle('active')` |
| 9 | **Footer** | `<footer>` | 4 колонки: лого, посилання, контакти, соцмережі |

---

## 🎨 CSS — як організовано стилі

Файл `styles.css` має чітку структуру розділів, відокремлених великими коментарями:

```
styles.css
├── /* РОЗДІЛ 1 */  Universal reset + body styles
├── /* РОЗДІЛ 2 */  :root змінні (кольори, відступи, шрифти)
├── /* РОЗДІЛ 3 */  Header + Navigation
├── /* РОЗДІЛ 4 */  Hero секція
├── /* РОЗДІЛ 5 */  Кнопки (.btn-primary, .btn-secondary)
├── /* РОЗДІЛ 6 */  Features grid
├── /* РОЗДІЛ 7 */  Content grid
├── /* РОЗДІЛ 8 */  Cards + hover overlay
├── /* РОЗДІЛ 9 */  @media (max-width: 768px)
└── /* КІНЕЦЬ */    Дизайн-система — коментар-резюме
```

### Дизайн-система (з кінця styles.css)

```css
/* КОЛІРНА ПАЛІТРА (6 основних кольорів):
┌─ Фон:           #f9fafb  (дуже світло-сірий)
├─ Карточки:      #ffffff  (чистий білий)
├─ Первинний:     #3b82f6  (яскравий синій для акцентів)
├─ Темний текст:  #1f2937  (для заголовків)
├─ Світлий текст: #6b7280  (для описів)
└─ Межі:          #e5e7eb  (ледве видні лінії)

ТИПОГРАФІЯ (3 рівні):
┌─ Заголовки: 48px → 36px → 20px → 16px
├─ Основний текст: 16px, line-height: 1.6
└─ Малий текст: 14px для деталей

МАКЕТ:
┌─ max-width: 1200px, центрований
├─ Вертикальний padding: 80px
└─ Gap: 60px (великий) / 30px (малий) / 20px (компактний) */
```

> 🔍 **Порада:** Всі кольори і відступи в `:root {}` у верхній частині файлу. Змінюй там — зміни підхоплять всі елементи одразу.

---

## ⚡ JavaScript

Всі скрипти у `script.js` розбиті на іменовані функції. Жодних зовнішніх бібліотек — тільки чистий браузерний JS.

| Функція | Метод | Опис |
|---------|-------|------|
| 📜 **Sticky header** | `window.addEventListener('scroll')` | Додає клас `.scrolled` після 50px прокрутки |
| 🍔 **Mobile burger** | `classList.toggle('open')` | Відкриває мобільне меню з CSS анімацією |
| ❓ **FAQ акордеон** | `querySelectorAll` + `forEach` | Клік закриває інші, відкриває поточний |
| 🎞️ **Scroll анімації** | `IntersectionObserver` | Додає `.visible` коли елемент з'являється |
| 🔢 **Лічильники** | `requestAnimationFrame` | Числа зростають від 0 до цільового значення |

```javascript
// Приклад: IntersectionObserver для анімацій
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
    }
  });
}, { threshold: 0.1 });

document.querySelectorAll('.animate').forEach(el => observer.observe(el));
```

---

## 🖌️ Кольорова палітра

<!--
  ╔══════════════════════════════════════════╗
  ║           КОЛЬОРОВА ПАЛІТРА              ║
  ╚══════════════════════════════════════════╝
-->
<div align="center">
<table style="border:0;border-collapse:separate;border-spacing:8px">
<tr>
  <td align="center" style="background:#f4eeeb;padding:16px 20px;border-radius:10px;border:1px solid #ccc0b0;min-width:130px">
    <b style="color:#292e1e">Isabelline</b><br/><code>#F4EEEB</code><br/><sub>Основний фон</sub>
  </td>
  <td align="center" style="background:#ede3d6;padding:16px 20px;border-radius:10px;border:1px solid #ccc0b0;min-width:130px">
    <b style="color:#292e1e">Southern Sand</b><br/><code>#EDE3D6</code><br/><sub>Поверхні, карточки</sub>
  </td>
  <td align="center" style="background:#b3a696;padding:16px 20px;border-radius:10px;border:1px solid #9a8d80;min-width:130px">
    <b style="color:#292e1e">Taupe</b><br/><code>#B3A696</code><br/><sub>Хедери коду</sub>
  </td>
  <td align="center" style="background:#7a6b5e;padding:16px 20px;border-radius:10px;min-width:130px">
    <b style="color:#f4eeeb">Vintage Coin</b><br/><code style="color:#f4eeeb">#7A6B5E</code><br/><sub style="color:#ddd">Приглушений текст</sub>
  </td>
  <td align="center" style="background:#292e1e;padding:16px 20px;border-radius:10px;min-width:130px">
    <b style="color:#f4eeeb">Pine Tree</b><br/><code style="color:#b3a696">#292E1E</code><br/><sub style="color:#b3a696">Текст, акценти</sub>
  </td>
</tr>
</table>
</div>

<br/>

---

## 💡 Поради та фішки

### Навігація по файлу
- **`Ctrl+F`** у браузері — шукай будь-яке слово. Гайд побудований так, щоб пошук одразу знаходив потрібний блок
- Кожна секція має `id` — посилання `href="#section"` плавно прокручують до неї
- Великі коментарі `═══` видно навіть при швидкому скролі коду

### Розробка
- **`F12`** → DevTools — бачиш CSS будь-якого елемента і тестуєш зміни в реальному часі
- Кнопка **`copy`** на кожному блоці коду — один клік, і код у буфері обміну
- Стискай вікно до `768px` щоб перевірити мобільну версію

### Кастомізація
```css
/* Змінюй кольори в одному місці — :root у styles.css */
:root {
  --primary-color: #3b82f6;   /* ← один рядок змінює весь акцент */
  --font-size-base: 16px;
  --border-radius: 12px;
}
```

### Корисні розширення VS Code
| Розширення | Що робить |
|-----------|-----------|
| **Live Server** | Авто-перезавантаження при збереженні |
| **Prettier** | Форматування коду |
| **Auto Rename Tag** | Перейменовує парний тег автоматично |
| **Color Highlight** | Показує кольори прямо в коді |
| **CSS Peek** | Переходить до CSS класу по `Ctrl+Click` |

---

## 🚀 Швидкий старт

```bash
# 1. Клонуй репозиторій
git clone https://github.com/webguide-dev/webguide.git

# 2. Перейди в папку
cd webguide

# 3. Відкрий у VS Code
code .

# 4. Запусти Live Server або просто відкрий index.html
```

**Або завантаж ZIP** → розпакуй → відкрий `index.html` у браузері. Готово ✅

---

## 📬 Контакти

Є питання по коду, знайшов помилку або хочеш запропонувати вдосконалення?

<!--
  ╔══════════════════════════════════════════╗
  ║               КОНТАКТИ                   ║
  ╚══════════════════════════════════════════╝
-->
<div align="center">
<table style="border:0;border-collapse:separate;border-spacing:10px">
<tr>
  <td align="center" style="background:#f4eeeb;padding:14px 22px;border-radius:10px;border:1px solid #b3a696">
    <a href="mailto:hello@webguide.dev">✉️ <b>Email</b></a><br/><sub>hello@webguide.dev</sub>
  </td>
  <td align="center" style="background:#f4eeeb;padding:14px 22px;border-radius:10px;border:1px solid #b3a696">
    <a href="https://github.com/webguide-dev">🐙 <b>GitHub</b></a><br/><sub>@webguide-dev</sub>
  </td>
  <td align="center" style="background:#f4eeeb;padding:14px 22px;border-radius:10px;border:1px solid #b3a696">
    <a href="https://t.me/webguide_dev">✈️ <b>Telegram</b></a><br/><sub>@webguide_dev</sub>
  </td>
  <td align="center" style="background:#f4eeeb;padding:14px 22px;border-radius:10px;border:1px solid #b3a696">
    <a href="https://instagram.com/webguide.dev">📸 <b>Instagram</b></a><br/><sub>@webguide.dev</sub>
  </td>
</tr>
</table>
</div>

---

<!--
  ╔══════════════════════════════════════════╗
  ║                 FOOTER                   ║
  ╚══════════════════════════════════════════╝
-->
<div align="center">
<table width="100%" style="border:0;background:#292e1e;border-radius:12px"><tr><td align="center" style="padding:28px 24px">

### 🌿 Якщо гайд був корисний — постав ⭐ на GitHub

*Це допомагає проєкту розвиватись і публікувати нові матеріали*

<br/>

[![⭐ Star on GitHub](https://img.shields.io/badge/⭐_Star_on_GitHub-292e1e?style=for-the-badge&logo=github&logoColor=b3a696&labelColor=3d4a2a)](https://github.com/webguide-dev/webguide)
[![🍴 Fork](https://img.shields.io/badge/🍴_Fork-292e1e?style=for-the-badge&logo=github&logoColor=b3a696&labelColor=3d4a2a)](https://github.com/webguide-dev/webguide/fork)

<br/>

**WebGuide.dev** · HTML · CSS · JavaScript · © 2026

`README · Isabelline Edition · v1.0`

</td></tr></table>
</div>
