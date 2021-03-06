# Homebrew Script for OSX

To execute: save and `chmod +x ./macInstall.sh` then `./macInstall.sh`

## Backups

Don't be dumb, backup all this shit before you format or you will regret it.

Don't forget to save/export:

- Enpass export
- Sequel pro connections
- Remote desktop connections
- SSH keys
- Transmit connections
- VS code settings.json

## Other Installs

- Xcode - `xcode-select --install`
- [Github Desktop](https://desktop.github.com)
- [How to Install Ruby on Mac OS X with RVM](https://usabilityetc.com/articles/ruby-on-mac-os-x-with-rvm/) (see following)

```
brew install gnupg
gpg --keyserver hkp://pool.sks-keyservers.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
\curl -sSL https://get.rvm.io | bash -s stable --ruby
```

## VS Code Extensions

- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [Git File History](https://marketplace.visualstudio.com/items?itemName=pomber.git-file-history)
- [GitLens — Git supercharged](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Markdown Preview Github Styling](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-preview-github-styles)
- [One Dark Pro](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [TODO Highlight](https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight)
- [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree)
- [Version Lens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)
- [VS Code Styled Components](https://marketplace.visualstudio.com/items?itemName=jpoissonnier.vscode-styled-components)
- [WordPress Snippets](https://marketplace.visualstudio.com/items?itemName=wordpresstoolbox.wordpress-toolbox)
- [Workspace Switcher](https://marketplace.visualstudio.com/items?itemName=sadesyllas.vscode-workspace-switcher)

## Props

This setup script was built referencing ideas from:

- https://github.com/marceloglacial/macos-fresh-install
- https://github.com/maxyermayank/developer-mac-setup

## Git Push Issues

```
git remote -v ; git remote remove origin
git remote add origin git@github.com:troychaplin79/repo.git
```

If issues persiste, also run `git push --set-upstream origin master`
