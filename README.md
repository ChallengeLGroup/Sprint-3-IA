# Sprint-3-IA

FELIPE SENDAI– RM: 96553 
GUSTAVO BALLOGH – RM: 96542 
JOHAN MARZOLLA - RM: 97041
 LAU SAMPAIO BENTO COSTA - RM: 97306 
RAQUEL CALMON - RM: 97373 

Introdução: No ambiente corporativo, encontrar e contratar fornecedores que atendam às necessidades específicas de uma empresa pode ser um processo complicado, demorado e caro. Empresas de todos os tamanhos enfrentam desafios nessa área, desde encontrar fornecedores que possam entregar os produtos necessários dentro do prazo desejado até negociar preços acessíveis e garantir a qualidade dos produtos ou serviços oferecidos.

Desafios Atuais: Atualmente, o processo de busca e contratação de fornecedores geralmente envolve várias etapas, incluindo pesquisas extensas, reuniões presenciais, negociações demoradas e, muitas vezes, riscos de segurança de dados. Para contornar esses desafios, muitas empresas recorrem a intermediários, o que pode aumentar ainda mais o tempo necessário para fechar um contrato e adicionar custos adicionais ao processo.

Proposta de Solução: Para enfrentar esses desafios, surge o projeto Fast Supply. A ideia por trás do Fast Supply é criar uma plataforma centralizada que simplifique e agilize o processo de busca e contratação de fornecedores. Inspirado em aplicativos populares como iFood e Mercado Livre, o Fast Supply seria uma plataforma online onde as empresas podem encontrar rapidamente fornecedores compatíveis com suas necessidades específicas em termos de urgência, quantidade, preço e qualidade.

Funcionamento do Fast Supply: Ao usar o Fast Supply, uma empresa simplesmente faria uma solicitação para um determinado produto ou serviço através da plataforma. O Fast Supply então usaria algoritmos avançados, incluindo Machine Learning, para analisar a solicitação e encontrar os fornecedores mais adequados com base em uma variedade de fatores, como custo, tempo de entrega e histórico de qualidade.
Benefícios para as Empresas:

Redução de Tempo e Custos: Ao automatizar e simplificar o processo de busca e contratação de fornecedores, o Fast Supply reduz significativamente o tempo necessário para fechar contratos e elimina custos desnecessários associados a intermediários.

Acesso a uma Rede de Fornecedores Qualificados: O Fast Supply permite que as empresas acessem uma ampla rede de fornecedores pré-qualificados, garantindo que apenas os melhores e mais confiáveis estejam disponíveis para atender às suas necessidades.
Maior Eficiência e Agilidade: Com o Fast Supply, as empresas podem tomar decisões mais rapidamente e agir com mais agilidade, permitindo que respondam de forma mais eficaz às demandas do mercado e às necessidades dos clientes.

Modelo de Negócio: O Fast Supply opera em um modelo de negócios sustentável, onde a receita é gerada através do funcionamento da plataforma online e dos serviços oferecidos aos clientes. Isso permite que a empresa mantenha seus lucros mesmo com um aumento no volume de transações.

Conclusão: Em resumo, o Fast Supply é uma solução inovadora e eficiente para os desafios enfrentados pelas empresas na busca e contratação de fornecedores. Ao simplificar e agilizar esse processo, o Fast Supply oferece uma maneira mais rápida, econômica e confiável para as empresas encontrarem os fornecedores certos para suas necessidades específicas. É uma verdadeira revolução no mundo corporativo, oferecendo eficiência, economia e qualidade em um único pacote.

Livrarias planejadas a serem usadas
No desenvolvimento da nossa solução para facilitação de busca e contratação de serviços voltados a suprimentos de produtos, podemos fazer uso de várias bibliotecas, frameworks, APIs e ferramentas em Python. Aqui estão as principais identificas que serão utilizadas no nosso projeto: 

Framework Web: Django ou Flask: 
Justificativa: Ambos são frameworks web populares em Python. Django é mais opinativo e segue o modelo "batteries-included", enquanto Flask é mais leve e flexível. A escolha dependerá das necessidades que apareceram, porém para o nosso projeto o djando se aparenta mais útil. 

Banco de Dados Relacional: SQLAlchemy: 
Justificativa: SQLAlchemy é um ORM (Object-Relational Mapping) que facilita a interação com bancos de dados relacionais. Ele oferece uma maneira eficiente e segura de manipular dados do banco de dados, garantindo a segurança contra injeção de SQL. 

Banco de Dados NoSQL: MongoDB (ou CouchDB): 
Justificativa: Se a estrutura de dados da sua aplicação é mais flexível e não segue um modelo tabular rígido, um banco de dados NoSQL como o MongoDB pode ser uma escolha adequada. 

Framework para APIs: Django REST Framework: 
Justificativa: Se a sua aplicação precisar de uma API RESTful para comunicação entre diferentes componentes, o Django REST Framework é uma extensão do Django que facilita a criação de APIs de forma rápida e eficiente. 

Ferramentas de Machine Learning: scikit-learn, TensorFlow, PyTorch: 
Justificativa: Para a implementação de algoritmos de machine learning, scikit-learn oferece uma ampla variedade de modelos e ferramentas. TensorFlow e PyTorch são mais voltados para deep learning e podem ser úteis com tarefas mais avançadas de aprendizado de máquina. 

Serviços em Nuvem: AWS SDK (boto3), Azure SDK, Google Cloud Client Library: 
Justificativa: Utiliza as bibliotecas específicas para interagir com os serviços de nuvem escolhidos. Por exemplo, boto3 para AWS, Azure SDK para Azure e Google Cloud Client Library para Google Cloud Platform. 

Ferramentas de Segurança: PyCryptodome, Bcrypt: 
Justificativa: Se lidar com dados sensíveis, é crucial implementar práticas de segurança. PyCryptodome oferece funcionalidades criptográficas, enquanto Bcrypt é útil para o hash seguro de senhas. 

Ferramentas de Autenticação e Autorização: OAuthLib, JWT (JSON Web Tokens): 
Justificativa: Se a autenticação de usuários e a autorização de acessos forem requisitos, ferramentas como OAuthLib para autenticação OAuth e JWT para tokens seguros podem ser implementadas. 

Framework para Frontend: React (com Django REST Framework) ou Flask para APIs RESTful: 
Justificativa: Dependendo da complexidade do nosso frontend, React pode ser uma escolha eficaz para criar interfaces interativas. Se a lógica do frontend for mais leve, Flask pode ser usado para renderizar templates HTML. 

No desenvolvimento do nosso projeto, os conceitos de Machine Learning (ML) e Inteligência Artificial (IA) serão aplicados para aprimorar a eficiência na busca e contratação de serviços voltados a suprimentos de produtos. Aqui estão algumas maneiras resumidas de como esses conceitos serão utilizados: 

Segmentação de Fornecedores: 
Utilização de algoritmos de ML para analisar dados históricos e atuais, segmentando os fornecedores com base em critérios como custo, tempo de entrega e histórico de transações. Isso permite apresentar ao cliente opções mais relevantes e alinhadas com suas necessidades. 

Recomendações Personalizadas: 
Implementação de sistemas de recomendação baseados em ML para sugerir produtos e fornecedores com base no histórico de preferências e escolhas do cliente. Isso melhora a experiência do usuário, tornando as recomendações mais personalizadas e alinhadas com as expectativas do cliente. 
