[user]
	email = eric.ferreira@luizalabs.com
	name = Eric Ferreira
[diff]
	tool = vscode
[difftool "vscode"]
	cmd = "code --wait --diff  "
[core]
	editor = code --wait
[push]
	followTags = true
[alias]
	s = !git status -s
	c = !git add --all && git commit -m
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
	t = !sh -c 'git tag -a $1 -m $1' -
