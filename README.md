# 📱 TechMobile – E-commerce Frontend

TechMobile is a responsive mobile e-commerce website that displays smartphones and electronics products using an external API. It includes product listing, categories, search, sorting, shopping cart (with localStorage), product modals, and a fully responsive UI.

## 🚀 Live Demo
*(Add your GitHub Pages or Netlify link here)*

## ✨ Features
- Product API integration
- Dynamic product cards
- Search system (real-time)
- Product sorting (price low-high / high-low)
- Category filtering
- Shopping cart with localStorage persistence
- Product details modal
- Responsive mobile-friendly UI

## 🗂 Main Files
| File | Purpose |
|------|---------|
| `index.html` | Website structure (navbar, hero, products, cart modal, footer) |
| `script.js` | API calls, search, sorting, cart logic, category filters, modal |
| `style.css` | Custom styles, responsive design, animations |

## 🔧 How It Works
1. Page loads → products fetched from external API
2. Products stored in memory → dynamic product cards displayed
3. User interacts: search, filter, sort, view modals, add/remove from cart (saved in localStorage)

## 💪 Strong Points
- Modern UI design
- Fully responsive layout
- Dynamic API data
- Working shopping cart
- Clean, organized functions

## ⚠️ Current Weaknesses
- No backend integration
- Uses dummy API only
- No authentication system
- No real checkout / payment gateway
- No database support

## 🗺 Recommended Roadmap
| Phase | Task |
|-------|------|
| 1 | Frontend optimization |
| 2 | Create Node.js backend |
| 3 | Add real database (MongoDB / PostgreSQL) |
| 4 | Add authentication (JWT) |
| 5 | Integrate payment gateway (Stripe / Razorpay) |
| 6 | Build admin dashboard |

## 🛠 Tech Stack (Current vs Future)
| Layer | Current | Full-stack vision |
|-------|---------|-------------------|
| Frontend | HTML, CSS, JS | React / Next.js |
| Backend | – | Node.js + Express |
| Database | – | MongoDB / PostgreSQL |
| Payments | – | Stripe / Razorpay |
| Deployment | – | Vercel + Render |

## 🧪 Run Locally
```bash
git clone https://github.com/yourusername/techmobile.git
cd techmobile
# Open index.html with Live Server or directly in browser
