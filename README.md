# 🧠 Programmable Arithmetic Node Editor

A visual drag-and-drop interface to build custom arithmetic logic using **Input**, **Function**, and **Output** nodes.  
Users can connect nodes to create a live-running data flow system — like a simplified version of Blender Geometry Nodes or Unreal Blueprints.

---

### 🚀 Features

- 🔢 Drag and drop **Input**, **Function**, and **Output** nodes
- 🔗 Connect nodes visually with animated connectors
- ✍️ Write custom JavaScript logic inside function nodes
- ⚡ Real-time execution — outputs update instantly
- 🎨 Modern UI with neon-glow effects
- 💻 100% Frontend — Runs directly in browser

---

### 🧩 Node Types

| Node | Description |
|------|-------------|
| 🔢 Input Node | User enters numeric values |
| 🧠 Function Node | Runs custom JavaScript on connected inputs |
| 📤 Output Node | Displays final computed result |

Example function code:

```js
// Sum of inputs
inputs.reduce((a, b) => a + b, 0);
