# Meu Primeiro Git

Projeto desenvolvido para praticar controle de versão utilizando Git e GitHub.

## O que foi feito

- Estrutura inicial do projeto.
- Documentação dos produtos.
- Página de produtos.
- Estilização inicial com CSS.
- Página e documentação de pedidos.
- Página e estilização de contato.

## Questionário

### 1. Qual é a diferença entre Working Directory, Staging Area e Repository?

O **Working Directory** é o local onde ficam os arquivos do projeto e onde fazemos as alterações.

A **Staging Area** é a área onde colocamos os arquivos que serão incluídos no próximo commit, utilizando o comando `git add`.

O **Repository** é onde o Git armazena o histórico dos commits e das versões do projeto.

### 2. Qual é a diferença entre git commit e git push?

O `git commit` salva as alterações no repositório local, criando uma nova versão do projeto.

O `git push` envia os commits que estão no repositório local para o repositório remoto, como o GitHub.

### 3. É possível realizar vários commits antes de executar um git push? Explique.

Sim. É possível realizar vários commits localmente antes de executar o `git push`. Os commits ficam armazenados no repositório local e, quando o `git push` é executado, todos os commits que ainda não foram enviados são enviados para o repositório remoto.

### 4. Por que é interessante realizar commits pequenos e descritivos?

Porque commits pequenos e descritivos facilitam a organização e o acompanhamento das alterações. Também tornam mais fácil entender o histórico do projeto e identificar quando uma determinada alteração foi realizada.

### 5. O que acontece com os commits locais quando ainda não executamos o git push?

Os commits continuam armazenados no repositório local. Eles não são perdidos e podem ser enviados posteriormente para o GitHub utilizando o comando `git push`.

### 6. Como verificar, pelo GitHub, se os commits foram enviados corretamente?

É possível acessar o repositório no GitHub e verificar o histórico de commits. Os commits enviados pelo `git push` aparecerão na página do repositório, na área de histórico de commits.