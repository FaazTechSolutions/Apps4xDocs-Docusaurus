---
sidebar_position : 4
---

# Chart

In Apps4x, you can display data visually using charts. The system supports different chart types such as line, column, area, spline, and pie.

## Chart Setup Guidelines

  - You can configure a chart to show summarized data using values like labels and numbers.

  - The data must follow a simple format with:
    - A label (e.g., New, In Progress)
    - A value (e.g., number of records)

  Example data format:

> New – 498  
> In Progress – 20

## Single vs. Multiple Charts

  - Most charts, like pie charts, only support one chart per form.

  - Some chart types, like column, line, area, and spline, can be combined together in the same view. These combinations help compare trends or show multiple values side-by-side.

### Allowed Chart Combinations

You can create multiple charts only with the following types, and in any combination:

  - Line
  - Column
  - Area
  - Spline

For example:

  - A line and column chart together
  - A column, area, and spline combination
  - Any mix of the above types

### Not Supported for Multiple Charts

  - Pie charts and a few other chart types do not support multiple charts in one view.

    - [Configuration](../../docs/Forms/Configuration/Configuration.md)
    
    - [Chart](../../docs/Forms/Chart.md)
  
    - [Data Source](../../docs/Forms/DataSource/DataSource.md)