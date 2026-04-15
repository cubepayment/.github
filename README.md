# 🚧 CubePay — We've Moved

<p align="center">
  <svg width="100%" height="220" viewBox="0 0 800 220" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="grad" x1="0" x2="1" y1="0" y2="1">
        <stop offset="0%" stop-color="#2563eb"/>
        <stop offset="100%" stop-color="#06b6d4"/>
      </linearGradient>
    </defs>

    <!-- Background -->
    <rect width="800" height="220" rx="16" fill="#0f172a"/>

    <!-- Left (Old) -->
    <rect x="80" y="70" width="140" height="80" rx="10" fill="#1e293b"/>
    <text x="150" y="115" text-anchor="middle" fill="#94a3b8" font-size="14" font-family="Arial, sans-serif">
      cubepayment
    </text>

    <!-- Right (New) -->
    <rect x="580" y="70" width="140" height="80" rx="10" fill="url(#grad)"/>
    <text x="650" y="115" text-anchor="middle" fill="white" font-size="14" font-family="Arial, sans-serif">
      cubepay
    </text>

    <!-- Arrow -->
    <path d="M240 110 L560 110" stroke="url(#grad)" stroke-width="4" marker-end="url(#arrow)"/>

    <!-- Arrowhead -->
    <defs>
      <marker id="arrow" markerWidth="10" markerHeight="10" refX="6" refY="3" orient="auto">
        <path d="M0,0 L0,6 L9,3 z" fill="#06b6d4"/>
      </marker>
    </defs>

    <!-- Title -->
    <text x="400" y="50" text-anchor="middle" fill="white" font-size="20" font-family="Arial, sans-serif">
      Repository Moved
    </text>
  </svg>
</p>

> 👋 You’ve landed on our **legacy GitHub organization (`cubepayment`)**

---

## 👉 Go here instead

### 🚀 https://github.com/cubepay

This is our **official and actively maintained** GitHub organization.

---

## 🧭 What happened?

We’ve consolidated all development, packages, and documentation into a single org:

- Cleaner structure  
- Active maintenance  
- Better developer support  

This organization is retained only to:
- prevent namespace / brand misuse  
- preserve legacy links  
- redirect developers to the correct source  

---

## ⚠️ Important

- ❌ No active development here  
- ❌ Issues / PRs are not monitored  
- ❌ Repositories may be outdated or deprecated  

If you are using code from this org, you should migrate.

---

## 🔧 Update your setup

```bash
git remote set-url origin https://github.com/cubepay/<repo>