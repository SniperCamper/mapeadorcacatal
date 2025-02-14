Mapeamento de Palavras
Este projeto é uma ferramenta web simples para mapear e destacar palavras em textos com base em um índice fornecido pelo usuário. A ferramenta permite que o usuário insira dois textos, destaque palavras específicas e visualize as palavras ao redor de um índice específico em ambos os textos.

Funcionalidades
Entrada de Texto: O usuário pode inserir dois textos nas áreas de texto fornecidas.

Destaque de Palavras: O usuário pode especificar palavras para destacar, separadas por espaços.

Índice de Palavra: O usuário pode inserir um índice para destacar uma palavra específica no texto. O índice pode começar em 0 ou 1, conforme selecionado pelo usuário.

Visualização Contextual: A ferramenta exibe as palavras ao redor do índice fornecido, destacando a palavra no índice e as palavras especificadas para destaque.

Estrutura do Código
HTML
Container Principal: Contém todos os elementos da interface do usuário.

Áreas de Texto: Duas áreas de texto para inserção dos textos.

Campo de Índice: Um campo de entrada para o índice da palavra a ser destacada.

Opções de Índice: Radio buttons para escolher se o índice começa em 0 ou 1.

Campo de Destaque: Um campo de entrada para palavras a serem destacadas.

Áreas de Resultado: Duas áreas para exibir os resultados processados dos textos.

CSS
Estilos Gerais: Define o layout e a aparência da página, incluindo cores, fontes e alinhamentos.

Estilos de Destaque: Define as cores e estilos para as palavras destacadas.

JavaScript
Processamento de Texto: Função para processar o texto, removendo caracteres especiais e dividindo o texto em palavras.

Atualização de Resultados: Função para atualizar os resultados exibidos com base no índice e nas palavras destacadas.

Event Listeners: Ouvintes de eventos para atualizar os resultados sempre que o usuário alterar o texto, o índice ou as palavras destacadas.

Como Usar
Insira o primeiro texto na primeira área de texto.

(Opcional) Insira o segundo texto na segunda área de texto.

Insira o índice da palavra que deseja destacar.

Escolha se o índice começa em 0 ou 1.

Insira as palavras que deseja destacar, separadas por espaços.

Os resultados serão exibidos automaticamente nas áreas de resultado, destacando a palavra no índice e as palavras especificadas.

Exemplo
Texto 1: "Este é um exemplo de texto para demonstrar a funcionalidade da ferramenta."

Texto 2: "Aqui está outro texto para comparar com o primeiro."

Índice: 5 (começando do 0)

Palavras para destacar: "exemplo ferramenta"

Resultado:

Texto 1: "Este é um exemplo de texto para demonstrar a funcionalidade da ferramenta."

Texto 2: "Aqui está outro texto para comparar com o primeiro."

Requisitos
Navegador moderno com suporte a HTML5, CSS3 e JavaScript.


Formatador de Texto
Este projeto é uma ferramenta web simples para formatar textos, removendo caracteres especiais e mantendo apenas letras, números, espaços e caracteres acentuados. A ferramenta é útil para limpar textos e prepará-los para uso em sistemas que não aceitam caracteres especiais.

Funcionalidades
Entrada de Texto: O usuário pode inserir o texto que deseja formatar em uma área de texto.

Formatação Automática: Ao clicar no botão "Formatar", o texto é processado para remover todos os caracteres especiais, exceto letras, números, espaços e caracteres acentuados.

Saída de Texto Formatado: O texto formatado é exibido em uma segunda área de texto, que é somente leitura.

Estrutura do Código
HTML
Container Principal: Contém todos os elementos da interface do usuário.

Área de Texto de Entrada: Uma área de texto para inserir o texto a ser formatado.

Botão de Formatação: Um botão que, ao ser clicado, executa a função de formatação.

Área de Texto de Saída: Uma área de texto somente leitura para exibir o texto formatado.

CSS
Estilos Gerais: Define o layout e a aparência da página, incluindo cores, fontes e alinhamentos.

Estilos de Botão: Define a aparência do botão de formatação, incluindo cores, sombras e efeitos de hover.

JavaScript
Função de Formatação: Uma função que remove todos os caracteres especiais do texto de entrada, exceto letras, números, espaços e caracteres acentuados, e exibe o resultado na área de texto de saída.

Como Usar
Insira o texto que deseja formatar na área de texto de entrada.

Clique no botão "Formatar".

O texto formatado será exibido na área de texto de saída.

Exemplo
Texto de Entrada: "Olá, mundo! Este é um exemplo de texto com caracteres especiais: @#$%^&*()."

Texto Formatado: "Olá mundo Este é um exemplo de texto com caracteres especiais"

Requisitos
Navegador moderno com suporte a HTML5, CSS3 e JavaScript.
