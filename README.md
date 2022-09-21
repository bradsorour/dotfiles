# dotfiles

A repository to store my dotfiles and associated configuration. It targets macOS.

## Install

```
$ bash -c "$(curl -#fL raw.github.com/bradsorour/dotfiles/main/install.sh)"
```

## Testing

Testing the install can be done by running it in an interactive Docker container:
```
docker run -it ubuntu
```

Install curl:
```
apt-get update; apt-get install curl
```

Run the install script:

```
bash -c "$(curl -#fL raw.github.com/bradsorour/dotfiles/main/install.sh)"
```

***

## Resources

- [Make your dotfiles portable with Git and a simple Bash script](https://freddiecarthy.com/blog/make-your-dotfiles-portable-with-git-and-a-simple-bash-script)

- [Use Git and Bash to automate your developer tooling](https://freddiecarthy.com/blog/use-git-and-bash-to-automate-your-developer-tooling)
