# MyPortfolio — лендинг frontend-разработчика

Статический одностраничный сайт-портфолио [Максима Трофимова](https://max876907389247.github.io/MyPortfolio/). Сделан под отклик на вакансию frontend-разработчика: показывает не просто список навыков, а **почему опыт и проекты релевантны роли**.

**Демо:** https://max876907389247.github.io/MyPortfolio/

## О проекте

Лендинг собран на чистом HTML, CSS и JavaScript без фреймворков и сборщиков. Структура заточена под оценку кандидата рекрутером или тимлидом:

- **Hero** — позиционирование, краткий профиль и фото
- **Соответствие роли** — блок «требование → мой опыт → результат»
- **Проекты** — кейсы с задачей, ролью, стеком и связью с frontend
- **Опыт** — хронология работы и образования, блок «Обо мне» со слайдером
- **Контакты** — телефон, email, Telegram, VK

## Стек

| Категория | Технологии |
|-----------|------------|
| Разметка и стили | HTML5, CSS3 (Grid, Flexbox, custom properties) |
| Интерактив | Vanilla JavaScript (Intersection Observer, слайдер) |
| Шрифты | DM Sans, JetBrains Mono (Google Fonts) |
| Деплой | GitHub Pages |

## Структура репозитория

```
├── index.html      # разметка и контент
├── styles.css      # стили, адаптив, тёмная тема
├── main.js         # меню, подсветка секций, слайдеры
└── images/         # фото и скриншоты проектов
```

## Локальный просмотр

```bash
git clone https://github.com/max876907389247/MyPortfolio.git
cd MyPortfolio
python3 -m http.server 8080
```

Откройте http://localhost:8080 или просто `index.html` в браузере.

## Деплой

Сайт публикуется через **GitHub Pages**:

1. Settings → Pages
2. Source: **Deploy from branch**
3. Branch: `main`, folder: `/ (root)`

После push изменения появляются на сайте через 1–3 минуты.

## Автор

**Максим Трофимов** — frontend-разработчик, Екатеринбург

- Email: maxxx999tte@gmail.com
- Telegram: [@Trafnya](https://t.me/Trafnya)
- VK: [vk.com/id414790909](https://vk.com/id414790909)
