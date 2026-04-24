# AP-Gurukul Shared UI

This is the central React component library and design system for AP-Gurukul. 

## 🎨 Unified Experience
AP-Gurukul consists of a Web App, a Telegram App, and an Admin Portal. To ensure a seamless, premium, and unified user experience across all these platforms, we store all of our core React components (Buttons, Cards, Modals, Typography) in this repository.

## 🔄 Universal Data Sync
Remember that AP-Gurukul uses a **unified Firebase database**. A user's profile picture or name pulled via Gmail authentication is identical everywhere. The components in this library are designed to accept those unified data structures and display them consistently, no matter what app the user is currently using.

## 🚀 Development

We use **Vite** to develop and test components in isolation.

```bash
npm install
npm run dev
```

## 📦 Publishing
This library is published to NPM. To use these components in the Web App or Admin Portal:
```bash
npm install @ap-gurukul/shared-ui
```

## 🤝 Contributing
Please see the `CONTRIBUTING.md` and `SECURITY.md` files for guidelines.
