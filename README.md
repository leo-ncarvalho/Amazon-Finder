# Amazon-Finder
Procure produtos na Amazon fácil

## Tecnologias Utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express, Axios
- **API de raspagem:** Amazon scraping via backend

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu sistema:

- [Node.js](https://nodejs.org/en/) - Para rodar o backend do projeto
- [npm](https://www.npmjs.com/) - Gerenciador de pacotes do Node.js

## Instalação

### 1. Clone o repositório

Clone o repositório para sua máquina local:
https://github.com/leo-ncarvalho/Amazon-Finder.git

2. Navegue até a pasta do projeto
cd amazon-finder

3. Instalar Dependências
Instale as dependências necessárias tanto para o backend quanto para o frontend.

Vá até a pasta api e instale as dependências do backend:

cd api
npm install

Volte para a pasta principal e instale as dependências do frontend:

cd ..
npm install

4. Configurar o Servidor
Antes de executar o servidor, verifique se você tem o ambiente configurado corretamente. O backend estará escutando na porta 3000 por padrão, mas isso pode ser alterado se necessário.

5. Executar o Servidor
Para iniciar o servidor do backend, execute o seguinte comando dentro da pasta backend:

npm start
Agora, o servidor estará rodando localmente em http://localhost:3000.

6. Acessar o Frontend
O frontend estará disponível na porta que você configurou ou, por padrão, será servido diretamente no navegador.

Abra o arquivo index.html diretamente no navegador ou, se configurado, execute um servidor local para testar a aplicação.

Como Usar
Acesse o frontend no seu navegador.

Digite uma palavra-chave no campo de busca (exemplo: "laptop", "smartphone").

Clique no botão "Buscar".

Os produtos relacionados à sua pesquisa serão exibidos abaixo, e você pode ver detalhes como imagem, título, avaliação e número de avaliações.
