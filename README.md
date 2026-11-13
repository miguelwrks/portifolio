# 🌟 Portfólio Profissional — mii.dev

## 👤 Nome do Aluno
**Miguel Silva Gonçalves**

---

## 💻 Descrição do Portfólio
Este projeto consiste em um **Portfólio Profissional** desenvolvido com foco acadêmico para a área de desenvolvimento de sistemas. O site foi estruturado para apresentar o perfil profissional, objetivos, competências técnicas, links para contato e uma seção dedicada à exibição de projetos realizados (incluindo aplicações em Python e páginas web interativas).

---

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Estruturação semântica de todas as páginas e seções.
* **CSS3:** Estilização personalizada e ajustes visuais.
* **Bootstrap (v5.3.3):** Framework CSS utilizado para garantir a responsividade do layout, organização em grid, componentes de navegação (navbar, cards, carousel) e utilitários.
* **Devicon:** Biblioteca de ícones para as tecnologias.
* **JavaScript:** Scripts do Bootstrap para controle de componentes interativos (como o menu mobile e o carrossel).
* **Git & GitHub:** Versionamento de código e hospedagem.

---

## 🔗 Link do Site Publicado
Você pode acessar o site publicado através do link:  
👉 [Portfólio Pessoal (GitHub Pages)](https://miguelwrks.github.io/portal-entreterimento-digital/)

---

## ⚙️ Explicação do Funcionamento do Projeto
O site é composto por uma página única (*single page* com navegação interna por âncoras) organizada nas seguintes seções principais:
1. **Menu de Navegação (Navbar):** Fixo no topo da página (*sticky-top*), permitindo transição rápida entre o perfil, projetos, interesses e contato, além de contar com suporte a dispositivos móveis (*responsivo*).
2. **Carrossel de Imagens:** Um destaque visual dinâmico com transição em fade no topo da página.
3. **Seção de Perfil:** Apresenta a biografia, informações de localização, formação, objetivos e as tecnologias/ferramentas estudadas com ícones visuais.
4. **Seção de Projetos:** Exibe cards interativos com imagens e descrições dos trabalhos desenvolvidos (Portfólio, Sistema em Python e Portal de Entretenimento Digital), com links diretos para visualização ou repositório.
5. **Seção de Contato:** Centraliza os meios de comunicação (E-mail, GitHub e LinkedIn) e localização.
6. **Rodapé:** Contém os créditos de desenvolvimento e ano atual.

---

## ✨ Descrição do Recurso Novo Adicionado
Como recurso adicional, foi implementada uma **Seção de Interesses Pessoais**, que vai além da programação tradicional. Nela, são compartilhados gostos pessoais do autor (como tecnologia/hardware retrô, música pop e leitura de livros) de forma dinâmica e interativa, incorporando vídeos diretamente do YouTube na página por meio de *iframes* embutidos dentro de cards organizados.

---

## 🚀 Como Esse Recurso Foi Implementado
A nova seção foi desenvolvida utilizando os seguintes conceitos e tecnologias:
* **Organização com Bootstrap (`grid` e `cards`):** A seção utiliza o sistema de grid do Bootstrap (`row`, `col-md-6`, `col-xl-4`) combinada com componentes de `card` (`h-100`, `shadow-sm`, `rounded-4`) para manter o alinhamento perfeito, responsividade e o padrão visual do restante do site em diferentes tamanhos de tela (computadores, tablets e celulares).
* **Incorporação de Vídeos via `<iframe>`:** Foram adicionadas tags `<iframe>` do YouTube dentro dos cards. Cada iframe recebeu o link em formato de incorporação (`/embed/`) fornecido pela plataforma, juntamente com parâmetros de controle de exibição (`title`, `frameborder`, `allowfullscreen`, etc.), permitindo que o usuário assista aos vídeos (sobre o console portátil Trimui Brick, músicas e recomendações de livros) diretamente na página do portfólio sem precisar sair dela.
