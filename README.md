# clementfernando.github.io

Personal bio site built with Jekyll and hosted on GitHub Pages.

## Development

This project uses a [Dev Container](https://containers.dev/) for a consistent development environment with Ruby 3.3.4 and the `github-pages` gem pre-installed.

### Prerequisites

- [Docker](https://www.docker.com/get-started)
- [VS Code](https://code.visualstudio.com/) with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### Getting started

1. Open the project in VS Code.
2. When prompted, click **Reopen in Container** (or run the command **Dev Containers: Reopen in Container** from the Command Palette).
3. Wait for the container to build and `bundle install` to finish.
4. Start the Jekyll dev server:
   ```sh
   bundle exec jekyll serve --livereload
   ```
5. Open [http://localhost:4000](http://localhost:4000) in your browser.
