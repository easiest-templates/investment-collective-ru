![Preview](https://cdn.poehali.dev/templates/investment-collective-ru/preview.jpg)

# ЗолотойКапитал - Инвестиционный лендинг

Премиальный лендинг для инвестиционного клуба в стиле арт-деко с темной темой.

## Теги

```json
["landing", "dark", "fintech"]
```

## Особенности

- Темная тема с золотыми акцентами
- Арт-деко декоративные элементы (sunburst, dividers)
- Адаптивный дизайн
- Форма захвата лидов
- Анимации при скролле и наведении
- Шрифты: Playfair Display (serif) + Inter (sans-serif)

## Технологии

- React 18
- TypeScript
- Vite
- Tailwind CSS
- Radix UI

## Установка

```bash
npm install
```

## Разработка

```bash
npm run dev
```

Сервер запустится на http://localhost:5173

## Сборка

```bash
npm run build
```

## Структура

```
src/
├── components/
│   ├── ui/          # Базовые UI компоненты
│   ├── ArtDecoSunburst.tsx
│   ├── ArtDecoDivider.tsx
│   ├── ServiceCard.tsx
│   └── CTAForm.tsx
├── lib/
│   └── utils.ts
├── App.tsx
├── main.tsx
└── index.css
```

## Секции лендинга

1. **Hero** - Главный экран с названием и описанием
2. **Philosophy** - Философия компании
3. **Services** - Три направления (искусство, коллекции, автомобили)
4. **Testimonial** - Отзыв клиента
5. **CTA** - Форма запроса приглашения
6. **Footer** - Подвал сайта
