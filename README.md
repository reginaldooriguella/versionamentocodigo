# Versionamento de codigo
Git e Versionamento

GIT é um sistema de controle de versão distribuído. Ele é um software livre desenvolvido por Linus Torvalds, o criador do Linux. O GIT foi originalmente criado para gerenciar o desenvolvimento do kernel do Linux, mas desde então se tornou um dos sistemas de controle de versão mais amplamente adotados por desenvolvedores de software ao redor do mundo.
Um sistema de controle de versão, como o GIT, permite que várias pessoas trabalhem em um projeto ao mesmo tempo sem sobrescrever o trabalho umas das outras. Cada desenvolvedor pode ter uma cópia completa do código (ou seja, um "repositório") em seu computador local. Eles podem fazer alterações em seu próprio ritmo, salvando ("comitando") suas alterações conforme avançam.
Quando estão prontos para compartilhar suas alterações com os outros, eles podem "empurrar" (push) suas alterações para um repositório compartilhado. Outros desenvolvedores podem então "puxar" (pull) essas alterações para seus repositórios locais.
Além disso, o GIT permite que você mantenha um histórico completo de todas as alterações feitas em um projeto. Você pode facilmente voltar para versões anteriores do projeto se algo der errado. Você também pode criar "ramos" (branches) separados do projeto para experimentar novas ideias sem afetar a linha principal (master ou main branch) do projeto.


Exemplo de comandos no git
Aqui estão alguns comandos básicos do Git que você pode achar útil:

git init: Este comando inicializa um novo repositório Git. Ele cria um novo subdiretório chamado .git que contém todos os arquivos necessários para o repositório.
git clone <url>: Este comando é usado para obter uma cópia de um repositório Git existente. A URL fornecida pode ser a URL de um repositório remoto, como um repositório hospedado no GitHub.
git status: Este comando mostra o estado do seu repositório. Ele pode mostrar quais arquivos foram alterados, quais alterações foram adicionadas para serem commitadas, e qual branch você está atualmente.
git add <arquivo>: Este comando adiciona um arquivo ao "stage" (área de preparação), o que significa que ele está pronto para ser commitado. Se você quiser adicionar todas as alterações, você pode usar git add ..
git commit -m "mensagem": Este comando cria um novo commit com as alterações que você adicionou ao stage. A "mensagem" deve ser uma breve descrição das alterações que você fez.
git push: Este comando envia seus commits para o repositório remoto.
git pull: Este comando busca as alterações do repositório remoto e as mescla com o seu branch local.
git branch: Este comando lista todos os branches no seu repositório. Para criar um novo branch, você pode usar git branch <nome-do-branch>. Para mudar para um branch existente, você pode usar git checkout <nome-do-branch>.
git merge <nome-do-branch>: Este comando mescla as alterações do branch especificado no branch atual.
Esses são apenas alguns dos muitos comandos disponíveis no Git. A ferramenta é muito poderosa e tem muitas outras funcionalidades que você pode explorar conforme se torna mais confortável com ela.

  
  Os comandos do Git são inseridos em uma linha de comando, utilizando um terminal ou console. Aqui estão algumas opções de onde você pode inserir os comandos do Git:
Terminal: Em sistemas Linux e macOS, você pode usar o terminal padrão. No Windows, você pode usar o PowerShell ou o Git Bash, que é um terminal que vem com a instalação do Git.
Interface gráfica do Git: Existem várias interfaces gráficas disponíveis para o Git, como o GitKraken, o Sourcetree e o GitHub Desktop. Essas ferramentas fornecem uma interface mais amigável e visual para executar os comandos do Git.
IDEs e editores de código: Muitas IDEs (Integrated Development Environments) e editores de código têm integração com o Git e oferecem uma interface para executar os comandos do Git. Alguns exemplos incluem o Visual Studio Code, o IntelliJ IDEA, o Eclipse e o Xcode.
Independentemente de onde você escolher inserir os comandos do Git, certifique-se de que você esteja no diretório correto (ou seja, o diretório do seu repositório Git) antes de executar os comandos. Isso pode ser feito navegando para o diretório desejado usando o comando cd no terminal ou abrindo o diretório diretamente na interface gráfica do Git ou IDE.
