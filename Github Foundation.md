### Controle de Versão
* O controle de versão é um sistema que registar alterações em um arquivo ou um conjunto de arquivos ao longo do tempo para que você possa recuperar versões específicas posteriormente.

### Git
* Um sistema de controle de versão distribuído (DVCS)
* Gratuito e de código aberto
* Projetado para lidar com tudo, desde projetos pequenos a muito grandes, com velocidade e eficiência
* Otimizado  para operações locais
* Branching (ramificações)
* Snapshots, não deltas

### Controle de Versão Centralizado

![[Pasted image 20250407193501.png]]
![[Pasted image 20250407193604.png]]

* Existem outras ferramentas de versionamento como o Mercurio

### Snapshots vs Deltas
* O Git utiliza o snapshot, que são como fotos que armazenam o estado atual quando o snapshot é capturado
* Caso algo dê errado, é possível capturar a foto do último estado funcional
* O delta apenas armazena as alterações realizadas
![[Pasted image 20250407194248.png]]

### Terminologia
* Working Tree - diretório de desenvolvimento
* Staging Area - revisão das mudanças
* Repository (repo) - armazena os desenvolvimentos
* Hash - código único para cada alteração (commit)
* Object - é a imagem do blob, conjunto de tudo que foi feito no código
* Commit - o registro da mudança
* Branch - ramificação, desvio ou caminho paralelo para teste sem interferir no ramo principal
* Remote - hospedado no servidor, onde várias pessoas acessam o mesmo código
* Comandos, subcomandos - módulos para usar os comandos do git

### Git interage com o Github

![[Pasted image 20250407200028.png]]

### Git vs Github

* Git é um Sistema de Controle de Versão Distribuído
* Github é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git
![[Pasted image 20250407203126.png]]

### Contas Github

![[Pasted image 20250409195128.png]]

### Github Enterprise Server
* Versão do Github que você pode hospedar no seu próprio ambiente de rede. Foi projetado para empresas que desejam a funcionalidade do Github, mas por razões de segurança ou regulamentação, precisam hospedá-lo em seus próprios servidores.
### Github Desktop
* É um aplicativo de software independente e de código aberto que permite que você seja mais produtivo.
* UI mais interativa

### Github Mobile
* Github móvel

### Github Marketplace
* É uma plataforma onde você pode descobrir e comprar que se integram ao Github para ajudar a otimizar o seu fluxo de trabalho.


### Funcionalidades
* Repos - arquivos e histórico de mudanças
* Issues - acompanha tarefas, melhorias e bugs
* Discussions - discutir ideias, pedir ajudas
* Pull Requests - Propostas de mudanças no código
* Notifications - Alertas de atividades no repositório
* Labels - organização e categorização das mudanças de códigos
* Actions - configurações automáticas para implementação das mudanças
* Forks - copia um repositório para testar sem afetar o repositório original
* Projects - para acompanhamento de um projeto específico

### Commit
* é um registro snapshot do seu repo em um momento específico da linha do tempo.
### Branch
* É um ponteiro para um commit específico.

### Estratégias de Branch
* Git Flow - branchs de main, hotfix, releases, develop e features
![[Pasted image 20250409204204.png]]
* Github Flow - branch main e feature
![[Pasted image 20250409204123.png]]

### Tipos de Repositórios

* Public: Se sua conta não for uma conta de usuário gerenciada, você poderá criar repositórios públicos. Os repositórios públicos são acessíveis a todos na internet.
* Internal: Repositórios internos podem ser acessados por todos os integrantes da empresa, estando disponíveis apenas em conta enterprise.
* Private: Os repositórios só podem ser acessados por você, pelas pessoas com as quais você compartilha explicitamente o acesso e, para repositórios da organização, por determinados integrantes da organização.
* Templates: Estrutura pronta para ajustar de acordo com a sua necessidade.

![[Pasted image 20250423074212.png]]

### Componentes Repositório
* MIT License: indica que é um repositório privado e que caso alguém faça um fork, a pessoa precisa ter dar os créditos e que ela não poderá responsabilizar pelo que aconteça após o fork.
* Readme: É um arquivo pra incluir informações sobre o repo em markdown.
### Arquivos Recomendados
* Readme
* Codeowners
* License: 
	* Dentro do escopo open source existem variações nas permissões atribuídas
	* De acordo com os Termos de Serviço, desde que seu código esteja em um repo público, outros podem ver e fazer um fork no seu código
	* Arquivo LICENSE.md geralmente é encontrado na raíz do repo
	* License picker na criação dos projetos
* Contributing: Utilizado para orientar sobre como outras pessoas podem contribuir com seu projeto
	* Contém orientações sobre como as contribuições serão absorvidas
	* Os usuários serão direcionados a esse arquivo quando criarem um issue ou abrir um PR
	* Visa estimular interações úteis e assertivas no contexto do projeto
	* Codeowners: Arquivo utilizado para definir os responsáveis por aprovações e revisões de códigos do repositório
		* O arquivo CODEOWNERS deve estar ou em .github, ou na raiz ou em docs
		* Pode haver mais de um arquivo, mas a varredura é realizada conforme a ordem acima
		* Cada branch pode ter um CODEOWNERS diferente
		* Os codeowners devem ter permissão de gravação no repo
		* Caso uma equipe seja revisora, ela deve estar visível e ter permissões de gravação
	* Readme: É o primeiro item que um visitante verá ao acessar seu repo. Ele é utilizado para detalhar o trabalho contido neste repo
		* Qual a finalidade do projeto?
		* Como outros usuários podem utilizar esse projeto?
		* Onde os usuários podem buscar ajuda sobre o projeto?
		* Quem são os responsáveis pela manutenção do projeto?
	![[Pasted image 20250423080834.png]]

### Mantendo um repo
![[Pasted image 20250423081017.png]]![[Pasted image 20250423081135.png]]

### 