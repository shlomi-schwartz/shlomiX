# Label

Renders an accessible label associated with controls.

- **Install**: `npx shadcn@latest add label`
- **Docs**: https://ui.shadcn.com/docs/components/label

## Import

```tsx
import { Label } from "@/components/ui/label"
```

## Default

```tsx
import { Checkbox } from "@/components/ui/checkbox"
import { Label } from "@/components/ui/label"

export default function LabelDemo() {
  return (
    <div>
      <div className="flex items-center space-x-2">
        <Checkbox id="terms" />
        <Label htmlFor="terms">Accept terms and conditions</Label>
      </div>
    </div>
  )
}

```

