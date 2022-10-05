```bash 
code --list-extensions
```
```
bradlc.vscode-tailwindcss
dbaeumer.vscode-eslint
dsznajder.es7-react-js-snippets
ecmel.vscode-html-css
kumar-harsh.graphql-for-vscode
mikestead.dotenv
ms-azuretools.vscode-docker
naumovs.color-highlight
PKief.material-icon-theme
Prisma.prisma
riazxrazor.html-to-jsx
rickynormandeau.mariana-pro
ritwickdey.LiveServer
shd101wyy.markdown-preview-enhanced
vincaslt.highlight-matching-tag
WallabyJs.quokka-vscode
Zignd.html-css-class-completion
```

#### install command
```
while read line; do code --install-extension "$line";done <vs-code-exstensions.txt
```
or
```
You can run the Following and it will install all line of the vs-code-exstensions.txt all
xargs -L1 code --install-exstension <vs-code-exstensions.txt
```