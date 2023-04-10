#README.md

## Download the `.gitignore` file from GitHub using `curl`

1. Open a terminal window and navigate to the root directory of your new project.

```console
cd /{root directory}
```

2. Use the `curl` command to download the `.gitignore` file and save it to your project directory.

```console
curl -o .gitignore https://raw.githubusercontent.com/renderedghost/ignorant-git/main/.gitignore
```

3. Check that the `.gitignore` file is saved in the project root by running the List command in the directory.

```console
ls
```

4. Add then commit the `.gitignore` file to the project's repository, then push to the main branch.

```console
git add .
git commit -m "added .gitignore"
git push origin main
```

The `.gitignore` file is now ready to use.
