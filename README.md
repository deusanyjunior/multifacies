# multifacies

Uma landing page que retrata uma entrevistada **multifacies**: uma só pessoa que
guarda muitas versões de si. O projeto nasceu de uma entrevista sobre percepção de
saúde, doença e tratamento, e transforma suas contradições em um retrato visual —
sempre **anonimizado**, feito apenas de ideias, tópicos e referências externas.

## O conceito

Um **ser central**, representado por uma silhueta abstrata e sem rosto, vive dentro
de um **icosaedro tridimensional**. O sólido tem doze vértices, e de cada um parte um
**encontro do ser**: uma faceta que carrega sua própria tensão interna (um paradoxo).
Nenhuma faceta cancela a outra — elas convivem, se tensionam e se completam, como um
grafo que irradia do núcleo.

Os doze encontros exploram tensões como:

- duas medicinas, uma raiz (homeopatia ↔ alopatia);
- o corpo como prática viva (teoria ↔ vivência);
- maternidade no plural (acolher ↔ respeitar o tempo);
- zelar pelo público, evitar o consultório (valorizar o sistema de saúde ↔ evitar médicos);
- usar a técnica sem se dizer técnica (tecnologia ↔ humanização);
- cuidar sem parar e não tolerar a dor (quase nunca adoecer ↔ uma dor de cabeça derruba);
- transmitir o que não se recebeu (pais apartados do corpo ↔ filhos com consciência corporal);
- saber da academia e escolher a água (o "tem que fazer" ↔ o que de fato se pratica);
- da Índia ao equilíbrio (corpo ↔ espírito);
- dizer não ao remédio e abrir uma exceção;
- a lei e o corpo (razão e Direito ↔ saber sensorial);
- madura e eterna aprendiz (meia-idade ↔ sempre estudando).

Cada faceta é ancorada em uma **referência externa** (Hipócrates, Eutonia, fáscias,
yoga, remo, enxaqueca, entre outras), nunca em uma pessoa.

## Privacidade

A página foi construída para **não identificar ninguém**. Não há nomes, idade, local,
profissão nem qualquer dado pessoal da entrevistada ou de terceiros. O conteúdo se
limita a tópicos, paradoxos e referências históricas ou conceituais.

## Tecnologia

Um único arquivo **HTML autossuficiente** — sem dependências, sem build e sem
bibliotecas externas:

- `landing-multifacies.html` — marcação, estilos (CSS) e lógica (JavaScript) embutidos.
- O icosaedro 3D é desenhado em um `<canvas>` com projeção em perspectiva e
  rotação em JavaScript puro (12 vértices, 30 arestas e 20 faces).
- Os cartões de cada encontro são gerados dinamicamente a partir de uma estrutura
  de dados no próprio script.

### Paleta

- **Vermelho** como cor predominante.
- **Verde** nos detalhes e acentos.

## Como usar

Abra o arquivo diretamente no navegador:

```
landing-multifacies.html
```

Não é preciso servidor nem instalação. Na figura central, **arraste para girar** o
icosaedro; ao soltar, a rotação automática é retomada.

## Licença

Domínio público (The Unlicense). Veja o arquivo [LICENSE](LICENSE).
