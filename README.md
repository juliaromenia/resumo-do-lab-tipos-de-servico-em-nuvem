# resumo-do-lab-tipos-de-servico-em-nuvem
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO

## Descrever a infraestrutura como serviço

O IaaS (infraestrutura como serviço) é a categoria mais flexível de serviços de nuvem, pois oferece o máximo de controle sobre os recursos de nuvem. Nesse modelo, o provedor de nuvem é responsável por manter o hardware, a conectividade de rede (com a Internet) e a segurança física.  Você é responsável por todo o resto: instalação, configuração e manutenção do sistema operacional; configuração de rede; configuração de banco de dados e armazenamento e assim por diante. Com o IaaS, basicamente o hardware é alugado em um datacenter de nuvem, mas cabe a você decidir o que fazer com ele.

- **Modelo de responsabilidade compartilhada**
    
    No IaaS, a maior parte da responsabilidade fica com você. O provedor de nuvem é responsável por manter a infraestrutura física e o acesso à Internet. Você é responsável por: instalação e configuração, aplicação de patch, atualizações e segurança.
    
- **Cenários**
    
    Alguns cenários comuns em que o IaaS faz sentido incluem:
    
    - Migração lift-and-shift(Elevação e deslocamento): Você está configurando recursos de nuvem semelhantes aos do datacenter local e apenas migra os elementos em execução local para execução na infraestrutura IaaS.
    - Teste e desenvolvimento: você estabeleceu configurações para ambientes de desenvolvimento e teste que precisa replicar rapidamente. Você pode inicializar ou desativar os diferentes ambientes rapidamente com uma estrutura de IaaS, mantendo o controle completo.

## Descrever a plataforma como serviço

O PaaS (Plataforma como serviço) é um meio termo entre alugar espaço em um datacenter (infraestrutura como serviço) e pagar uma solução completa e implantada (software como serviço). Nesse modelo, o provedor de nuvem mantém a infraestrutura física, a segurança física e a conexão com a Internet. Ele também mantém os sistemas operacionais, o middleware, as ferramentas de desenvolvimento e os serviços de business intelligence que compõem uma solução de nuvem. Você não precisa se preocupar com o licenciamento nem com a aplicação de patch em sistemas operacionais e bancos de dados.

O PaaS é adequado para fornecer um ambiente de desenvolvimento completo sem a preocupação de manter toda a infraestrutura de desenvolvimento.

- **Modelo de responsabilidade compartilhada**
    
    O PaaS divide a responsabilidade entre você e o provedor de nuvem. O provedor de nuvem é responsável por manter a infraestrutura física e o acesso à Internet, como no IaaS. No modelo de PaaS, o provedor de nuvem também mantém os sistemas operacionais, os bancos de dados e as ferramentas de desenvolvimento. Pense no PaaS como o uso de um computador conectado ao domínio: o departamento de TI mantém o dispositivo com atualizações, patches e renovações regulares.
    
    Dependendo da configuração, você ou o provedor de nuvem pode ser responsável pelas configurações de rede e a conectividade no ambiente de nuvem, a segurança da rede e do aplicativo e a infraestrutura de diretório.
    
- **Cenários:**
    
    Alguns cenários comuns em que o PaaS faz sentido incluem:
    
    - Estrutura de desenvolvimento: O PaaS fornece uma estrutura que os desenvolvedores podem usar como base para desenvolver ou personalizar aplicativos baseados em nuvem. Semelhante à forma como você cria uma macro do Excel, o PaaS permite aos desenvolvedores criar aplicativos usando componentes de software internos. São incluídos recursos de nuvem, como escalabilidade, alta disponibilidade e a funcionalidade de multilocatário, reduzindo a quantidade de codificação que os desenvolvedores precisam realizar.
    - Análise ou business intelligence: as ferramentas fornecidas como serviço com o PaaS permitem que as organizações analisem e minerem dados, encontrando insights e padrões e prevendo res  ultados para aprimorar a previsão, as decisões de design de produto, o retornos sobre investimentos e outras decisões de negócios.
    

## Descrever o software como serviço

O SaaS (software como serviço) é o modelo de serviço de nuvem mais completo do ponto de vista do produto. Nesse modelo, você está essencialmente alugando ou usando um aplicativo totalmente desenvolvido. Email, software financeiro, aplicativos de mensagens e software de conectividade são exemplos comuns de uma implementação de SaaS.

Embora o modelo de SaaS possa ser o menos flexível, ele também é o mais fácil de colocar em funcionamento. Ele requer a menor quantidade de conhecimento técnico ou experiência para o emprego total.

- **Modelo de responsabilidade compartilhada:**
    
    O SaaS é o modelo que coloca a maior responsabilidade sobre o provedor de nuvem e a menor responsabilidade com o usuário. Você é responsável pelos dados que coloca no sistema, pelos dispositivos que permite que se conectem ao sistema e pelos usuários que têm acesso. Quase todo o resto é responsabilidade do provedor de nuvem. O provedor de nuvem é responsável pela segurança física dos datacenters, pela energia, pela conectividade de rede e pelo desenvolvimento e aplicação de patch dos aplicativos.
    
- **Cenários:**
    
    Alguns cenários comuns de SaaS são:
    
    - Email e mensagens.
    - Aplicativos de produtividade empresarial.
    - Controle de finanças e despesas.
