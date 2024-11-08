Battle Card Game com Unity e Vuforia

Fiz este projeto para demonstrar um Battle Card Game baseado em mitologia chinesa, desenvolvido com Unity e Vuforia. O objetivo é transformar um jogo de cartas físico em uma experiência mista de jogo digital e galeria virtual, utilizando realidade aumentada para rastrear e exibir modelos 3D.

Funcionalidades da Primeira Versão
Nesta versão inicial do projeto, foram implementadas as seguintes funcionalidades:

Rastreamento de Cartas: O Vuforia foi configurado para rastrear 56 cartas diferentes, com uma taxa de sucesso de quase 100%. Apenas menos de 5 cartas apresentaram dificuldades de detecção.

Modelos 3D Visíveis: Os modelos 3D, inseridos através do Unity, estão visíveis na aplicação, proporcionando uma experiência imersiva para o usuário.

Posição dos Campos: Para evitar erros de posicionamento, as posições dos campos foram travadas, permitindo que as cartas sejam posicionadas sobre eles sem afetar a posição de mundo interna do Unity.

Interface de Usuário (UI): A interface exibe a posição das cartas invocadas e permite que o usuário encerre o turno, um recurso essencial para futuras animações de visualização.

Exibe também informações sobre o jogador da vez e a rodada atual, facilitando o acompanhamento do progresso da partida.

![image](https://github.com/user-attachments/assets/56f08d4c-0b5d-4e0e-a22f-12de421bfa4a)

Img1.: Modelos em 3D das invocações.

![image](https://github.com/user-attachments/assets/ba652162-8850-40c6-95aa-c98c051c779a)

Img2.: Visualização em Realidade Aumentada do jogo mostrando cartas em posições de partida real.

![image](https://github.com/user-attachments/assets/5b4b51fa-c685-4eb3-a0ac-fa7cf6be3ac2)

Img3.: Visualização Virtual do jogo mostrando a Img2 dentro do computador.
