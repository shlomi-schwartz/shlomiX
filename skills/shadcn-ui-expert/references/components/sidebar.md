# Sidebar

A composable, themeable and customizable sidebar component.

- **Install**: `npx shadcn@latest add sidebar`
- **Docs**: https://ui.shadcn.com/docs/components/sidebar

## Usage

The Sidebar component is highly composable. See the [Sidebar documentation](https://ui.shadcn.com/docs/components/sidebar) for full usage examples including:

- SidebarProvider and SidebarTrigger setup
- SidebarMenu, SidebarMenuItem, SidebarMenuButton
- Collapsible groups and submenus
- Multiple sidebar variants (floating, inset, icon)

```tsx
import {
  Sidebar,
  SidebarContent,
  SidebarFooter,
  SidebarGroup,
  SidebarHeader,
  SidebarProvider,
  SidebarTrigger,
} from "@/components/ui/sidebar"

export function AppSidebar() {
  return (
    <SidebarProvider>
      <Sidebar>
        <SidebarHeader />
        <SidebarContent>
          <SidebarGroup />
        </SidebarContent>
        <SidebarFooter />
      </Sidebar>
      <main>
        <SidebarTrigger />
      </main>
    </SidebarProvider>
  )
}
```
