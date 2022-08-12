Meu projeto do curso Javascript full stack


﻿1. Como se define variável counter para 8 e incrementar 1 em 1?
* COUNTER=8;
* COUNTER=$(($COUNTER + 1));


2. Serviço da AWS para criar imagem a partir da EC2 pré-configurado?
* AMI (Amazon Machine Images);


3. Qual ferramenta usada por cientistas de dados para ML?
* Amazon SageMaker;


4. Qual é a licença do Linux ?
* GPL (GNU Public licence);


5. Qual comando usar para colocar um serviço do linux na inicialização do SO?
* systemctl enable Serviço;


6. Qual arquivo é obrigatório no funcionamento do Amazon CodeDeploy?
* Appspec;


7. Como é feita a cobrança do Amazon CodeDeploy?
* $0.02 por instância local;


8. Docker é descrito como uma melhoria para?
* Virtualização;


9. Quais são os recursos mais importantes do docker?
* Versionamento;
* Posicionamento/afinidade;
* Modelagem Fácil;


10. Oque é Kubectl do kubernetes?
* CLI (command line interface);
* Ferramenta facilita execução localmente;


11. Onde os dados do cluster kubernetes são armazenados?
* Etcd - key-value store;


12. Nome da copia de paralela distinta da infraestrutura para testar feature nova?
* Branch;


13. Qual o comando para criar infraestrutura no terraform?
* Terraform Apply - gera ou atualiza dependendo da configuração;
* ?? Terraform Plan - executado antes do Apply para gerar um plano;
* ?? Terraform show - mostra um arquivo para humano ler;


14. Qual item não é uma funcionalidade do Ansible?
* NÃO tem: Exportação de filesystem;
* Ferramenta de OPEN de automação;
* Instala e att pacotes;
* Configura deploy;
* Gerenciamento de Usuários;


15. Oque faz a sequência de comandos do Ansible?
- syncrozine:
src: /etc/hosts
dest: /etc/hosts
delegate_to: "{{ inventory_hostname }}"
* Copia o arquivo do servidor de exceção para o servidor remoto;


16. Oque contém no objeto de um commit?
* As configurações do usuário.
* Específica a tree de nível mais alto para o snapshot;
* Usar.name e user.email;
* Timestamp;
* Mensagem do commit;


17. Quando executa git add engenheiros.yml, em qual área do git iremos estar?
* Staging Area;


18. Como podemos denominar níveis de testes?
* Teste de Regressão (garante que versões novas não causem defeitos);
* Teste Beta e teste Alpha (Não Planeada);
* Teste de aceitação (satisfazer requisitos como um todo);
* Teste de Sistema;
* Teste de integração;
* Teste de unidade;


19. Como é chamado o grau em que as especificações são seguidas na fabricação de um produto?
* Qualidade de Conformidade;
* Controle de Qualidade;
* Garantia de Qualidade;


20. Qual o ataque de estouro de buffer mais comum?
* StackOverFlow;


21. Quanto a FireWall, é correto afirmar?
* Programa ou dispositivo de uma rede com políticas de segurança;


22. Quais são as estruturas de repetição?
* While, for, foreach;


23. Se queremos mais de duas opções usamos?
* elif;


24. Qual extensão do arquivo python?
* .py;
* .ipynb (Jupyter Notebook);


25. Qual comando não permite interação com serviço web em PowerShell?
* request.get (python lib);


26. Qual comando importa um módulo powershell?
* Import-Module;


27. Qual comando do shell torna disponível as variáveis para o subshell?
* Export;
* Set lista todas as variáveis inclusive as de shell;
* Export -n rebaixa uma variável de ambiente em variável de shell;


