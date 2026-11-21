# Set up your Minecraft-inspired GitHub profile

1. On GitHub, create a **public repository named exactly `Thurnos`** under the `Thurnos` account. Add a README when creating it.
2. Download this ZIP, extract it, and upload the included **README.md**, the entire **assets/** folder, and **.github/workflows/snake.yml** to the root of your `Thurnos` repository. You must preserve the folder paths. Commit to your default branch.
3. Visit `https://github.com/Thurnos` to see the redesigned profile.
4. To activate the contribution snake, open `Thurnos/Thurnos` -> **Actions** -> **Generate contribution snake** -> **Run workflow**.
5. After the workflow completes, the snake image will be published to the `output` branch. Reload your profile.

### Important notes
- The `assets/overworld-banner.svg` and `assets/pixel-divider.svg` images are **original block-inspired pixel art** and don't require an external image host. The PNG in `assets/` is just a preview and isn't required in the GitHub repository.
- Third-party icons and animated statistics rely on their external services being available.
- Customize project descriptions/tech areas to reflect what you actually use. The Minecraft modding section is marked as an interest/exploration.
- If the GitHub Actions workflow can't publish, check **Settings > Actions > General > Workflow permissions**, allow **Read and write permissions** for `GITHUB_TOKEN` if required, save, and rerun.
- The profile README only displays when the repository is public, named exactly the same as your GitHub username, and contains a README at its root.
