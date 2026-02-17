# Radio Group

A set of checkable buttons — known as radio buttons — where no more than one of the buttons can be checked at a time.

- **Install**: `npx shadcn@latest add radio-group`
- **Docs**: https://ui.shadcn.com/docs/components/radio-group

## Import

```tsx
import {
  RadioGroup,
  RadioGroupItem,
} from "@/components/ui/radio-group"
```

## Default

```tsx
import { Label } from "@/components/ui/label"
import {
  RadioGroup,
  RadioGroupItem,
} from "@/components/ui/radio-group"

export default function RadioGroupDemo() {
  return (
    <RadioGroup defaultValue="comfortable">
      <div className="flex items-center gap-3">
        <RadioGroupItem value="default" id="r1" />
        <Label htmlFor="r1">Default</Label>
      </div>
      <div className="flex items-center gap-3">
        <RadioGroupItem value="comfortable" id="r2" />
        <Label htmlFor="r2">Comfortable</Label>
      </div>
      <div className="flex items-center gap-3">
        <RadioGroupItem value="compact" id="r3" />
        <Label htmlFor="r3">Compact</Label>
      </div>
    </RadioGroup>
  )
}

```

