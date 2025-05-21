# My VS Code Extensions

List of the extensions I use.

-   [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
-   [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
-   [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
-   [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
-   [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-   [file-icons](https://marketplace.visualstudio.com/items?itemName=file-icons.file-icons)
-   [Folder Size](https://marketplace.visualstudio.com/items?itemName=xiaoluoboding.vscode-folder-size)
-   [Git Blame](https://marketplace.visualstudio.com/items?itemName=waderyan.gitblame)
-   [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
-   [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
-   [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
-   [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
-   [Lorem Picsum photos](https://marketplace.visualstudio.com/items?itemName=huang-an-sheng.lorem-picsum-photos-snippets)
-   [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
-   [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
-   [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
-   [Svg Preview](https://marketplace.visualstudio.com/items?itemName=SimonSiefke.svg-preview)
-   [vscode-json](https://marketplace.visualstudio.com/items?itemName=andyyaldoo.vscode-json)
-   [Bear Theme](https://marketplace.visualstudio.com/items?itemName=dahong.theme-bear)
-   [Dark Lemon](https://marketplace.visualstudio.com/items?itemName=lucafluri.dark-lemon)
-   [Daybreak](https://marketplace.visualstudio.com/items?itemName=mtdmali.daybreak-theme)
-   [Monokai Pro](https://marketplace.visualstudio.com/items?itemName=monokai.theme-monokai-pro-vscode)
-   [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
-   [morgan.codes-theme](https://marketplace.visualstudio.com/items?itemName=morgan-codes.morgan-codes-vscode-theme)
-   [Date & Time](https://marketplace.visualstudio.com/items?itemName=rid9.datetime)
-   [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
-   [Thunder Client](https://marketplace.visualstudio.com/items?itemName=rangav.vscode-thunder-client)

<hr/>

My setting for **indent-rainbow**:

```
"indentRainbow.includedLanguages": [
    "html",
    "sass",
    "scss",
    "css"
],
"indentRainbow.colors": [
"rgba(0,0,0,0.07)",
"rgba(29,29,29,0.07)",
"rgba(47,47,47,0.07)",
"rgba(71,71,71,0.07)",
"rgba(95,95,95,0.07)",
"rgba(119,119,119,0.07)",
"rgba(142,142,142,0.07)",
"rgba(166,166,166,0.07)",
"rgba(190,190,190,0.07)",
"rgba(214,214,214,0.07)",
"rgba(238,238,238,0.07)"
],
```

Looks good with [Dark Lemon](https://marketplace.visualstudio.com/items?itemName=lucafluri.dark-lemon) theme 👍

### UPDATE 2025. Extension package names

```
beardedbear.beardedicons
aaron-bond.better-comments
catppuccin.catppuccin-vsc
catppuccin.catppuccin-vsc-icons
streetsidesoftware.code-spell-checker
ratismal.copy-filename-from-menu
mikestead.dotenv
janisdd.vscode-edit-csv
dbaeumer.vscode-eslint
mkxml.vscode-filesize
waderyan.gitblame
mhutchie.git-graph
ambooth.git-rename
eamodio.gitlens
wix.vscode-import-cost
kjhx.vscode-lifeline
ddiu8081.moegi-theme
esbenp.prettier-vscode
yoavbls.pretty-ts-errors
kevinwolfcr.vscode-quiet-canvas
chrisburgin95.quills
burkeholland.simple-react-snippets
joeberria.statusbarerror
svelte.svelte-vscode
simonsiefke.svg-preview
gruntfuggly.todo-tree
danielgjackson.auto-dark-mode-windows
shardulm94.trailing-spaces
antfu.theme-vitesse
codeium.codeium
using.theme-zen
```

Steps for quick installation:

1. save as `vs-ext.txt` or whatever you want :)

```
nano vs-ext.txt
```

2. then open terminal and put this line:

```
cat vs-ext.txt | xargs -L1 code --install-extension
```

3. enjoy 🎉
