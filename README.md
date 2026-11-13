# Altavilla Advocacia — Landing Page

Landing page institucional de um escritório de advocacia **fictício**, o **Altavilla Advocacia**.

> **Projeto de demonstração.** O escritório, o nome, a logo, a numeração de OAB (`OAB/UF 000.000`) e os textos são inventados e não têm relação com nenhum escritório ou advogado real. O site serve como portfólio e como modelo de layout.

O objetivo da página é apresentar o escritório, mostrar as áreas de atuação e levar o visitante à seção de contato.
 
---
# Link github pages

https://vinirodrigues-hub.github.io/altavilla-advocacia/

## Estrutura da página

A página é de rolagem única e tem 5 partes, de cima para baixo.

### 1. Cabeçalho (menu)
Barra azul escura no topo, com a logo do escritório à esquerda (monograma "A" em dourado, o nome "ALTAVILLA", "ADVOCACIA" e o placeholder de OAB) e o menu de navegação. Quando desce pelas abas a barra fica transparente.
 
| Item do menu | O que faz |
|---|---|
| **Início** | Leva ao topo da página (seção principal). |
| **Sobre** | Leva à seção "Sobre a empresa". |
| **Áreas de atuação** | Leva à seção com os cards das áreas do direito. |
| **O escritório** | Leva à seção "O escritório", que vem logo depois das áreas de atuação. |
| **Contato** | Leva à seção de contato, no final da página. |

### 2. Início (hero)
Seção de abertura com fundo escuro, detalhes em dourado e uma imagem da estátua da Justiça com livros ao fundo.

- **Rótulo:** "ALTAVILLA ADVOCACIA"
- **Título:** "Seus direitos merecem atenção e cuidado."
- **Texto de apoio:** apresenta a atuação baseada em ética, transparência e dedicação.
- **Botão "Agende sua consulta"** (dourado): leva direto para a **seção de contato**, no final da página.
<img width="1341" height="632" alt="image" src="https://github.com/user-attachments/assets/2da439a0-b7cd-43b0-bd30-f1a770a44e64" />


### 3. Sobre a empresa
Fundo bege claro, em duas colunas: à esquerda o título "Compromisso, qualidade e confiança em cada projeto."; à direita três parágrafos sobre o escritório (propósito de tornar o caminho jurídico mais claro, ética e transparência, e as áreas em que atua). Seção apenas informativa, sem botões.
<img width="1349" height="536" alt="image" src="https://github.com/user-attachments/assets/2d79b7f7-ee58-4d3c-a3d2-5852a730277b" />

### 4. Áreas de atuação
Título "Áreas de atuação" com o rótulo "COMO PODEMOS AJUDAR" e uma breve introdução. Abaixo, três cards com cantos retos e borda fina:

| Nº | Área | Resumo |
|---|---|---|
| 01 | **Direito Bancário** | Orientação em contratos bancários, empréstimos e financiamentos. |
| 02 | **Direito Civil** | Orientação em contratos, responsabilidade civil, indenizações e relações jurídicas do cotidiano. |
| 03 | **Direito Previdenciário** | Informações e acompanhamento em demandas relacionadas a benefícios previdenciários. |

Os cards **não são botões e não levam a lugar nenhum**. Ao passar o mouse, o card aumenta levemente, ganha uma sombra suave e a borda fica dourada (efeito apenas visual). O terceiro card fica centralizado e mais estreito, de propósito.
<img width="1348" height="602" alt="image" src="https://github.com/user-attachments/assets/3a4a22b9-bdbb-4a0e-a792-fbd52a3b5bb2" />

### 5. O escritório
Seção com fundo azul-marinho escuro, que vem logo depois das áreas de atuação. À esquerda aparece a logo do Altavilla Advocacia (monograma "A" dourado, nome e placeholder de OAB). À direita ficam:
 
- **Rótulo:** "O ESCRITÓRIO", com um pequeno traço dourado.
- **Título:** "Uma advocacia próxima, estratégica e humana."
- **Texto:** explica o propósito de tornar o caminho jurídico mais compreensível, com atenção individualizada e acompanhamento alinhado às necessidades de cada cliente.
- **Botão "Entre em contato"** (dourado): leva para a **seção de contato**, no final da página.
<img width="1345" height="601" alt="image" src="https://github.com/user-attachments/assets/bcbbb533-0019-462d-99cf-c07f8b89615c" />

### 6. Entre em contato
Fundo bege, rótulo "ENTRE EM CONTATO", o título "Vamos conversar sobre o seu caso?" e um texto curto convidando o visitante a enviar uma mensagem. À direita, dois ícones:

| Ícone | Função |
|---|---|
| **WhatsApp** | **Meramente ilustrativo. Não tem funcionalidade e não leva a lugar nenhum.** |
| **Instagram** | **Meramente ilustrativo. Não tem funcionalidade e não leva a lugar nenhum.** |

Os ícones só existem para mostrar como ficaria o contato em um site real. Em um projeto real, bastaria colocar o link do WhatsApp e do perfil do Instagram nos dois ícones.

### Rodapé
Faixa azul escura com o crédito: *© 2026 - Desenvolvido por: Vinícius Silva Rodrigues*.
<img width="1340" height="501" alt="image" src="https://github.com/user-attachments/assets/b134578f-53da-4d97-b4a0-d25bb74e5cbf" />


---

## Identidade visual

| Elemento | Valor |
|---|---|
| Dourado (rótulos, bordas no hover, botão) | `#B8903F` |
| Fundo escuro (menu, hero, rodapé) | preto, em torno de `#0b0b0b` |
| Fundo claro das seções | bege suave |
| Fontes | títulos em fonte serifada e textos em sem serifa (referência: Playfair Display e DM Sans) |
| Logo | monograma "A" dourado dentro de círculo duplo, criado para este projeto |
| Estilo | Sóbrio, cantos retos, bordas finas, bastante espaço em branco |

## Tecnologias

- HTML5
- CSS3 (transições, hover, `filter: drop-shadow`)
- Bootstrap (sistema de grid: `row` e `col-lg-*`)

## Pontos de atenção

- **Conteúdo fictício:** nenhuma informação do site representa um escritório real. Se o layout for usado para um cliente de verdade, troque nome, OAB, textos, imagens e links, e confira as regras de publicidade da OAB.
- **Imagens:** use apenas imagens de uso livre (bancos gratuitos ou produzidas por você) e confira a licença antes de publicar.
- **Ícones de contato:** são só ilustração, sem link. Para que a troca de cor no hover funcione, os ícones precisam ser SVG inline com `fill="currentColor"` (ou Font Awesome). Com `<img>`, só a animação de subida funciona.

## Melhorias futuras

- **Links reais** nos ícones de WhatsApp e Instagram, se o projeto deixar de ser só uma demonstração.

## Autoria

Desenvolvido por **Vinícius Silva Rodrigues**.
