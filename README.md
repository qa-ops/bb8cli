#### Selecione sua Língua | Select your Language
<a href='#requisitos'><img src="images/pt-br.png" alt="Português" width="50" /></a>
<a href='#requirements'><img src="images/en.jpg" alt="English" width="50" /></a>


## Requisitos

- Git
- Bash 4+

## Passo a passo

### Instalando versão mais nova do bash

* No OSX: Usando Homebrew

```shell
brew install bash
```

* No Linux - use o gerenciador de pacote (package manager) da sua distruição para instalar o bash

### Git clone

Idealmente, esse projeto precisa ser clonado na mesma pasta que os outros projetos do QaOps

```shell
git clone git@github.com:qa-ops/bb8cli.git
```
ou

```shell
git clone https://github.com/qa-ops/bb8cli.git
```

### Adicionado ao PATH

Você precisa adicionar o caminho da CLI no seu $PATH
Isso é possível adicionando o comando abaixo no *.bash_profile* ou *.zprofile* (caso use ZSH).

```shell
export PATH=$PATH:/caminho_para_pasta_do_qaops/bb8cli
```

Reinicei o terminal e seja feliz :D

---

## Requirements

- Git
- Bash 4+

## Walkthrough

### Install latest bash

* On OSX: Using Homebrew

```shell
brew install bash
```

* On Linux - use the distribution package manager to install bash

### Git clone

Ideally, this project must be cloned in the same folder where the other QaOps projects are

```shell
git clone git@github.com:qa-ops/bb8cli.git
```
or

```shell
git clone https://github.com/qa-ops/bb8cli.git
```

### Add to PATH

You need to set up your $PATH variable to recgonize devcli in your terminal.
You can do this through *.bash_profile*, or *.zprofile* (if you use ZSH).

```shell
export PATH=$PATH:/path_to_qaops_root_folder/bb8cli
```

Restart your terminal and be happy :D

