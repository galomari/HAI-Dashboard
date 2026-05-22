# HAI Dashboard

A visual dashboard for your [HAI-Script](https://github.com/KamWittaK/HAI-Script) task stages.

## Setup

### 1. Create your own copy

Click **Use this template → Create a new repository** (top right of this page). Make it **public**.

### 2. Enable GitHub Pages

Go to your new repo → **Settings → Pages → Branch: main → Save**.

Your dashboard will be live at `https://YOUR_USERNAME.github.io/HAI-Dashboard`.

### 3. Connect HAI-Script

In your [HAI-Script](https://github.com/KamWittaK/HAI-Script) folder, add `dashboardPath` to `config.json`:

```json
{
  "projectTasksUrl": "https://ai.joinhandshake.com/fellow/YOUR_PROJECT_ID/tasks",
  "dashboardPath": "C:\\path\\to\\your\\HAI-Dashboard"
}
```

### 4. Run

```bash
node main.js
```

After each run, your dashboard is automatically updated and pushed to GitHub. Open your Pages URL to see the results.

---

No credentials are stored in this repo. Each person uses their own fork with their own data.
