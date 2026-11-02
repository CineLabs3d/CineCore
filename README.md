# CineCore
Framework de IA integrado ao Claude para criação automatizada de vídeos animados explicativos em 3D, com cenários, animações, elementos 2D e efeitos visuais e sonoros.


💻 Instalação

A instalação pode ser realizada com auxílio de uma inteligência artificial ou manualmente.

🤖 Método 1 — Instalação com IA

Recomendado para quem utiliza Claude Code.

Passo 1. Abra a pasta do CineCore em uma IA de programação compatível.

Passo 2. Solicite a instalação utilizando a seguinte instrução:

Leia o arquivo instrucoes/INSTALAR.md
e instale o CineCore seguindo todas
as instruções disponíveis.

Configure o projeto, instale as dependências,
verifique a instalação e configure a skill
/cinecore.

A IA seguirá as instruções de instalação, incluindo:

Cópia e configuração do projeto.

Download dos pacotes necessários.

Instalação do navegador de renderização.

Verificação da instalação.

Geração de uma imagem de teste.

Instalação da Skill /cinecore.

🛠️ Método 2 — Instalação manual

Também é possível instalar sem utilizar uma IA.

Windows:

Execute:

instrucoes/instalar.ps1

macOS / Linux:

Execute:

sh instrucoes/instalar.sh

📌 Para obter informações completas, consulte instrucoes/INSTALAR.md.

🧩 Skill CineCore

O projeto possui uma Skill chamada /cinecore, responsável por orientar o Claude durante o processo de criação dos vídeos.

Ela faz parte da estrutura do projeto e pode ser instalada seguindo as instruções disponíveis no repositório.

📌 Regras de produção

O CineCore possui algumas regras fixas de funcionamento:

📱 Os vídeos são produzidos exclusivamente no formato vertical.

🎭 Cada novo tema recebe um personagem e uma roupa novos.

🎬 A IA constrói as cenas acompanhando o Remotion Studio ao vivo.

✅ O roteiro e a ficha de cenas precisam ser aprovados.

✅ A folha visual com todas as cenas também precisa ser aprovada.

❓ Perguntas frequentes

<details>
<summary>🤔 O que é o CineCore?</summary>

É um framework que utiliza inteligência artificial para auxiliar na criação de vídeos animados explicativos em 3D.

</details>

<details>
<summary>🤖 Preciso utilizar o Claude?</summary>

O projeto foi desenvolvido para trabalhar com o Claude como inteligência central. Consulte as instruções de instalação para conhecer o fluxo de utilização.

</details>

<details>
<summary>🎬 Posso criar vídeos sobre qualquer assunto?</summary>

O CineCore foi desenvolvido para vídeos curtos explicativos. Você pode informar diferentes temas para a IA preparar o conteúdo.

</details>

<details>
<summary>📱 Posso produzir vídeos horizontais?</summary>

Não. O formato de produção definido atualmente é exclusivamente vertical, na proporção 9:16.

</details>

<details>
<summary>🛠️ Preciso instalar tudo manualmente?</summary>

Não. Você pode utilizar uma IA de programação para realizar a instalação seguindo o arquivo instrucoes/INSTALAR.md.

</details>

🧪 Status do projeto

<kbd> BETA </kbd>

O CineCore está em sua versão Beta.

Isso significa que o framework ainda está em desenvolvimento e pode receber melhorias, correções e atualizações.

🤝 Contribuições

Ideias, sugestões, melhorias e contribuições são bem-vindas!

Se você deseja contribuir:

Faça um Fork do repositório.

Crie uma Branch para sua alteração.

Realize suas modificações.

Envie um Pull Request explicando o que foi alterado.

Toda contribuição que ajude a melhorar o CineCore é bem-vinda!

🌟 Agradecimentos

Agradecimentos às tecnologias e ferramentas que tornam este projeto possível:

🤖 Claude — Inteligência artificial.

🧊 Three.js — Construção e renderização 3D.

🎞️ Remotion — Composição e renderização de vídeos.

