# AngularBlog.
# 🦇 DC Comics Portal - Angular UI.

U## 🙏 Agradecimentos e Créditos

Este projeto foi desenvolvido com base no excelente repositório de estudos de blog em Angular criado pelo professor **Felipe Aguiar**. 

* **Repositório Original:** [angular-blog by Felipe Aguiar](https://github.com/felipeAguiarCode/angular-blog)
* **Canal/Perfil do Professor:** [Felipe Aguiar no GitHub](https://github.com/felipeAguiarCode)

Todo o design visual e a estrutura inicial serviram como base para os meus estudos e customizações pessoais neste projeto.

---

## 🚀 Tecnologias e Ferramentas Utilizadas

* **Angular** (Componentes, Roteamento e Arquitetura SPA)
* **HTML5** (Marcação semântica)
* **CSS3** (Flexbox, Grid, Variáveis, Transições e Efeitos Neon)
* **TypeScript** (Lógica dos componentes)
* **Google Fonts** (Tipografia *Open Sans*)
* **Git & GitHub** (Controle de versão e publicação)

---

## 🎨 Identidade Visual & Paleta de Cores

O projeto foi construído do zero com foco em uma experiência visual imersiva e limpa, eliminando artefatos visuais (como fundos pretos indesejados e marcadores de lista) e aplicando o seguinte padrão de cores:

* **Fundo Geral (`body`)**: `#050814` (Azul noturno profundo e imersivo)
* **Fundo dos Cards (`.container`)**: `#0b1329` (Azul escuro em camadas)
* **Bordas**: `#1e3a8a` (Azul clássico)
* **Efeito Neon / Hover Accent**: `#3b82f6` com sombras customizadas (`box-shadow` e `inset`)
* **Tipografia**: Cores em branco puro (`#ffffff`) para títulos e cinza claro (`#a8b2d1`) para descrições.

---

## 🧩 Arquitetura de Componentes

O projeto segue os princípios de componentização do Angular, garantindo alta reutilização de código e separação de responsabilidades:

1. **`MenuBarComponent`**: Barra de navegação superior com botões estilizados no mesmo padrão neon dos cards.
2. **`MenuTitleComponent`**: Cabeçalho estilizado centralizado com linhas decorativas (`hr`) e título destacado.
3. **`BigCardComponent`**: Card principal em destaque (lado esquerdo) para artigos de grande importância, contendo imagem de capa em destaque, título e descrição.
4. **`SmallCardComponent`**: Cards secundários organizados em lista lateral (lado direito) com miniaturas de imagem e links dinâmicos via roteamento (`[routerLink]`).

---

## 🛠️ Técnicas e Desafios Resolvidos

* **Isolamento de Estilos no Angular (Shadow DOM)**: Utilização bem-sucedida de seletores específicos e a diretiva `!important` no escopo dos componentes para evitar heranças indesejadas de cores e fundos pretos vindos do navegador ou resets globais.
* **Remoção de Artefatos de Lista**: Limpeza rigorosa de marcadores (`list-style: none`) em tags estruturais para garantir o alinhamento visual perfeito dos small cards.
* **Efeitos de Transição e Hover**: Implementação de elevação suave (`transform: translateY`) combinada com sombras de neon dinâmicas (`box-shadow`) para interatividade ao passar o mouse.
* **Layout Responsivo**: Estruturação baseada em **Flexbox** e controle de larguras máximas para garantir que o layout se adapte perfeitamente entre dispositivos móveis e telas grandes.

---


