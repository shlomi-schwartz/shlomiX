# Separator

Visually or semantically separates content.

- **Install**: `npx shadcn@latest add separator`
- **Docs**: https://ui.shadcn.com/docs/components/separator

## Import

```tsx
import { Separator } from "@/components/ui/separator"
```

## Default

```tsx
import { Separator } from "@/components/ui/separator"

export default function SeparatorDemo() {
  return (
    <div>
      <div className="space-y-1">
        <h4 className="text-sm leading-none font-medium">Radix Primitives</h4>
        <p className="text-muted-foreground text-sm">
          An open-source UI component library.
        </p>
      </div>
      <Separator className="my-4" />
      <div className="flex h-5 items-center space-x-4 text-sm">
        <div>Blog</div>
        <Separator orientation="vertical" />
        <div>Docs</div>
        <Separator orientation="vertical" />
        <div>Source</div>
      </div>
    </div>
  )
}

```

