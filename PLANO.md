# PLANO DO PROJETO: HTML/CSS/JS

> Gerado automaticamente pelo SK Code Editor em 18/06/2026, 23:43:30
> **329 arquivo(s)** | **~107.146 linhas de codigo**

---

## RESUMO EXECUTIVO

- **Tipo de aplicacao:** Aplicacao Web Frontend (React)
- **Frontend / Stack principal:** React, TypeScript
- **Versao:** 0.0.0

**Para rodar o projeto:**
```bash
# Abra index.html no Preview (botao Play)
```

---

## ESTRUTURA DE ARQUIVOS

```
HTML/CSS/JS/
├── .github/
│   └── workflows/
│       ├── build-apk.yml
│       └── eas-build.yml
├── .replit-artifact/
│   └── artifact.toml
├── app/
│   ├── (tabs)/
│   │   ├── _layout.tsx
│   │   ├── ai.tsx
│   │   ├── editor.tsx
│   │   ├── index.tsx
│   │   ├── plugins.tsx
│   │   ├── pwa.tsx
│   │   ├── settings.tsx
│   │   ├── tasks.tsx
│   │   ├── terminal.tsx
│   │   └── tree.tsx
│   ├── _layout.tsx
│   └── +not-found.tsx
├── artifacts/
│   ├── api-server/
│   │   ├── .replit-artifact/
│   │   │   └── artifact.toml
│   │   ├── src/
│   │   │   ├── lib/
│   │   │   │   └── logger.ts
│   │   │   ├── routes/
│   │   │   │   ├── ai-chat.ts
│   │   │   │   ├── ai-forward.ts
│   │   │   │   ├── config.ts
│   │   │   │   ├── db.ts
│   │   │   │   ├── drive.ts
│   │   │   │   ├── exec.ts
│   │   │   │   ├── github.ts
│   │   │   │   ├── health.ts
│   │   │   │   ├── index.ts
│   │   │   │   ├── legal-ai.ts
│   │   │   │   ├── pages.ts
│   │   │   │   ├── proxy.ts
│   │   │   │   ├── search.ts
│   │   │   │   ├── twa.ts
│   │   │   │   ├── upload.ts
│   │   │   │   ├── voice.ts
│   │   │   │   └── workspace.ts
│   │   │   ├── app.ts
│   │   │   └── index.ts
│   │   ├── build.mjs
│   │   ├── package.json
│   │   ├── pty_helper.c
│   │   └── tsconfig.json
│   └── code-editor/
│       ├── .github/
│       │   └── workflows/
│       │       ├── build-apk.yml
│       │       └── deploy.yml
│       ├── .replit-artifact/
│       │   └── artifact.toml
│       ├── dist-pronto/
│       │   ├── assets/
│       │   │   ├── index-CszvMv4M.css
│       │   │   ├── vendor-fs-BeamS8bA.js
│       │   │   ├── vendor-highlight-Bu9o_ty_.js
│       │   │   ├── vendor-highlight-DOOs4slz.css
│       │   │   ├── vendor-lucide-NZRTcJIq.js
│       │   │   ├── vendor-markdown-CM6-e2rl.js
│       │   │   ├── vendor-misc-COW7C1HQ.js
│       │   │   ├── vendor-monaco-CS9w1txC.js
│       │   │   ├── vendor-react-D8m3Uig9.js
│       │   │   ├── vendor-react-dom-CdNyEL3a.js
│       │   │   ├── vendor-webcontainer-BPoiPq3D.js
│       │   │   ├── vendor-xterm-CT6HrMBF.js
│       │   │   └── vendor-xterm-DDGTF8rc.css
│       │   ├── favicon.svg
│       │   ├── guia-completo-apk.md
│       │   ├── index.html
│       │   ├── manifest.json
│       │   ├── manual-dev.md
│       │   ├── MANUAL-SK-CODE-EDITOR.md
│       │   └── sw.js
│       ├── dist-standalone/
│       │   ├── assets/
│       │   │   ├── index-D5g-sV5e.css
│       │   │   ├── vendor-fs-BeamS8bA.js
│       │   │   ├── vendor-highlight-Bu9o_ty_.js
│       │   │   ├── vendor-highlight-DOOs4slz.css
│       │   │   ├── vendor-lucide-NZRTcJIq.js
│       │   │   ├── vendor-markdown-CM6-e2rl.js
│       │   │   ├── vendor-misc-COW7C1HQ.js
│       │   │   ├── vendor-monaco-CS9w1txC.js
│       │   │   ├── vendor-react-D8m3Uig9.js
│       │   │   ├── vendor-react-dom-CdNyEL3a.js
│       │   │   ├── vendor-webcontainer-BPoiPq3D.js
│       │   │   ├── vendor-xterm-CT6HrMBF.js
│       │   │   └── vendor-xterm-DDGTF8rc.css
│       │   ├── favicon.svg
│       │   ├── guia-completo-apk.md
│       │   ├── index.html
│       │   ├── LEIA-ME-PARA-PROGRAMADOR.md
│       │   ├── manifest.json
│       │   ├── manual-dev.md
│       │   ├── MANUAL-SK-CODE-EDITOR.md
│       │   └── sw.js
│       ├── public/
│       │   ├── favicon.svg
│       │   ├── guia-completo-apk.md
│       │   ├── manifest.json
│       │   ├── manual-dev.md
│       │   ├── MANUAL-SK-CODE-EDITOR.md
│       │   └── sw.js
│       ├── src/
│       │   ├── components/
│       │   │   ├── ui/
│       │   │   │   ├── accordion.tsx
│       │   │   │   ├── alert-dialog.tsx
│       │   │   │   ├── alert.tsx
│       │   │   │   ├── aspect-ratio.tsx
│       │   │   │   ├── avatar.tsx
│       │   │   │   ├── badge.tsx
│       │   │   │   ├── breadcrumb.tsx
│       │   │   │   ├── button-group.tsx
│       │   │   │   ├── button.tsx
│       │   │   │   ├── calendar.tsx
│       │   │   │   ├── card.tsx
│       │   │   │   ├── carousel.tsx
│       │   │   │   ├── chart.tsx
│       │   │   │   ├── checkbox.tsx
│       │   │   │   ├── collapsible.tsx
│       │   │   │   ├── command.tsx
│       │   │   │   ├── context-menu.tsx
│       │   │   │   ├── dialog.tsx
│       │   │   │   ├── drawer.tsx
│       │   │   │   ├── dropdown-menu.tsx
│       │   │   │   ├── empty.tsx
│       │   │   │   ├── field.tsx
│       │   │   │   ├── form.tsx
│       │   │   │   ├── hover-card.tsx
│       │   │   │   ├── input-group.tsx
│       │   │   │   ├── input-otp.tsx
│       │   │   │   ├── input.tsx
│       │   │   │   ├── item.tsx
│       │   │   │   ├── kbd.tsx
│       │   │   │   ├── label.tsx
│       │   │   │   ├── menubar.tsx
│       │   │   │   ├── navigation-menu.tsx
│       │   │   │   ├── pagination.tsx
│       │   │   │   ├── popover.tsx
│       │   │   │   ├── progress.tsx
│       │   │   │   ├── radio-group.tsx
│       │   │   │   ├── resizable.tsx
│       │   │   │   ├── scroll-area.tsx
│       │   │   │   ├── select.tsx
│       │   │   │   ├── separator.tsx
│       │   │   │   ├── sheet.tsx
│       │   │   │   ├── sidebar.tsx
│       │   │   │   ├── skeleton.tsx
│       │   │   │   ├── slider.tsx
│       │   │   │   ├── sonner.tsx
│       │   │   │   ├── spinner.tsx
│       │   │   │   ├── switch.tsx
│       │   │   │   ├── table.tsx
│       │   │   │   ├── tabs.tsx
│       │   │   │   ├── textarea.tsx
│       │   │   │   ├── toast.tsx
│       │   │   │   ├── toaster.tsx
│       │   │   │   ├── toggle-group.tsx
│       │   │   │   ├── toggle.tsx
│       │   │   │   └── tooltip.tsx
│       │   │   ├── AIChat.tsx
│       │   │   ├── APKBuilderPanel.tsx
│       │   │   ├── AssistenteJuridico.tsx
│       │   │   ├── CampoLivre.tsx
│       │   │   ├── CodeEditor.tsx
│       │   │   ├── CombinarApps.tsx
│       │   │   ├── DriveBackupPanel.tsx
│       │   │   ├── EditorLayout.tsx
│       │   │   ├── FileTree.tsx
│       │   │   ├── GitHubPanel.tsx
│       │   │   ├── Manual.tsx
│       │   │   ├── PackageSearch.tsx
│       │   │   ├── Preview.tsx
│       │   │   ├── QuickPrompt.tsx
│       │   │   ├── RealTerminal.tsx
│       │   │   ├── StreamTerminal.tsx
│       │   │   ├── SystemStatusPanel.tsx
│       │   │   ├── TemplateSelector.tsx
│       │   │   ├── Terminal.tsx
│       │   │   ├── VoiceCard.tsx
│       │   │   ├── VoiceMode.tsx
│       │   │   ├── VSCodeWebPanel.tsx
│       │   │   └── WebContainerTerminal.tsx
│       │   ├── hooks/
│       │   │   ├── use-mobile.tsx
│       │   │   └── use-toast.ts
│       │   ├── lib/
│       │   │   ├── ai-service.ts
│       │   │   ├── github-service.ts
│       │   │   ├── projects.ts
│       │   │   ├── store.ts
│       │   │   ├── templates.ts
│       │   │   ├── tts-service.ts
│       │   │   ├── utils.ts
│       │   │   ├── virtual-fs.ts
│       │   │   └── zip-service.ts
│       │   ├── App.tsx
│       │   ├── index.css
│       │   └── main.tsx
│       ├── components.json
│       ├── index.html
│       ├── INSTALAR.md
│       ├── package-standalone.json
│       ├── package.json
│       ├── SYSTEM_DOCS.md
│       ├── tsconfig.json
│       ├── vite.config.standalone.ts
│       └── vite.config.ts
├── components/
│   ├── AIChat.tsx
│   ├── AIMemoryModal.tsx
│   ├── APKBuilderModal.tsx
│   ├── CampoLivreModal.tsx
│   ├── CheckpointsModal.tsx
│   ├── CodeEditor.tsx
│   ├── CombinarAppsModal.tsx
│   ├── ErrorBoundary.tsx
│   ├── ErrorFallback.tsx
│   ├── FileSidebar.tsx
│   ├── FloatingAI.tsx
│   ├── GitHubModal.tsx
│   ├── HtmlPlayground.tsx
│   ├── KeyboardAwareScrollViewCompat.tsx
│   ├── LibrarySearch.tsx
│   ├── ManualModal.tsx
│   ├── MessageRenderer.tsx
│   ├── MonacoEditor.tsx
│   ├── PreviewPanel.tsx
│   ├── ProjectOverviewModal.tsx
│   ├── ProjectPlanModal.tsx
│   ├── SystemStatus.tsx
│   ├── TasksPanel.tsx
│   ├── Terminal.tsx
│   ├── VoiceAssistant.tsx
│   ├── VSCodeView.tsx
│   └── VSCodeWebModal.tsx
├── constants/
│   └── colors.ts
├── context/
│   └── AppContext.tsx
├── data/
│   └── featuredProjects.ts
├── devmobile-fix/
│   ├── .github/
│   │   └── workflows/
│   │       ├── build-apk-eas.yml
│   │       └── build-apk-local.yml
│   ├── .replit-artifact/
│   │   └── artifact.toml
│   ├── app/
│   │   ├── (tabs)/
│   │   │   ├── _layout.tsx
│   │   │   ├── ai.tsx
│   │   │   ├── browser.tsx
│   │   │   ├── editor.tsx
│   │   │   ├── index.tsx
│   │   │   ├── plugins.tsx
│   │   │   ├── pwa.tsx
│   │   │   ├── settings.tsx
│   │   │   ├── tasks.tsx
│   │   │   └── terminal.tsx
│   │   ├── _layout.tsx
│   │   └── +not-found.tsx
│   ├── components/
│   │   ├── AIChat.tsx
│   │   ├── AIMemoryModal.tsx
│   │   ├── APKBuilderModal.tsx
│   │   ├── CampoLivreModal.tsx
│   │   ├── CheckpointsModal.tsx
│   │   ├── CodeEditor.tsx
│   │   ├── CombinarAppsModal.tsx
│   │   ├── DatabasePanel.tsx
│   │   ├── ErrorBoundary.tsx
│   │   ├── ErrorFallback.tsx
│   │   ├── FileSidebar.tsx
│   │   ├── FloatingAI.tsx
│   │   ├── GitHubModal.tsx
│   │   ├── HtmlPlayground.tsx
│   │   ├── KeyboardAwareScrollViewCompat.tsx
│   │   ├── LibrarySearch.tsx
│   │   ├── ManualModal.tsx
│   │   ├── MessageRenderer.tsx
│   │   ├── MonacoEditor.tsx
│   │   ├── PreviewPanel.tsx
│   │   ├── ProjectOverviewModal.tsx
│   │   ├── ProjectPlanModal.tsx
│   │   ├── SystemStatus.tsx
│   │   ├── Terminal.tsx
│   │   ├── VoiceAssistant.tsx
│   │   ├── VSCodeView.tsx
│   │   ├── VSCodeWebModal.tsx
│   │   └── XTermWebView.tsx
│   ├── constants/
│   │   └── colors.ts
│   ├── context/
│   │   └── AppContext.tsx
│   ├── data/
│   │   └── featuredProjects.ts
│   ├── hooks/
│   │   ├── useApiBase.ts
│   │   └── useColors.ts
│   ├── plugins/
│   │   └── withTermuxIntent.js
│   ├── server/
│   │   ├── templates/
│   │   │   └── landing-page.html
│   │   └── serve.js
│   ├── services/
│   │   ├── apiBase.ts
│   │   ├── githubService.ts
│   │   ├── localSQLite.ts
│   │   ├── previewService.ts
│   │   ├── runtimeMode.ts
│   │   ├── storageService.ts
│   │   └── terminalService.ts
│   ├── utils/
│   │   ├── projectPlan.ts
│   │   └── zipUtils.ts
│   ├── .easignore
│   ├── .env
│   ├── .env.example
│   ├── .gitignore
│   ├── .npmrc
│   ├── app.json
│   ├── babel.config.js
│   ├── capacitor.config.ts
│   ├── COMO_BUILDAR.md
│   ├── COMO-BUILDAR-APK.md
│   ├── eas.json
│   ├── expo-env.d.ts
│   ├── GERAR-APK.md
│   ├── metro.config.js
│   ├── package.json
│   ├── PLANO.md
│   └── tsconfig.json
├── hooks/
│   ├── useApiBase.ts
│   └── useColors.ts
├── lib/
│   ├── androidBuilder.ts
│   ├── archiveApk.ts
│   ├── eas.ts
│   └── githubApk.ts
├── scripts/
│   └── build.js
├── server/
│   ├── templates/
│   │   └── landing-page.html
│   └── serve.js
├── services/
│   ├── apiBase.ts
│   ├── githubService.ts
│   ├── localSQLite.ts
│   ├── previewService.ts
│   ├── runtimeMode.ts
│   ├── storageService.ts
│   └── terminalService.ts
├── utils/
│   ├── projectPlan.ts
│   └── zipUtils.ts
├── .gitignore
├── app.json
├── babel.config.js
├── eas.json
├── expo-env.d.ts
├── manifest.webmanifest
├── MANUAL-GERAR-APK.html
├── metro.config.js
├── package.json
├── pnpm-workspace.yaml
├── README.md
├── sw.js
└── tsconfig.json
```

