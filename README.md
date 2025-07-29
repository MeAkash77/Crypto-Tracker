
# CryptoBoo 👻 
A Cryptocurrency price tracking app made using Next.js

CryptoBoo 👻 is a responsive and feature-rich cryptocurrency price tracking web application built with Next.js, TypeScript, Tailwind CSS, and Chart.js. It fetches real-time data from the Coinranking API to display up-to-date prices, historical trends, and detailed statistics for various cryptocurrencies. The application supports price tracking in both fiat and crypto currencies, integrates a live search, pagination for scalability, and renders intuitive price charts for visual analysis. Designed with performance and usability in mind, CryptoBoo offers a clean, modern UI and a smooth user experience across all devices.

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwindcss&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=flat-square&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Amp](https://img.shields.io/badge/Amp-005AF0?style=for-the-badge&logo=amp&logoColor=white)

👉 [**Live Demo**](https://crypto-tracker-two-theta.vercel.app/)

![App Screenshot](https://cryptoboo.vercel.app/screenshots/homepage.jpg)

## Contact Page

<img width="959" height="443" alt="Image" src="https://github.com/user-attachments/assets/ceacd188-f550-462e-a473-6da38c41b73a" />


## Run Locally

**1. Clone the project**

```bash
  git clone https://github.com/MeAkash77/Crypto-Tracker.git
```

**2. Go to the project directory**

```bash
  cd project-directory
```

**3. Install dependencies**

```bash
  npm install
```

**4. Get an API Key** for Coinranking API from [**here**](https://rapidapi.com/Coinranking/api/coinranking1/)

You can find the Docs for the API [here](https://developers.coinranking.com/api/documentation)  

**5. Create .env.local file** in your project's root directory and create a variable
```js
NEXT_PUBLIC_RAPID_API={PASTE_YOUR_API_KEY_HERE}
```

**6. Start the server**

```bash
  npm run dev
```
Open http://localhost:3000 with your browser to see the result.


## Features

- Price tracking
- International Fiat Currency support (Prices can also be viewed in other cryptocurrencies)
- Historical Price data
- Search Cryptocurrencies
- Pagination
- Chart.js implementation for charts


## More Screenshots
**Coin Details**

![App Screenshot](https://cryptoboo.vercel.app/screenshots/coin_details_page.jpg)

**Choose currency**
![App Screenshot](https://cryptoboo.vercel.app/screenshots/choose_currency_dialog.jpg)

**Price Chart**
![App Screenshot](https://cryptoboo.vercel.app/screenshots/price_chart_2.jpg)


## Tech Stack

**Client:** React, Next.js, Typescript,  TailwindCSS, Chart.js

**API:** Coinranking API

