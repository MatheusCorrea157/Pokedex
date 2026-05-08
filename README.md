Uma Pokédex interativa construída com HTML, CSS e JavaScript puro, consumindo a PokéAPI para exibir informações detalhadas de qualquer Pokémon.

📸 Preview
Busque um Pokémon pelo nome ou número e veja seu card completo com imagem, tipos e status base.

Funcionalidades
- Busca por nome ou número do Pokémon
- Exibe a artwork oficial do Pokémon
- Mostra os tipos com cores correspondentes (fogo, água, grama, etc.)
- Exibe as stats base com barras de progresso animadas
- Suporte a busca via tecla Enter
- Mensagem de erro amigável para Pokémon não encontrado

Clone ou baixe o repositório:
bash
gitclone https://github.com/MatheusCorrea157/pokedex.git

Abra o arquivo index.html diretamente no navegador — sem necessidade de servidor ou instalação.
Digite o nome ou número de um Pokémon no campo de busca e clique em Buscar (ou pressione Enter).

 Tecnologias utilizadas:
Tecnologia               Uso
HTML5                    Estrutura semântica da página
CSS3                     Layout, animações e tema escuro
JavaScript (ES6+)        Lógica de busca e manipulação do DOM
PokéAPI                  Fonte dos dados dos Pokémons
Google Fonts – Poppins   Tipografia

A Pokédex reconhece e aplica cores automaticamente para todos os 18 tipos:
fire · water · grass · electric · psychic · ice · dragon · dark · fairy · normal · fighting · poison · ground · flying · bug · rock · ghost · steel

API utilizada
Os dados são obtidos em tempo real da PokéAPI:
GET https://pokeapi.co/api/v2/pokemon/{nome-ou-numero}
Nenhuma chave de API é necessária — a PokéAPI é pública e gratuita.

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

