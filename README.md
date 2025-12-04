<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Yevhenii Martynenko — Junior Manual QA</title>
    <meta name="description" content="Junior Manual QA portfolio: projects, test documentation, and bug reports by Yevhenii Martynenko (Kyiv, Ukraine)." />

    <!-- TailwindCSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>

    <style>
      /* Subtle animated gradient background */
      .bg-animated {
        background: radial-gradient(1200px 600px at 10% 10%, rgba(59,130,246,0.12), transparent 60%),
                    radial-gradient(1000px 500px at 90% 20%, rgba(16,185,129,0.12), transparent 60%),
                    radial-gradient(900px 500px at 50% 80%, rgba(236,72,153,0.10), transparent 60%);
      }
      .chip { @apply inline-flex items-center rounded-full border px-3 py-1 text-sm; }
      .btn { @apply inline-flex items-center justify-center rounded-2xl border px-4 py-2 text-sm font-medium transition hover:-translate-y-0.5 hover:shadow; }
      .card { @apply rounded-2xl border bg-white/70 backdrop-blur-sm shadow-sm; }
      .grid-cards { @apply grid gap-4 sm:grid-cols-2; }
      .section { @apply mx-auto max-w-5xl px-4 sm:px-6 lg:px-8; }
    </style>
  </head>
  <body class="bg-slate-50 text-slate-800 bg-animated">
    <!-- Header -->
    <header class="section pt-10 pb-6">
      <div class="flex flex-col items-start sm:flex-row sm:items-center sm:justify-between gap-4">
        <div>
          <h1 class="text-3xl sm:text-4xl font-extrabold tracking-tight">Yevhenii Martynenko</h1>
          <p class="mt-1 text-slate-600">Junior Manual QA • Kyiv, Ukraine</p>
        </div>
        <div class="flex gap-2">
          <a class="btn border-slate-300 bg-white" href="mailto:mrtnenko@gmail.com">Mail</a>
          <a class="btn border-slate-300 bg-white" href="https://www.linkedin.com/in/yevhenii-martynenko" target="_blank" rel="noreferrer">LinkedIn</a>
          <a class="btn border-slate-300 bg-white" href="https://t.me/Yevhenii_Martynenko" target="_blank" rel="noreferrer">Telegram</a>
          <a class="btn border-slate-300 bg-white" href="#projects">Projects</a>
        </div>
      </div>
    </header>

    <!-- Summary / Hero -->
    <section class="section pb-10">
      <div class="card p-0 overflow-hidden">
        <img src="https://github.com/yevhenii-martynenko-qa/yevhenii-martynenko-qa/blob/main/Yevhenii%20Martynenko%20(5).png?raw=true" alt="Header — Yevhenii Martynenko" class="w-full max-h-72 object-cover"/>
        <div class="p-6">
          <p class="text-lg">I’m a Junior QA Engineer passionate about software quality and detail‑oriented. Skilled in manual testing, bug reporting, and test documentation. Eager to grow in QA, contribute to reliable and user‑friendly products, and expand my skills in automation testing in the near future.</p>
        </div>
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="section pb-12">
      <h2 class="mb-4 text-2xl font-bold">Projects</h2>
      <div class="grid-cards">
        <!-- Kapusta -->
        <article class="card p-6">
          <div class="flex items-start justify-between gap-3">
            <div>
              <h3 class="text-xl font-semibold">Kapusta — Financial Web Application (Team Project)</h3>
              <p class="mt-1 text-sm text-slate-600">Team QA: requirements review, checklists, FE/BE bug reports, DevTools network checks.</p>
            </div>
            <span class="chip border-emerald-200 bg-emerald-50 text-emerald-700">Web • Team</span>
          </div>
          <div class="mt-4 flex flex-wrap gap-2">
            <a class="btn border-slate-300 bg-white" href="https://docs.google.com/spreadsheets/d/1i_Kz8J2-cOEprkzZKkyyk7i3UqjhKo5oSR9cl9qr6W8/edit?gid=1752727054#gid=1752727054" target="_blank" rel="noreferrer">Project Sheet</a>
          </div>
        </article>

        <!-- Swag Labs -->
        <article class="card p-6">
          <div class="flex items-start justify-between gap-3">
            <div>
              $1
              <p class="mt-2 text-xs text-slate-500">Metrics: <strong>15</strong> test cases • <strong>5</strong> bugs reported</p>
            </div>
            <span class="chip border-blue-200 bg-blue-50 text-blue-700">Web</span>
          </div>
          <div class="mt-4 flex flex-wrap gap-2">
            <a class="btn border-slate-300 bg-white" href="https://docs.google.com/spreadsheets/d/1z_YecUeb6k9zVlNuGwj7jc5iojFRisMlsiI9aU0d7RA/edit?usp=sharing" target="_blank" rel="noreferrer">Project Sheet</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 01_Requirements.csv" target="_blank">Requirements</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 02_Test Plan.csv" target="_blank">Test Plan</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 03_Checklist.csv" target="_blank">Checklist</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 04_Test Cases.csv" target="_blank">Test Cases</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 05_EP_BVA.csv" target="_blank">EP/BVA</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 06_Traceability.csv" target="_blank">Traceability</a>
            <a class="btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 07_Bug Reports.csv" target="_blank">Bug Reports</a>
          </div>
        </article>
      </div>
    </section>

    <!-- Tools -->
    <section class="section pb-12">
      <h2 class="mb-4 text-2xl font-bold">Tools</h2>
      <div class="card p-6">
        <div class="flex flex-wrap gap-2 items-center">
          <img src="https://img.shields.io/badge/Jira-090909?style=for-the-badge&logo=Jira&logoColor=0052cc" alt="Jira"/>
          <img src="https://img.shields.io/badge/Postman-090909?style=for-the-badge&logo=Postman&logoColor=orange" alt="Postman"/>
          <img src="https://img.shields.io/badge/Swagger-090909?style=for-the-badge&logo=Swagger&logoColor=Swagger" alt="Swagger"/>
          <img src="https://img.shields.io/badge/GitHub-090909?style=for-the-badge&logo=GitHub&logoColor=white" alt="GitHub"/>
          <img src="https://img.shields.io/badge/MySQL-090909?style=for-the-badge&logo=mysql&logoColor=blue" alt="MySQL"/>
          <img src="https://img.shields.io/badge/DEVTOOLS-090909?style=for-the-badge&logo=googlechrome&logoColor=blue" alt="DevTools"/>
          <img src="https://img.shields.io/badge/Testrail-090909?style=for-the-badge&logo=Testrail&logoColor=darkblue" alt="Testrail"/>
          <img src="https://img.shields.io/badge/html-090909?style=for-the-badge&logo=html5&logoColor=orange" alt="HTML"/>
          <img src="https://img.shields.io/badge/Trello-090909?style=for-the-badge&logo=Trello&logoColor=blue" alt="Trello"/>
          <img src="https://img.shields.io/badge/JSON-090909?style=for-the-badge&logo=JSON&logoColor=red" alt="JSON"/>
        </div>
      </div>
    </section>

    <!-- Test Documentation -->
    <section class="section pb-12">
      <h2 class="mb-4 text-2xl font-bold">Test Documentation</h2>
      <div class="grid-cards">
        <article class="card p-6">
          <h3 class="font-semibold">SQL Queries</h3>
          <p class="text-sm text-slate-600">Examples of test data checks and validation queries.</p>
          <a class="mt-3 btn border-slate-300 bg-white" href="#" target="_blank" rel="noreferrer">Open</a>
        </article>
        <article class="card p-6">
          <h3 class="font-semibold">Bug Reports</h3>
          <p class="text-sm text-slate-600">Selected issues with repro steps, expected/actual results, and attachments.</p>
          <a class="mt-3 btn border-slate-300 bg-white" href="/mnt/data/Swag Labs — QA Documentation (Login Feature) — Yevhenii Martynenko - 07_Bug Reports.csv" target="_blank">Open</a>
        </article>
      </div>
    </section>

    <!-- About / CV -->
    <section class="section pb-16">
      <div class="card p-6 flex flex-col gap-4 md:flex-row md:items-center md:justify-between">
        <div>
          <h2 class="text-2xl font-bold">About</h2>
          <p class="mt-1 text-slate-700 max-w-2xl">Junior Manual QA with strong focus on clarity and reliability of test documentation, ready to contribute to a product team in Kyiv (onsite/hybrid/remote).</p>
        </div>
        <div class="flex gap-2">
          <a class="btn border-slate-300 bg-white" href="/mnt/data/QA Portfolio — Yevhenii Martynenko — Index (1).docx" target="_blank">Download CV (DOCX)</a>
          <a class="btn border-slate-300 bg-white" href="https://github.com/yevhenii-martynenko-qa" target="_blank" rel="noreferrer">GitHub</a>
          <a class="btn border-slate-300 bg-white" href="https://t.me/Yevhenii_Martynenko" target="_blank" rel="noreferrer">Telegram</a>
        </div>
      </div>
      <p class="mt-3 text-xs text-slate-500">Tip: host this file as <code>index.html</code> in your repo (root or <code>/docs</code>) and enable GitHub Pages.</p>
    </section>

    <footer class="section pb-10">
      <p class="text-center text-xs text-slate-500">© <span id="year"></span> Yevhenii Martynenko • Kyiv, Ukraine</p>
    </footer>

    <script>
      document.getElementById('year').textContent = new Date().getFullYear();
    </script>
  </body>
</html>
