# Spectral Castle

Jogo de ação e sobrevivência desenvolvido no Construct 3. Enfrente cinco ondas de espectros, evolua as habilidades do herói e liberte o castelo.

## Abrir o projeto

1. Baixe o arquivo **Spectral-Castle.c3p** deste repositório.
2. Acesse https://editor.construct.net/ e entre em uma conta gratuita.
3. Use **Abrir → Arquivo** e selecione o `.c3p`.
4. Execute a prévia para jogar.

O arquivo `.c3p` é o projeto editável. Não é uma versão HTML5 pronta para jogar pelo GitHub Pages.

## Controles

| Tecla | Ação |
|---|---|
| WASD | Movimentar |
| E | Atacar |
| Espaço, mantido pressionado | Erguer o escudo e bloquear dano |
| R | Reiniciar |

Solte Espaço para atacar. O escudo pode ser usado enquanto o personagem se movimenta. Sem defesa, cada golpe recebido tira meio coração.

## Progressão

- Cinco ondas de 25 segundos, com metas de 2, 2, 3, 3 e 4 abates.
- Velocidade, alcance e proteção após dano melhoram a cada onda.
- Dano do herói dobra na quarta onda.
- Os espectros ganham velocidade e resistência.
- Recuperação de um coração entre ondas, até o máximo de cinco.

## Estrutura

- `Spectral-Castle.c3p`: versão atual do projeto com escudo.
- `docs/controles-e-mecanicas.md`: detalhes da versão e das verificações realizadas.
- `docs/validacao.md`: roteiro de testes antes da entrega.

## Construct 3 gratuito

O projeto contém 35 entradas nas folhas de eventos, duas camadas e nenhum efeito. Use uma conta gratuita, pois o modo visitante tem um limite menor de eventos.

## Estado do projeto

A estrutura do arquivo foi verificada. A versão mais recente ainda precisa de uma partida completa de validação no Construct 3. Não é apresentada como uma versão Gold validada.

## Créditos

Os assets visuais e a trilha foram mantidos do projeto original fornecido pela equipe. As fontes, autores e licenças desses assets ainda precisam ser documentados. Nenhuma licença de redistribuição foi atribuída por este repositório.
