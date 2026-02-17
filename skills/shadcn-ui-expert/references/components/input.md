# Input

Displays a form input field or a component that looks like an input field.

- **Install**: `npx shadcn@latest add input`
- **Docs**: https://ui.shadcn.com/docs/components/input

## Import

```tsx
import { Input } from "@/components/ui/input"
```

## Variants

> **6 variants available.** Ask the user which variant they need before providing code.

- Default
- Disabled
- File
- With Button
- With Label
- With Text

## Default

```tsx
import { Input } from "@/components/ui/input"

export default function InputDemo() {
  return <Input type="email" placeholder="Email" />
}

```

## Disabled

```tsx
import { Input } from "@/components/ui/input"

export default function InputDisabled() {
  return <Input disabled type="email" placeholder="Email" />
}

```

## File

```tsx
import { Input } from "@/components/ui/input"
import { Label } from "@/components/ui/label"

export default function InputFile() {
  return (
    <div className="grid w-full max-w-sm items-center gap-3">
      <Label htmlFor="picture">Picture</Label>
      <Input id="picture" type="file" />
    </div>
  )
}

```

## With Button

```tsx
import { Button } from "@/components/ui/button"
import { Input } from "@/components/ui/input"

export default function InputWithButton() {
  return (
    <div className="flex w-full max-w-sm items-center gap-2">
      <Input type="email" placeholder="Email" />
      <Button type="submit" variant="outline">
        Subscribe
      </Button>
    </div>
  )
}

```

## With Label

```tsx
import { Input } from "@/components/ui/input"
import { Label } from "@/components/ui/label"

export default function InputWithLabel() {
  return (
    <div className="grid w-full max-w-sm items-center gap-3">
      <Label htmlFor="email">Email</Label>
      <Input type="email" id="email" placeholder="Email" />
    </div>
  )
}

```

## With Text

```tsx
import { Input } from "@/components/ui/input"
import { Label } from "@/components/ui/label"

export default function InputWithText() {
  return (
    <div className="grid w-full max-w-sm items-center gap-3">
      <Label htmlFor="email-2">Email</Label>
      <Input type="email" id="email-2" placeholder="Email" />
      <p className="text-muted-foreground text-sm">Enter your email address.</p>
    </div>
  )
}

```

