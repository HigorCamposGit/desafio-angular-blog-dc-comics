# 🦇 DC Comics Portal - Angular UI.

## 🙏 Agradecimentos e Créditos

Este projeto foi desenvolvido com base no excelente repositório de estudos de blog em Angular criado pelo professor **Felipe Aguiar**. 

- **Repositório Original:** [angular-blog by Felipe Aguiar](https://github.com/felipeAguiarCode/angular-blog)
- **Canal/Perfil do Professor:** [Felipe Aguiar no GitHub](https://github.com/felipeAguiarCode)

Todo o design visual e a estrutura inicial serviram como base para os meus estudos e customizações pessoais neste projeto.

---

## 🚀 Tecnologias e Ferramentas Utilizadas

- **Angular** (Componentes, Roteamento e Arquitetura SPA).
- **HTML5** (Marcação semântica).
- **CSS3** (Flexbox, Grid, Variáveis, Transições e Efeitos Neon).
- **TypeScript** (Lógica dos componentes).
- **Google Fonts** (Tipografia *Open Sans*).
- **Git & GitHub** (Controle de versão e publicação).

---

## 🎨 Identidade Visual & Paleta de Cores

O projeto foi construído com  base no repo fornecido e pelas aulas com foco em uma experiência visual imersiva e limpa, eliminando artefatos visuais.

- **Fundo Geral (`body`)**: `#050814` (Azul noturno profundo e imersivo)
- **Fundo dos Cards (`.container`)**: `#0b1329` (Azul escuro em camadas)
- **Bordas**: `#1e3a8a` (Azul clássico)
- **Efeito Neon / Hover Accent**: `#3b82f6` com sombras customizadas (`box-shadow` e `inset`)
- **Tipografia**: Cores em branco puro (`#ffffff`) para títulos e cinza claro (`#a8b2d1`) para descrições.

---

## 🧩 Arquitetura de Componentes e Base de Layout

O projeto segue os princípios de componentização e encapsulamento do Angular, dividindo a interface entre componentes estruturais de layout e unidades reutilizáveis de dados:

1. **Componentes de Layout e Estrutura**:
   - **`MenuBarComponent`**: Barra de navegação superior com botões estilizados no mesmo padrão neon dos cards.
   - **`MenuTitleComponent`**: Cabeçalho estilizado centralizado com linhas decorativas (`hr`) e título destacado.

2. **Base de Componentes (Cards de Conteúdo)**:
   - **`BigCardComponent`**: Card principal em destaque (lado esquerdo) para artigos de grande importância, contendo imagem de capa em destaque, título e descrição.
   - **`SmallCardComponent`**: Cards secundários organizados em lista lateral (lado direito) com miniaturas de imagem e links dinâmicos via roteamento.

---

## ⚙️ Conceitos e Lógica de Implementação

- **Construtores (`constructor`)**: Utilizados nos componentes para injeção de dependências e inicialização de estados locais quando necessário antes da renderização do template.
- **Passagem de Dados Dinâmicos (`@Input`)**: Utilização de propriedades decoradas com `@Input()` para injetar dados dinâmicos (como títulos, descrições, IDs e caminhos de imagens) diretamente nos componentes reutilizáveis (`BigCard` e `SmallCard`), permitindo que a mesma estrutura exiba conteúdos diferentes vindos de fontes mockadas ou APIs.
- **Múltiplos CSS em um Componente**: Configuração avançada de estilos locais e múltiplos arquivos de estilização e escopo por componente através da propriedade `styleUrls` no decorator `@Component`, permitindo modularizar regras visuais específicas sem conflitos globais.

---

## 🛠️ Técnicas e Desafios Resolvidos

- **Isolamento de Estilos no Angular (Shadow DOM / Encapsulamento)**: Utilização bem-sucedida de seletores específicos e escopos isolados para evitar heranças indesejadas de cores e fundos vindos do navegador ou resets globais.
- **Efeitos de Transição e Hover**: Implementação de elevação suave (`transform: translateY`) combinada com sombras de neon dinâmicas (`box-shadow`) para interatividade ao passar o mouse.
- **Layout Responsivo**: Estruturação baseada em **Flexbox** e controle de larguras máximas para garantir que o layout se adapte perfeitamente entre dispositivos móveis e telas grandes.

---
---

🔗 Conecte-se comigo: [HigorCamposGit](https://github.com/HigorCamposGit) (Higor de Campos)
