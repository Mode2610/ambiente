# Preparação de ambiente
Criar uma máquina virtual para instalar as ferramentas e dependências para o estudo de algoritmo e lógica de programação 

## Criar o diretório base
Vamos criar um diretório para guardar a nossa máquina virtual. Será criado no Drive D. Nomeada com o nome do usuário.

<img src="criar-diretorio-d.png">

## Preparação da máquina virtual
### vamos usar a ferramenta de visualização chamada Virtual Box

<img src="tela-virtualbox.png">

<a href="https://www.virtualbox.org/wiki/Downloads">Faça o download aqui</a>

## Criando a máquina virtual


<img src="nova-maquina-virtual.png">

<img src="print-vm-intalaçao-desassistida.png">

<img src="Captura-de-tela-Hardware.png">

<img src="Captura-de-tela-Disco-Rigido.png">

## Pós instalação:

Para atualizar oa sistema iremos usar os seguintes comandos:

```shell
sudo apt update -y

```

```shell
sudo apt upgrade -y
```


ou

```shell
sudo apt updat -y && sudo apt upgrade -y
```

## instalação do cockpit

Ferramenta para gerenciar o servidor, por meio de um ambiente gráfico online

<img src="captura-de-tela-cockpit.png">

```shell
sudo apt install cockpit -y
```






