# POLYMAZE website

Website of **POLYMAZE**, a robotics competition: teams design and build a robot to conquer a complex maze filled with tricky paths and surprise turns.

Live at **https://polymaze.vic-enp.com**.

## What is on the site

- The competition page, with 3D visuals (Three.js)
- About us, how to participate, FAQ and testimonies
- Team registration, stored in Supabase

## Stack

Next.js (App Router), React, TypeScript, Tailwind CSS, Three.js with React Three Fiber, Framer Motion, Swiper, Supabase.

## Run it

```bash
npm install
npm run dev      # http://localhost:3000
npm run build
npm run lint
```

Registration needs Supabase credentials in environment variables (`.env.local`). They are not in the repo.

## Layout

| Path | What |
|---|---|
| `src/app` | routes: `polymaze`, `aboutus`, `participate`, `faq`, `testimonies`, `register` |
| `src/app/components` | navbar, loader, shared sections |
| `src/components` | UI components |
| `src/lib`, `src/utils` | helpers |

Related: [POLYMAZE Champions League draw](https://github.com/puIad/POLYMAZE-Champions-League), [VIC landing page](https://github.com/puIad/vic-enp).
