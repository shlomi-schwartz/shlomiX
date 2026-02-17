# Switch

A control that allows the user to toggle between checked and not checked.

- **Install**: `npx shadcn@latest add switch`
- **Docs**: https://ui.shadcn.com/docs/components/switch

## Import

```tsx
import { Switch } from "@/components/ui/switch"
```

## Default

```tsx
import { Label } from "@/components/ui/label"
import { Switch } from "@/components/ui/switch"

export default function SwitchDemo() {
  return (
    <div className="flex items-center space-x-2">
      <Switch id="airplane-mode" />
      <Label htmlFor="airplane-mode">Airplane Mode</Label>
    </div>
  )
}

```

