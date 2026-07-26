# BeautifAI

**Discover. Learn. Glow.**

BeautifAI is an open-source AI-powered beauty platform that helps users match cosmetics to their skin tone, try virtual makeup and hairstyles, learn professional techniques, and shop for the healthiest and best-priced beauty products locally and online.

---

## ✨ Features

### 🧠 AI Beauty Intelligence
- Skin tone and undertone detection from uploaded selfies
- Personalized cosmetic shade matching (foundation, concealer, blush, lipstick)
- Real-time facial analysis using computer vision
- Adaptive recommendations based on skin type, tone, and preferences

### 💄 Virtual Makeup System
- Real-time virtual makeup try-on
- Layered cosmetics simulation (foundation, contour, highlight, eye makeup, lips)
- Adjustable intensity and style presets
- Before/after comparison views

### 💇 Hairstyle & Hair Color Simulation
- Virtual haircut and hairstyle try-on (length, texture, style)
- Hair color transformation (solid, highlights, balayage, ombré)
- Face shape-based hairstyle recommendations
- Full combined makeup + hairstyle look previews

### 📸 Media Uploads & Downloads
- Upload selfies or reference images for AI processing
- Camera capture support
- Save generated looks locally or in cloud storage
- Download before/after transformations and style results

### 🎓 Learning & Tutorials
- Step-by-step makeup tutorials (beginner to advanced)
- Hairstyling and hair care guides
- AI-generated personalized beauty recommendations
- Video and image-based learning system

### 🛒 Smart Shopping System
- Compare cosmetic prices across online and local retailers
- Highlight best-value and budget-friendly options
- Ingredient safety analysis and warnings
- Filters for:
  - Cruelty-free
  - Vegan
  - Organic
  - Non-toxic / clean beauty
- Wishlist and cart system

### 🧴 Ingredient & Health Awareness
- Detect potentially harmful cosmetic ingredients
- Suggest safer alternatives
- Transparent product breakdowns
- Skin sensitivity-aware filtering system

### 👤 User Profiles & Personalization
- Saved looks, shades, and hairstyles
- Personal beauty history tracking
- AI-driven recommendations over time
- Preference-based customization engine

### ☁️ Storage & Sharing
- Secure image storage system
- Downloadable beauty transformations
- Optional sharing system for community use
- Version history of generated looks

### 🔐 Privacy & Security
- Encrypted media storage (at rest + in transit)
- JWT / OAuth2 authentication
- Optional local-only processing mode
- No unauthorized image exposure

### 🧩 Modular Architecture
- Fully modular plug-in system
- Independent feature modules (makeup, hair, shopping, media)
- API-first backend design
- Expandable AI engine layer

---

## 🧠 Tech Stack

### Frontend
- React Native (mobile app)
- TailwindCSS (UI styling)

### Backend
- Node.js (Express or NestJS)
- REST API (optional GraphQL layer)

### Database
- PostgreSQL (structured data)
- MongoDB (media + flexible data)

### AI / Machine Learning
- PyTorch (model training)
- TensorFlow.js (on-device inference)
- OpenCV (image processing)
- MediaPipe (facial landmark detection)

### Media & Storage
- MinIO (self-hosted object storage)
- S3-compatible storage support

### Video System
- HLS streaming for tutorials
- Optional self-hosted video server

### Authentication
- JWT-based authentication
- OAuth2 support

---

## Specification Branding License (SBL)

### Standard
- Fully AGPL-3.0+ compliant system
- Copyleft enforced for network deployments
- Required attribution:
  - Roxanne Ardary
  - https://www.roxanneardary.com/

### Optional

- **Specification Branding License (SBL)**
  - Attribution-free commercial deployment
  - Pricing based on scale, usage, and deployment scope
  - [https://roxanneardary.com/beautifai/](https://roxanneardary.com/beautifai/)

---

## 🧩 License & Notice Requirements

BeautifAI is released under the **GNU Affero General Public License v3.0 or later (AGPL-3.0+)**.   
By contributing to any Open Arsenal project, you agree that your contributions will also be released under this license.

Please note the following:

- All contributions must comply with the **AGPL-3.0+** terms.  
- Under **Section 7** of the license, all redistributions, forks, and derivative works must preserve attribution to:  
  **Roxanne Ardary** and **[roxanneardary.com](https://www.roxanneardary.com/)**.
- Open Arsenal BeautifAI specifications are free to use with attribution. A Specification Branding License can be negotiated upon request.
- The project's **notice.md** file tracks attribution requirements and contributor acknowledgments.   
  Any update that adds new contributors or modifies attribution should also update `notice.md`. 
- When submitting a pull request, ensure that any new files maintain the attribution headers where applicable.
- Network-deployed versions of this software must also remain fully AGPL-3.0+ compliant, including exposure of source code modifications when applicable under the license.

For full legal details, please refer to the AGPL-3.0+ license and the project's `notice.md` file.
