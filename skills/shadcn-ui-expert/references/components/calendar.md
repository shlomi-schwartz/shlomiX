# Calendar

A date field component that allows users to enter and edit date.

- **Install**: `npx shadcn@latest add calendar`
- **Docs**: https://ui.shadcn.com/docs/components/calendar

## Import

```tsx
import { Calendar } from "@/components/ui/calendar"
```

## Default

```tsx
"use client"

import * as React from "react"

import { Calendar } from "@/components/ui/calendar"

export default function CalendarDemo() {
  const [date, setDate] = React.useState<Date | undefined>(new Date())

  return (
    <Calendar
      mode="single"
      selected={date}
      onSelect={setDate}
      className="rounded-md border shadow-sm"
      captionLayout="dropdown"
    />
  )
}

```

