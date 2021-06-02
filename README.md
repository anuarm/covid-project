# vue 3 base

Proyecto con configuracion base para los proyectos de

## Architecture

```text
├─ public           // static assets.
├─ service          // commands and webpack configurations.
├─ src
│  ├─ assets        // assets such as images or font files.
│  ├─ components    // universal Vue components.
│  │  ├─ atoms      // atoms.
│  │  ├─ molecules  // molecules.
│  │  ├─ organisms  // organisms.
│  │  └─ templates  // templates.
│  ├─ router        // view's routers config.
│  ├─ store         // Vuex store modules.
│  └─ typings       // typescript .d.ts files.
```

## Commands

```bash
# Start development server.
npm run dev

# Compile production bundle.
npm run build
```
