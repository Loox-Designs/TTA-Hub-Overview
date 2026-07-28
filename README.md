Two Trees Hub

An internal AI platform I designed and built for the architecture firm where I work. It's in daily use across 14 active projects.

What it is

Two Trees Hub is the software my firm uses to assist in its projects. I'm an architectural designer and project manager there. I built the Hub because I kept hitting the same slow, manual work every day and wanted to fix it.

It brings the parts of a project into one place: code research, renderings, client updates, and project tracking. Everyone at the firm uses it.

What it does

Code research with cited sources. Ask a question about building codes, HOA guidelines, easements, or local regulations and get an answer that points to the exact source. It reads across thousands of pages, including scanned documents, tables, and diagrams. Research that used to take hours takes minutes.
Rendering pipeline. Turns design work into project renderings in-house, built to replace the paid third-party tools we used before.
Client portal. Homeowners follow their own project in real time. They see renderings, drawings, timelines, and leave feedback without emailing anyone.
Multi-tenant security. Each organization's data is isolated at the database level, and automated tests check that isolation on every change. One firm can never see another's data.
How I built it

I build by directing AI coding tools. I act as the product owner, the architect, and the QA. I decide what to build and how it should work, I write the specifications, I review every change, and I test it against real use before it ships. I don't hand-write the production code. This is the method, and it's how one person shipped a platform this size.

The part that took the most work wasn't the code. Most of my coworkers had never used AI in their jobs. I sat with them, watched where they got stuck, and cut any feature they didn't use. The Hub keeps growing because I keep running that loop.

Impact

Used daily across the whole firm, on 14 active projects.
Code research dropped from hours to minutes.
Renderings moved in-house, replacing paid third-party software.
Built multi-tenant from the start, so it can serve other firms, not just mine.
Stack

React, TypeScript, Vite, deployed on Vercel. Supabase and Postgres for data, auth, and storage, with row-level security on every table. Gemini for generation and embeddings, with a reranking step, for the code research. Mapbox for site maps. Resend for email. Hosted GPU image models for rendering.

Screenshots
<img width="1816" height="1225" alt="Sample Home Page" src="https://github.com/user-attachments/assets/85fcafdc-f999-4314-8341-a3e9af97cd2e" />
<img width="1816" height="1225" alt="Sample Map View" src="https://github.com/user-attachments/assets/107c5e37-b9d2-45c2-9a48-529ef3a717f8" />
<img width="1816" height="1225" alt="Sample Project Page" src="https://github.com/user-attachments/assets/412a3035-0476-4d69-a1f3-01f549a807e1" />
<img width="1816" height="1225" alt="Sample Timeline" src="https://github.com/user-attachments/assets/223cdf4b-ff34-4d75-a5ca-3a0d1aaee473" />
<img width="1816" height="1225" alt="Sample Code Reseach" src="https://github.com/user-attachments/assets/891e91b2-1d2c-44bd-b7ce-ac70f501123f" />
<img width="1816" height="1225" alt="Sample Code Reseach 2" src="https://github.com/user-attachments/assets/371c9aae-69c2-48f2-bf61-76bf5ea25729" />
<img width="1816" height="1225" alt="Sample Rendering Flow" src="https://github.com/user-attachments/assets/4e0734f2-916e-4249-aec6-94cc175784a0" />


Sample Home Page Sample Map View Sample Project Page Sample Timeline Sample Code Reseach 2 Sample Code Reseach Sample Rendering Flow
A note on the code

The actual codebase is private. It runs a working firm and holds real client and project data, so I can't open it up. This repo is here to explain what I built and how.

If you'd like to see it, I'm happy to walk through the live product and the code with you.

— Lautaro Perez Blua
