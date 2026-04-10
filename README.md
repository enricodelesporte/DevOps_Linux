
# Projeto Linux - Simulação de Sistema Bancário

Meu primeiro projeto utilizando uma VM Linux na Azure.

A proposta foi praticar comandos básicos do terminal simulando um sistema bancário simples, com organização de clientes, transações, logs e análise de dados.

---

## Estrutura do projeto

### clientes
- cliente_001_joao_silva.txt  
- cliente_002_maria_santos.txt  
- cliente_003_pedro_oliveira.txt  

### transacoes
- transacoes_janeiro_2025.txt  
- transacoes_fevereiro_2025.txt  

### logs
- sistema_dimdim.log  
- acesso_usuarios.log  
- transacoes_api.log  
- erro_sistema.log  

### relatorios

### backup

---

## Criação dos logs

```bash
cd logs
touch sistema_dimdim.log acesso_usuarios.log transacoes_api.log erro_sistema.logMeu primeiro projeto na VM !!
#  Projeto Linux - Simulação de Sistema Bancário

Esse projeto foi desenvolvido como atividade prática utilizando uma máquina virtual Linux na Azure.

A ideia foi simular um pequeno sistema de organização de dados de clientes e transações, utilizando apenas comandos básicos do terminal.

---

##  Estrutura criada

- Pasta `clientes`
  - cliente_001_joao_silva.txt
  - cliente_002_maria_santos.txt
  - cliente_003_pedro_oliveira.txt

- Pasta `transacoes`
  - transacoes_janeiro_2025.txt
  - transacoes_fevereiro_2025.txt

- Pasta `relatorios`

- Pasta `Backup`

---

## Comandos utilizados

### Criação de diretórios
```bash
mkdir clientes
mkdir transacoes
ls -l
touch
echo
cat
cp
cd
mv
tail

## Aula 3

Nessa etapa do projeto continuei aprofundando os conhecimentos em Linux, trabalhando principalmente com manipulação de arquivos, permissões, processos e comandos mais avançados.

Comecei utilizando comandos como `chmod` para alterar permissões de arquivos, entendendo melhor como funcionam os níveis de acesso (usuário, grupo e outros) e a representação numérica dessas permissões.

Também utilizei o comando `ls -a` para visualizar arquivos ocultos e compreendi melhor a estrutura do sistema Linux, incluindo diretórios e arquivos de configuração.

Na parte de manipulação de texto, trabalhei com comandos como `cat`, `head` e `tail` para leitura de arquivos, além do uso de redirecionamento (`>`) para salvar saídas de comandos em arquivos.

Outro ponto importante foi o uso do pipe (`|`), permitindo encadear comandos e processar dados de forma mais eficiente. Combinei comandos como `ls`, `grep`, `head` e `tail` para filtrar e analisar informações.

Também explorei o comando `tr` para transformação de texto e o `grep` para busca de padrões dentro de arquivos, o que é muito útil para análise de logs e dados.

Na parte de processos, utilizei comandos como `ps`, `top`, `sleep` e `kill`, entendendo como monitorar e controlar processos no sistema. Também aprendi a executar processos em background utilizando `&` e a trazer de volta para o foreground com `fg`.

No geral, essa etapa foi importante para consolidar o uso do terminal Linux, tornando mais claro como automatizar tarefas, manipular arquivos e entender o funcionamento do sistema.

##Aula Docker

O Docker é uma plataforma de código aberto que permite criar, empacotar e executar aplicações em ambientes isolados chamados containers. Esses containers incluem tudo o que a aplicação precisa para funcionar, como código, bibliotecas e dependências, garantindo que ela rode da mesma forma em qualquer ambiente, seja no desenvolvimento, testes ou produção.

Ele é amplamente utilizado para resolver o problema clássico de “funciona na minha máquina”, padronizando o ambiente de execução e facilitando a portabilidade entre diferentes sistemas.

Para que serve:

O Docker serve para simplificar o desenvolvimento, distribuição e execução de aplicações. Com ele, é possível:

Criar ambientes consistentes e reproduzíveis
Isolar aplicações e suas dependências
Facilitar a integração contínua e entrega contínua (CI/CD)
Executar múltiplos serviços de forma independente no mesmo sistema

Vantagens
Portabilidade: funciona em qualquer máquina que tenha Docker instalado
Leveza: containers são mais rápidos e consomem menos recursos que máquinas virtuais
Escalabilidade: facilita a criação e replicação de serviços
Isolamento: evita conflitos entre dependências de diferentes projetos
Produtividade: acelera o setup de ambientes e o onboarding de novos desenvolvedores
Principais funções
Build de imagens: criação de imagens a partir de um Dockerfile
Execução de containers: iniciar, parar e gerenciar containers
Gerenciamento de volumes: persistência de dados
Redes: comunicação entre containers
Orquestração básica: com ferramentas como Docker Compose, para rodar múltiplos serviços juntos

Passo a passo:

1° Entre no VsCode
2° Baixe a entensão do Docker 
3° No terminal coloque o comenado "docker" e em seguida o comando "docker container run ubuntu" (Na lateral esquerda vai aparecer o ícone de Containers)
