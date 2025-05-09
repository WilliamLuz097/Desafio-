# Computação em Nuvem _ AZ-900
O que é computação em nuvem?
Refere-se à disponibilidade sob demanda de recursos de computação (como servidores, armazenamento, bancos de dados, software, redes, análise e inteligência) pela internet.

Modelo de Negocio:
 
 => Ambiente on-premise(Datacenter local)
 => Ambiente Cloud
 => Ambiente  Hibrido: Maquina locais e ambiente em cluoud=> Usado em periodos sazonias 
 => Modelo Multicloud 
 =>É posivel utilizar Regions & Zones para manter a alta disponibilidade.
O que é Capex e Opexç 
=> Capex: Refere-se aos gastos que uma empresa realiza para adquirir, melhorar ou prolongar a vida útil de ativos de longo prazo, também conhecidos como ativos fixos.
=> OpEx: Gastar com produtos e serviços conforme necessário , pagamento conforme o uso.
Refere-se aos custos contínuos e de curto prazo necessários para manter e operar os recursos e serviços na nuvem.      

 Benefícios da computação em nuvem: 
    => Alta disponibilidade
    => Escalabilidade
    => Dimensionamento vertical - Aumento de CPUs ou RAM para a máquina virtual.Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos verticalmente.
    => Dimensionamento horizontal - e você experimentasse um salto repentino acentuado na demanda, seus recursos implantados poderiam ser expandidos (automaticamente ou manualmente). Por exemplo, você pode adicionar máquinas virtuais ou contêineres por meio da       expansão.   Da mesma forma, se houver uma queda significativa na demanda, os recursos implantados poderão ser reduzidos horizontalmente (de maneira automática ou manual).
    =>Confiabilidade - Microsoft Azure Well-Architected
    =>Previsibilidade -  Microsoft Azure Well-Architected Framework
    =>Desempenho
    =>Custo
    =>Segurança  


O que são os Modelos de Serviço em Nuvem?
=> Modelos de serviço em nuvem definem o nível de controle que a empresa tem sobre a infraestrutura e os serviços fornecidos pelo provedor de nuvem. Eles ajudam a escolher a solução mais adequada às necessidades do negócio, podendo envolver diferentes níveis de abstração e responsabilidades.


=>É possivel dividir os serviços da seguinte forma:

  => IaaS: oferece infraestrutura de TI básica como serviço, fornecendo recursos como servidores virtuais, armazenamento, redes e outros componentes essenciais de TI, com base em uma cobrança por uso.\
  Exemplos:
	• Amazon EC2, Google Compute Engine, Microsoft Azure VMs.
	• Armazenamento de dados com serviços como Amazon S3 ou Google Cloud Storage.
	•  Vantagens: Controle total sobre a infraestrutura, escalabilidade e flexibilidade.
 Destantagens: Requer gestão de servidores e configurações, mais responsabilidade do que PaaS ou SaaS.
======================================================================================================================
  => PaaS: oferece uma plataforma de desenvolvimento completa na nuvem, permitindo que os desenvolvedores construam, testem e implementem aplicativos sem se preocupar com a infraestrutura subjacente.
Exemplos:
	• Google App Engine, Microsoft Azure App Services, AWS Elastic Beanstalk.
	• Ferramentas de banco de dados como Amazon RDS ou Google Cloud SQL. Vantagens: Simplificação no desenvolvimento, abstração da infraestrutura e foco no desenvolvimento do aplicativo. 
	• Desvantagens: Menos controle sobre a infraestrutura, limitações na personalização de configurações.
============================================================================================================
SaaS: Entrega software e aplicações completas pela nuvem, sendo acessadas via internet, sem necessidade de instalação ou manutenção local. O provedor cuida de tudo, desde a infraestrutura até as atualizações do software.
Exemplos:
	• Google Workspace, Microsoft Office 365, Salesforce.
	• Ferramentas de comunicação como Slack ou Zoom.
	•  Vantagens: Fácil implementação, sem necessidade de gestão de infraestrutura, pagamento por uso.
	•  Desvantagens: Dependência de internet, menor controle sobre o software e dados.
====================================================================================================================================
BaaS: É um modelo de serviço de computação em nuvem que fornece aos desenvolvedores web e de aplicativos móveis uma maneira de conectar seus aplicativos a serviços de backend baseados na nuvem. Isso elimina a necessidade de configurar e gerenciar a infraestrutura de backend por conta própria.
Exemplos:
	• Firebase (Google), AWS Amplify e Back4App
	•  Vantagens: Simplificação no desenvolvimento, abstração da infraestrutura e foco no desenvolvimento do aplicativo.
	•  Desvantagens: Menos controle sobre a infraestrutura, limitações na personalização de configurações.
=======================================================================================================================================
FaaS: é uma forma de computação em nuvem onde você executa funções de código específicas, sem precisar gerenciar servidores. Também conhecida como "serverless", permite que o código seja executado em resposta a eventos, com cobrança baseada na execução real.![image]
Exemplos:
	• AWS Lambda, Azure Functions, Google Cloud Functions. 
	• Vantagens: Escalabilidade automática, pagamento por execução, redução da sobrecarga de gerenciamento de infraestrutura.
Desvantagens: Limitações em tempo de execução e complexidade na manutenção de funções pequenas e event-driven.
==============================================================================================================================
DBaaS: oferece bancos de dados gerenciados como serviço, permitindo aos usuários acessar e gerenciar bancos de dados na nuvem sem se preocupar com a infraestrutura subjacente.
Exemplos:
	• Amazon RDS, Azure SQL Database, Google Cloud SQL.
 Vantagens: Facilidade de escalabilidade, gerenciamento simplificado de backups e atualizações.
 Desvantagens: Menor controle sobre a configuração do banco de dados e personalização.
==========================================================================================================



