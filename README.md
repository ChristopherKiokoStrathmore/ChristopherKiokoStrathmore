# Hi, I'm Chris Nguu 👋

**Christopher Nguu Kioko** · Data Scientist · Nairobi, Kenya

I'm a data scientist in Nairobi doing an MSc in Data Science at Strathmore University. I care most about the part of machine learning that happens after the notebook: leak-free pipelines, one shared preprocessing path for training and serving, honest metrics, and models that send low-confidence predictions to a human. My projects sit on East African problems (mobile-money fraud, telecom customer care, county-level health capacity), and I ship them as working APIs and apps rather than leaving them as slides.

- 📊 **Data Scientist**: ML models from baseline to deployed API (TensorFlow/Keras, scikit-learn, FastAPI, Docker)
- 🎓 **MSc Data Science, Strathmore**: Applied ML coursework (DSA 8401), built as reproducible, leak-free labs
- 🔭 **Currently building**: the *Nairobi Fintech Fraud Flag API* for the UNECA African AI Innovators showcase
- 🛠️ **Builder**: full-stack products for Kenyan clients and teams (Next.js, React, Supabase, Django)
- 🌍 **Based in**: Nairobi, Kenya

## 🔬 Research & Interests

- **Trustworthy ML in production**: training/serving skew, leakage, and routing uncertain predictions to human review
- **Fintech & financial inclusion**: mobile-money fraud signals that don't penalise thin-file wallets
- **NLP for customer care**: multi-head classification of telecom complaints (issue, sentiment, urgency)
- **Public-health analytics**: surge hospital capacity across Kenya's 47 counties, with the model's limits stated up front

## 🌐 Portfolio & Links

- 💼 **Data science portfolio:** [chris-nguu.vercel.app](https://chris-nguu.vercel.app)
- 💻 **GitHub:** [ChristopherKiokoStrathmore](https://github.com/ChristopherKiokoStrathmore) (projects) · [ChristopherKioko](https://github.com/ChristopherKioko)
- 🎵 Away from code I make gospel music as **Chris Clave**: [chris-clave.vercel.app](https://chris-clave.vercel.app)

## 🚀 Featured Projects

### Data Science & ML

| Project | What it does | Stack | Links |
|---|---|---|---|
| **MNIST Live: Handwritten Digit Recognition API** | Dense neural net built from scratch and benchmarked against a CNN, served as a live REST API with a draw-a-digit front end. Training and serving share one preprocessing module, and predictions below 0.60 confidence are routed to human review. | TensorFlow/Keras, FastAPI, Docker, Render | [Repo](https://github.com/ChristopherKiokoStrathmore/handwritten-digit-recognition-api) · [Live](https://mnist-live.onrender.com) |
| **Multi-head Customer-Care Classifier** | Reads telecom customer complaints on three axes (Issue, Sentiment, Urgency). The demo UI handles single messages and batch CSV, and it has an eval harness that runs against the live model API. | Next.js, TypeScript, FastAPI on Modal | [Repo](https://github.com/ChristopherKiokoStrathmore/MULTI-HEAD-) · [Live](https://multi-head.vercel.app) |
| **Nairobi Fintech Fraud Flag API** (DSA 8401 lab) | Scores synthetic mobile-money wallets and returns a fraud probability, a risk band, and up to three reasons. Alternative-credit signals can lower the score, so a new wallet isn't flagged just for being new. The repo also keeps the Week 1 leak-free regression baseline on real-estate valuation. | Python, scikit-learn, FastAPI, Docker | [Repo](https://github.com/ChristopherKiokoStrathmore/DSA-8401---CREDIT-LAB) |
| **How prepared is Kenya for a disease outbreak?** | Interactive map that ranks Kenya's 47 counties by the attack rate at which surge inpatient beds run out, using the Master Health Facility List (n=8,932) and the 2019 Census. It comes with a three-slide COVID-19 data-story deck. | Python, D3, GSAP, Three.js | [Repo](https://github.com/ChristopherKiokoStrathmore/SLIDES) · [Live](https://slides-pink-ten.vercel.app) |

### Products & Client Builds

| Project | What it does | Stack | Links |
|---|---|---|---|
| **Sheer Logic HR System** | HR lifecycle monorepo with an admin dashboard and an employee self-service PWA. It has English/Swahili i18n, AI-assisted CV screening, and handles personal data in line with Kenya's Data Protection Act (KDPA). | Next.js, Turborepo, Supabase, TypeScript | [Repo](https://github.com/ChristopherKiokoStrathmore/HR-SYSTEM) · [Live](https://hr-system-dashboard-sheerlogic.vercel.app) |
| **Airtel Champions PWA** | PWA for Home Broadband (HBB) leads, installer assignments, performance tracking, and team collaboration, aimed at sales executives and zone managers. | React, Vite, Supabase, Capacitor | [Repo](https://github.com/ChristopherKiokoStrathmore/Airtel-Champions-PWA-APRIL-) · [Live](https://airtel-champions-pwa-april.vercel.app) |
| **TestOps** | QA testing platform for mobile-payment flows (M-Pesa, USSD, STK Push), with role-based dashboards, daily test logging, pass-rate analytics, and PDF reports. | React, TypeScript, Supabase, Recharts | [Repo](https://github.com/ChristopherKiokoStrathmore/testops) |
| **Createch Architects** | Production site for a Nairobi architecture and interiors practice, with a PIN-protected admin for editing site content and a separate Django media/content API. | Next.js, Tailwind, Django REST Framework, Vercel, Railway | [Website](https://github.com/ChristopherKiokoStrathmore/Createch-Arch-Website) · [Backend](https://github.com/ChristopherKiokoStrathmore/Createch-Arch-Backend) · [Earlier build](https://github.com/ChristopherKiokoStrathmore/Createch) · [Site](https://createch.co.ke) |
| **Createch Hobbies** | E-commerce store for a Kenyan seller of DIY educational kits for children. It uses headless WooCommerce, takes M-Pesa, Airtel Money, and card payments, and has an order dashboard. | Next.js, Django REST Framework, WooCommerce | [Storefront](https://github.com/ChristopherKiokoStrathmore/Createch-Hobbies) · [Backend](https://github.com/ChristopherKiokoStrathmore/createch-backend) · [Site](https://createch-hobbies.co.ke) |

---

<sub>Built in Nairobi 🇰🇪 · All project repos live at [github.com/ChristopherKiokoStrathmore](https://github.com/ChristopherKiokoStrathmore?tab=repositories)</sub>
