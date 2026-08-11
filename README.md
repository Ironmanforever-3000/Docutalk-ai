# Docutalk-ai
DocuTalk AI is an enterprise-grade document intelligence and interactive chat platform. Seamlessly upload PDF and DOCX files to extract structured insights and parse raw text. Interact with custom data sources using automated vector analysis and smart real-time AI.
## 🛠️ Tech Stack

### **Frontend**
* **Framework:** [React 18](https://react.dev/) + [TypeScript](https://www.typescriptlang.org/)
* **Build Tool:** [Vite](https://vitejs.dev/)
* **UI & Component Primitives:** [Radix UI Slot](https://www.radix-ui.com/), [Lucide React Icons](https://lucide.dev/)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/), `@tailwindcss/typography`, `tailwindcss-animate`
* **Animations:** [Motion](https://motion.dev/) (Framer Motion) & [GSAP](https://gsap.com/)

### **Backend & Database**
* **BaaS / Database:** [Supabase](https://supabase.com/) (`@supabase/supabase-js`)
* **Database Driver:** [PostgreSQL](https://www.postgresql.org/) (`pg`)

### **Document Processing & Machine Learning**
* **PDF Parsing:** [PDF.js](https://mozilla.github.io/pdf.js/) (`pdfjs-dist`)
* **DOCX Parsing:** [Mammoth.js](https://github.com/mwilliamson/node-mammoth)
* **Data & Vector Analytics:** [ml-pca](https://github.com/mljs/pca) (Principal Component Analysis)

### **Development & Quality**
* **Linting & Code Quality:** ESLint 9 + TypeScript-ESLint
* **Build Tooling:** PostCSS & Autoprefixer
