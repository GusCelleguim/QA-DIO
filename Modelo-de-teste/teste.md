Tipos de teste

Tipos de teste e objetivos
Grupo de atividades de teste destinado a verificar características específicas de um sistema, com base em objetivos específicos.
Avaliar características funcionais 
Avaliar características não funcionais
Avaliar estrutura ou arquitetura  de componente/sistema
Avaliar efeitos de alterações em outras partes do código

teste funcional 

Avaliação de funções que o sistema deve executar
Desenvolvidos a partir de especificações de requisitos, histórias de usuário, casos de uso
Os testes funcionais podem ser realizados em todos os níveis de teste
Técnicas caixa-preta são bem úteis para avaliação de comportamentos funcionais do sistema

Teste não funcional

Avaliação de características não funcionais como usabilidade, eficiência de performance, segurança, etc…
Também pode ser feito em todos os níveis de teste

teste de caixa branca 

Teste caixa-branca

Foco em testes com base na estrutura interna do sistema

Código-fonte
Arquitetura
Fluxo de dados
Cobertura de código com testes de unidade ou integração
Teste de Caixa Branca
Também conhecido como teste estrutural ou teste baseado em código, o teste de caixa branca se concentra na análise da estrutura interna do software. Isso significa que o tester precisa ter acesso ao código-fonte e ter conhecimento sobre sua lógica para verificar o funcionamento correto.

Características:
O foco é testar o fluxo lógico do código, estruturas de controle, condicionais, e caminhos de decisão.
Usado principalmente para garantir que todas as instruções, ramos e caminhos do código sejam cobertos.
Geralmente aplicados em testes de unidade ou testes de integração, onde o comportamento interno do código é examinado detalhadamente.
É uma abordagem determinística, onde os testadores verificam o comportamento esperado em cenários específicos e com conhecimento completo da lógica.
Benefícios:
Detecta erros lógicos e defeitos que podem não ser visíveis em testes funcionais.
Permite testar a eficiência do código em termos de estrutura e fluxo.
Garante uma cobertura mais ampla de todas as ramificações e decisões do sistema.
Desvantagens:
Exige um conhecimento profundo do código, o que pode ser um obstáculo se o tester não tiver experiência com a linguagem ou estrutura utilizada.
Não aborda como o sistema se comporta do ponto de vista do usuário final, focando mais na implementação técnica.
Exemplo de Técnicas Usadas no Teste de Caixa Branca:
Cobertura de instruções: Verifica se cada linha de código foi executada.
Cobertura de decisões: Testa todas as decisões (condicionais) possíveis dentro do código.
Cobertura de caminhos: Garante que todos os caminhos possíveis entre as instruções do código sejam executados.
Teste de Caixa Preta
Diferente do teste de caixa branca, o teste de caixa preta se concentra em validar o comportamento externo do software, sem considerar a estrutura interna do código. O tester foca nos inputs e outputs do sistema, garantindo que ele se comporte conforme os requisitos funcionais, mas sem conhecer como esses resultados são alcançados internamente.

Características:
O tester não tem acesso ao código-fonte, apenas aos requisitos e à interface do sistema.
A principal preocupação é verificar se o software faz o que deveria fazer, de acordo com as especificações.
É amplamente utilizado para testes funcionais, onde o objetivo é testar o comportamento do sistema em relação às suas funcionalidades especificadas.
A abordagem é focada no usuário final, ou seja, os testes simulam a interação de um usuário ou cliente com o sistema.
Benefícios:
Ideal para validar requisitos funcionais e garantir que o sistema atende às expectativas dos usuários.
Não requer conhecimento técnico do código, sendo acessível para testers que não têm experiência com a linguagem ou estrutura do sistema.
Facilita a descoberta de comportamentos inesperados, bugs ou falhas a partir da perspectiva do usuário.
Desvantagens:
Como o tester não tem acesso ao código, não há como identificar problemas na lógica ou estrutura interna do software.
Não garante a cobertura completa dos caminhos lógicos, já que não considera como o software foi implementado.
Exemplo de Técnicas Usadas no Teste de Caixa Preta:
Particionamento de equivalência: Divide os dados de entrada em classes que devem ser processadas da mesma maneira, tanto para entradas válidas quanto inválidas.
Análise de valor limite: Testa os valores nos limites das partições de entrada (como mínimo, máximo e valores próximos a eles).
Teste baseado em casos de uso: Testa o sistema com base em cenários reais de uso, simulando a interação do usuário com a aplicação.
Diferenças Principais
Visão do Sistema:

Caixa Branca: Foco na lógica interna e estrutura do código.
Caixa Preta: Foco no comportamento externo do sistema.
Conhecimento Necessário:

Caixa Branca: O tester precisa conhecer o código-fonte e sua lógica.
Caixa Preta: Não há necessidade de conhecer o código; o tester usa apenas os requisitos e as funcionalidades do software.
Nível de Teste:

Caixa Branca: Aplicado principalmente em níveis mais baixos, como teste de unidade e integração.
Caixa Preta: Comum em testes de sistema e aceitação, focado na experiência do usuário final.
Conclusão
Ambas as abordagens, caixa branca e caixa preta, são essenciais para garantir a qualidade do software. O teste de caixa branca oferece uma análise mais profunda e técnica, enquanto o teste de caixa preta reflete a experiência do usuário e a funcionalidade do sistema. Para obter uma cobertura abrangente e eficaz de testes, muitas vezes as equipes de QA combinam ambas as abordagens, assegurando que tanto a lógica interna quanto o comportamento externo do software sejam validados.
