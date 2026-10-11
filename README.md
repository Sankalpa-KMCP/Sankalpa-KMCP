<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/banner-mobile-dark.svg" />
  <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="./assets/banner-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="./assets/banner-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="./assets/banner-light.svg" />
  <img src="./assets/banner-dark.svg" width="100%" alt="Sankalpa K M C P, software developer. Built with care: local-first apps and thoughtful developer tools." />
</picture>

# Useful software. Carefully made.

I'm **Sankalpa**. I build browser workspaces and desktop utilities that make everyday work clearer. My interests sit at the intersection of thoughtful interfaces, local data ownership, and dependable engineering.

[Selected work](#selected-work) &nbsp; / &nbsp; [Engineering approach](#engineering-approach) &nbsp; / &nbsp; [Toolkit](#toolkit) &nbsp; / &nbsp; [All repositories](https://github.com/Sankalpa-KMCP?tab=repositories)

---

## Selected work

Four projects. Different problems. A shared attention to the details.

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sankalpa-KMCP/StudyApp">
      <picture>
        <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/study-dashboard-mobile.svg" />
        <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="./assets/study-dashboard-mobile-light.svg" />
        <source media="(prefers-color-scheme: dark)" srcset="./assets/study-dashboard.svg" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/study-dashboard-light.svg" />
        <img src="./assets/study-dashboard.svg" width="100%" alt="Study Dashboard: an illustrated weekly plan, focus session and task checklist." />
      </picture>
      </a>
      <h3>Study Dashboard</h3>
      <p>A browser-local workspace for subjects, tasks, notes and focus sessions. Study-time progress and validated JSON backups keep planning connected to the work.</p>
      <p><sub>React · TypeScript · Vite · Dexie / IndexedDB</sub></p>
      <p><a href="https://github.com/Sankalpa-KMCP/StudyApp"><strong>Explore the workspace ↗</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sankalpa-KMCP/PortPurge-System">
      <picture>
        <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/portpurge-mobile.svg" />
        <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="./assets/portpurge-mobile-light.svg" />
        <source media="(prefers-color-scheme: dark)" srcset="./assets/portpurge.svg" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/portpurge-light.svg" />
        <img src="./assets/portpurge.svg" width="100%" alt="PortPurge: an illustrated port list, process inspection panel and protection shield." />
      </picture>
      </a>
      <h3>PortPurge</h3>
      <p>See what owns a localhost port before acting. A cross-platform desktop utility with process inspection, protected-process controls and an action ledger.</p>
      <p><sub>Tauri · Rust · React · TypeScript</sub></p>
      <p><a href="https://github.com/Sankalpa-KMCP/PortPurge-System"><strong>Explore the utility ↗</strong></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Sankalpa-KMCP/AG2-Router">
      <picture>
        <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/ag2-router-mobile.svg" />
        <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="./assets/ag2-router-mobile-light.svg" />
        <source media="(prefers-color-scheme: dark)" srcset="./assets/ag2-router.svg" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/ag2-router-light.svg" />
        <img src="./assets/ag2-router.svg" width="100%" alt="AG2 Router: an illustrated workload-routing graph with a verification gate and local vault." />
      </picture>
      </a>
      <h3>AG2 Router</h3>
      <p>A native Windows companion for Antigravity. Quota-aware routing, verified account transitions and private usage accounting stay on your machine.</p>
      <p><sub>C# / .NET · WPF · WebView2 · Svelte</sub></p>
      <p><a href="https://github.com/Sankalpa-KMCP/AG2-Router"><strong>Explore the router ↗</strong></a> · <a href="https://github.com/Sankalpa-KMCP/AG2-Router/releases">Releases</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Sankalpa-KMCP/promptQuiz">
      <picture>
        <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="./assets/promptquiz-mobile.svg" />
        <source media="(max-width: 600px) and (prefers-color-scheme: light)" srcset="./assets/promptquiz-mobile-light.svg" />
        <source media="(prefers-color-scheme: dark)" srcset="./assets/promptquiz.svg" />
        <source media="(prefers-color-scheme: light)" srcset="./assets/promptquiz-light.svg" />
        <img src="./assets/promptquiz.svg" width="100%" alt="PromptQuiz: an illustrated recall deck and the recall, rate and review cycle." />
      </picture>
      </a>
      <h3>PromptQuiz</h3>
      <p>Turn material into browser-local quiz decks. Practice active recall, schedule SM-2 reviews and use a copy-paste prompt builder without API keys.</p>
      <p><sub>React · JavaScript · Tailwind CSS · IndexedDB</sub></p>
      <p><a href="https://github.com/Sankalpa-KMCP/promptQuiz"><strong>Explore the learning tool ↗</strong></a></p>
    </td>
  </tr>
</table>

<sub>Original concept illustrations; not application screenshots.</sub>

## Engineering approach

**Keep data close.** I’m interested in local-first applications with clear persistence, understandable backups and explicit recovery boundaries.

**Make state understandable.** Useful interfaces should explain what is happening, handle failure carefully and remain accessible to keyboard users.

**Build beyond the happy path.** Validation, testable boundaries and safe desktop interactions matter as much as the first impression.

## Toolkit

| Area | Tools I build with |
| :--- | :--- |
| Interfaces | React · TypeScript · JavaScript · Svelte · Tailwind CSS |
| Desktop & systems | Rust · Tauri · C# / .NET · WPF · WebView2 |
| Local data | IndexedDB · Dexie · validated JSON backups |
| Delivery & checks | Vite · Git · GitHub Actions · Vitest · Playwright |

## More to explore

**[TurboQuiz ↗](https://github.com/Sankalpa-KMCP/turbo_quiz)**<br>
Browser-local practice and exam sessions, mistake review and attempt history.

**[3D Portfolio ↗](https://github.com/Sankalpa-KMCP/Sankalpa_KMCP)**<br>
An exploration of React Three Fiber scenes, procedural 3D and animated transitions.

---

<p align="center"><strong>Consider the experience. Care for the details.</strong><br /><sub>Sankalpa K M C P · Always building, always learning.</sub></p>
