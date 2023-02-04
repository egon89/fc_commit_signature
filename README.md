# Commands

```
gpg --full-generate-key

gpg --list-secret-key --keyid-form=long

gpg --armor --export <id>

git config --global user.signingkey <id>

[ -f ~/.bashrc ] && echo 'export GPG_TTY=$(tty)' >> ~/.bashrc
```

or edit vim ~/.bashrc

## Only current repository
```
git config commit.gpgsign true
```
