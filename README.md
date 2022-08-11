# Deploy React to Vercel with Vite

Use Vite to create React app then deploy via Vercel.

## Create React App

Generate boilerplate application using the React Vite template.

```bash
yarn create vite my-react-app --template react
cd my-react-app
yarn
yarn dev
```

Open [localhost:5173](http://localhost:5173/) in browser.

```jsx
// src/App.jsx

import reactLogo from './assets/react.svg'
import './App.css'

function App() {
  return (
    <div className="App">
      <div>
        <a href="https://vitejs.dev" target="_blank">
          <img src="/vite.svg" className="logo" alt="Vite logo" />
        </a>
        <a href="https://reactjs.org" target="_blank">
          <img src={reactLogo} className="logo react" alt="React logo" />
        </a>
      </div>
      <h1>Deploy React to Vercel with Vite</h1>
      <p className="read-the-docs">
        Use Vite to create React app then deploy via Vercel.
      </p>
    </div>
  )
}

export default App
```

## Deploy to Vercel

[Go to link for Vercel CLI download instructions](https://vercel.com/docs/cli)

```bash
vercel
```

Open [my-react-app-kohl.vercel.app](https://my-react-app-kohl.vercel.app).

## Create GitHub Repository

Open link to [repo.new](https://repo.new)

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/teachjenntech/my-react-app.git
git push -u origin main
```

## Jenn Notes

- `git add README.md` only uploads that file whereas `git add .` uploads all files

- `git remote add origin https://github.com/teachjenntech/my-react-app.git` is based on each individual repo

- Create GitHub Repository, use folder name as project name 

- Make sure to commit changes to GitHub 

```bash
git add .
git commit -m "first commit"
git push
```