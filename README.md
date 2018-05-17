#Teste de desenvolvimento .NET (C#) - AMcom

Implemente uma Web API que permita consultar e listas as 5 Unidades Básicas de Saúde (UBSs) mais próximas das coordenadas de latitude e longitude fornecidas como parâmetro e apresente o resultado ordenado pela avaliação de desempenho dessas unidades, da mais alta para a mais baixa.

### Solução

A solução está divida nas seguintes camadas:

* Web API - Camada de Web API que deverá expor um método HTTP GET para retornar os dados solicitados no exercício.
* Services - Camada de lógica de aplicação, que deve ser consumida pela Web API com as regras de negócio do exercício.
* DAL - Camada de acesso a dados, onde a carga e disponibilização dos dados da aplicação devem ser implementadas.

A estrutuda da aplicações está conforme abaixo:

src\AMcom.Teste.WebApi
src\AMcom.Teste.Service
src\AMcom.Teste.DAL

test\AMcom.Teste.Service.Tests

**Cada projeto das camadas listadas acima contém um arquivo README.md com mais detalhes sobre como a implementação deste exercício deve ser feita.**

