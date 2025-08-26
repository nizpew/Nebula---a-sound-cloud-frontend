

# 📌 Nebula

**PT:** Nebula é um cliente desktop moderno para **SoundCloud**, construído com **Electron**.
Oferece uma experiência limpa e polida, com AdBlock nativo e login via navegador, funcionando em **Linux, Windows e macOS**.

**EN:** Nebula is a modern desktop client for **SoundCloud**, built with **Electron**.
It provides a clean and polished experience, with native AdBlock and browser-based login, running on **Linux, Windows, and macOS**.

---

## Funcionalidades / Features

**PT:**

* AdBlock nativo para bloquear anúncios do SoundCloud
* Login externo usando navegador padrão do usuário
* Janela elegante, sem scroll lateral
* Tray system para acesso rápido às funções do app
* Cross-platform: Linux, Windows, macOS
* AppImage (Linux) e instalador (Windows) para fácil distribuição

**EN:**

* Native AdBlock for blocking SoundCloud ads
* External login using the user's default browser
* Polished window, no side scroll bar
* System tray for quick access to app functions
* Cross-platform: Linux, Windows, macOS
* AppImage (Linux) and installer (Windows) for easy distribution

---

## Instalação / Installation

**PT (Linux)**

```bash
pnpm install
pnpm start
pnpm run dist
chmod +x dist/Nebula-1.0.0.AppImage
./dist/Nebula-1.0.0.AppImage --no-sandbox
```

**EN (Windows)**

```bash
pnpm install
pnpm start
pnpm run dist
# Execute the generated installer
```

---

## Uso / Usage

**PT:**

* Clique no tray para abrir o menu:

  * Show Nebula
  * Login with Google
  * Quit
* Navegação: role usando mouse ou trackpad, sem scroll lateral visível

**EN:**

* Click the tray icon to open menu:

  * Show Nebula
  * Login with Google
  * Quit
* Navigation: scroll using mouse or trackpad, no visible side scroll

---

## Contribuição / Contributing

**PT:** Pull requests são bem-vindos!
**EN:** Pull requests are welcome!




Inspo: https://github.com/th-ch/youtube-music
