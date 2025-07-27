<p align="center">
  <img src="https://github.com/Delaford/game/raw/master/src/assets/github/logo.png"/>
</p>

<div align="center">
<a href="https://discord.gg/nkZnHvD"><img src="https://camo.githubusercontent.com/b12a95e20b7ca35f918c0ab5103fe56b6f44c067/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636861742d6f6e253230646973636f72642d3732383964612e737667" alt="Discord" /></a>
  
Atualização de Julho de 2022: versão beta disponível em https://beta.delaford.com/

Me avise seu interesse no tópico de discussões do GitHub (https://github.com/delaford/game/discussions/152)!

</div> <p align="center"> <strong>Bem-vindo ao Delaford Game. Um jogo medieval online em 2D, feito com JavaScript e HTML5.</strong> <img width="704" alt="Captura de tela do jogo" src="https://github.com/delaford/game/blob/master/src/assets/github/readme_hero.png"> </p>

  Primeiros Passos
  Primeiro, faça um fork do repositório. Em seguida, vá até o seu terminal favorito:

    git clone git@github.com:YOUR_USERNAME/game.git
    cd game
    npm install
    npm run serve

> `npm run serve` iniciará o servidor de desenvolvimento e observará mudanças no código do lado do cliente dentro da pasta src e em outras partes aplicáveis.
Agora, ainda dentro da pasta game, abra outro terminal na mesma localização. Digite e execute:
 `npm run dev:node`. Isso iniciará o servidor de jogo Node.js.
Se quiser depurar, digite npm run ndb. O ndb é uma ferramenta de depuração da Google para Node.js que permite ver facilmente todo o contexto e variáveis. Altamente recomendado para facilitar o desenvolvimento.
Agora você pode visitar http://localhost:8080 para fazer login e começar a desenvolver!
Por favor, esteja ciente de um possível golpe relacionado ao Delaford que promete dinheiro por testes ou ações similares.

## Contribuindo
Confira nosso guia [CONTRIBUTING.md](https://github.com/Delaford/game/blob/master/.github/CONTRIBUTING.md) sobre como você pode participar ativamente do desenvolvimento deste jogo medieval. É bem fácil e divertido!

## Sistemas e Motores
Aqui estão os tipos de recursos que serão adicionados como produto mínimo viável (alpha). Não é nada exagerado, mas suficiente para cobrir o básico até que mais seja adicionado. Cada seção possui um link para um projeto que contém suas subtarefas.

O que significa um item com marca de verificação?
Quando um item está com marca de verificação, significa que a base foi implementada, mas não necessariamente finalizada. Por exemplo, o Inventário está marcado, mas atualmente só suporta armas. Você pode ajudar a expandir isso.

 - [Jogador](https://github.com/Delaford/game/projects/1)
  - [x] Caminhar / pathfinding
  - [x] Menu de contexto / Ações
  - [ ]  Vida e status
  - [x] Inventário
  - [x] Equipamento do personagem
  - [ ] Sua primeira missão

- [Interface do usuário](https://github.com/Delaford/game/projects/2)
  - [x] Aba de inventário
  - [ ] Aba de missões
  - [x] Caixa de chat (para jogadores e ações)
  - [x] Aba de equipamentos
  - [x] Aparência geral
  
 - [NPC](https://github.com/Delaford/game/projects/3)
  - [x] Comércio (Lojas)
  - [ ] Interação por diálogo
  - [x] Caminhando pelo mapa
  - [x] Banco

- [Monstros](https://github.com/Delaford/game/projects/3)
  - [ ] Sistema de Batalha
  - [ ] Coleta de itens (Loot)
  - [ ] Aparição (Spawning)

- [Via-Rede/Rede](https://github.com/Delaford/game/projects/5)
  - [x] Jogadores podem ser ver
  - [x] Personagens não jogáveis
  - [ ] Monstros
  - [ ] Troca entre jogadores
  - [x] Itens

- Mundo
  - [x] Sistema de renascimento
  - [ ] Habilidades de recurso
  - [ ] Jogador vs Jogador
  - [x] Mineração
  - [ ] Serralharia (Quase finalizado)
  - [ ] Pescaria
  - [ ] Culinária

Quando todos esses itens estiverem marcados, o Delaford estará estável sem mudanças drásticas. Mas, por enquanto, sinta-se à vontade para participar e ajudar a implementar essas funcionalidades!

## Depuração
Aprender a depurar neste jogo é essencial para interagir com o servidor Node.js e com o cliente. Sua principal ferramenta deve ser o ndb do Google. Ele oferece uma experiência de depuração drasticamente melhor para o lado do cliente. (https://github.com/GoogleChromeLabs/ndb) tool from Google. 
Leia mais em: [DEBUGGING.md](debugging.md).

## Noticias
 Aviso
Delaford contém trabalhos de várias fontes que não foram criadas diretamente por contribuições internas.
- Tileset, monstros, itens, personagens por David E. Gervais. · [Licença CC]
- Música da tela principal por Matthew Pablo. · [Licença CC]
- Fonte do jogo 'PixelMix' por Andrew Tyler
- Fonte do chat 'IBM VGA 8' por IBM
- Heroicons por Steve Schoger

# Status do Site
O site atualmente está fora do ar. O número de usuários não justificava o custo mensal.

# Aviso de Golpe
Contribuintes do Delaford, ou qualquer pessoa associada ao projeto, nunca entrarão em contato oferecendo dinheiro para testes ou solicitando que você baixe algo relacionado ao desenvolvimento do jogo em troca de pagamento ou criptomoeda.

Recebemos relatos verificados de pessoas fingindo ser donos do Delaford prometendo recompensas se os usuários baixarem pastas com os conteúdos do repositório. Fique atento!

## 👏 Agradecimentos
> - `ℹ️ Dan Jasnowski - https://github.com/djasnowski`

---

## 📄 Licença

Este projeto está licenciado sob a Licença  `MIT`. Veja o arquivo [LICENSE](https://github.com/nicollascarvalh0/delaford-game/blob/main/LICENSE) para obter informações adicionais.

---

