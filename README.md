# PromptVault
lightweight platform for versioning and testing GPT prompts
PromptVault is a lightweight, open-source tool for dev teams to store, version, and live-test prompts for generative models like GPT-4o.
It’s designed for collaborative prompt engineering with version control, and cost tracking.


## 🏗️ Tech Stack

### 🧩 Frontend – Angular 17 + Material 3 / Tailwind
ngx-monaco-editor – prompt editor with syntax highlighting + diff view.

SignalR (@microsoft/signalr) – for real-time model responses.

RxJS – streaming support from backend.

### ⚙️ Backend – ASP.NET Core 9 + Minimal APIs
SQLite + EF Core – lightweight DB with migrations.

OpenAI SDK – GPT-4o calls + token usage calculation.

SignalR – streams model output to Angular frontend.

REST API – CRUD for prompts + test endpoint.
