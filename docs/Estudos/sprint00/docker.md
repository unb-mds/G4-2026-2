# Estudo: Docker

## O que é Docker:
Docker é uma plataforma que permite empacotar aplicações e suas dependências em contêiner. Um contêiner é um ambiente isolado, leve e portátil, que roda de forma independente do sistema operacional da máquina.

## Qual problema o Docker resolve?
O Docker apareceu para resolver um problema comum de uma aplicação funcionar perfeitamente na sua máquina e apresentar erros em outros ambientes. Isso acontece,muitas vezes por conta dá, diferenças de versão de sistema operacional, bibliotecas ou configurações.

Esse é o famoso problema "Na minha maquina funciona". O Docker resolve isso empacotando a aplicação desenvolvida junto com tudo que ela precisa para rodar: dependências, bibliotecas e configurações.

## Por que usar o Docker?
- Padronização de ambiente
- Isolamento
- Leveza e agilidade
- Facilidade de distribuição
- Escalabilidade

Site oficial: https://docs.docker.com/get-started/docker-overview/
## Instalação no linux
A forma mais simples de instalar o docker no Linux (Ubuntu/Debian) é através do scrip oficial.
```bash
# Atualizar pacotes
sudo apt update

# Baixar e executar o script oficial de instalação
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh

# Verificar a instalação
docker --version
```
Para usar o Docker sem precisar digitar "sudo" toda vez, recomendo que leia no site oficial como fazer isso e os riscos que tem ao adiciona seu usuario ao grupo docker.

Site oficial etapas de pós-instalação do Linux: https://docs.docker.com/engine/install/linux-postinstall/

E para outras distriibuições linux que não são da familia Ubuntu/Debia, acesse: https://docs.docker.com/engine/install/

## Instalação no Windows
No windows, a forma recomendada é instalar o Docker Desktop, que já inclui o Docker Engine, o Docker CLI e uma interface gráfica.

### Passo 1: 
Certifique-se de que o WSL2 (Windows Substem for Linux) está habilitado.Para instalar, abra o PowerShell como administrador e execute:
```powershell
wsl -- install
```

### Passo 2:
Baixe o instalador do Docker Desktop no site oficial: 👉 https://www.docker.com/products/docker-desktop

### Passo 3: 
Execute o instalador e siga as instruções na tela.

### Passo 4: 
Reinicie o computador, se solicitado.

### Passo 5:
Abra o Docker Desktop e aguarde o serviço iniciar.

### Passo 6:
Verifique a instalação abrindo o PowerShell ou o terminal e digitando:
```powershell
docker --version
```
Guia oficial:https://docs.docker.com/desktop/setup/install/windows-install/

## Recomendação: 
Para se aprofundar melhor no mundo do docker, dando seus comandos quanto sua teoria recomendo os seguintes videos:
### Prática: 
Canal Diolinux: https://www.youtube.com/watch?v=Y6kz884AoME&t=491s&pp=ygUGRG9ja2Vy

### Teoria:
Canal TI: https://www.youtube.com/watch?v=74RfAbJWDHs&pp=ygUGRG9ja2Vy
