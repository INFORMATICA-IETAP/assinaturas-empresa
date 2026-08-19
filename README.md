Galeria de Assinaturas Corporativas
Este repositório foi criado para hospedar e centralizar as imagens de assinaturas de e-mail dos colaboradores da empresa, utilizando o GitHub Pages como servidor CDN de alta disponibilidade.

🎯 Finalidade do Projeto
Hospedagem Permanente: Manter o upload das assinaturas em um servidor estável e gratuito, evitando links quebrados e imagens expiradas no e-mail.

Sincronização com o Outlook Web: Permitir que o departamento de TI e os colaboradores copiem e colem facilmente a imagem da assinatura no e-mail sem bloqueios de segurança do navegador.

Manutenção Centralizada: Atualizar a imagem de um colaborador sem a necessidade de reconfigurar individualmente a assinatura na máquina ou na conta do usuário.

🛠️ Como Utilizar a Galeria
Acesse o site publicado no GitHub Pages:

[https://informatica-ietap.github.io/assinaturas-empresa/](https://informatica-ietap.github.io/assinaturas-empresa/)

Localize o card com a assinatura desejada.

Clique com o botão direito do mouse sobre a imagem e selecione "Copiar imagem".

No editor de assinaturas do Outlook Web, cole a imagem (Ctrl + V) no campo correspondente e salve.

📂 Estrutura do Repositório
Plaintext
├── ASSINATURAS/          # Pasta contendo os arquivos de imagem (.png)
├── index.html            # Galeria dinâmica em HTML/JS
└── README.md             # Documentação do repositório
➕ Como Adicionar uma Nova Assinatura
Abra a pasta ASSINATURAS/.

Clique em Add file > Upload files, envie o novo arquivo e clique em Commit changes.

Volte à raiz do repositório, abra o arquivo index.html e clique no ícone do Lápis ✏️ (Edit).

Dentro do script, adicione o nome do novo arquivo na lista const imagens = [...]:

JavaScript
const imagens = [
  // ...
  "Nome do Colaborador.png",
];
Clique no botão Commit changes. O GitHub Pages atualizará o site automaticamente em até 2 minutos.
