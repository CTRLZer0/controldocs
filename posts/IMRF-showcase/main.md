---
title: "The IMRF Engine Showcase"
date: "2025-12-22"
authors: ["CTRLZer0"]
tags: ["IMRF", "Showcase", "Features"]
cover: "https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?q=80&w=2564&auto=format&fit=crop"
description: "A comprehensive demonstration of the Interactive Markdown Rendering Framework (IMRF) capabilities."
---

# Introduction

Welcome to the **IMRF Showcase**. This document is rendered entirely using our custom engine. It demonstrates the specialized "Liquid Glass" typography and components available to documentation authors.

## Typography

The engine automatically styles standard Markdown elements to match the CtrlZeroDev aesthetic.

### Headers
Headers are automatically graded in size and color. H1s have a gradient, H2s feature a subtle underline.

*   This is a list item
*   Another list item
    *   ested item

1.  Ordered List
2.  Second Item

> **Blockquotes** look like this. They are perfect for calling out important information or quotes. They feature a glass-like background and a cyan accent border.

## Custom Components

We have exposed specific React components to Markdown via MDX.

### Alerts
Use alerts to highlight critical info.

<Alert>
  <AlertTitle>Heads Up!</AlertTitle>
  <AlertDescription>
    This is a custom `Alert` component directly embedded in Markdown.
  </AlertDescription>
</Alert>

### Cards
Cards can be used to group information.

<Card>
    <CardHeader>
        <CardTitle>Feature Card</CardTitle>
    </CardHeader>
    <CardContent>
        <p>This content lives inside a glassmorphic card container.</p>
    </CardContent>
</Card>

## Code & Syntax

Inline code looks like `this`.

Block code gets a specialized terminal-like container:

```typescript
// Example TypeScript Code
interface User {
  id: string;
  name: string;
}

function greet(user: User) {
  console.log(`Hello, ${user.name}`);
}
```

## Images

Images are rendered with rounded corners and subtle borders.

![Cyberpunk City](https://images.unsplash.com/photo-1545152594-b258679cb737?auto=format&fit=crop&w=1000&q=80)
*Caption: Images automatically fit the width of the container.*

---

## Conclusion

The IMRF engine allows for mixing **rich content** with **interactive components**, all while maintaining a consistent, high-end visual style.
