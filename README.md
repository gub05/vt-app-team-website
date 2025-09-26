# VT App Club Website 

Hey team! This is our website for the VT App Development Club. We're building it with React and it's going to be awesome!

## What We're Building
- **Homepage** - Welcome people to our club
- **About** - Tell people what we do
- **Projects** - Show off cool stuff we've built
- **Join** - Get new members to join us

## How to Get Started

### 1. Get the code running on your computer
```bash
# Download the project
git clone <repository-url>
cd vt-app-team-website

# Install everything we need
npm install

# Start the website
npm run dev
```
## How to Write Code

### Each person gets their own page/component (this is where you write code based on the two files): 
- **Homepage** → `src/pages/Home.jsx` + `src/pages/Home.css`
- **About** → `src/pages/About.jsx` + `src/pages/About.css`
- **Projects** → `src/pages/Projects.jsx` + `src/pages/Projects.css`
- **Join** → `src/pages/Join.jsx` + `src/pages/Join.css`
- **NavBar** → `src/components/NavBar.jsx` + `src/components/NavBar.css`
- **Footer** → `src/components/Footer.jsx` + `src/components/Footer.css`

## How React Works (The Basics)

**JSX files (.jsx) = Your HTML + JavaScript combined**
- You write HTML like code inside your JavaScript
- This is called "JSX" - it looks like HTML but it's actually JavaScript
- Example: `<h1>Hello World</h1>` inside a function

**CSS files (.css) = Your styling**
- You write normal CSS to make things look pretty
- Colors, fonts, spacing, layouts - everything visual goes here
- Each component has its own CSS file

**How they connect:**
- In your JSX file, you write: `import './Home.css'`
- Then you use `className="my-style"` instead of `class="my-style"`
- React automatically connects your JSX to your CSS!

## How to See Your Code in Action

### 1. Start the development server
```bash
npm run dev
```

### 2. Open your browser
- Go to `http://localhost:5173` (or whatever port it shows)
- You'll see your website live!
- **Hot reload**: When you save changes, the page updates automatically!



### 3. View your code changes instantly
- Edit any `.jsx` or `.css` file
- Save the file
- Refresh your browser
- See your changes immediately!


## Git Workflow (How to Save Your Work)

### 1. Fork the repository
- Go to the main repository on GitHub
- Click the "Fork" button in the top right
- This creates your own copy of the repository

### 2. Clone your fork to your computer
```bash
git clone https://github.com/YOUR_USERNAME/vt-app-team-website.git
cd vt-app-team-website
```

### 3. Make your changes
- Edit your files
- Test that it works
- Make sure it looks good

### 4. Save your work
```bash
git add .
git commit -m "I added the homepage"
git push origin main
```

### 5. Create a Pull Request
- Go to your forked repository on GitHub
- Click "New Pull Request"
- Select your fork → main repository
- Add a description of what you changed
- Ask Liz or Tetra to review your code
- Once approved, they'll merge it!

