# Ordenation.py
## 2° CheckPoint dev-and-coding-for-security
## Informações do Check Point
### Atividade em duplas
### Data de entrega: A atividade poderá ser entregue até o dia 30/04 (sexta-feira)
#### Duplas declaradas no servidor do discord
Cada dupla deverá entregar o arquivo `ordenatio_RM1_RM2.py` onde o **RM é o (Registro de Matrícula) de cada um dos alunos da Dupla**.

---
## Entregáveis
1. arquivo `ordenation_RM00000_RM00000.py`  

### DESENVOLVIMENTO

- Elabore um programa em linguagem Python que leia um array com 10 palavras
*IMPUTADOS* pelo usuário, e depois ordene de forma *Crescente* e *Decrescente*.
> Exemplo: 
> lista  =  ["linux",  "ubuntu",  "centos",  "kali",  "slack",  "suse","redhat", "fedora", "archlinux", "debian"]
> Crescente: ['archlinux',  'centos',  'debian',  'fedora',  'kali',  'linux', 'redhat', 'slack', 'suse', 'ubuntu']
> Decrescente: ['ubuntu',   'suse',   'slack',   'redhat','linux',   'kali', 'fedora', 'debian', 'centos', 'archlinux']
##### Observações:
Trabalho deve ser realizado em duplas
Cada dupla entregará apenas um código
O nome dos integrantes deve constar na forma de comentário multiline no corpo do código
Apenas um integrante da dupla deverá entregar o arquivo fibonacci_RM1_RM2.py 


### Padrão de entrega

- Todos os arquivos entregues tem que possuir, no inicio do codigo, o seguinte padrão
``` 
'''
FIAP
Defesa Cibernética - 1TDCF - 2021
Development e Coding for Security
Prof. Ms. Fábio H. Cabrini
Atividade: Check Point 1  
Alunos
Nome - RM00000
Nome - RM00000  
''' 
    Codigo
```
  
- Após finalizar todo código eviar no [formulario](https://forms.gle/uFsrEd1bVBpZZ396A) 

---

## Habilidades

Neste projeto, verificamos se você é capaz de:

- Utilizar IF em estrutura aninhada
- Utilizar While para fazer as repetições necessárias

---

### ANTES DE COMEÇAR A DESENVOLVER

1. Clone o repositório
  * `git clone https://github.com/FIAP-1TDCF-Paulista/Fibonacci.git`.
  * Entre na pasta do repositório que você acabou de clonar:
    * `cd Fibonacci`
    
2. Crie uma branch a partir da branch `main`
  * Verifique que você está na branch `main`
    * Exemplo: `git branch`
  * Se não estiver, mude para a branch `main`
    * Exemplo: `git checkout main`
  * Agora crie uma branch para qual você vai submeter os `commits` do seu projeto
    * Você deve criar uma branch no seguinte formato: `nome-de-usuarioGitHub-nome-do-projeto`
    * Exemplo: `git checkout -b victordg00-fibonacci`
    * No caso de trabalhos em dupla colocar o nome dos dois integrantes: `git checkout -b victordg00-PranaKnight-fibonacci`
    
3. Adicione as mudanças ao _stage_ do Git e faça um `commit`
  * Verifique que as mudanças ainda não estão no _stage_
    * Exemplo: `git status` (o arquivo adicionado deve aparecer em vermelho)
  * Adicione o novo arquivo ao _stage_ do Git
      * Exemplo:
        * `git add .` (adicionando todas as mudanças - _que estavam em vermelho_ - ao stage do Git)
        * `git status` (deve aparecer listado o arquivo `src/zoo.js` em verde)
  * Faça o `commit` inicial
      * Exemplo:
        * `git commit -m 'iniciando o projeto. VAMOS COM TUDO :rocket:'` (fazendo o primeiro commit)
        * `git status` (deve aparecer uma mensagem tipo _nothing to commit_ )

4. Adicione a sua branch com o novo `commit` ao repositório remoto
  * Usando o exemplo anterior: `git push -u origin victordg00-fibonacci`

5. Crie um novo `Pull Request` _(PR)_
  * Vá até a página de _Pull Requests_ do [repositório no GitHub](https://github.com/FIAP-1TDCF-Paulista/Fibonacci/pulls)
  * Clique no botão verde _"New pull request"_
  * Clique na caixa de seleção _"Compare"_ e escolha a sua branch **com atenção**
  * Clique no botão verde _"Create pull request"_
  * Adicione uma descrição para o _Pull Request_ e clique no botão verde _"Create pull request"_
  * **Não se preocupe em preencher mais nada!**
  * Volte até a [página de _Pull Requests_ do repositório](https://github.com/FIAP-1TDCF-Paulista/Fibonacci/pulls) e confira que o seu _Pull Request_ está criado.
