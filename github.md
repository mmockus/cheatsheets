# Github Cheatsheet

## Connect via SSH

<https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh>

## Create SSH

`ssh-keygen -t keyname -C "your_email@example.com"`

## Load SSH key

```
$ eval "$(ssh-agent -s)"
> Agent pid 59566
```

## How to view SSH

`ls ~/.ssh/`
`cat ~/.ssh/id_rsa.pub`