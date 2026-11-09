# 🎵 Sistema Musical

Aplicação web interativa para gerenciamento e organização de biblioteca musical, artistas e cadastros. Desenvolvida para oferecer uma interface limpa, intuitiva e responsiva aos usuários.

---

## 📌 Funcionalidades

- **Dashboard Principal:** Painel inicial centralizado com acesso rápido às seções do sistema e controle de sessão.
- **Gerenciamento de Artistas:** Área dedicada para cadastro, listagem e edição dos dados dos artistas.
- **Biblioteca Musical:** 
  - Listagem completa das músicas cadastradas em tabela estruturada.
  - Filtros avançados por busca geral (título, álbum ou artista), seleção por artista e por gênero musical.
  - Ações rápidas em cada registro: botão para assistir diretamente no YouTube, editar dados e excluir registros.
- **Cadastro de Músicas:** Formulário completo com campos para:
  - Seleção de Artista e Título (obrigatórios)
  - Álbum e Gênero Musical
  - Link do YouTube com validação de URL
  - Upload de Capa do Álbum (suporte a JPG/PNG até 5MB)
  - Campo expansível para Letra da Música (opcional)

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica de formulários, tabelas, modais e elementos de navegação.
- **CSS3:** Estilização moderna utilizando CSS Grid, Flexbox, efeitos de hover, padronização de cores e layout responsivo.

---

## 📁 Estrutura de Arquivos

```text
.
├── cadastro_artista.html # Formulário de cadastro de artista
├── cadastro_musica.html # Formulário de cadastro de novas músicas
├── index.html          # Painel principal / Dashboard
├── listagem_musicas.html     # Listagem e busca de músicas
├── login.html       # Cadastro do usuário
└──  styles.css       # Estilos globais e componentes visuais
