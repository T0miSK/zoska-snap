Tomáš Šuba 4.C 2. skupina


Instalacia nextjs:

npx create-next-app@latest

What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
What import alias would you like configured? @/*

npm run dev – spusti server v administrativnom rezime

vyhradene subory:
page.tsx
layout.tsx
not-found.tsx

import  Typography  from "@mui/material/Typography";

export default function Home() {
  return (
    <Typography>Domovska stranka</Typography>
  );
}


git  branch -m main
git config --global user.name "zoska-snap"
git config --global user.email "tomas.suba77@gmail.com"

git remote add origin https://github.com/T0miSK/zoska-snap.git

git add .