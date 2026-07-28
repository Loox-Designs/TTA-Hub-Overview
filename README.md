# Two Trees Hub

An internal AI platform I designed and built for the architecture firm where I work. It's in daily use across 14 active projects.

## What it is

Two Trees Hub is the software my firm uses to assist in its projects. I'm an architectural designer and project manager there. I built the Hub because I kept hitting the same slow, manual work every day and wanted to fix it.

It brings the parts of a project into one place: code research, renderings, client updates, and project tracking. Everyone at the firm uses it.

## What it does

- **Code research with cited sources.** Ask a question about building codes, HOA guidelines, easements, or local regulations and get an answer that points to the exact source. It reads across thousands of pages, including scanned documents, tables, and diagrams. Research that used to take hours takes minutes.
- **Rendering pipeline.** Turns design work into project renderings in-house, built to replace the paid third-party tools we used before.
- **Client portal.** Homeowners follow their own project in real time. They see renderings, drawings, timelines, and leave feedback without emailing anyone.
- **Multi-tenant security.** Each organization's data is isolated at the database level, and automated tests check that isolation on every change. One firm can never see another's data.

## How I built it

I build by directing AI coding tools. I act as the product owner, the architect, and the QA. I decide what to build and how it should work, I write the specifications, I review every change, and I test it against real use before it ships. I don't hand-write the production code. This is the method, and it's how one person shipped a platform this size.

The part that took the most work wasn't the code. Most of my coworkers had never used AI in their jobs. I sat with them, watched where they got stuck, and cut any feature they didn't use. The Hub keeps growing because I keep running that loop.

## Impact

- Used daily across the whole firm, on 14 active projects.
- Code research dropped from hours to minutes.
- Renderings moved in-house, replacing paid third-party software.
- Built multi-tenant from the start, so it can serve other firms, not just mine.

## Stack

React, TypeScript, Vite, deployed on Vercel. Supabase and Postgres for data, auth, and storage, with row-level security on every table. Gemini for generation and embeddings, with a reranking step, for the code research. Mapbox for site maps. Resend for email. Hosted GPU image models for rendering.

## Screenshots

<!-- Add screenshots here. Avoid anything with client names, addresses, or identifiable properties. -->

<img width="1816" height="1225" alt="Sample Home Page" src="https://github.com/user-attachments/assets/85cdcf6a-9129-454b-b379-d2c596c1d0e1" />
<img width="1816" height="1225" alt="Sample Map View" src="https://github.com/user-attachments/assets/44ef49b3-7cbc-4937-8d22-675b7c611c9c" />
<img width="1816" height="1225" alt="Sample Project Page" src="https://github.com/user-attachments/assets/821b868e-e64a-4b8f-aff8-fd6783467f0b" />
<img width="1816" height="1225" alt="Sample Timeline" src="https://github.com/user-attachments/assets/51702142-262a-4338-be8b-42aa54b45433" />
<img width="1816" height="1225" alt="Sample Code Reseach 2" src="https://github.com/user-attachments/assets/407a69b7-6f5e-4dca-aa67-68beb1a6fe08" />
<img width="1816" height="1225" alt="Sample Code Reseach" src="https://github.com/user-attachments/assets/76e98a0d-7e38-40ec-a90e-a46a4a889f3e" />
<img width="1816" height="1225" alt="Sample Rendering Flow" src="https://github.com/user-attachments/assets/b5dbd0ea-23c4-4d7f-a335-a433cd3b915b" />


## A note on the code

The actual codebase is private. It runs a working firm and holds real client and project data, so I can't open it up. This repo is here to explain what I built and how.

If you'd like to see it, I'm happy to walk through the live product and the code with you.

— Lautaro Perez Blua
