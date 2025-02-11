# OpenWeather
 Aplicação Web de Consulta Climática

Nossa aplicação web permite aos usuários obter informações meteorológicas em tempo real de qualquer cidade do mundo. Utilizando a API da OpenWeather, a aplicação faz uma requisição com o nome da cidade fornecida pelo usuário e exibe na tela diversos dados climáticos, incluindo temperatura, umidade, velocidade do vento e descrição das condições meteorológicas.

Funcionalidades Principais:
Interface Simples e Intuitiva: A interface do usuário é projetada para ser clara e fácil de usar. Um campo de texto permite que os usuários insiram o nome da cidade que desejam consultar.

Dados Climáticos em Tempo Real: Após inserir o nome da cidade e enviar a requisição, a aplicação faz uma chamada à API da OpenWeather. Os dados são atualizados em tempo real e exibidos imediatamente na tela.

Exibição de Informações Detalhadas:

Temperatura Atual: Mostrada em graus Celsius ou Fahrenheit.
Umidade Relativa: Exibida em porcentagem.
Velocidade do Vento: Exibida em km/h ou m/s.
Condições Meteorológicas: Uma descrição textual do clima, como "ensolarado", "nublado", "chuva", etc.
Ícone do Clima: Uma imagem representativa das condições climáticas atuais.
Tecnologias Utilizadas:
Frontend: HTML, CSS, JavaScript para criar a interface do usuário.
API da OpenWeather: Utilizada para obter os dados climáticos.
JavaScript Fetch API: Para realizar requisições HTTP e obter dados da API.
Fluxo de Funcionamento:
O usuário acessa a aplicação web e insere o nome de uma cidade no campo de entrada.
Ao clicar no botão "Buscar" (ou similar), a aplicação realiza uma requisição à API da OpenWeather utilizando a função fetch.
A resposta da API é processada e os dados relevantes são extraídos.
Os dados são apresentados na interface de forma organizada e visualmente atraente.
Com esta aplicação, os usuários podem facilmente obter informações climáticas precisas e atualizadas, ajudando-os a planejar seu dia ou suas viagens com maior segurança e conforto.

