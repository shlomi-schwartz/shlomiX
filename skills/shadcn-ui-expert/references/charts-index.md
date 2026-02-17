# shadcn/ui Chart Reference

All charts use [Recharts](https://recharts.org/) with shadcn/ui theming via the `<ChartContainer>` wrapper.

**Install**: `npx shadcn@latest add chart`

| Chart Type | Variants | File |
|------------|----------|------|
| [Area Chart](charts/area.md) | 10 | charts/area.md |
| [Bar Chart](charts/bar.md) | 10 | charts/bar.md |
| [Line Chart](charts/line.md) | 10 | charts/line.md |
| [Pie Chart](charts/pie.md) | 11 | charts/pie.md |
| [Radar Chart](charts/radar.md) | 14 | charts/radar.md |
| [Radial Chart](charts/radial.md) | 6 | charts/radial.md |
| [Chart Tooltip](charts/tooltip.md) | 9 | charts/tooltip.md |

## Chart Types

### [Area Chart](charts/area.md)

Area charts show quantitative data graphically with filled areas under lines. Built on top of Recharts AreaChart.

**Variants:** Default, Linear, Step, Stacked, Stacked Expanded, Legend, Icons, Gradient, Axes, Interactive

### [Bar Chart](charts/bar.md)

Bar charts display categorical data with rectangular bars. Built on top of Recharts BarChart.

**Variants:** Default, Horizontal, Multiple, Stacked, Label, Custom Label, Mixed, Active, Negative, Interactive

### [Line Chart](charts/line.md)

Line charts display data points connected by straight line segments. Built on top of Recharts LineChart.

**Variants:** Default, Linear, Step, Multiple, Dots, Custom Dots, Dots Colors, Label, Custom Label, Interactive

### [Pie Chart](charts/pie.md)

Pie charts display data as proportional segments of a circle. Built on top of Recharts PieChart.

**Variants:** Simple, Label, Custom Label, Label List, Legend, Donut, Donut Active, Donut with Text, Stacked, No Separator, Interactive

### [Radar Chart](charts/radar.md)

Radar charts display multivariate data on a two-dimensional chart. Built on top of Recharts RadarChart.

**Variants:** Default, Dots, Multiple, Lines Only, Legend, Icons, Custom Label, Radius Axis, Grid Circle, Grid Circle Filled, Grid Circle No Lines, Grid Fill, Grid None, Grid Custom

### [Radial Chart](charts/radial.md)

Radial charts display data in a circular layout. Built on top of Recharts RadialBarChart.

**Variants:** Simple, Label, Grid, Text, Shape, Stacked

### [Chart Tooltip](charts/tooltip.md)

Customizable tooltip component for Recharts charts. Shows data on hover.

**Variants:** Default, Line Indicator, No Indicator, No Label, Custom Label, Label Formatter, Formatter, Icons, Advanced

