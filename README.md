# 🌐 VT App Club Website

Hey team! This is our website for the VT App Development Club. We're building it with React.

---

## 🚀 What We're Building
- **Homepage** – Welcomes visitors to our club  
- **About** – Explains who we are and what we do  
- **Projects** – Showcases our builds and achievements  
- **Join** – Invites new members to sign up  

---

## Tech Stack
- **Next.js** – Framework built on React for routing, server-side rendering, and optimization  
- **React** – Component-based JavaScript library for UI  
- **Tailwind CSS** *(optional if enabled)* – Utility-first CSS framework for styling  
- **Node.js / npm** – For running and managing dependencies  

---

## How Next.js Works

Next.js uses the **`app/` directory** to handle routes automatically.  
Each folder or file in `app/` becomes a new page on the website.

| File/Folder | URL Route |
|--------------|-----------|
| `app/page.tsx` | `/` (Homepage) |
| `app/about/page.tsx` | `/about` |
| `app/projects/page.tsx` | `/projects` |
| `app/join/page.tsx` | `/join` |

### Component Structure
- Each section (like About or Projects) is a **React component**.  
- You can also create reusable components inside a `components/` folder (e.g., Navbar, Footer).  

### Styling
- Global styles live in `app/globals.css`.  
- You can also use **CSS modules** (e.g., `NavBar.module.css`) or **Tailwind classes** directly in your components.

---

## 💻 How to Get Started

### 1. Clone the repository
```bash
git clone <repository-url>
cd vt-app-team-website
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm run dev
```

### 4. Open your browser
Go to **[http://localhost:3000](http://localhost:3000)**  
(or whatever link shows in your terminal).

---

## ✏️ How to Contribute

Each person can work on a different page/component:

| Page | File Path |
|------|------------|
| **Homepage** | `app/page.tsx` |
| **About** | `app/about/page.tsx` |
| **Projects** | `app/projects/page.tsx` |
| **Join** | `app/join/page.tsx` |
| **NavBar** | `components/NavBar.tsx` |
| **Footer** | `components/Footer.tsx` |

---

## 🔄 Git Workflow (How to Save and Share Your Work)

### 1. Fork the repository
- Go to the main GitHub repo  
- Click **Fork** in the top-right corner  

### 2. Clone your fork
```bash
git clone https://github.com/YOUR_USERNAME/vt-app-team-website.git
cd vt-app-team-website
```

### 3. Make your changes
- Edit files  
- Test that it works  
- Make sure it looks good  

### 4. Save your work
```bash
git add .
git commit -m "Added About page"
git push origin main
```

### 5. Create a Pull Request
- Go to your GitHub fork  
- Click **New Pull Request**  
- Write what you changed  
- Ask a teammate to review before merging  

---

### Tips for New Members
- Next.js automatically updates your site when you save a file (**hot reload**)  
- You don’t need React Router — Next.js handles routing automatically  
- Use components to keep your code organized  
- Run `npm run dev` every time before testing your changes  