28. Qual é o firewall da AWS que protege de bots e outros ataques que ameaçam a disponibilidade da aplicação?
* OK - AWS WAF (Web Application Firewall) (protege contra bots e mantém disponibilidade);
* KO - AWS Network FireWall (protege a rede VPC);
* KO - AWS Shield (protege contra DDoS;


29. Qual fator é considerado para calcular o TotalCost Ownership (TCO) numa migração?
* ?? - Número de API's;


30. Como alterar as permissões para -rwxrw-r–?
* Chmod 764 arquivo;


31. Comando para encontrar o binário do vim?
* Which vim;


32. Como inicializar um diretório no terraform?
* terraform init;


33. Terraform é uma linguagem?
* Declarativa;


34. Comando para parar um docker?
* docker stop;


35. Qual o requisito mais importante para criar uma imagem em docker?
* Imagem;


36. Oque faz o git reset?
* Redefine o index e o diretório para o estado do último commit;


37. Como listar todos os repositórios remotos de um projeto?
* git remote -v | –verbose;


38. Como definir uma função?
* def;


39. Quanto a desenvolvimento com python, oque está correto?
* KO - O compilador traduz o códigos para uma linguagem de baixo para alto nível;
* OK - A função len retorna a quantidade de elementos de um objeto;
* OK - o controle de bloco é feita por indentação;


40. Qual serviço bloqueia entrada/saída dentro da AWS VPC ?
* NACL AWS (Network Access Control List);


41. Como armazenar contêineres e imagens docker usando o ECS (elastic container service)
* Com ECR (elastic container registry);


42. Quais as conexões de saída da Lambda?
* TCP/IP (Transmission Control Protocol);
* UDP/IP (User Datagram Protocol);


43. Como as variáveis de ambiente de uma Lambda são armazenadas?
* Par de chave valor;
* usar o Amazon Secret Manager com AWS Cloudformation;
* Não armazenar no banco de dados;


44. Como o Prometheus lida com o Grafana?
* Consulta diretamente;
* Grafana Port: 3000;
* Prometheus Port: 9090;


—


45. Qual tipo de instância ec2 usar quando for usar por mais de 1 ano e ter uma economia de 72%?
* OK - Reserved (1 a 3 anos | 40% a 60%);
* KO - Dedicated Host (Hardware dedicado e Suporte a Licenças de software);
* KO - Spot (para aplicações sem estados e tolerantes a falha, HPC (alta performance));
* KO - On-Demand (regular);


46. Qual serviço é usado para logar as ações dos seus usuários?
* OK - Cloud Trail (Control Tower - fornece um registro das ações executadas por um usuário);
* KO - IAM (Identity and Access Management);


47. Qual o arquivo para atribuir nomes a ips simulando dns?
* OK - /etc/hosts (127.0.0.1 localhost);
* KO - /etc/resolv.conf (convert name to ip) (nameserver 173.203.2.5);


48. Terraform é desenvolvida por?
* Hashicorp;


49. Quais são os recursos mais importantes do docker?
* Controle de versão;
* Modelagem Fácil;
* Posicionamento/afinidade (CPU affinity, swarm affinity)


50. Sobre as variáveis?
* Representam posições na memória;
* Servem para guardar dados;


51. Qual é a função do git config?
* Forma de definir configurações do git;


52. Qual não é um estado do git?
* Monitoring;


53. Qual não é uma prática recomendada com IAM?
* Anexar políticas a usuários individuais;


54. Como código ou conteúdo adicional pode ser fornecido para a Lambda?
* Layers;


55. Qual serviço usar para migrar trabalhos administrativos usando c#?
* AWS Lambda com c#;


56. Qual componente do prometheus permite obter dados?
* KO - Alert Manager (handles alerts sent by client applications);
* OK - PushGateway (allows you to push metrics from jobs which cannot be scraped);
* KO - Federation (scrape selected time series from another Prometheus server);


57. Como colocar logs, métricas e traces em todas as lambdas python usando um layer oficial?
* Lambda PowerTools Python;


58. Onde estão armazenados os hashes das senhas no linux?
* /etc/shadow;


—


59. Qual é a melhor definição de região na AWS?
* Uma região geografia com um conjunto de zonas de disponibilidade;


60. Qual é o serviço de mensagens desenvolvido para Apache Active MQ e rabbit MQ?
* Amazon MQ;


61. O uso de 750h por mês do EC2 faz parte de qual camada gratuita?
* 12 meses gratuitos;


62. Qual componente da infraestrutura global da AWS que o Amazon CloudFront usa para manter baixa latência?
* AWS edge location;


63. No CentOs onde fica as configurações do comando yum?
* /etc/yum.repos.d;


64. Quando executamos no linux o comando abaixo?
#adduser -u 3333 -g engenheiros -c "João da Silva" jpuan
* -c, --comment (used for full name);
* -g --gid GROUP (group name or number, must exist);
* -u, --uid UID (unique value ID);
* O usuário jpuan será criado com uid 3333 no grupo engenheiros;


65. Qual é a função do Ctrl + c no linux?
* Suspende a execução de um comando;


66. Em uma condição simples (IF) em shell script linux oque significa o atributo -f?
[[ -f engenheiros ]]
* Se arquivo existe e não é vazio;


67. No conceito de docker oq é um registry?
* Um local onde as imagens ficam armazenadas;


68. Quais são os estados do container docker?
* One of created, restarting, running, removing, paused, exited, or dead;


69. Quais os principais fatores que determinam a quantidade de container que podemos rodar em um servidor?
* ?? Memória e CPU;


70. Quando executamos no docker o comando docker run ubuntu oque acontece?
* Verifica se existe a imagem, baixa, e executa;


71. Qual é o comando para criar infraestrutura na ferramenta terraform?
* terraform apply;


72. Qual é a extensão do arquivo terraform?
* .tf;


73. Qual é o comando para mostrar o plano de execução e não aplicar na ferramenta terraform?
* terraform show;


74. Qual é o comando para mostrar o workspace que o usuário está utilizando no terraform?
* OK - terraform workspace show (mostra o workspace atual);
* KO - terraform workspace new (cria novo);
* KO - terraform workspace list ( mostra todos os diretórios);


75. A ferramenta terraform é?
* ?? - Code Software;


76. Sobre o fluxo básico de trabalho do git temos três ações principais?
* 1 - Modifica arquivo;
* 2 - Prepara os arquivos;
* 3 - faz o commit;


77. Qual é a função do clone na ferramenta git?
* Cria uma cópia;


78. Oque faz o git push?
* Atualiza um repositório remoto;


79. Oque é git, gitlab e github?
* Servidores de controle de versão;


80. Quando faz clone, oque acontece?
* Dá cd antes de rodar make…;
* Vai para working directory;


81. Qual é o operador de atribuição?
* = ;


82. Como fazer comentários em python?
* #;


83. Qual framework web usa o Python?
* Django;


84. Como interromper uma lambda em loop infinito?
* ?? - Delete a função;


85. A AWS Lambda executa?
* ?? - Executáveis;


86. Qual serviço não usar para criar a arquitetura de um aplicativo web na aws?
* AWS Config;


87. Como armazenar e pesquisar logs usando S3?
* Carregue os dados no Amazon ElasticSearch(visualiza no cloud watch);


88. Qual método usar para ver log da lambda?
* ?? - Metricas lambda e alarms no AWS Cloudwatch;


89. Qual serviço usar para reduzir possíveis interrupções em site hospedado na aws?
* Usar ELB (Elastic Load Balance) (distribui carga para mais zonas de disponibilidade (AZ));


90. _ Permite uma rede privada?
* VPC (virtual private cloud);


91. ?
* ;


92. ?
* ;


93. ?
* ;


94. ?
* ;


95. ?
* ;


96. ?
* ;


97. ?
* ;


98. ?
* ;


99. ?
* ;
