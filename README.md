# HueHint

**HueHint** enhances code readability by **colorizing comments based on intent**. It brings visual structure and emphasis to your comments, making it easier to spot alerts, questions, TODOs, and more — all without modifying the underlying code.

---

## ✨ Features

HueHint automatically highlights specially formatted comments with distinct colors:

### Supported Comment Types

| Prefix      | Meaning           | Example                      |
|-------------|-------------------|------------------------------|
| `//!`       | **Alert**         | `//! Watch out for overflow` |
| `//?`       | **Question**      | `//? Should we refactor this?` |
| `//.`       | **Silent Comment**| `//. Internal logic`         |
| `//~`       | **Insight**       | `//~ Derived from equation 2` |
| `//+`       | **Add Note**      | `//+ Consider edge cases`    |
| `// TODO`   | **Task Reminder** | `// TODO: Clean this up`     |

HueHint makes your comments **easier to scan**, helping you focus on what matters most.

---

## 📦 Requirements


No additional dependencies are required.

---

## ⚙️ Extension Settings

Currently, HueHint does not expose any user-configurable settings. Future releases may include customization for:

- Custom prefix definitions
- Theme color overrides
- Toggle individual highlight types

---

## 🐞 Known Issues

- HueHint uses regex-based matching. Unusual comment formats or edge cases may be highlighted inconsistently.
- Might not render as expected in themes with conflicting comment styling.

Please report issues or feature requests via the [GitHub repository](https://github.com/YourName/huehint/issues).

---

## 📘 Release Notes

### 1.0.0

- Initial release of HueHint
- Supports 6 comment types with color highlighting

---

**Enjoy using HueHint! Make your comments count.** 🎨
