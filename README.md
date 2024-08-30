# Atividade 2 TDD
Tarefa da aula de TDD 14/08/2024

# Relâmpago Marquinhos

Este é um projeto simples em HTML que apresenta o personagem Relâmpago Marquinhos. A aplicação contém três páginas principais: Home, Contato e Sobre. O objetivo é oferecer uma introdução ao personagem, além de fornecer informações de contato.

## Estrutura do Projeto

O projeto é composto por três páginas:

- **Home**: A página inicial que apresenta o Relâmpago Marquinhos, com uma breve descrição e imagem do personagem.
  
- **Sobre**: Uma página que fornece mais informações sobre o Relâmpago Marquinhos, incluindo sua origem, características e curiosidades.
  
- **Contato**: Uma página simples onde é possível encontrar informações para entrar em contato.

## Tecnologias Utilizadas

- HTML5: Estruturação das páginas.
- CSS3: Estilização das páginas (se aplicável).

## Inicialização do Projeto (Página HOME)

Para que o projeto funcione e rode em seu navegador, execute o arquivo index.html

```bash
cd relampago/index.html
```

## Configuração do Git para desenvolvimento

1. Clone o repositório para sua máquina local.
   ```bash
   git clone https://github.com/JenniferThamara/relampago.git
   ```
2. Navegue até o diretório do projeto.
   ```bash
   cd relampago
   ```
3. Abra o arquivo `index.html` no seu navegador para visualizar a aplicação.



## Criação e uso das Ramificações
Para cada página foi criado uma branch

#### Página HOME
criando a branch:

```bash
git checkout -b desenvolvimento/home
git add .
git commit -m "criação da branch home"
git push origin desenvolvimento/home
```

#### Mesclagem das Ramificações
```
git checkout main
git merge desenvolvimento/home
git add .
git commit -m "mesclagem da branch home com a main"
git push origin main
```
#### Página SOBRE
criando a branch:

```bash
git checkout -b desenvolvimento/sobre
git add .
git commit -m "criação da branch sobre"
git push origin desenvolvimento/sobre
```
#### Mesclagem das Ramificações
```bash
git checkout main
git merge desenvolvimento/sobre
git add .
git commit -m "mesclagem da branch sobre com a main"
git push origin main
```
#### Página CONTATO
criando a branch:

```bash
git checkout -b desenvolvimento/contato
git add .
git commit -m "criação da branch contato"
git push origin desenvolvimento/contato
```
#### Mesclagem das Ramificações
```bash
git checkout main
git merge desenvolvimento/contato
git add .
git commit -m "mesclagem da branch contato com a main"
git push origin main
```
## Envio para o GitHub
É necessário estar na branch main:
```bash
git checkout main
```
Execute os seguintes comandos:
```bash
git remote add origin https://github.com/JenniferThamara/relampago.git
git push -u origin main
```



## Contribuições do Projeto
* Carlos: contribuiu com o desenvovimento da Home, foi interessante realizar a mesclagem para a main antes de enviar o repositório para o Github. Fiz um teste de estilo colocando os código internos, depois foi transcrito no arquivo styles.css .

* Jennifer: contribuiu com o desenvolvimento de sobre, foi um grande aprendizado utilizar a mesclagem, precisamos apenas alinhar oque cada um iria alterar, para n correr conflitos e alterar as mesmas coisas.

* Rafael: contribuiu com o desenvolvimento dos estilos de cada página do projeto, foi legal testar os merges das branchs e ver como ficaria o projeto final.

* Alexsander: contribuiu com o desenvolvimento da tela de contatos, foi bastante interessante a questão do merge entre as branchs, o que facilita muito no desenvolvimento.

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo `LICENSE` para obter mais detalhes.
