# gh-command-manual
gh-command-manual



## Istall
```shell
type -p curl >/dev/null || (sudo apt update && sudo apt install curl -y)
curl -fsSL https://cli.github.com/packages/githubcli-archive-keyring.gpg | sudo dd of=/usr/share/keyrings/githubcli-archive-keyring.gpg \
&& sudo chmod go+r /usr/share/keyrings/githubcli-archive-keyring.gpg \
&& echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/githubcli-archive-keyring.gpg] https://cli.github.com/packages stable main" | sudo tee /etc/apt/sources.list.d/github-cli.list > /dev/null \
&& sudo apt update \
&& sudo apt install gh -y
```


## Auth
```shell
gh auth login
```



# nvm
```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
```

```shell
source ~/.bashrc
```

```shell
nvm install stable
```



# golang

```shell
wget https://go.dev/dl/go1.20.6.linux-amd64.tar.gz && rm -rf /usr/local/go && tar -C /usr/local -xzf go1.20.6.linux-amd64.tar.gz

```

```shell
export PATH=$PATH:/usr/local/go/bin
```

```shell
go version
```


# Act -  Think Globally , Act localy 
## Install 
```shell
curl -s https://raw.githubusercontent.com/nektos/act/master/install.sh | sudo bash
```

```shell
install bin/act  /usr/local/bin/
```


## Use
list
```shell
act -l
```

dry-run
```shell
act -n
```

real act
```shell
act
```


# Action

```shell
https://azure.github.io/actions/
https://github.com/marketplace?type=actions&query=Azure
```