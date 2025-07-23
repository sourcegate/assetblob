# 🧱 AssetBlob

A lightweight asset repository for publicly serving static UI assets like icons and illustrations — fast, free, and CDN-backed.

Hosted on GitHub. Delivered via [jsDelivr](https://www.jsdelivr.com/).

---

## 🚀 How to Use

You can hotlink to any file in this repo using jsDelivr CDN.

### ✅ Basic Usage

```
https://cdn.jsdelivr.net/gh/sourcegate/assetblob/<path>
```

Example for the Bell icon:

```html
<img src="https://cdn.jsdelivr.net/gh/sourcegate/assetblob/images/icons/Bell.png" alt="Bell Icon" />
```

---

### 📌 Pin to a Specific Version (for production)

For caching and reliability in production, lock to a commit:

```
https://cdn.jsdelivr.net/gh/sourcegate/assetblob@<commit>/<path>
```

Example:

```html
<img src="https://cdn.jsdelivr.net/gh/sourcegate/assetblob@a01b232/images/icons/Bell.png" />
```

Find the commit hash in GitHub’s file view (e.g., `a01b232`) and replace accordingly.

---

## 📁 Folder Structure

Organized by usage:

```
images/
├── icons/
│   ├── Bell.png
│   ├── Billing.png
│   └── Client.png
├── Contract Status.png
├── Dashboards.png
├── Intake Form.png
└── Project Workspace.png
```

Use clean, lowercase file naming when possible. Avoid spaces if integrating programmatically.

---

## 🧩 Best Practices

- Optimize assets for web use (e.g., SVG, WebP, PNG).
- Keep file sizes minimal — avoid large media.
- Organize into folders like `icons/`, `ui/`, `logos/`, etc.
- Version-pinning is strongly encouraged for production reliability.

---

## 🛠 Sample Use Cases

### In HTML

```html
<img src="https://cdn.jsdelivr.net/gh/sourcegate/assetblob/images/icons/Client.png" />
```

### In CSS

```css
background-image: url('https://cdn.jsdelivr.net/gh/sourcegate/assetblob/images/icons/Client.png');
```

### In Markdown

```markdown
![Client](https://cdn.jsdelivr.net/gh/sourcegate/assetblob/images/icons/Client.png)
```

---

## 🙌 Maintainer

Built and maintained by [@sourcegate](https://github.com/sourcegate).  
CDN powered by [jsDelivr](https://www.jsdelivr.com/).

---

## 🧠 Pro Tip

You can explore this repo visually by pasting this in your browser:

```
https://cdn.jsdelivr.net/gh/sourcegate/assetblob/
```

Just append file paths to preview anything live.
