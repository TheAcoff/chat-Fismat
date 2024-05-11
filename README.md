# ChatBot para Auxílio em Anotações
ChatBot especializado em Física Matemática para auxiliar seus estudos com o método Zettelkasten utilizando o Obsidian! Faça upload de suas notas e aproveite para tirar dúvidas com livros selecionados e conteúdos das suas notas. Temos também auxílio direto na edição e melhoramento de suas notas.

---
# Ferramenta
Digite sua pergunta sobre um tema específico, pergunte sobre suas notas, peça sugestões de melhorias, corrija erros e muito mais, baseado nos seus livros e nas suas notas, podendo tirar sua dúvida ou potencializar suas anotações de forma automática.

---
# Obsidian
Aplicativo para tomar notas e separá-las por conexões entre os temas. Utilizamos recursos do sistema markdown. Para conectar suas notas, utilize [[tema]] dentro de uma anotação para linkar com outra. 

## Sincronização com o Drive
Baixe o aplicativo do Google Drive no seu PC e faza a sincronização da sua pasta cofre.

## Método Zettelkasten
Método de estudo destinado a reformular a forma de pensamento para os estudos. Ao invés de pular na aplicação ou em um tema avançado, começamos a estudar os conceitos individualmente, e progressivamente, vamos conectando os tópicos e ideias.

---
# Como usar o ChatBot?
Após fazer a sua sincronização com o Google Drive, insira sua chave API no Colab e autorize o _mount_ dos seus arquivos nos arquivos. Copie o endereço do seu cofre coloque na variável "pasta_origem". Caso queira que os novos arquivos fique em uma pasta separada para uma segunda análise no Obsidian, crie essa pasta e coloque na pasta "pasta_nova". Se não quiser, mantenha o endereço da "pasta_origem" em "pasta_nova"

O chat irá coletar seu primeiro comando, gerar um texto e perguntar se gostou ou não para melhorias. Use o comando "fim" para finalizar a seção. 

## Vantagens
Com a sua base de notas como "treinamento", ele pode seguir a sua formatação, seu estilo de links, e até mesmo a maneira em que escreve equações

## Exemplos:
Deixo junto com o PDF minhas notas pessoais de Física Matemática.

![Nota Antiga](https://github.com/TheAcoff/chat-Fismat/assets/87444624/ecec4e95-9b72-44c9-b152-9223261a808f)
![Nota Melhorada](https://github.com/TheAcoff/chat-Fismat/assets/87444624/874ee759-d2da-4889-99c9-7b882ef837d3)

# Futuras Melhorias
Para futuras versões, pretendo implementar um sistema de organização de pastas, para fazer um detalhamento melhor sobre tópicos da Física, além de expandir para PDF de livros mais avançados e sugestões de exercícios.






