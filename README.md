# Deployment

```
chezmoi init https://github.com/BFang-Overflow/dotfiles.git
```

Check what changes that chezmoi will make to your home directory by running:
```
chezmoi diff
```
If you are happy with the changes that chezmoi will make then run:
```
chezmoi apply -v
```
If you are not happy with the changes to a file then either edit it with:
```
chezmoi edit $FILE
```
