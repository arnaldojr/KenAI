# Definição do projeto

Uma inteligência artificial dedicada ao monitoramento de idosos, capaz de discernir entre seres humanos e outros objetos, rastreando suas atividades diárias, como comer, sentar, andar, deitar e levantar. Além disso, é apta a identificar a posição do indivíduo, seja deitado ou sentado, e alertar em caso de movimentos bruscos, como quedas. Também possui a capacidade de reconhecimento facial e identificação de objetos específicos, como remédios, celular e chaves, contribuindo para a segurança e o bem-estar dos idosos.

- a IA será capaz de identificar: um ser humano, movimentação (comer, sentar, andar, deitar, levantar, etc.), posição(deitada, sentada), movimentos bruscos(caídas), reconhecimento facial, objetos especificos(remédios, celular, chaves e etc).

## Rubricas

1.0 ***R1 - NOTA 2: Identificar pessoas*** -> Alice
A base do nosso projeto consiste na identificação de pessoas em câmeras e vídeos. Para isso, empregamos a biblioteca MediaPipe para capturar os principais pontos de referência do corpo, conhecidos como landmarks. Essa abordagem nos permite acessar todos os pontos do corpo, desde o nariz (representado pelo valor 0) até a ponta do pé (representado pelo valor 32).

Utilizamos o MediaPipe Solutions API para reconhecer esses landmarks e criar conexões de pose para formar um "esqueleto" da pessoa. Com o auxílio da função draw_landmarks, podemos desenhar facilmente essas conexões. Além disso, podemos personalizar a cor dos landmarks e das conexões usando o DrawingSpec.


1.1 ***R4 - NOTA 2: Identificar objetos*** -> Ester

2.0 ***R2 - NOTA 1: Identificar posição*** -> Guilherme

2.1 ***R5 - NOTA 2: Reconhecimento facial*** -> Larissa

3 ***R3 - NOTA 1: Identificar movimentos bruscos*** -> Alice

4 ***R6 - NOTA 2: Unir posição com objetos e pessoa para definição de ações*** -> Mateus/Todos