---

## STACK TECNOLOGICO DETECTADO

- **Frontend:** React, TypeScript
- **Todos os pacotes (3):** @replit/connectors-sdk, prettier, typescript

---

## ROTAS DA API (endpoints detectados automaticamente)

```
USE    /api  (em artifacts/api-server/src/app.ts)
GET    /ai/chat  (em artifacts/api-server/src/routes/ai-chat.ts)
POST   /ai/chat  (em artifacts/api-server/src/routes/ai-chat.ts)
POST   /ai/forward  (em artifacts/api-server/src/routes/ai-forward.ts)
GET    /config  (em artifacts/api-server/src/routes/config.ts)
POST   /db/neon/create  (em artifacts/api-server/src/routes/db.ts)
GET    /db/neon/projects  (em artifacts/api-server/src/routes/db.ts)
POST   /db/neon/credentials  (em artifacts/api-server/src/routes/db.ts)
POST   /db/execute  (em artifacts/api-server/src/routes/db.ts)
POST   /db/test-connection  (em artifacts/api-server/src/routes/db.ts)
GET    /drive/list  (em artifacts/api-server/src/routes/drive.ts)
POST   /drive/upload  (em artifacts/api-server/src/routes/drive.ts)
DELETE /drive/delete/:fileId  (em artifacts/api-server/src/routes/drive.ts)
POST   /exec/npm-install  (em artifacts/api-server/src/routes/exec.ts)
POST   /exec/run-node  (em artifacts/api-server/src/routes/exec.ts)
POST   /exec/run-node-vfs  (em artifacts/api-server/src/routes/exec.ts)
POST   /db/query  (em artifacts/api-server/src/routes/exec.ts)
POST   /projects/:projectId/exec-stdin  (em artifacts/api-server/src/routes/exec.ts)
POST   /projects/:projectId/exec-stream  (em artifacts/api-server/src/routes/exec.ts)
GET    /github/user  (em artifacts/api-server/src/routes/github.ts)
GET    /github/repos  (em artifacts/api-server/src/routes/github.ts)
POST   /github/repos  (em artifacts/api-server/src/routes/github.ts)
POST   /github/push  (em artifacts/api-server/src/routes/github.ts)
DELETE /github/repos/:owner/:repo  (em artifacts/api-server/src/routes/github.ts)
GET    /healthz  (em artifacts/api-server/src/routes/health.ts)
USE    /voice  (em artifacts/api-server/src/routes/index.ts)
POST   /legal/process  (em artifacts/api-server/src/routes/legal-ai.ts)
POST   /legal/refine  (em artifacts/api-server/src/routes/legal-ai.ts)
POST   /pages/deploy  (em artifacts/api-server/src/routes/pages.ts)
GET    /search  (em artifacts/api-server/src/routes/search.ts)
GET    /npm-search  (em artifacts/api-server/src/routes/search.ts)
GET    /pwa-check  (em artifacts/api-server/src/routes/twa.ts)
GET    /twa-files  (em artifacts/api-server/src/routes/twa.ts)
GET    /twa-package  (em artifacts/api-server/src/routes/twa.ts)
POST   /upload/extract-text  (em artifacts/api-server/src/routes/upload.ts)
POST   /transcribe  (em artifacts/api-server/src/routes/voice.ts)
POST   /speak  (em artifacts/api-server/src/routes/voice.ts)
GET    /workspace/info  (em artifacts/api-server/src/routes/workspace.ts)
POST   /workspace/write  (em artifacts/api-server/src/routes/workspace.ts)
GET    /workspace/read  (em artifacts/api-server/src/routes/workspace.ts)
GET    /workspace/list  (em artifacts/api-server/src/routes/workspace.ts)
POST   /workspace/delete  (em artifacts/api-server/src/routes/workspace.ts)
POST   /workspace/install  (em artifacts/api-server/src/routes/workspace.ts)
POST   /workspace/run  (em artifacts/api-server/src/routes/workspace.ts)
POST   /workspace/sync  (em artifacts/api-server/src/routes/workspace.ts)
GET    /api/items  (em artifacts/code-editor/src/lib/templates.ts)
GET    /api/items/:id  (em artifacts/code-editor/src/lib/templates.ts)
POST   /api/items  (em artifacts/code-editor/src/lib/templates.ts)
GET    /api/health  (em artifacts/code-editor/src/lib/templates.ts)
USE    /api/auth  (em artifacts/code-editor/src/lib/templates.ts)
USE    /api/usuarios  (em artifacts/code-editor/src/lib/templates.ts)
POST   /register  (em artifacts/code-editor/src/lib/templates.ts)
POST   /login  (em artifacts/code-editor/src/lib/templates.ts)
GET    /perfil  (em artifacts/code-editor/src/lib/templates.ts)
GET    /api/provedores  (em artifacts/code-editor/src/lib/templates.ts)
POST   /api/chat  (em artifacts/code-editor/src/lib/templates.ts)
GET    /health  (em artifacts/code-editor/src/lib/templates.ts)
POST   /auth/login  (em artifacts/code-editor/src/lib/templates.ts)
POST   /auth/registro  (em artifacts/code-editor/src/lib/templates.ts)
GET    /clientes  (em artifacts/code-editor/src/lib/templates.ts)
GET    /clientes/:id  (em artifacts/code-editor/src/lib/templates.ts)
POST   /clientes  (em artifacts/code-editor/src/lib/templates.ts)
PUT    /clientes/:id  (em artifacts/code-editor/src/lib/templates.ts)
GET    /processos  (em artifacts/code-editor/src/lib/templates.ts)
GET    /processos/:id  (em artifacts/code-editor/src/lib/templates.ts)
POST   /processos  (em artifacts/code-editor/src/lib/templates.ts)
GET    /audiencias  (em artifacts/code-editor/src/lib/templates.ts)
POST   /audiencias  (em artifacts/code-editor/src/lib/templates.ts)
GET    /prazos/proximos  (em artifacts/code-editor/src/lib/templates.ts)
GET    /dashboard  (em artifacts/code-editor/src/lib/templates.ts)
GET    /api/registros  (em artifacts/code-editor/src/lib/templates.ts)
GET    /api/registros/:id  (em artifacts/code-editor/src/lib/templates.ts)
POST   /api/registros  (em artifacts/code-editor/src/lib/templates.ts)
PUT    /api/registros/:id  (em artifacts/code-editor/src/lib/templates.ts)
DELETE /api/registros/:id  (em artifacts/code-editor/src/lib/templates.ts)
POST   /api/chat  (em data/featuredProjects.ts)
GET    /api/saude  (em data/featuredProjects.ts)
POST   /api/chat  (em data/featuredProjects.ts)
GET    /api/saude  (em data/featuredProjects.ts)
POST   /api/chat  (em data/featuredProjects.ts)
GET    /api/saude  (em data/featuredProjects.ts)
POST   /api/chat  (em data/featuredProjects.ts)
GET    /api/provedores  (em data/featuredProjects.ts)
GET    /api/saude  (em data/featuredProjects.ts)
POST   /api/chat  (em devmobile-fix/data/featuredProjects.ts)
GET    /api/saude  (em devmobile-fix/data/featuredProjects.ts)
POST   /api/chat  (em devmobile-fix/data/featuredProjects.ts)
GET    /api/saude  (em devmobile-fix/data/featuredProjects.ts)
POST   /api/chat  (em devmobile-fix/data/featuredProjects.ts)
GET    /api/saude  (em devmobile-fix/data/featuredProjects.ts)
POST   /api/chat  (em devmobile-fix/data/featuredProjects.ts)
GET    /api/provedores  (em devmobile-fix/data/featuredProjects.ts)
GET    /api/saude  (em devmobile-fix/data/featuredProjects.ts)
```

