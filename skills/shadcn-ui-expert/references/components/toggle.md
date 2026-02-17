# Toggle

A two-state button that can be either on or off.

- **Install**: `npx shadcn@latest add toggle`
- **Docs**: https://ui.shadcn.com/docs/components/toggle

## Import

```tsx
import { Toggle } from "@/components/ui/toggle"
```

## Variants

> **6 variants available.** Ask the user which variant they need before providing code.

- Default
- Outline
- With Text
- Sm
- Lg
- Disabled

## Default

```tsx
import { BookmarkIcon } from "lucide-react"

import { Toggle } from "@/components/ui/toggle"

export default function ToggleDemo() {
  return (
    <Toggle
      aria-label="Toggle bookmark"
      size="sm"
      variant="outline"
      className="data-[state=on]:bg-transparent data-[state=on]:*:[svg]:fill-blue-500 data-[state=on]:*:[svg]:stroke-blue-500"
    >
      <BookmarkIcon />
      Bookmark
    </Toggle>
  )
}

```

## Outline

```tsx
import { Italic } from "lucide-react"

import { Toggle } from "@/components/ui/toggle"

export default function ToggleOutline() {
  return (
    <Toggle variant="outline" aria-label="Toggle italic">
      <Italic />
    </Toggle>
  )
}

```

## With Text

```tsx
import { Italic } from "lucide-react"

import { Toggle } from "@/components/ui/toggle"

export default function ToggleWithText() {
  return (
    <Toggle aria-label="Toggle italic">
      <Italic />
      Italic
    </Toggle>
  )
}

```

## Sm

```tsx
import { Italic } from "lucide-react"

import { Toggle } from "@/components/ui/toggle"

export default function ToggleSm() {
  return (
    <Toggle size="sm" aria-label="Toggle italic">
      <Italic />
    </Toggle>
  )
}

```

## Lg

```tsx
import { Italic } from "lucide-react"

import { Toggle } from "@/components/ui/toggle"

export default function ToggleLg() {
  return (
    <Toggle size="lg" aria-label="Toggle italic">
      <Italic />
    </Toggle>
  )
}

```

## Disabled

```tsx
import { Underline } from "lucide-react"

import { Toggle } from "@/components/ui/toggle"

export default function ToggleDisabled() {
  return (
    <Toggle aria-label="Toggle italic" disabled>
      <Underline className="h-4 w-4" />
    </Toggle>
  )
}

```

