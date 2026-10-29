## ARBATIQA AI v1.1.0

### What's New

- **Intelligence & Reasoning Core** — intent understanding, ambiguity and missing-information detection, problem decomposition, comparative strategy evaluation, and structured action planning.
- **Adaptive Model Routing & Resilience** — task-complexity based model selection, provider health checks, retry/backoff recovery, verified fallback execution, and prompt-budget protection.
- **Unified Context & Verification** — conversation history, long-term memory, project knowledge, documents and RAG combined into one ranked context; claims are checked against evidence before being presented as fact.
- **Agentic Tool Reasoning** — tools are only invoked when they add real value; multi-step task state, specialist collaboration and verified procedure learning keep long tasks on track.
- **ARBATIQA Code Studio** — VS Code-style editor with line numbers, syntax colours, smart indentation, local multi-language execution, an embedded Chromium preview for HTML/CSS/JS/SVG/Markdown, standard input, and cloud fallback.
- **Expanded Windows Control** — brightness, volume, media keys, Wi-Fi, Bluetooth, airplane mode, power actions, display tools, personalisation, Settings pages, app control, and a risk-based permission/approval engine.
- **Web Research Upgrade** — clean readable text extraction from public webpages plus stronger live search and evidence handling.
- **Security Hardening** — persistent login lockout with escalating cooldowns, URL safety checks, and SHA-256 verified update installers.
- **Refined Chromium chat surface** — smoother streaming, Markdown rendering, thinking state and conversation presentation.
- **3-day update grace period** — every release notification is optional for three days, then becomes mandatory until the update is installed. Once mandatory, the app shell is locked to the update center until the verified installer runs; the only alternative is exiting the application.
- **Windows version metadata** — the packaged executable now reports `FileVersion 1.1.0.0` and `ProductVersion 1.1.0` in Windows Properties.

### Upgrade Path

- Users on **v1.0.9** receive an immediate in-app notification for v1.1.0.
- The update stays optional for **3 days** from `published_at`.
- After 3 days the app requires the update before normal use; the verified installer is downloaded over HTTPS and auto-launched after user confirmation. Navigation, settings and chat are blocked while the required update is pending.
- The same flow is already prepared for **v1.1.1** (`minimum_supported_version = 1.1.0`), so this build will receive that notification and the three-day enforcement automatically.

### Binary Verification

- **Filename:** `ARBATIQA_AI_Setup_1.1.0.exe`
- **SHA-256:** `C9C4D242A10BF6E62CD4D947F876AB160A970AEBCEDEB88DFDDFE1DA32C16402`
- **Download URL:** `https://github.com/arbatiqa/ARBATIQA_AI_Releases/releases/download/v1.1.0/ARBATIQA_AI_Setup_1.1.0.exe`
