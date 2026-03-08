# terminalzinho

Um terminal falso onde crianças podem digitar qualquer coisa e receber respostas divertidas e seguras. Um único arquivo HTML, sem dependências, funciona offline.

Traduzido e adaptado por [@gutogarrote](https://github.com/gutogarrote) a partir da criação de [@meimakes](https://x.com/meimakes)


<img width="946" height="519" alt="image" src="https://github.com/user-attachments/assets/a957eac1-a42c-44b5-96a0-21b5253b4b34" />

## Problema

A maioria dos aplicativos de "aprender a digitar" são exercícios entediantes ou exigem cadastro e instalação. Crianças pequenas e pré-leitoras precisam de algo que recompense cada tecla pressionada — palavras reais E teclado amassado — sem frustração ou estados de falha.

## Solução

Um terminal no navegador que responde a tudo que uma criança digita:

- **Animais** — arte ASCII + sons para 20 animais (gato, cachorro, tubarão, dinossauro, lagosta...)
- **Veículos** — caminhões, aviões, foguetes, escavadeiras, guindastes, tratores...
- **Cores** — digite uma cor, veja emojis de coisas com essa cor
- **Letras** — digite qualquer letra, veja ela grande com seu animal
- **Números** — digite um número, veja essa quantidade de emojis. Números grandes (1000+) ganham uma animação de contagem
- **Teclado amassado** — sempre divertido! Explosões de emojis, criaturas feitas das letras digitadas, feitiços arco-íris
- **Desafios** — após algumas entradas sem sentido, aparece um desafio com imagem ("que animal é esse?") para incentivar a digitar palavras reais

Nada é nunca um erro. Cada tecla pressionada é uma vitória.

## Como usar

Abra o arquivo `index.html` em qualquer navegador. É isso. Só isso/

Funciona no computador e no celular. Suporta modo claro e escuro (segue a preferência do sistema).

## Funcionalidades

- Zero dependências, zero build, zero servidor
- 20 animais com arte ASCII
- 12 veículos com arte ASCII
- 10 cores com coleções de emojis
- Alfabeto completo com associações de animais
- Visualização de números (1-10: fileiras de emojis, 11-999: exibição em escala, 1000+: animação de contagem)
- Detecção de teclado amassado com 5 tipos de resposta variados
- Desafios com imagens que incentivam a digitar palavras reais
- Piadas, palavras mágicas, festa dançante, modo arco-íris
- Modo escuro + modo claro (prefers-color-scheme)
- Arte ASCII "hello!" de boas-vindas com emojis aleatórios a cada carregamento
- Bilíngue: funciona em português e inglês (gato/cat, aviao/airplane, vermelho/red...)

## Comandos disponíveis

| Português | Inglês | O que faz |
|-----------|--------|-----------|
| gato, cachorro, sapo... | cat, dog, frog... | Mostra arte ASCII + som do animal |
| aviao, foguete, trem... | airplane, rocket, train... | Mostra arte ASCII + som do veículo |
| vermelho, azul, verde... | red, blue, green... | Mostra emojis dessa cor |
| a, b, c... | a, b, c... | Mostra a letra grande com um animal |
| 1, 2, 3, 1000... | 1, 2, 3, 1000... | Mostra emojis ou animação de contagem |
| piada | joke | Conta uma piada |
| danca / festa | dance / party | Festa de dança! |
| magia / abracadabra | magic / abracadabra | Feitiço mágico |
| arco-iris | rainbow | Arco-íris colorido |
| robo | robot | Mostra o robô |
| lua / sol / estrelas | moon / sun / stars | Emojis do espaço |
| animais | animals | Lista todos os animais |
| veiculos | vehicles | Lista todos os veículos |
| cores | colors | Lista todas as cores |
| letras | letters | Mostra o alfabeto |
| numeros | numbers | Mostra os números |
| limpar | clear | Limpa a tela |
| eu sou [nome] | i am [nome] | Cumprimento personalizado |
| ajuda | help | Mostra os comandos principais |

## Filosofia de Design

- Toda entrada recebe uma resposta positiva
- Saída curta — linhas simples, sem parágrafos
- Visual em vez de textual (emojis, arte ASCII, letras grandes)
- Teclado amassado é celebrado, palavras reais são recompensadas mais
- Incentivos suaves para digitar palavras reais através de desafios com imagens
- Sem pontuação, sem falhas, sem anúncios, sem rastreamento

## Mais como este

[@meimakes](https://x.com/meimakes) criou o tiny-terminal como parte do ensino de pensamento computacional para seu filho de 3 anos através da brincadeira. Ela escreveu um currículo completo sobre isso — [12 Weeks of Tech Projects to Build With Your Kid](https://shop.raisingpixels.dev/l/12-weeks-tech-projects). 60 atividades, principalmente desplugadas, para idades de 2 a 6 anos.

## Licença

MIT
