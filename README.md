# Nice Gadgets Store

A responsive React + TypeScript catalog for phones, tablets, and accessories.

This project started as the Mate Academy Phone Catalog task, but I used it as a chance to build a more complete product-like experience. Besides the base catalog functionality, I added localization, theme switching, animated icons, persistent cart/favorites state, loading states, and a cleaner UI flow.

[Demo](https://Bukavyna.github.io/react-phone-catalog/)

## Features

- Product catalog with separate pages for phones, tablets, and accessories
- Product details page with image gallery, color picker, and capacity picker
- Shopping cart with quantity controls and localStorage persistence
- Favorites page with saved products
- Product sliders for new models, hot prices, and suggested products
- Sorting and pagination synced with URL search params
- Responsive layout for mobile, tablet, and desktop
- Breadcrumbs, back navigation, sticky header, and footer
- Loading states, skeletons, and basic error handling
- English and Ukrainian localization
- Theme switching with several visual themes
- Animated UI icons using Lordicon

## Why I Built It This Way

I wanted this project to feel less like a static task solution and more like a small real store interface. The main focus was on reusable UI, predictable state management, and details that make the app nicer to use: saved cart items, saved favorites, remembered language/theme, smooth navigation, and clear product pages.

It also gave me a good place to practice TypeScript with React Router, Context, custom hooks, localStorage, SCSS Modules, and i18next.

## Tech Stack

- React 18
- TypeScript
- React Router
- SCSS Modules
- Vite
- i18next
- react-i18next
- Lordicon
- React Hot Toast
- Cypress
- ESLint
- Prettier
- Stylelint

## Project Structure

```txt
src/
  api/                 API client and product loaders
  components/          Shared UI components
  context/             Cart, favorites, and theme providers
  hooks/               Reusable app hooks
  i18n/                Language configuration and translations
  Layout/              Header, footer, navigation, layout shell
  modules/             Page-level modules
  styles/              Global styles, variables, mixins, themes
  types/               Shared TypeScript types
  utils/               Sorting, filtering, errors, helpers
```

## Getting Started

Clone the repository:

```bash
git clone https://github.com/Bukavyna/react-phone-catalog.git
cd react_phone-catalog
```

Install dependencies:

```bash
npm install
```

Run the project locally:

```bash
npm start
```

Build for production:

```bash
npm run build
```

Run linting:

```bash
npm run lint
```

Run tests:

```bash
npm test
```

## Available Pages

- `/` - Home page
- `/phones` - Phones catalog
- `/tablets` - Tablets catalog
- `/accessories` - Accessories catalog
- `/:category/:productId` - Product details page
- `/cart` - Shopping cart
- `/favorites` - Favorite products
- `*` - Not found page

## Internationalization

Translations are stored in:

```txt
src/i18n/locales/en/common.json
src/i18n/locales/uk/common.json
```

The app currently supports English and Ukrainian. The selected language is remembered between visits.

## Notes

This project is based on the Mate Academy React + TypeScript Phone Catalog task and extends it with additional UI, state management, localization, theme, and animation features.
