# Badge

Displays a badge or a component that looks like a badge.

- **Install**: `npx shadcn@latest add badge`
- **Docs**: https://ui.shadcn.com/docs/components/badge

## Import

```tsx
import { Badge } from "@/components/ui/badge"
```

## Variants

> **4 variants available.** Ask the user which variant they need before providing code.

- Default
- Secondary
- Outline
- Destructive

## Default

```tsx
import { AlertCircleIcon, BadgeCheckIcon, CheckIcon } from "lucide-react"

import { Badge } from "@/components/ui/badge"

export default function BadgeDemo() {
  return (
    <div className="flex flex-col items-center gap-2">
      <div className="flex w-full flex-wrap gap-2">
        <Badge>Badge</Badge>
        <Badge variant="secondary">Secondary</Badge>
        <Badge variant="destructive">Destructive</Badge>
        <Badge variant="outline">Outline</Badge>
      </div>
      <div className="flex w-full flex-wrap gap-2">
        <Badge
          variant="secondary"
          className="bg-blue-500 text-white dark:bg-blue-600"
        >
          <BadgeCheckIcon />
          Verified
        </Badge>
        <Badge className="h-5 min-w-5 rounded-full px-1 font-mono tabular-nums">
          8
        </Badge>
        <Badge
          className="h-5 min-w-5 rounded-full px-1 font-mono tabular-nums"
          variant="destructive"
        >
          99
        </Badge>
        <Badge
          className="h-5 min-w-5 rounded-full px-1 font-mono tabular-nums"
          variant="outline"
        >
          20+
        </Badge>
      </div>
    </div>
  )
}

```

## Secondary

```tsx
import { Badge } from "@/components/ui/badge"

export default function BadgeSecondary() {
  return <Badge variant="secondary">Secondary</Badge>
}

```

## Outline

```tsx
import { Badge } from "@/components/ui/badge"

export default function BadgeOutline() {
  return <Badge variant="outline">Outline</Badge>
}

```

## Destructive

```tsx
import { Badge } from "@/components/ui/badge"

export default function BadgeDestructive() {
  return <Badge variant="destructive">Destructive</Badge>
}

```

