Pokémon NFT - Blockchain ERC-721
Este projeto cria NFTs exclusivos de Pokémon utilizando a tecnologia de contratos inteligentes no padrão ERC-721 sobre o blockchain Ethereum. Cada NFT representa um Pokémon único com atributos como nome, nível e tipo elemental.

Objetivo
O propósito deste projeto é demonstrar a criação de um NFT (Token Não Fungível) que representa um Pokémon único. O projeto utiliza o padrão ERC-721 para criar e gerenciar NFTs e pode ser expandido para incluir funcionalidades adicionais, como evolução de Pokémon, marketplace para negociação de NFTs, e mais.

Tecnologias Utilizadas
Solidity: Linguagem utilizada para criar contratos inteligentes na rede Ethereum.
Remix IDE: Um ambiente online para desenvolvimento de contratos inteligentes.
MetaMask: Carteira digital usada para interagir com o contrato no blockchain.
OpenZeppelin: Biblioteca utilizada para a implementação do padrão ERC-721 e funcionalidades de segurança.
Funcionalidades
Criação de NFTs: Criação de Pokémons únicos com nome, nível e tipo (fogo, água, elétrico, etc).
Atributos Exclusivos: Cada NFT tem seu próprio conjunto de atributos e pode ser consultado diretamente no contrato.
Função de Mint: Apenas o dono do contrato pode criar novos NFTs.
Estrutura do Código
O contrato é desenvolvido em Solidity e implementa o padrão ERC-721, com as seguintes funcionalidades principais:

Pokemon Struct: Contém os atributos do Pokémon, como nome, nível e tipo.
Mapping pokemonCollection: Mapeia o ID do token para os detalhes do Pokémon.
Função mintPokemon: Mintar novos tokens NFTs para Pokémons exclusivos.
Função getPokemonDetails: Permite visualizar os detalhes do Pokémon por meio do ID do token.
Pré-Requisitos
Node.js: Certifique-se de ter o Node.js instalado para rodar o ambiente de desenvolvimento.
MetaMask: Instale a extensão do MetaMask no seu navegador.
Remix IDE: Acesse o Remix IDE para compilar e implantar o contrato.
Testnet Ethereum: Conecte sua MetaMask a uma rede de testes Ethereum como Rinkeby ou Goerli.
Instalação e Deploy
Clone este repositório:

bash
Copiar código
git clone https://github.com/seuusuario/PokemonNFT.git
Acesse o Remix IDE e crie um novo arquivo .sol.

Cole o código do contrato PokemonNFT.sol no Remix IDE.

Compile o contrato no Remix.

Conecte sua MetaMask ao Remix e selecione uma rede de testes Ethereum.

Faça o deploy do contrato clicando no botão Deploy.

Após o deploy, você pode começar a criar seus NFTs de Pokémon utilizando a função mintPokemon diretamente no Remix.

Exemplo de Uso
Aqui está um exemplo de como criar um novo Pokémon utilizando a função mintPokemon:

solidity
Copiar código
// Mint um novo Pokémon
mintPokemon("Pikachu", 5, "Electric");
Visualizando Detalhes
Para visualizar os detalhes de um Pokémon NFT específico, você pode usar a função getPokemonDetails(tokenId), onde tokenId é o ID do Pokémon NFT.

solidity
Copiar código
// Visualizar detalhes do Pokémon com tokenId 1
getPokemonDetails(1);
Expansões Futuras
Este projeto pode ser expandido para incluir as seguintes funcionalidades:

Sistema de Evolução de Pokémon: Uma função para aumentar o nível do Pokémon ao longo do tempo.
Marketplace de Pokémon: Criar um marketplace descentralizado onde os usuários podem comprar, vender e trocar Pokémons NFTs.
Sistema de Raridade: Implementar raridades e habilidades especiais para cada Pokémon.
Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request com melhorias e novas funcionalidades.

Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.


