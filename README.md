# Cross language Framework

Advanced Internationalization Framework

Built for a global audience with comprehensive internationalization and localization support.

## 🗺️ Supported Languages

- English (en)
- Spanish (es) 
- French (fr)
- German (de)
- Japanese (ja)
- Chinese (zh)

## ✨ International Features

- **Multi-language Support**: Dynamic language switching with RTL/LTR layout support
- **Locale-aware Formatting**: Automatic date, time, number and currency formatting
- **Unicode Compliance**: Full UTF-8 support for all writing systems

## 🚀 Quick Start

```bash
git clone https://github.com/user/ARVO2025_Melinna.git
cd ARVO2025_Melinna
npm install
```

## 🌐 Usage with Localization

```javascript
import { i18n } from 'arvo-melinna';

// Initialize with user locale
i18n.init({ 
  locale: 'ja',
  fallback: 'en'
});

// Use translated content
const greeting = i18n.t('welcome.message');
```

## 🤝 Contributing Translations

We welcome translation contributions! See our [i18n guide](docs/i18n.md).

## 📄 License

MIT
