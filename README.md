# FitLife - Landing Page 📱💪

Landing page moderna, limpa e sofisticada desenvolvida para o **FitLife**, um aplicativo móvel voltado para o acompanhamento de uma vida fitness, organização de treinos e saúde.

## 🚀 Sobre o Projeto

Este projeto foi construído com foco em **design minimalista, acessibilidade e responsividade**, utilizando apenas HTML5 e CSS3 puro (sem frameworks pesados). A página apresenta uma interface limpa com predominância de tons claros e detalhes em verde elegante, transmitindo saúde, bem-estar e tecnologia.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estrutura otimizada para SEO e com suporte a leitores de tela (uso de tags como `header`, `main`, `section`, `article`, `footer`, além de atributos ARIA).
- **CSS3 Moderno:**
  - Variáveis CSS (`:root`) para padronização de cores.
  - Layouts flexíveis utilizando **Flexbox**.
  - Responsividade avançada com **Media Queries** e funções matemáticas como `clamp()`.
  - Importação da fonte **Roboto** via Google Fonts.

---

## 📂 Estrutura de Arquivos

```text
/
├── index.html       # Arquivo principal com a estrutura da landing page
├── style.css        # Folha de estilos customizada e responsiva
├── plan.md          # Planejamento inicial e diretrizes do projeto
└── images/          # Pasta contendo os prints e recursos visuais do app
    ├── print_1.png  # Tela principal (Hero)
    ├── print_2.png  # Tela de contagem de calorias
    ├── print_3.png  # Tela de exercícios específicos
    └── print_4.png  # Tela de compartilhamento com amigos
```

---

## 🧱 Seções da Landing Page

1. **Header (Cabeçalho):**
   - Logomarca minimalista em CSS (um círculo verde-escuro com a letra "F" centralizada) acompanhada do nome da marca.
   - Botão de ação rápida (*Call-to-Action*) para download no canto direito.

2. **Hero Section (Destaque Principal):**
   - Estrutura em três colunas (em telas maiores):
     - **Esquerda:** Eyebrow *"Seu ritmo, sua evolução"*, título principal (`<h1>`) e descrição.
     - **Centro:** Mockup em destaque com o print principal do aplicativo (`print_1.png`).
     - **Direita:** Lista de pontos-chave do app (Saúde, Exercício, Amigos) com ícones e fundos suaves.

3. **Seção de Funcionalidades (Features):**
   - Apresentação em formato zigue-zague (alternando imagem e texto entre esquerda e direita):
     - **01. Acompanhamento de calorias:** Foco em hábitos alimentares e visão diária (`print_2.png`).
     - **02. Exercício ideal:** Rotinas personalizadas para diferentes objetivos (`print_3.png`).
     - **03. Conquistas com amigos:** Recursos de motivação e compartilhamento social (`print_4.png`).

4. **Call to Action (CTA de Baixar):**
   - Bloco de conversão final com fundo suave, reforçando o valor do app e um botão grande de download acompanhado pelo selo *"Totalmente gratuito"*.

5. **Rodapé (Footer):**
   - Rodapé limpo com aviso de direitos reservados.

---

## 📱 Responsividade

O projeto foi totalmente planejado para se adaptar perfeitamente a diferentes tamanhos de tela:
- **Desktop:** Layout amplo em três colunas na Hero e cards em zigue-zague na seção de funcionalidades.
- **Tablets e Celulares:** Ajustes dinâmicos de espaçamento (`clamp`), empilhamento de elementos verticais e otimização visual para telas menores (como ocultar o texto da marca no header em telas reduzidas para priorizar o design compacto).

---

## 🚀 Como Executar o Projeto Localmente

1. Clone o repositório para o seu computador:
   ```bash
   git clone https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
   ```
2. Abra a pasta do projeto no seu editor de código favorito (como o **VS Code**).
3. Abra o arquivo `index.html` diretamente no seu navegador ou utilize uma extensão como o *Live Server*.

---

Desenvolvido com foco em performance e elegância. 🍃
