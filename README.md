# Interactive Notification Workspace

## Overview

This project demonstrates modern CSS using **Container Queries** and the **`:has()` selector**. The notification cards adapt based on the size of their individual containers rather than the browser window.

## Features

- Uses `container-type: inline-size` to create container contexts.
- Cards stack vertically in narrow containers.
- Cards switch to a horizontal layout at `500px` using `@container`.
- Uses `:has()` to detect when the **Archive** checkbox is selected.
- Archived cards automatically change appearance.
- Uses no JavaScript or viewport-based `@media` queries for card sizing.

## How to Run

Open `index.html` in a web browser or view the project through its GitHub Pages link.

## AI Assistance

AI was used to help generate and organize the CSS based on the assignment requirements, including the container query and `:has()` state styling.