# 🗂️ @robert.tools/molecule-link

A component to provide links.

## 📜 Usage

### 🟢 Installation

```bash
npm install @robert.tools/molecule-link
```

### 📝 Sample usage

#### prerequisites

- define css variables
- filter: `safe` and `url`are default filter
- dependant components: `@robert.tools/atom-text`

#### Template

Use the link component as shown below:

```html
{{ component("molecule/link", {}) }}
```

#### CSS

Use the basic styling

```css
@import '@robert.tools/molecule-link/src/index.css';
```

#### TypeScript

Include TypeScript by importing the link component

```typescript
import * as MoleculeLink from '@robert.tools/molecule-link';
```

## ⚖️ Notes

This software is hand-crafted, test-driven and assisted by AI tools. I know each
line of my code. ✌️

| Tool | Comment |
| --- | --- |
| ![assisted by Jest](https://img.shields.io/badge/Jest-TDD-008800?logo=jest) | Test-driven development with Jest |
| ![assisted by robert.tools](https://img.shields.io/badge/robert.tools-ecosystem-008800) | Part of the robert.tools ecosystem |
| ![assisted by GitHub Copilot](https://img.shields.io/badge/GitHub_Copilot-assisted-8A2BE2?logo=githubcopilot) | Code completion |
| ![assisted by OpenAI](https://img.shields.io/badge/OpenAI-assisted-8A2BE2?logo=openai) | chatGPT research |
