## Hi there 👋

### 🛠️ Commands

```bash
rails new [project_name] --css=tailwind --database=postgresql
```

### 🎨 CSS Snippets

#### Turbo Frame Debug

```css
.debug {
  turbo-frame {
    border: 1px dashed red;
    display: block;

    &::before {
      content: "Frame #" attr(id) " src=" attr(src) " loading=" attr(loading);
      font-size: 0.75rem;
      padding: 0.25rem;
      border: 1px dashed red;
      background: white;
    }
  }
}
```

#### Button Cursor Fix

```css
@layer base {
  button:not(:disabled),
  [role="button"]:not(:disabled) {
    cursor: pointer;
  }
}
```

<!--
**JalenYan/JalenYan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