---

## SCRIPTS DISPONIVEIS (package.json)

```bash
npm run preinstall    # sh -c 'rm -f package-lock.json yarn.lock; case "$npm_config_user_agent" in pnpm/*) ;; *) echo "Use pnpm instead" >&2; exit 1 ;; esac'
npm run build         # pnpm run typecheck && pnpm -r --if-present run build
npm run typecheck:libs  # tsc --build
npm run typecheck     # pnpm run typecheck:libs && pnpm -r --filter "./artifacts/**" --filter "./scripts" --if-present run typecheck
```

---

## VARIAVEIS DE AMBIENTE NECESSARIAS

Crie um arquivo `.env` na raiz com estas variaveis:

```env
LOG_LEVEL=seu_valor_aqui
DATABASE_URL=seu_valor_aqui
AI_INTEGRATIONS_OPENAI_BASE_URL=seu_valor_aqui
AI_INTEGRATIONS_OPENAI_API_KEY=seu_valor_aqui
PORT=seu_valor_aqui
ALLOWED_ORIGINS=seu_valor_aqui
JWT_SECRET=seu_valor_aqui
JWT_EXPIRES_IN=seu_valor_aqui
GROQ_API_KEY=seu_valor_aqui
OPENAI_API_KEY=seu_valor_aqui
GEMINI_API_KEY=seu_valor_aqui
ANTHROPIC_API_KEY=seu_valor_aqui
XAI_API_KEY=seu_valor_aqui
OPENROUTER_API_KEY=seu_valor_aqui
PERPLEXITY_API_KEY=seu_valor_aqui
TELEGRAM_TOKEN=seu_valor_aqui
BASE_PATH=seu_valor_aqui
REPL_ID=seu_valor_aqui
GROQ_MODEL=seu_valor_aqui
CLAUDE_MODEL=seu_valor_aqui
GEMINI_MODEL=seu_valor_aqui
EXPO_PUBLIC_DOMAIN=seu_valor_aqui
EXPO_PUBLIC_API_BASE_URL=seu_valor_aqui
EXPO_PUBLIC_REMOTE_API_URL=seu_valor_aqui
EXPO_PUBLIC_APP_MODE=seu_valor_aqui
EXPO_PUBLIC_API_STRATEGY=seu_valor_aqui
EXPO_PUBLIC_LOCAL_API_PORT=seu_valor_aqui
EXPO_PUBLIC_LOCAL_PREVIEW_PORT=seu_valor_aqui
EXPO_PUBLIC_ENABLE_TERMUX=seu_valor_aqui
EXPO_PUBLIC_ENABLE_REMOTE_AI=seu_valor_aqui
EXPO_PUBLIC_ENABLE_GITHUB=seu_valor_aqui
EXPO_PUBLIC_ENABLE_REMOTE_DB=seu_valor_aqui
EXPO_PUBLIC_ENABLE_REMOTE_TERMINAL=seu_valor_aqui
REPLIT_INTERNAL_APP_DOMAIN=seu_valor_aqui
REPLIT_DEV_DOMAIN=seu_valor_aqui
EXPO_PUBLIC_REPL_ID=seu_valor_aqui
```

---

## ARQUIVOS PRINCIPAIS

