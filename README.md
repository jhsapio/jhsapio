
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:5C0A0F,100:B8860B&height=180&section=header&text=John%20Hero%20Sapio&fontSize=46&fontColor=FFFFFF&fontAlignY=36&desc=I%20turn%20raw%20student%20data%20into%20dashboards&descSize=16&descAlignY=58&animation=fadeIn" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&pause=1200&color=E8B923&center=true&vCenter=true&width=620&lines=CSV+in+%E2%86%92+dashboards+out;Building+SDVS+%E2%80%94+MSU+Student+Data+Visualization+System;Quasar+%C2%B7+Vue+3+%C2%B7+Pinia+%C2%B7+Firebase;22+%C2%B7+MSU+Main+Campus" />
</p>

---

### 🔐 `users/jhsapio`

My system stores every user as a Firestore doc, so here's mine:

```js
{
  name: 'John Hero Sapio',
  age: 22,
  campus: 'MSU Main Campus',
  role: 'developer',
  isActive: true,
  pendingApproval: false,
  currentlyBuilding: 'SDVS — MSU Student Data Visualization System',
  permissions: ['uploadData', 'viewDashboards', 'shipFeatures'],
  favoriteBug: 'the one where the charts and the lists disagreed'
}
```

### 🧭 What I'm building

**SDVS** takes the registrar's raw student files and turns them into something people can actually read: role-based dashboards, filters, and reports for Admins, Registrar Staff, Faculty, Policy Makers, and ICTC.

```mermaid
flowchart LR
    A[📄 CSV / Excel] --> B{Validate<br/>& clean}
    B -->|bad / duplicate rows| X[🚫 Skipped]
    B --> C[(Firestore<br/>students)]
    C --> D[(Per-term<br/>summaries)]
    D --> E[📊 Dashboards]
    C --> F[🔎 Custom Search]
    C --> G[📑 PDF / Excel Reports]
```

### 📜 Activity log

Every action in my system gets logged, so here's mine:

| Action           | Detail                                                                 |
| ---------------- | ---------------------------------------------------------------------- |
| `project.start`  | Started SDVS as our capstone project                                   |
| `feature.ship`   | Role-based access with 5 roles and an admin approval flow              |
| `feature.ship`   | CSV/Excel upload with validation, duplicate checks, and upload drafts  |
| `feature.ship`   | Dashboards by college, gender, year level, age, grades, and address    |
| `feature.ship`   | PDF and Excel report generation                                        |
| `status.current` | Polishing, testing, and getting ready for the defense                  |

### 🧰 Stack

| Layer          | Tools                                                                                                                                                                                                                                        |
| -------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Frontend       | <img height="40" src="https://skillicons.dev/icons?i=vue,js,html,css,sass,vite" />                                                                                                                                                           |
| Framework      | ![Quasar](https://img.shields.io/badge/Quasar-1976D2?style=flat-square&logo=quasar&logoColor=white) ![Pinia](https://img.shields.io/badge/Pinia-FFD859?style=flat-square&logo=pinia&logoColor=black) ![Vue Router](https://img.shields.io/badge/Vue_Router-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white) |
| Backend & Data | <img height="40" src="https://skillicons.dev/icons?i=firebase,nodejs" />                                                                                                                                                                     |
| Charts & Docs  | ![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=flat-square&logo=chartdotjs&logoColor=white) ![jsPDF](https://img.shields.io/badge/jsPDF-PDF-E34F26?style=flat-square) ![SheetJS](https://img.shields.io/badge/SheetJS-Excel-217346?style=flat-square) |
| Tools          | <img height="40" src="https://skillicons.dev/icons?i=git,github,vscode,pnpm" />                                                                                                                                                              |

### 📈 Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=jhsapio&background=0D1117&ring=E8B923&fire=B22222&currStreakNum=FFFFFF&sideNums=E8B923&currStreakLabel=E8B923&sideLabels=C9D1D9&dates=8B949E&stroke=30363D&hide_border=true" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jhsapio&color=8B0000&style=flat-square&label=profile+views" />
  <a href="https://github.com/jhsapio?tab=repositories"><img src="https://img.shields.io/badge/browse_my_repos-0D1117?style=flat-square&logo=github&logoColor=E8B923" /></a>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:B8860B,100:5C0A0F&height=110&section=footer" />
