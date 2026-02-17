# Skeleton

Use to show a placeholder while content is loading.

- **Install**: `npx shadcn@latest add skeleton`
- **Docs**: https://ui.shadcn.com/docs/components/skeleton

## Import

```tsx
import { Skeleton } from "@/components/ui/skeleton"
```

## Variants

> **2 variants available.** Ask the user which variant they need before providing code.

- Default
- Card

## Default

```tsx
import { Skeleton } from "@/components/ui/skeleton"

export default function SkeletonDemo() {
  return (
    <div className="flex items-center space-x-4">
      <Skeleton className="h-12 w-12 rounded-full" />
      <div className="space-y-2">
        <Skeleton className="h-4 w-[250px]" />
        <Skeleton className="h-4 w-[200px]" />
      </div>
    </div>
  )
}

```

## Card

```tsx
import { Skeleton } from "@/components/ui/skeleton"

export default function SkeletonCard() {
  return (
    <div className="flex flex-col space-y-3">
      <Skeleton className="h-[125px] w-[250px] rounded-xl" />
      <div className="space-y-2">
        <Skeleton className="h-4 w-[250px]" />
        <Skeleton className="h-4 w-[200px]" />
      </div>
    </div>
  )
}

```

