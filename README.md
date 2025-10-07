# 🎬 Projeto Web: Combinação Perfeita (A Perfect Pairing)

Um site desenvolvido para fãs do filme de comédia romântica da Netflix, **"Combinação Perfeita"** (2022). Este projeto é um exercício prático em **HTML5 e CSS3 responsivo**, utilizando técnicas modernas de layout.

---

## 👩‍💻 Desenvolvedora

| Nome Completo | Instituição |
| :--- | :--- |
| **Ingridy Vitória Aragão Alves** | IFSC (Instituto Federal de Santa Catarina) |

---

## ✨ Tecnologias Utilizadas

* **HTML5:** Estrutura semântica do conteúdo.
* **CSS3:** Estilização, responsividade e layout (Flexbox e CSS Grid).

---

## 🚀 Funcionalidades e Páginas

O site é estruturado em quatro páginas, todas compartilhando o mesmo **cabeçalho fixo** e o mesmo **rodapé centralizado**.

### 1. Página Inicial (`index.html`)

Apresenta o filme de forma visual e interativa:
* **Menu de Ícones:** Navegação secundária estilizada para as seções principais (`Elenco`, `Extras`, `Sobre`).
* **Áudio Integrado:** Player de música com reprodução automática e controles (`Home - Edith Whiskers`).

### 2. Página Elenco e Equipe (`elencoequipe.html`)

Detalha os profissionais envolvidos na produção:
* **Listas Organizadas:** Seções dedicadas a **Elenco**, **Produção**, **Direção**, **Roteiro**, etc., com links externos (AdoroCinema, IMDb).
* **Destaque Visual:** Imagem principal (`#vit`) com efeito de escala (`:hover`) e sombra.

### 3. Página Extras (`extra.html`)

Reúne informações adicionais e multimídia:
* **Trailer Oficial:** Vídeo incorporado via `<iframe>` do YouTube.
* **Galeria (`grid-galeria`):** Uso de **CSS Grid** para exibir imagens do filme em um layout responsivo, com *hover effect* nas fotos.
* **Curiosidades e Críticas:** Seções formatadas em parágrafos com detalhes sobre a produção e avaliações.

### 4. Página Sobre (`sobre.html`)

Contém a sinopse e detalhes técnicos:
* **Informações Técnicas:** Título, ano, gênero e duração do filme.
* **Sinopse Completa:** Descrição detalhada da trama.

---

## 🎨 Destaques de Estilização (CSS)

O projeto utiliza um conjunto de estilos para garantir uma identidade visual coesa baseada em tons de rosa e vinho:

* **Reset Global:** Uso de `box-sizing: border-box;` e zeragem de `margin` e `padding` em todos os elementos.
* **Layout Fixo:** `header` com `position: fixed` e `z-index` para sobrepor o conteúdo.
* **Flexbox na Navegação:** Utilizado para centralizar a lista de links no cabeçalho.
* **Design Coeso:** Uso de **Degradê linear** no `header` e sombras suaves (`box-shadow` com `rgba`).
* **Responsividade:** Uso de *Media Queries* para otimizar o layout, fontes e tamanhos de elementos em diferentes tamanhos de tela (Tablets e Smartphones).

---

## 🛠️ Como Visualizar o Projeto

1.  Baixe ou clone os arquivos do projeto.
2.  Mantenha a estrutura de pastas.
3.  Abra o arquivo **`index.html`** em qualquer navegador web moderno para começar a navegação.