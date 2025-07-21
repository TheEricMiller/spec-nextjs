# How to Dev Next.js App
====================

## Getting Started

- `nvm install --lts` to install the latest LTS version of Node.js.
- `nvm use --lts` to switch to the required Node.js version.
<!-- or `nvm install node` then `nvm alias default node` -->
<!-- - `npm install` to install all necessary packages. -->


- `npx create-next-app@latest` to create a new Next.js app.

  - YES to TypeScript
  - YES to ESLint
  - YES to Tailwind CSS
  - YES to `src/` directory
  - YES to App Router
  - YES to Turbopack for `next dev`
  - NO to customize the import alias (`@/*` by default)

- `cd <app-name>` to navigate to the app directory.

- `mv README.md README--ORIGINAL.md` to rename readme file.


- `curl -L https://gist.githubusercontent.com/TheEricMiller/891d30b5a2a16ef4999834c2aa8fe2c5/raw/467fb45ebccc7ed17009508840608e537603b451/spec-README.md > README.md`



- `touch .env.template` Create env template file and add any required environment variables.
- Update GitIgnore `echo '\n\n!.env.template' >> .gitignore` to include the template environment file.
- `cp .env.template .env.local` Copy env file and update any required variables.

- `cp src/app/page.tsx src/app/page--ORIGINAL.tsx` to create a backup of the original page file.

  - Edit as desired.

- `npm run dev` to start the Next.js development server.

- `git add -A && git commit -m "First Commit"` to commit changes.

- `git branch dev` to create a new branch  (or `git switch -c dev` to auto switch).
- `git switch dev` to switch to branch.


## Install Firebase

- `npm install firebase` to install the Firebase package.
- update `.env.local` with Firebase configuration.


## Install ShadCN UI Kit

- `npx shadcn@latest add button` to add a button component.

## Next.js Structure Guide

- https://mydevpa.ge/blog/how-to-setup-firebase-realtime-database-with-nextjs-15

* https://codelynx.dev/posts/2024-09-03-how-organise-files-in-nextjs
* https://www.inngest.com/
* https://www.prisma.io/
* https://ui.shadcn.com/
* https://vercel.com/products/previews
* https://v0.dev/
* https://n8n.io
* https://neon.tech
* https://www.langchain.com/

### Notes

`nvm -v ; npm -v ; node -v ; npm ls react`

## Sudo Code for App

1. Add a new page to the app.
2. Add a new component to the app.
3. Add a new layout to the app.
4. Add a new utility to the app.
5. Add a new hook to the app.
6. Add a new context to the app.
7. Add a new service to the app.
8. Add a new API route to the app.
9. Add a new environment variable to the app.

10. Add a page for Create Item
11. Add a page to list Items
12. Add a page to view Item
13. Add a page to edit Item
14. Add a page to delete Item

////////

'use client';

import { useState, useEffect } from 'react';
import { collection, doc, getDocs, setDoc } from 'firebase/firestore';
import { db_firestore } from '@/lib/firebase';


``` javascript
              {/* <Button type="submit" onClick={() => handleUpdate_Item(item.id, item.name)}><Save />Update</Button> */}
              {/* <Input type="text" name={"inputItemName-" + item.id} defaultValue={item.name} required className="field-sizing-content" /> */}

              {/* Great for Realtime */}
              {/* <Input type="text" name={"inputItemName-" + item.id} defaultValue={item.name} onChange={(e) => handleUpdate_Item(item.id, e.target.value)} required className="field-sizing-content" /> */}
```

* http://localhost:3000/
* http://localhost:6006/


* https://vercel.com/templates/next.js/ragbot-starter
* https://vercel.com/templates/next.js/platforms-starter-kit
* https://vercel.com/templates/next.js/nextjs-enterprise-boilerplate
* https://www.datastax.com/products/datastax-astra
* https://storybook.js.org/docs/get-started/frameworks/nextjs
* https://next-auth.js.org/getting-started/example

* https://console.firebase.google.com/project/edev-333/firestore/databases/-default-/data/~2Fitems~2F9fbF7WtH1qn9I4awbxh9?fb_gclid=Cj0KCQiAz6q-BhCfARIsAOezPxluPF1Q-QZmyjTY0wy-jIZbyzC3KmZ_Izat0_FWIuqqDlzYaKYG5EUaApQxEALw_wcB


* https://github.com/TheEricMiller/e-next-app

* https://vercel.com/nexes

* https://github.com/langflow-ai/langflow

* https://vercel.com/templates/next.js/ragbot-starter


* https://vercel.com/nexes
* https://github.com/TheEricMiller/e-next-app

* https://console.firebase.google.com/project/edev-333/firestore/databases/
* https://firebase.google.com/docs/firestore/library-integrations

* https://next-auth.js.org/
* https://blocks.tremor.so/
* https://vercel.com/storage/blob
* https://novel.sh/

* https://zod.dev/

* https://tailwindcss.com/docs/
* https://tailwindcss.com/docs/justify-content
* https://ui.shadcn.com/docs/components/accordion
* https://lucide.dev/

* https://vercel.com/templates/next.js/admin-dashboard-tailwind-postgres-react-nextjs
* https://vercel.com/templates/next.js/nextjs-enterprise-boilerplate
* https://vercel.com/templates/next.js/app-directory






# =================================================

# =================================================
