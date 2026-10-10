Here is the comprehensive `README.md` file for your **Cozy Corner** cafe project:

# Cozy Corner — Hot & Cold Coffee & Softea Chocklet Cafe

Cozy Corner is a modern, feature-rich web application for a specialty cafe serving handcrafted hot coffee, artisanal cold brews, and signature Softea Chocklet drinks, complete with online ordering and instant loyalty rewards.

---

## ☕ Features

* **Online Ordering:** Browse and order handcrafted hot coffee, cold coffee frappes, signature soft chocolate drinks, and desserts.


* **Cozy Beans Loyalty Program:** Earn loyalty rewards and discounts with every order placed.


* **AI Integration:** Built-in server-side Gemini AI capabilities powered by the Google Gen AI SDK.


* **Responsive Design:** Styled with Tailwind CSS and Framer Motion animations for a smooth, cozy user experience.



---

## 🛠️ Tech Stack

* **Framework:** React 19 with TypeScript


* **Build Tool:** Vite


* **Styling:** Tailwind CSS v4


* **Icons & Animation:** `lucide-react`, `motion`

* **Backend / Server:** Express with TypeScript (`tsx`)


* **AI SDK:** `@google/genai`


---

## ⚙️ Environment Variables

The application requires the following environment variables (automatically injected in runtime environments like AI Studio or configured via `.env`):

* `GEMINI_API_KEY`: Required for Gemini AI API calls.


* `APP_URL`: The URL where this applet is hosted, used for self-referential links, OAuth callbacks, and API endpoints.



---

## 🚀 Getting Started

### 1. Installation

Install the project dependencies using npm:

```bash
npm install

```

### 2. Development

Start the development server with Hot Module Replacement (HMR):

```bash
npm run dev

```

*(The app will be accessible at `http://localhost:3000`)*

### 3. Build & Preview

To build the project for production and preview the build output:

```bash
npm run build
npm run preview

```

### 4. Code Quality & Maintenance

* **Type Checking & Linting:** Run TypeScript compilation checks without emitting files:


```bash
npm run lint

```


* **Clean Build Artifacts:** Remove the `dist` directory and built server files:


```bash
npm run clean

```
