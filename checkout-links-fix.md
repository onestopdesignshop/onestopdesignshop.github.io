# Checkout Link Fix — One Stop Design Shop

Your buy buttons currently point to fake placeholder URLs (slugs like
`checkout/buy/cosmos-icon-set`) instead of Lemon Squeezy’s real UUID-based
checkout links. That’s why clicking “Buy” 404s.

## How to apply this fix

1. Open your repo on GitHub: `onestopdesignshop`
1. Tap into `index.html`
1. Tap the pencil/edit icon (or “Edit this file”)
1. Use Find (your browser’s find-in-page, or GitHub’s search) to locate each
   OLD line below
1. Replace it with the matching NEW line
1. Scroll to the bottom, tap “Commit changes”

There are 5 replacements total — one per product.

-----

### 1. Cosmos Icon Set

**Find:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/cosmos-icon-set"
```

**Replace with:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/05bd93ad-abfb-4079-81c4-795eb627cf61"
```

-----

### 2. Social Media Kit

**Find:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/social-media-kit"
```

**Replace with:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/b1b44503-090c-49ea-a356-1c6af5308dd5"
```

-----

### 3. Pro Color Palettes

**Find:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/pro-color-palettes"
```

**Replace with:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/ff13fbf3-87ea-4e3d-8ede-a7c92eb22c28"
```

-----

### 4. UI Component Snippets

**Find:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/ui-component-snippets"
```

**Replace with:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/325cf1e8-b013-4981-9efb-68688bcbfd9b"
```

-----

### 5. Full Bundle

**Find:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/full-bundle"
```

**Replace with:**

```
href="https://onestopdesignshop.lemonsqueezy.com/checkout/buy/59a59fec-94b2-44b9-abc6-787ae1112e1c"
```

-----

## After committing

Re-test each button live on your actual site (not just the raw link) to
confirm it now lands on a real Lemon Squeezy checkout page instead of a 404.

Remember: your Lemon Squeezy store is also still in **test mode**, pending
their account review. These link fixes make checkout *reachable* — actual
real-money payments will only process once that review clears.