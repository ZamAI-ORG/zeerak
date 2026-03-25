# Zeerak AI — App Screenshots

High-quality screenshots of the Zeerak AI web application, captured at production-quality resolution for showcase and mockup purposes.

## Desktop Screenshots (1440×900)

| Screenshot | Page | Description |
|---|---|---|
| ![Login](01-login-english.png) | **Login** | Authentication screen — English |
| ![Register](02-register.png) | **Register** | New user registration |
| ![Forgot Password](03-forgot-password.png) | **Forgot Password** | Password recovery |
| ![Home Dashboard](04-home-dashboard.png) | **Home Dashboard** | Main dashboard with market prices, stats, and quick actions |
| ![AI Chat](05-chat.png) | **AI Chat** | Zeerak Chat — multilingual AI conversation (Pashto/Dari/English) |
| ![Vision AI](06-vision.png) | **Vision AI** | Camera-based OCR, translation, and object recognition |
| ![CodeKhona](07-code-khona.png) | **CodeKhona** | Interactive code playground (Python, JavaScript, HTML/CSS) |
| ![Agriculture](08-agriculture.png) | **Dehqan AI** | Agriculture assistant — crop disease, market prices, weather |
| ![Health](09-health.png) | **Tabib AI** | Health assistant — symptom checker, appointments, specialists |
| ![Education](10-education.png) | **AI Tutor** | Afghan curriculum tutoring (Classes 6–12) |
| ![Skills](11-skills.png) | **Hunar Suite** | Vocational skills training and AI resume builder |
| ![Settings](12-settings.png) | **Settings** | User preferences, language, and app settings |
| ![Profile](13-profile.png) | **Profile** | User profile and account management |
| ![Pricing](14-pricing.png) | **Pricing** | Subscription plans and pricing |

## Wide Desktop Screenshots (1920×1080)

| Screenshot | Page |
|---|---|
| ![Home Wide](04b-home-wide.png) | **Home Dashboard** — Full HD |

## Mobile Screenshots (390×844 — iPhone 14 Pro)

| Screenshot | Page |
|---|---|
| ![Login Mobile](15-login-mobile.png) | **Login** |
| ![Home Mobile](16-home-mobile.png) | **Home Dashboard** |
| ![Chat Mobile](17-chat-mobile.png) | **AI Chat** |
| ![Agriculture Mobile](18-agriculture-mobile.png) | **Dehqan AI** |
| ![Health Mobile](19-health-mobile.png) | **Tabib AI** |

## Technical Details

- **Captured with**: Playwright (Chromium headless shell)
- **Demo mode**: VITE_DEMO_MODE=true — no backend required
- **API mocking**: All `/api/**` endpoints mocked with realistic demo data
- **Demo user**: Ahmad Karimi (Premium account, authenticated)
- **Viewports**:
  - Desktop: 1440×900
  - Wide: 1920×1080
  - Mobile: 390×844

## Regenerating Screenshots

```bash
# Build demo version
VITE_DEMO_MODE=true npx vite build --outDir /tmp/dist-demo

# Run screenshot script
node /tmp/playwright-final.js
```
