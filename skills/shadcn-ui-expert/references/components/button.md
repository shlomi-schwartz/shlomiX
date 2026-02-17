# Button

Displays a button or a component that looks like a button.

- **Install**: `npx shadcn@latest add button`
- **Docs**: https://ui.shadcn.com/docs/components/button

## Import

```tsx
import { Button } from "@/components/ui/button"
```

## Variants

> **10 variants available.** Ask the user which variant they need before providing code.

- Default
- Secondary
- Destructive
- Outline
- Ghost
- Link
- Icon
- With Icon
- Loading
- As Child

## Default

```tsx
import { ArrowUpIcon } from "lucide-react"

import { Button } from "@/components/ui/button"

export default function ButtonDemo() {
  return (
    <div className="flex flex-wrap items-center gap-2 md:flex-row">
      <Button variant="outline">Button</Button>
      <Button variant="outline" size="icon" aria-label="Submit">
        <ArrowUpIcon />
      </Button>
    </div>
  )
}

```

## Secondary

```tsx
import { Button } from "@/components/ui/button"

export default function ButtonSecondary() {
  return <Button variant="secondary">Secondary</Button>
}

```

## Destructive

```tsx
import { Button } from "@/components/ui/button"

export default function ButtonDestructive() {
  return <Button variant="destructive">Destructive</Button>
}

```

## Outline

```tsx
import { Button } from "@/components/ui/button"

export default function ButtonOutline() {
  return <Button variant="outline">Outline</Button>
}

```

## Ghost

```tsx
import { Button } from "@/components/ui/button"

export default function ButtonGhost() {
  return <Button variant="ghost">Ghost</Button>
}

```

## Link

```tsx
import { Button } from "@/components/ui/button"

export default function ButtonLink() {
  return <Button variant="link">Link</Button>
}

```

## Icon

```tsx
import { CircleFadingArrowUpIcon } from "lucide-react"

import { Button } from "@/components/ui/button"

export default function ButtonIcon() {
  return (
    <Button variant="outline" size="icon">
      <CircleFadingArrowUpIcon />
    </Button>
  )
}

```

## With Icon

```tsx
import { IconGitBranch } from "@tabler/icons-react"

import { Button } from "@/components/ui/button"

export default function ButtonWithIcon() {
  return (
    <Button variant="outline" size="sm">
      <IconGitBranch /> New Branch
    </Button>
  )
}

```

## Loading

```tsx
import { Button } from "@/components/ui/button"
import { Spinner } from "@/components/ui/spinner"

export default function ButtonLoading() {
  return (
    <Button size="sm" variant="outline" disabled>
      <Spinner />
      Submit
    </Button>
  )
}

```

## As Child

```tsx
import Link from "next/link"

import { Button } from "@/components/ui/button"

export default function ButtonAsChild() {
  return (
    <Button asChild>
      <Link href="/login">Login</Link>
    </Button>
  )
}

```

