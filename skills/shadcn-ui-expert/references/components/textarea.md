# Textarea

Displays a form textarea or a component that looks like a textarea.

- **Install**: `npx shadcn@latest add textarea`
- **Docs**: https://ui.shadcn.com/docs/components/textarea

## Import

```tsx
import { Textarea } from "@/components/ui/textarea"
```

## Variants

> **5 variants available.** Ask the user which variant they need before providing code.

- Default
- Disabled
- With Button
- With Label
- With Text

## Default

```tsx
import { Textarea } from "@/components/ui/textarea"

export default function TextareaDemo() {
  return <Textarea placeholder="Type your message here." />
}

```

## Disabled

```tsx
import { Textarea } from "@/components/ui/textarea"

export default function TextareaDisabled() {
  return <Textarea placeholder="Type your message here." disabled />
}

```

## With Button

```tsx
import { Button } from "@/components/ui/button"
import { Textarea } from "@/components/ui/textarea"

export default function TextareaWithButton() {
  return (
    <div className="grid w-full gap-2">
      <Textarea placeholder="Type your message here." />
      <Button>Send message</Button>
    </div>
  )
}

```

## With Label

```tsx
import { Label } from "@/components/ui/label"
import { Textarea } from "@/components/ui/textarea"

export default function TextareaWithLabel() {
  return (
    <div className="grid w-full gap-3">
      <Label htmlFor="message">Your message</Label>
      <Textarea placeholder="Type your message here." id="message" />
    </div>
  )
}

```

## With Text

```tsx
import { Label } from "@/components/ui/label"
import { Textarea } from "@/components/ui/textarea"

export default function TextareaWithText() {
  return (
    <div className="grid w-full gap-3">
      <Label htmlFor="message-2">Your Message</Label>
      <Textarea placeholder="Type your message here." id="message-2" />
      <p className="text-muted-foreground text-sm">
        Your message will be copied to the support team.
      </p>
    </div>
  )
}

```