- `app/(tabs)/index.tsx` — Arquivo principal
- `artifacts/api-server/src/app.ts` — Ponto de entrada do backend
- `artifacts/api-server/src/index.ts` — Ponto de entrada do backend
- `artifacts/api-server/src/routes/index.ts` — Ponto de entrada do backend
- `artifacts/code-editor/dist-pronto/index.html` — Arquivo principal
- `artifacts/code-editor/dist-standalone/index.html` — Arquivo principal
- `artifacts/code-editor/index.html` — Arquivo principal
- `artifacts/code-editor/src/App.tsx` — Componente raiz do frontend
- `artifacts/code-editor/src/main.tsx` — Arquivo principal
- `devmobile-fix/app/(tabs)/index.tsx` — Arquivo principal

---

## GUIA COMPLETO — O QUE CADA PARTE DO PROJETO FAZ

> Esta secao explica, em linguagem simples, o que e para que serve cada pasta e cada arquivo.

### 📁 Raiz do Projeto (pasta principal)
> Arquivos de configuracao e pontos de entrada ficam aqui.

**`.gitignore`** _(42 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`MANUAL-GERAR-APK.html`** _(122 linhas)_
Arquivo HTML — parte do projeto.

**`README.md`** _(3 linhas)_
Documentacao principal do projeto. Explica o que o projeto faz e como rodar.

**`app.json`** _(66 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`babel.config.js`** _(7 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`eas.json`** _(21 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`expo-env.d.ts`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`manifest.webmanifest`** _(50 linhas)_
Arquivo WEBMANIFEST — parte do projeto.

**`metro.config.js`** _(4 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`package.json`** _(36 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`pnpm-workspace.yaml`** _(161 linhas)_
Arquivo YAML — parte do projeto.

**`sw.js`** _(16 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tsconfig.json`** _(17 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(24 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`+not-found.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`_layout.tsx`** _(52 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

---

### 📁 `components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(1038 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`AIMemoryModal.tsx`** _(203 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`APKBuilderModal.tsx`** _(1299 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`CampoLivreModal.tsx`** _(1039 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`CheckpointsModal.tsx`** _(173 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`CodeEditor.tsx`** _(383 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`CombinarAppsModal.tsx`** _(352 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`ErrorBoundary.tsx`** _(55 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`ErrorFallback.tsx`** _(279 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`FileSidebar.tsx`** _(742 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`FloatingAI.tsx`** _(897 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubModal.tsx`** _(1208 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`HtmlPlayground.tsx`** _(772 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`KeyboardAwareScrollViewCompat.tsx`** _(30 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`LibrarySearch.tsx`** _(327 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`ManualModal.tsx`** _(776 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`MessageRenderer.tsx`** _(290 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`MonacoEditor.tsx`** _(163 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`PreviewPanel.tsx`** _(500 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`ProjectOverviewModal.tsx`** _(504 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`ProjectPlanModal.tsx`** _(369 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`SystemStatus.tsx`** _(480 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TasksPanel.tsx`** _(426 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1058 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VSCodeView.tsx`** _(685 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`VSCodeWebModal.tsx`** _(287 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`VoiceAssistant.tsx`** _(1033 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `constants/`
> Pasta 'constants' — agrupamento de arquivos relacionados.

**`colors.ts`** _(98 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `context/`
> Gerenciamento de estado global — dados compartilhados entre telas.

**`AppContext.tsx`** _(1396 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

---

### 📁 `data/`
> Pasta 'data' — agrupamento de arquivos relacionados.

**`featuredProjects.ts`** _(802 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `devmobile-fix/`
> Pasta 'devmobile-fix' — agrupamento de arquivos relacionados.

**`.easignore`** _(25 linhas)_
Arquivo EASIGNORE — parte do projeto.

**`.env`** _(2 linhas)_
Arquivo de variaveis secretas (senhas, chaves de API). NUNCA suba este arquivo para o GitHub.

**`.env.example`** _(91 linhas)_
Arquivo de variaveis secretas (senhas, chaves de API). NUNCA suba este arquivo para o GitHub.

**`.gitignore`** _(42 linhas)_
Lista de arquivos/pastas que o Git deve IGNORAR (nao versionar). Ex: node_modules, .env

**`.npmrc`** _(3 linhas)_
Arquivo NPMRC — parte do projeto.

**`COMO-BUILDAR-APK.md`** _(78 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`COMO_BUILDAR.md`** _(113 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`GERAR-APK.md`** _(62 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`PLANO.md`** _(187 linhas)_
Este documento! Gerado automaticamente pelo SK Code Editor com toda a estrutura do projeto.

**`app.json`** _(63 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`babel.config.js`** _(7 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`capacitor.config.ts`** _(43 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`eas.json`** _(58 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`expo-env.d.ts`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`metro.config.js`** _(28 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`package.json`** _(78 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(24 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`useApiBase.ts`** _(100 linhas)_
HOOK de dados — busca informacoes da API e gerencia estado de carregamento e erro.

**`useColors.ts`** _(25 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'colors'.

---

### 📁 `lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`androidBuilder.ts`** _(430 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`archiveApk.ts`** _(301 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`eas.ts`** _(151 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`githubApk.ts`** _(222 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `scripts/`
> Pasta 'scripts' — agrupamento de arquivos relacionados.

**`build.js`** _(574 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `server/`
> Pasta 'server' — agrupamento de arquivos relacionados.

**`serve.js`** _(136 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `services/`
> Comunicacao com servidor, banco de dados ou APIs externas.

**`apiBase.ts`** _(28 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`githubService.ts`** _(387 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`localSQLite.ts`** _(81 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`previewService.ts`** _(17 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`runtimeMode.ts`** _(56 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storageService.ts`** _(16 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`terminalService.ts`** _(29 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `utils/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`projectPlan.ts`** _(208 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zipUtils.ts`** _(472 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `.github/workflows/`
> Pasta 'workflows' — agrupamento de arquivos relacionados.

**`build-apk.yml`** _(60 linhas)_
Arquivo YML — parte do projeto.

**`eas-build.yml`** _(32 linhas)_
Arquivo YML — parte do projeto.

---

### 📁 `app/(tabs)/`
> Pasta '(tabs)' — agrupamento de arquivos relacionados.

**`_layout.tsx`** _(167 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`ai.tsx`** _(81 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`editor.tsx`** _(1643 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`index.tsx`** _(3964 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

**`plugins.tsx`** _(1234 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`pwa.tsx`** _(658 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`settings.tsx`** _(1877 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`tasks.tsx`** _(522 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`terminal.tsx`** _(216 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tree.tsx`** _(241 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `artifacts/api-server/`
> Pasta 'api-server' — agrupamento de arquivos relacionados.

**`build.mjs`** _(159 linhas)_
Arquivo MJS — parte do projeto.

**`package.json`** _(48 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`pty_helper.c`** _(138 linhas)_
Arquivo C — parte do projeto.

**`tsconfig.json`** _(18 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

---

### 📁 `artifacts/code-editor/`
> Pasta 'code-editor' — agrupamento de arquivos relacionados.

**`INSTALAR.md`** _(105 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`SYSTEM_DOCS.md`** _(292 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`components.json`** _(20 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`index.html`** _(98 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`package-standalone.json`** _(42 linhas)_
Arquivo de dados ou configuracao no formato JSON (chave: valor).

**`package.json`** _(93 linhas)_
Registro de dependencias e scripts do projeto. Aqui ficam os comandos (npm run dev, npm start) e os pacotes instalados.

**`tsconfig.json`** _(23 linhas)_
Configuracao do TypeScript. Diz para o computador como interpretar o codigo .ts e .tsx.

**`vite.config.standalone.ts`** _(45 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`vite.config.ts`** _(69 linhas)_
Configuracao do Vite (servidor de desenvolvimento). Define a porta, alias de caminhos e plugins usados.

---

### 📁 `devmobile-fix/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(23 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `devmobile-fix/app/`
> Pasta 'app' — agrupamento de arquivos relacionados.

**`+not-found.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`_layout.tsx`** _(69 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

---

### 📁 `devmobile-fix/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(1549 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`AIMemoryModal.tsx`** _(203 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`APKBuilderModal.tsx`** _(1058 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`CampoLivreModal.tsx`** _(989 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`CheckpointsModal.tsx`** _(173 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`CodeEditor.tsx`** _(383 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`CombinarAppsModal.tsx`** _(352 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`DatabasePanel.tsx`** _(887 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`ErrorBoundary.tsx`** _(55 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`ErrorFallback.tsx`** _(279 linhas)_
Componente de ERRO — exibido quando algo da errado, com mensagem explicativa.

**`FileSidebar.tsx`** _(742 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`FloatingAI.tsx`** _(897 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubModal.tsx`** _(1257 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`HtmlPlayground.tsx`** _(706 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`KeyboardAwareScrollViewCompat.tsx`** _(30 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`LibrarySearch.tsx`** _(327 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`ManualModal.tsx`** _(776 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`MessageRenderer.tsx`** _(504 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`MonacoEditor.tsx`** _(163 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`PreviewPanel.tsx`** _(500 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`ProjectOverviewModal.tsx`** _(504 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`ProjectPlanModal.tsx`** _(369 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`SystemStatus.tsx`** _(480 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1297 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VSCodeView.tsx`** _(685 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`VSCodeWebModal.tsx`** _(363 linhas)_
Componente MODAL — janela/popup que aparece sobre a tela pedindo uma acao ou mostrando uma informacao importante.

**`VoiceAssistant.tsx`** _(991 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`XTermWebView.tsx`** _(311 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

---

### 📁 `devmobile-fix/constants/`
> Pasta 'constants' — agrupamento de arquivos relacionados.

**`colors.ts`** _(98 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `devmobile-fix/context/`
> Gerenciamento de estado global — dados compartilhados entre telas.

**`AppContext.tsx`** _(1382 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

---

### 📁 `devmobile-fix/data/`
> Pasta 'data' — agrupamento de arquivos relacionados.

**`featuredProjects.ts`** _(802 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `devmobile-fix/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`useApiBase.ts`** _(100 linhas)_
HOOK de dados — busca informacoes da API e gerencia estado de carregamento e erro.

**`useColors.ts`** _(25 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de 'colors'.

---

### 📁 `devmobile-fix/plugins/`
> Pasta 'plugins' — agrupamento de arquivos relacionados.

**`withTermuxIntent.js`** _(26 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `devmobile-fix/server/`
> Pasta 'server' — agrupamento de arquivos relacionados.

**`serve.js`** _(136 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `devmobile-fix/services/`
> Comunicacao com servidor, banco de dados ou APIs externas.

**`apiBase.ts`** _(28 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`githubService.ts`** _(530 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`localSQLite.ts`** _(81 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`previewService.ts`** _(17 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`runtimeMode.ts`** _(56 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`storageService.ts`** _(16 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`terminalService.ts`** _(29 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `devmobile-fix/utils/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`projectPlan.ts`** _(208 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zipUtils.ts`** _(473 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

---

### 📁 `server/templates/`
> Pasta 'templates' — agrupamento de arquivos relacionados.

**`landing-page.html`** _(461 linhas)_
Arquivo HTML — parte do projeto.

---

### 📁 `artifacts/api-server/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(33 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `artifacts/api-server/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`app.ts`** _(35 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.ts`** _(288 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

---

### 📁 `artifacts/code-editor/.replit-artifact/`
> Pasta '.replit-artifact' — agrupamento de arquivos relacionados.

**`artifact.toml`** _(32 linhas)_
Arquivo TOML — parte do projeto.

---

### 📁 `artifacts/code-editor/dist-pronto/`
> Pasta 'dist-pronto' — agrupamento de arquivos relacionados.

**`MANUAL-SK-CODE-EDITOR.md`** _(344 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`guia-completo-apk.md`** _(949 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`index.html`** _(111 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(61 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`manual-dev.md`** _(281 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`sw.js`** _(186 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `artifacts/code-editor/dist-standalone/`
> Pasta 'dist-standalone' — agrupamento de arquivos relacionados.

**`LEIA-ME-PARA-PROGRAMADOR.md`** _(73 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`MANUAL-SK-CODE-EDITOR.md`** _(344 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`guia-completo-apk.md`** _(949 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`index.html`** _(111 linhas)_
Pagina HTML raiz do projeto. E o ponto de entrada que o browser carrega primeiro.

**`manifest.json`** _(61 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`manual-dev.md`** _(281 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`sw.js`** _(186 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `artifacts/code-editor/public/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`MANUAL-SK-CODE-EDITOR.md`** _(344 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`favicon.svg`** _(17 linhas)_
Imagem vetorial (icone ou ilustracao que nao perde qualidade ao ampliar).

**`guia-completo-apk.md`** _(949 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`manifest.json`** _(61 linhas)_
Manifesto do PWA — define nome, icone e configuracoes para instalar o app no celular.

**`manual-dev.md`** _(281 linhas)_
Arquivo de documentacao em Markdown (texto formatado com #titulos, **negrito**, listas).

**`sw.js`** _(186 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `artifacts/code-editor/src/`
> Codigo-fonte principal do projeto. Nao apague esta pasta.

**`App.tsx`** _(218 linhas)_
Componente RAIZ do frontend — e o pai de todos os outros componentes. Aqui ficam as rotas principais.

**`index.css`** _(167 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`main.tsx`** _(6 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

---

### 📁 `devmobile-fix/.github/workflows/`
> Pasta 'workflows' — agrupamento de arquivos relacionados.

**`build-apk-eas.yml`** _(72 linhas)_
Arquivo YML — parte do projeto.

**`build-apk-local.yml`** _(126 linhas)_
Arquivo YML — parte do projeto.

---

### 📁 `devmobile-fix/app/(tabs)/`
> Pasta '(tabs)' — agrupamento de arquivos relacionados.

**`_layout.tsx`** _(170 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`ai.tsx`** _(81 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`browser.tsx`** _(203 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`editor.tsx`** _(1403 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`index.tsx`** _(3958 linhas)_
Ponto de entrada do React — monta o componente App na pagina HTML.

**`plugins.tsx`** _(1234 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`pwa.tsx`** _(625 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`settings.tsx`** _(1886 linhas)_
Componente de CONFIGURACOES — tela onde o usuario ajusta preferencias do app.

**`tasks.tsx`** _(522 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`terminal.tsx`** _(213 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `devmobile-fix/server/templates/`
> Pasta 'templates' — agrupamento de arquivos relacionados.

**`landing-page.html`** _(461 linhas)_
Arquivo HTML — parte do projeto.

---

### 📁 `artifacts/api-server/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`logger.ts`** _(21 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `artifacts/api-server/src/routes/`
> Definicao das URLs e navegacao do app.

**`ai-chat.ts`** _(125 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`ai-forward.ts`** _(156 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`config.ts`** _(27 linhas)_
Arquivo de CONSTANTES/CONFIGURACAO — valores fixos usados em varios lugares do projeto.

**`db.ts`** _(362 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`drive.ts`** _(108 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`exec.ts`** _(381 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`github.ts`** _(107 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`health.ts`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`index.ts`** _(39 linhas)_
Arquivo INDEX — ponto de entrada da pasta, exporta tudo que esta dentro.

**`legal-ai.ts`** _(328 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`pages.ts`** _(203 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`proxy.ts`** _(62 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`search.ts`** _(63 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`twa.ts`** _(618 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`upload.ts`** _(77 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`voice.ts`** _(88 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`workspace.ts`** _(318 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

---

### 📁 `artifacts/code-editor/.github/workflows/`
> Pasta 'workflows' — agrupamento de arquivos relacionados.

**`build-apk.yml`** _(295 linhas)_
Arquivo YML — parte do projeto.

**`deploy.yml`** _(38 linhas)_
Arquivo YML — parte do projeto.

---

### 📁 `artifacts/code-editor/dist-pronto/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`index-CszvMv4M.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`vendor-fs-BeamS8bA.js`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-highlight-Bu9o_ty_.js`** _(6 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-highlight-DOOs4slz.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`vendor-lucide-NZRTcJIq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-markdown-CM6-e2rl.js`** _(30 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-misc-COW7C1HQ.js`** _(4 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-monaco-CS9w1txC.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-react-D8m3Uig9.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-react-dom-CdNyEL3a.js`** _(10 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-webcontainer-BPoiPq3D.js`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-xterm-CT6HrMBF.js`** _(17 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-xterm-DDGTF8rc.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

---

### 📁 `artifacts/code-editor/dist-standalone/assets/`
> Arquivos estaticos: imagens, icones, fontes, arquivos publicos.

**`index-D5g-sV5e.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`vendor-fs-BeamS8bA.js`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-highlight-Bu9o_ty_.js`** _(6 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-highlight-DOOs4slz.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

**`vendor-lucide-NZRTcJIq.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-markdown-CM6-e2rl.js`** _(30 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-misc-COW7C1HQ.js`** _(4 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-monaco-CS9w1txC.js`** _(12 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-react-D8m3Uig9.js`** _(2 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-react-dom-CdNyEL3a.js`** _(10 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-webcontainer-BPoiPq3D.js`** _(3 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-xterm-CT6HrMBF.js`** _(17 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`vendor-xterm-DDGTF8rc.css`** _(2 linhas)_
Arquivo de estilos visuais — cores, tamanhos, fontes, espacamentos da interface.

---

### 📁 `artifacts/code-editor/src/components/`
> Pecas visuais reutilizaveis da interface (botoes, cards, formularios...).

**`AIChat.tsx`** _(2402 linhas)_
Componente de CHAT/MENSAGENS — interface de conversa em tempo real.

**`APKBuilderPanel.tsx`** _(536 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`AssistenteJuridico.tsx`** _(1286 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CampoLivre.tsx`** _(763 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`CodeEditor.tsx`** _(154 linhas)_
Componente EDITOR — area de edicao de texto, codigo ou conteudo rico.

**`CombinarApps.tsx`** _(359 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`DriveBackupPanel.tsx`** _(200 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`EditorLayout.tsx`** _(2842 linhas)_
Componente de LAYOUT — define a estrutura visual da pagina (cabecalho, sidebar, rodape). Envolve outros componentes.

**`FileTree.tsx`** _(400 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`GitHubPanel.tsx`** _(969 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Manual.tsx`** _(1783 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`PackageSearch.tsx`** _(415 linhas)_
Componente de BUSCA — campo e logica para filtrar/encontrar conteudo.

**`Preview.tsx`** _(496 linhas)_
Componente de PAGINA/TELA — representa uma tela completa navegavel no app.

**`QuickPrompt.tsx`** _(274 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`RealTerminal.tsx`** _(724 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`StreamTerminal.tsx`** _(594 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`SystemStatusPanel.tsx`** _(351 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`TemplateSelector.tsx`** _(589 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`Terminal.tsx`** _(1528 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VSCodeWebPanel.tsx`** _(314 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`VoiceCard.tsx`** _(427 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`VoiceMode.tsx`** _(277 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`WebContainerTerminal.tsx`** _(333 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

### 📁 `artifacts/code-editor/src/hooks/`
> Hooks React customizados — logica reutilizavel de estado e efeitos.

**`use-mobile.tsx`** _(20 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`use-toast.ts`** _(192 linhas)_
HOOK React personalizado para gerenciar estado/comportamento de '-toast'.

---

### 📁 `artifacts/code-editor/src/lib/`
> Funcoes auxiliares reutilizaveis em varios lugares do projeto.

**`ai-service.ts`** _(433 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`github-service.ts`** _(237 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`projects.ts`** _(206 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`store.ts`** _(38 linhas)_
STORE de estado — gerencia o estado global do app (dados compartilhados entre telas).

**`templates.ts`** _(4532 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`tts-service.ts`** _(312 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

**`utils.ts`** _(7 linhas)_
Funcoes UTILITARIAS — ferramentas reutilizaveis de uso geral no projeto.

**`virtual-fs.ts`** _(200 linhas)_
Arquivo TypeScript/JavaScript — logica, funcoes ou modulo do projeto.

**`zip-service.ts`** _(217 linhas)_
Arquivo de SERVICO/API — funcoes para comunicar com o servidor ou API externa.

---

### 📁 `artifacts/code-editor/src/components/ui/`
> Componentes de UI (interface) basicos e genericos.

**`accordion.tsx`** _(56 linhas)_
Componente ACCORDION — secoes que abrem/fecham ao clicar, economizando espaco na tela.

**`alert-dialog.tsx`** _(140 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`alert.tsx`** _(60 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`aspect-ratio.tsx`** _(6 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`avatar.tsx`** _(51 linhas)_
Componente AVATAR — foto ou iniciais do usuario em formato circular.

**`badge.tsx`** _(44 linhas)_
Componente BADGE (etiqueta) — pequeno indicador com numero ou status (ex: '3 novas mensagens').

**`breadcrumb.tsx`** _(116 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`button-group.tsx`** _(84 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`button.tsx`** _(66 linhas)_
Componente de BOTAO — elemento clicavel reutilizavel com estilo padrao do projeto.

**`calendar.tsx`** _(214 linhas)_
Componente CALENDARIO/AGENDA — visualizacao e selecao de datas e eventos.

**`card.tsx`** _(77 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`carousel.tsx`** _(261 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`chart.tsx`** _(368 linhas)_
Componente de GRAFICO — visualizacao de dados em forma de grafico (barras, linhas, pizza...).

**`checkbox.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`collapsible.tsx`** _(12 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`command.tsx`** _(154 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`context-menu.tsx`** _(199 linhas)_
CONTEXT do React — mecanismo para compartilhar dados entre componentes sem passar por props.

**`dialog.tsx`** _(121 linhas)_
Componente DIALOG — caixa de dialogo que exige resposta do usuario (confirmar, cancelar...).

**`drawer.tsx`** _(117 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`dropdown-menu.tsx`** _(202 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`empty.tsx`** _(105 linhas)_
Componente de ESTADO VAZIO — exibido quando nao ha dados para mostrar (ex: 'Nenhum resultado encontrado').

**`field.tsx`** _(245 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`form.tsx`** _(177 linhas)_
Componente de FORMULARIO — campos de entrada de dados (texto, selecao, etc.) com validacao.

**`hover-card.tsx`** _(28 linhas)_
Componente CARD (cartao) — exibe uma informacao em um bloco visual com borda e sombra. Muito usado para listas de items.

**`input-group.tsx`** _(169 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input-otp.tsx`** _(70 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`input.tsx`** _(23 linhas)_
Componente de CAMPO DE ENTRADA — elemento de input com estilo personalizado.

**`item.tsx`** _(194 linhas)_
Componente de ITEM — representa um elemento individual dentro de uma lista ou colecao.

**`kbd.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`label.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`menubar.tsx`** _(255 linhas)_
Componente de MENU/DROPDOWN — lista de opcoes que aparece ao clicar em um botao.

**`navigation-menu.tsx`** _(129 linhas)_
Componente de NAVEGACAO/CABECALHO — barra superior com logo, menu e links de navegacao.

**`pagination.tsx`** _(118 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`popover.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`progress.tsx`** _(29 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`radio-group.tsx`** _(43 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`resizable.tsx`** _(46 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`scroll-area.tsx`** _(47 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`select.tsx`** _(160 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`separator.tsx`** _(30 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sheet.tsx`** _(141 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sidebar.tsx`** _(728 linhas)_
Componente de BARRA LATERAL — menu ou painel que aparece na lateral da tela.

**`skeleton.tsx`** _(16 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`slider.tsx`** _(27 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`sonner.tsx`** _(32 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`spinner.tsx`** _(17 linhas)_
Componente de CARREGAMENTO — animacao visual que aparece enquanto dados estao sendo buscados.

**`switch.tsx`** _(28 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`table.tsx`** _(121 linhas)_
Componente de TABELA — exibe dados em linhas e colunas.

**`tabs.tsx`** _(54 linhas)_
Componente de ABAS — permite alternar entre diferentes secoes de conteudo com clique.

**`textarea.tsx`** _(23 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toast.tsx`** _(128 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toaster.tsx`** _(34 linhas)_
Componente de NOTIFICACAO/ALERTA — mensagem temporaria que aparece na tela (ex: 'Salvo com sucesso!').

**`toggle-group.tsx`** _(62 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`toggle.tsx`** _(44 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

**`tooltip.tsx`** _(33 linhas)_
Componente React — parte visual reutilizavel da interface do usuario.

---

## CONTEXTO PARA IA (copie e cole para continuar o projeto)

> Use este bloco para explicar o projeto para qualquer IA ou desenvolvedor:

```
Projeto: HTML/CSS/JS
Tipo: Aplicacao Web Frontend (React)
Stack: React, TypeScript
Arquivos: 329 | Linhas: ~107.146
Rotas API: 93 endpoint(s) detectado(s)
Variaveis de ambiente necessarias: LOG_LEVEL, DATABASE_URL, AI_INTEGRATIONS_OPENAI_BASE_URL, AI_INTEGRATIONS_OPENAI_API_KEY, PORT, ALLOWED_ORIGINS, JWT_SECRET, JWT_EXPIRES_IN, GROQ_API_KEY, OPENAI_API_KEY, GEMINI_API_KEY, ANTHROPIC_API_KEY, XAI_API_KEY, OPENROUTER_API_KEY, PERPLEXITY_API_KEY, TELEGRAM_TOKEN, BASE_PATH, REPL_ID, GROQ_MODEL, CLAUDE_MODEL, GEMINI_MODEL, EXPO_PUBLIC_DOMAIN, EXPO_PUBLIC_API_BASE_URL, EXPO_PUBLIC_REMOTE_API_URL, EXPO_PUBLIC_APP_MODE, EXPO_PUBLIC_API_STRATEGY, EXPO_PUBLIC_LOCAL_API_PORT, EXPO_PUBLIC_LOCAL_PREVIEW_PORT, EXPO_PUBLIC_ENABLE_TERMUX, EXPO_PUBLIC_ENABLE_REMOTE_AI, EXPO_PUBLIC_ENABLE_GITHUB, EXPO_PUBLIC_ENABLE_REMOTE_DB, EXPO_PUBLIC_ENABLE_REMOTE_TERMINAL, REPLIT_INTERNAL_APP_DOMAIN, REPLIT_DEV_DOMAIN, EXPO_PUBLIC_REPL_ID

Estrutura principal:
  .github/workflows/build-apk.yml
  .github/workflows/eas-build.yml
  .gitignore
  .replit-artifact/artifact.toml
  MANUAL-GERAR-APK.html
  README.md
  app.json
  app/(tabs)/_layout.tsx
  app/(tabs)/ai.tsx
  app/(tabs)/editor.tsx
  app/(tabs)/index.tsx
  app/(tabs)/plugins.tsx
  app/(tabs)/pwa.tsx
  app/(tabs)/settings.tsx
  app/(tabs)/tasks.tsx
  app/(tabs)/terminal.tsx
  app/(tabs)/tree.tsx
  app/+not-found.tsx
  app/_layout.tsx
  artifacts/api-server/.replit-artifact/artifact.toml
  artifacts/api-server/build.mjs
  artifacts/api-server/package.json
  artifacts/api-server/pty_helper.c
  artifacts/api-server/src/app.ts
  artifacts/api-server/src/index.ts
  artifacts/api-server/src/lib/logger.ts
  artifacts/api-server/src/routes/ai-chat.ts
  artifacts/api-server/src/routes/ai-forward.ts
  artifacts/api-server/src/routes/config.ts
  artifacts/api-server/src/routes/db.ts
  artifacts/api-server/src/routes/drive.ts
  artifacts/api-server/src/routes/exec.ts
  artifacts/api-server/src/routes/github.ts
  artifacts/api-server/src/routes/health.ts
  artifacts/api-server/src/routes/index.ts
  artifacts/api-server/src/routes/legal-ai.ts
  artifacts/api-server/src/routes/pages.ts
  artifacts/api-server/src/routes/proxy.ts
  artifacts/api-server/src/routes/search.ts
  artifacts/api-server/src/routes/twa.ts
  artifacts/api-server/src/routes/upload.ts
  artifacts/api-server/src/routes/voice.ts
  artifacts/api-server/src/routes/workspace.ts
  artifacts/api-server/tsconfig.json
  artifacts/code-editor/.github/workflows/build-apk.yml
  artifacts/code-editor/.github/workflows/deploy.yml
  artifacts/code-editor/.replit-artifact/artifact.toml
  artifacts/code-editor/INSTALAR.md
  artifacts/code-editor/SYSTEM_DOCS.md
  artifacts/code-editor/components.json
  artifacts/code-editor/dist-pronto/MANUAL-SK-CODE-EDITOR.md
  artifacts/code-editor/dist-pronto/assets/index-CszvMv4M.css
  artifacts/code-editor/dist-pronto/assets/vendor-fs-BeamS8bA.js
  artifacts/code-editor/dist-pronto/assets/vendor-highlight-Bu9o_ty_.js
  artifacts/code-editor/dist-pronto/assets/vendor-highlight-DOOs4slz.css
  artifacts/code-editor/dist-pronto/assets/vendor-lucide-NZRTcJIq.js
  artifacts/code-editor/dist-pronto/assets/vendor-markdown-CM6-e2rl.js
  artifacts/code-editor/dist-pronto/assets/vendor-misc-COW7C1HQ.js
  artifacts/code-editor/dist-pronto/assets/vendor-monaco-CS9w1txC.js
  artifacts/code-editor/dist-pronto/assets/vendor-react-D8m3Uig9.js
  artifacts/code-editor/dist-pronto/assets/vendor-react-dom-CdNyEL3a.js
  artifacts/code-editor/dist-pronto/assets/vendor-webcontainer-BPoiPq3D.js
  artifacts/code-editor/dist-pronto/assets/vendor-xterm-CT6HrMBF.js
  artifacts/code-editor/dist-pronto/assets/vendor-xterm-DDGTF8rc.css
  artifacts/code-editor/dist-pronto/favicon.svg
  artifacts/code-editor/dist-pronto/guia-completo-apk.md
  artifacts/code-editor/dist-pronto/index.html
  artifacts/code-editor/dist-pronto/manifest.json
  artifacts/code-editor/dist-pronto/manual-dev.md
  artifacts/code-editor/dist-pronto/sw.js
  artifacts/code-editor/dist-standalone/LEIA-ME-PARA-PROGRAMADOR.md
  artifacts/code-editor/dist-standalone/MANUAL-SK-CODE-EDITOR.md
  artifacts/code-editor/dist-standalone/assets/index-D5g-sV5e.css
  artifacts/code-editor/dist-standalone/assets/vendor-fs-BeamS8bA.js
  artifacts/code-editor/dist-standalone/assets/vendor-highlight-Bu9o_ty_.js
  artifacts/code-editor/dist-standalone/assets/vendor-highlight-DOOs4slz.css
  artifacts/code-editor/dist-standalone/assets/vendor-lucide-NZRTcJIq.js
  artifacts/code-editor/dist-standalone/assets/vendor-markdown-CM6-e2rl.js
  artifacts/code-editor/dist-standalone/assets/vendor-misc-COW7C1HQ.js
  artifacts/code-editor/dist-standalone/assets/vendor-monaco-CS9w1txC.js
  artifacts/code-editor/dist-standalone/assets/vendor-react-D8m3Uig9.js
  artifacts/code-editor/dist-standalone/assets/vendor-react-dom-CdNyEL3a.js
  artifacts/code-editor/dist-standalone/assets/vendor-webcontainer-BPoiPq3D.js
  artifacts/code-editor/dist-standalone/assets/vendor-xterm-CT6HrMBF.js
  artifacts/code-editor/dist-standalone/assets/vendor-xterm-DDGTF8rc.css
  artifacts/code-editor/dist-standalone/favicon.svg
  artifacts/code-editor/dist-standalone/guia-completo-apk.md
  artifacts/code-editor/dist-standalone/index.html
  artifacts/code-editor/dist-standalone/manifest.json
  artifacts/code-editor/dist-standalone/manual-dev.md
  artifacts/code-editor/dist-standalone/sw.js
  artifacts/code-editor/index.html
  artifacts/code-editor/package-standalone.json
  artifacts/code-editor/package.json
  artifacts/code-editor/public/MANUAL-SK-CODE-EDITOR.md
  artifacts/code-editor/public/favicon.svg
  artifacts/code-editor/public/guia-completo-apk.md
  artifacts/code-editor/public/manifest.json
  artifacts/code-editor/public/manual-dev.md
  artifacts/code-editor/public/sw.js
  artifacts/code-editor/src/App.tsx
  artifacts/code-editor/src/components/AIChat.tsx
  artifacts/code-editor/src/components/APKBuilderPanel.tsx
  artifacts/code-editor/src/components/AssistenteJuridico.tsx
  artifacts/code-editor/src/components/CampoLivre.tsx
  artifacts/code-editor/src/components/CodeEditor.tsx
  artifacts/code-editor/src/components/CombinarApps.tsx
  artifacts/code-editor/src/components/DriveBackupPanel.tsx
  artifacts/code-editor/src/components/EditorLayout.tsx
  artifacts/code-editor/src/components/FileTree.tsx
  artifacts/code-editor/src/components/GitHubPanel.tsx
  artifacts/code-editor/src/components/Manual.tsx
  artifacts/code-editor/src/components/PackageSearch.tsx
  artifacts/code-editor/src/components/Preview.tsx
  artifacts/code-editor/src/components/QuickPrompt.tsx
  artifacts/code-editor/src/components/RealTerminal.tsx
  artifacts/code-editor/src/components/StreamTerminal.tsx
  artifacts/code-editor/src/components/SystemStatusPanel.tsx
  artifacts/code-editor/src/components/TemplateSelector.tsx
  artifacts/code-editor/src/components/Terminal.tsx
  artifacts/code-editor/src/components/VSCodeWebPanel.tsx
  artifacts/code-editor/src/components/VoiceCard.tsx
  artifacts/code-editor/src/components/VoiceMode.tsx
  artifacts/code-editor/src/components/WebContainerTerminal.tsx
  artifacts/code-editor/src/components/ui/accordion.tsx
  artifacts/code-editor/src/components/ui/alert-dialog.tsx
  artifacts/code-editor/src/components/ui/alert.tsx
  artifacts/code-editor/src/components/ui/aspect-ratio.tsx
  artifacts/code-editor/src/components/ui/avatar.tsx
  artifacts/code-editor/src/components/ui/badge.tsx
  artifacts/code-editor/src/components/ui/breadcrumb.tsx
  artifacts/code-editor/src/components/ui/button-group.tsx
  artifacts/code-editor/src/components/ui/button.tsx
  artifacts/code-editor/src/components/ui/calendar.tsx
  artifacts/code-editor/src/components/ui/card.tsx
  artifacts/code-editor/src/components/ui/carousel.tsx
  artifacts/code-editor/src/components/ui/chart.tsx
  artifacts/code-editor/src/components/ui/checkbox.tsx
  artifacts/code-editor/src/components/ui/collapsible.tsx
  artifacts/code-editor/src/components/ui/command.tsx
  artifacts/code-editor/src/components/ui/context-menu.tsx
  artifacts/code-editor/src/components/ui/dialog.tsx
  artifacts/code-editor/src/components/ui/drawer.tsx
  artifacts/code-editor/src/components/ui/dropdown-menu.tsx
  artifacts/code-editor/src/components/ui/empty.tsx
  artifacts/code-editor/src/components/ui/field.tsx
  artifacts/code-editor/src/components/ui/form.tsx
  artifacts/code-editor/src/components/ui/hover-card.tsx
  artifacts/code-editor/src/components/ui/input-group.tsx
  artifacts/code-editor/src/components/ui/input-otp.tsx
  artifacts/code-editor/src/components/ui/input.tsx
  artifacts/code-editor/src/components/ui/item.tsx
  artifacts/code-editor/src/components/ui/kbd.tsx
  artifacts/code-editor/src/components/ui/label.tsx
  artifacts/code-editor/src/components/ui/menubar.tsx
  artifacts/code-editor/src/components/ui/navigation-menu.tsx
  artifacts/code-editor/src/components/ui/pagination.tsx
  artifacts/code-editor/src/components/ui/popover.tsx
  artifacts/code-editor/src/components/ui/progress.tsx
  artifacts/code-editor/src/components/ui/radio-group.tsx
  artifacts/code-editor/src/components/ui/resizable.tsx
  artifacts/code-editor/src/components/ui/scroll-area.tsx
  artifacts/code-editor/src/components/ui/select.tsx
  artifacts/code-editor/src/components/ui/separator.tsx
  artifacts/code-editor/src/components/ui/sheet.tsx
  artifacts/code-editor/src/components/ui/sidebar.tsx
  artifacts/code-editor/src/components/ui/skeleton.tsx
  artifacts/code-editor/src/components/ui/slider.tsx
  artifacts/code-editor/src/components/ui/sonner.tsx
  artifacts/code-editor/src/components/ui/spinner.tsx
  artifacts/code-editor/src/components/ui/switch.tsx
  artifacts/code-editor/src/components/ui/table.tsx
  artifacts/code-editor/src/components/ui/tabs.tsx
  artifacts/code-editor/src/components/ui/textarea.tsx
  artifacts/code-editor/src/components/ui/toast.tsx
  artifacts/code-editor/src/components/ui/toaster.tsx
  artifacts/code-editor/src/components/ui/toggle-group.tsx
  artifacts/code-editor/src/components/ui/toggle.tsx
  artifacts/code-editor/src/components/ui/tooltip.tsx
  artifacts/code-editor/src/hooks/use-mobile.tsx
  artifacts/code-editor/src/hooks/use-toast.ts
  artifacts/code-editor/src/index.css
  artifacts/code-editor/src/lib/ai-service.ts
  artifacts/code-editor/src/lib/github-service.ts
  artifacts/code-editor/src/lib/projects.ts
  artifacts/code-editor/src/lib/store.ts
  artifacts/code-editor/src/lib/templates.ts
  artifacts/code-editor/src/lib/tts-service.ts
  artifacts/code-editor/src/lib/utils.ts
  artifacts/code-editor/src/lib/virtual-fs.ts
  artifacts/code-editor/src/lib/zip-service.ts
  artifacts/code-editor/src/main.tsx
  artifacts/code-editor/tsconfig.json
  artifacts/code-editor/vite.config.standalone.ts
  artifacts/code-editor/vite.config.ts
  babel.config.js
  components/AIChat.tsx
  components/AIMemoryModal.tsx
  components/APKBuilderModal.tsx
  components/CampoLivreModal.tsx
  components/CheckpointsModal.tsx
  components/CodeEditor.tsx
  components/CombinarAppsModal.tsx
  components/ErrorBoundary.tsx
  components/ErrorFallback.tsx
  components/FileSidebar.tsx
  components/FloatingAI.tsx
  components/GitHubModal.tsx
  components/HtmlPlayground.tsx
  components/KeyboardAwareScrollViewCompat.tsx
  components/LibrarySearch.tsx
  components/ManualModal.tsx
  components/MessageRenderer.tsx
  components/MonacoEditor.tsx
  components/PreviewPanel.tsx
  components/ProjectOverviewModal.tsx
  components/ProjectPlanModal.tsx
  components/SystemStatus.tsx
  components/TasksPanel.tsx
  components/Terminal.tsx
  components/VSCodeView.tsx
  components/VSCodeWebModal.tsx
  components/VoiceAssistant.tsx
  constants/colors.ts
  context/AppContext.tsx
  data/featuredProjects.ts
  devmobile-fix/.easignore
  devmobile-fix/.env
  devmobile-fix/.env.example
  devmobile-fix/.github/workflows/build-apk-eas.yml
  devmobile-fix/.github/workflows/build-apk-local.yml
  devmobile-fix/.gitignore
  devmobile-fix/.npmrc
  devmobile-fix/.replit-artifact/artifact.toml
  devmobile-fix/COMO-BUILDAR-APK.md
  devmobile-fix/COMO_BUILDAR.md
  devmobile-fix/GERAR-APK.md
  devmobile-fix/PLANO.md
  devmobile-fix/app.json
  devmobile-fix/app/(tabs)/_layout.tsx
  devmobile-fix/app/(tabs)/ai.tsx
  devmobile-fix/app/(tabs)/browser.tsx
  devmobile-fix/app/(tabs)/editor.tsx
  devmobile-fix/app/(tabs)/index.tsx
  devmobile-fix/app/(tabs)/plugins.tsx
  devmobile-fix/app/(tabs)/pwa.tsx
  devmobile-fix/app/(tabs)/settings.tsx
  devmobile-fix/app/(tabs)/tasks.tsx
  devmobile-fix/app/(tabs)/terminal.tsx
  devmobile-fix/app/+not-found.tsx
  devmobile-fix/app/_layout.tsx
  devmobile-fix/babel.config.js
  devmobile-fix/capacitor.config.ts
  devmobile-fix/components/AIChat.tsx
  devmobile-fix/components/AIMemoryModal.tsx
  devmobile-fix/components/APKBuilderModal.tsx
  devmobile-fix/components/CampoLivreModal.tsx
  devmobile-fix/components/CheckpointsModal.tsx
  devmobile-fix/components/CodeEditor.tsx
  devmobile-fix/components/CombinarAppsModal.tsx
  devmobile-fix/components/DatabasePanel.tsx
  devmobile-fix/components/ErrorBoundary.tsx
  devmobile-fix/components/ErrorFallback.tsx
  devmobile-fix/components/FileSidebar.tsx
  devmobile-fix/components/FloatingAI.tsx
  devmobile-fix/components/GitHubModal.tsx
  devmobile-fix/components/HtmlPlayground.tsx
  devmobile-fix/components/KeyboardAwareScrollViewCompat.tsx
  devmobile-fix/components/LibrarySearch.tsx
  devmobile-fix/components/ManualModal.tsx
  devmobile-fix/components/MessageRenderer.tsx
  devmobile-fix/components/MonacoEditor.tsx
  devmobile-fix/components/PreviewPanel.tsx
  devmobile-fix/components/ProjectOverviewModal.tsx
  devmobile-fix/components/ProjectPlanModal.tsx
  devmobile-fix/components/SystemStatus.tsx
  devmobile-fix/components/Terminal.tsx
  devmobile-fix/components/VSCodeView.tsx
  devmobile-fix/components/VSCodeWebModal.tsx
  devmobile-fix/components/VoiceAssistant.tsx
  devmobile-fix/components/XTermWebView.tsx
  devmobile-fix/constants/colors.ts
  devmobile-fix/context/AppContext.tsx
  devmobile-fix/data/featuredProjects.ts
  devmobile-fix/eas.json
  devmobile-fix/expo-env.d.ts
  devmobile-fix/hooks/useApiBase.ts
  devmobile-fix/hooks/useColors.ts
  devmobile-fix/metro.config.js
  devmobile-fix/package.json
  devmobile-fix/plugins/withTermuxIntent.js
  devmobile-fix/server/serve.js
  devmobile-fix/server/templates/landing-page.html
  devmobile-fix/services/apiBase.ts
  devmobile-fix/services/githubService.ts
  devmobile-fix/services/localSQLite.ts
  devmobile-fix/services/previewService.ts
  devmobile-fix/services/runtimeMode.ts
  devmobile-fix/services/storageService.ts
  devmobile-fix/services/terminalService.ts
  devmobile-fix/tsconfig.json
  devmobile-fix/utils/projectPlan.ts
  devmobile-fix/utils/zipUtils.ts
  eas.json
  expo-env.d.ts
  hooks/useApiBase.ts
  hooks/useColors.ts
  lib/androidBuilder.ts
  lib/archiveApk.ts
  lib/eas.ts
  lib/githubApk.ts
  manifest.webmanifest
  metro.config.js
  package.json
  pnpm-workspace.yaml
  scripts/build.js
  server/serve.js
  server/templates/landing-page.html
  services/apiBase.ts
  services/githubService.ts
  services/localSQLite.ts
  services/previewService.ts
  services/runtimeMode.ts
  services/storageService.ts
  services/terminalService.ts
  sw.js
  tsconfig.json
  utils/projectPlan.ts
  utils/zipUtils.ts
```

---

*Plano gerado pelo SK Code Editor — 18/06/2026, 23:43:30*