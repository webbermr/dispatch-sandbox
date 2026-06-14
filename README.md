# Dispatch Sandbox

A minimal static HTML project used as a simple sandbox page.

## Overview

This repository currently contains a single `index.html` file. The page renders a basic heading:

```text
Hello Charlie and Baxter
```

There is no build system, package manager, framework, or runtime dependency required.

## Project Structure

```text
.
├── index.html
└── README.md
```

## Running Locally

Open `index.html` directly in a browser:

```sh
open index.html
```

Or serve the directory with a lightweight local server:

```sh
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Development

Edit `index.html` to change the page content. Since this is a plain static page, refreshing the browser is enough to see updates.
