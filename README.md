# JumpStone GitHub-Skylines

Here you can find all the 3D printing files for my GitHub Skylines.

I recommend downloading the files from [Releases](https://github.com/JumpStone/my-github-skylines/releases), although you can also find them in the [main branch](https://github.com/JumpStone/my-github-skylines/tree/main).

### Years

- [2025](2025/README.md)

Want to create your own GitHub Skyline? Check out the [GitHub Skyline Generator](https://skyline.github.com/).

I created these using the GitHub CLI with the following commands:

First, [install the GitHub CLI](https://cli.github.com/). Then, run this command to install the Skyline extension:

```bash
gh extension install github/gh-skyline
```

After that, run the following command to generate your own Skyline:

```bash
gh skyline --user <your-github-username> --year <your-year>
```

Replace `<your-github-username>` with your GitHub username and `<your-year>` with the desired year. The generated Skyline will be saved as an STL file in your current directory.
