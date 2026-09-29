# Week 2 Budget Tracker Upgrade

This project is an upgraded version of the Budget Tracker web page created for Week 2. It introduces structured tables, enhanced form controls, embedded media, interactive HTML tags, and advanced CSS selectors.

## Key Features Added

1. **Structured Expense Table**: 
   - Uses proper `<table>`, `<thead>`, `<tbody>`, `<th>`, and `<td>` tags.
   - Contains 5 pre-populated expense entries.
   - Formatted using `border-collapse: collapse`, cell padding, custom header colors, and alternating row background colors via `:nth-child(even)`.

2. **Upgraded Form**:
   - Replaced basic category input with a `<select>` dropdown menu containing 5 options (*Food*, *Transport*, *Rent*, *Entertainment*, *Other*).
   - Wrapped inside a `<form>` element.
   - Included a `<button type="button">` with `cursor: pointer`.
   - Explicit `id` attributes added to all form inputs (`expense-name`, `expense-amount`, `expense-category`, `expense-date`).

3. **Multimedia Content**:
   - Logo image (`<img>`) near the main title with defined `alt` and `width` attributes.
   - Embedded budgeting video using an `<iframe>` with `width`, `height`, `title`, and `frameborder` attributes.

4. **Interactive Elements**:
   - Collapsible `<details>` and `<summary>` element providing instructions on how to use the tracker.
   - Hover effects (`:hover`) on table rows to highlight data.

5. **Advanced CSS Selectors Implemented**:
   - **Descendant Selector**: `.expenses-section td`
   - **Direct Child Selector**: `.add-expense-section > h2`
   - **Position Pseudo-Class**: `.expense-table tbody tr:nth-child(even)`
   - **Focus State Selector**: `input:focus, select:focus`
   - **Negation Pseudo-Class**: `input:not([type="submit"])`
