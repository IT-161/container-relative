# Interactive Notification Workspace

This project demonstrates modern responsive CSS using **Container Queries** and the **`:has()` pseudo-class**.

## Features

* Uses `container-type: inline-size` to create container contexts.
* Uses `@container (min-width: 500px)` to change notification cards from a stacked layout to a horizontal layout based on their container size.
* Uses `:has()` to detect when the Archive checkbox is selected and visually dim the archived card.
* Uses identical card HTML in both the sidebar and main content area.
* Uses **no JavaScript** and **no viewport `@media` queries** for card responsiveness.

## Files

* `index.html` — Contains the semantic structure of the notification workspace.
* `styles.css` — Contains the layout, container query, and state-aware styling.
