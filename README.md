# Altavilla Advocacia — Landing Page

Landing page institucional de um escritório de advocacia **fictício**, o **Altavilla Advocacia**.

> **Projeto de demonstração.** O escritório, o nome, a logo, a numeração de OAB (`OAB/UF 000.000`) e os textos são inventados e não têm relação com nenhum escritório ou advogado real. O site serve como portfólio e como modelo de layout.

O objetivo da página é apresentar o escritório, mostrar as áreas de atuação e levar o visitante à seção de contato.

---

## Estrutura da página

A página é de rolagem única e tem 5 partes, de cima para baixo.

### 1. Cabeçalho (menu)
Barra preta no topo, com a logo do escritório à esquerda (monograma "A" em dourado, o nome "ALTAVILLA", "ADVOCACIA" e o placeholder de OAB) e o menu de navegação.
 
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
- **Botão "Entre em contato"** (dourado): leva direto para a **seção de contato**, no final da página.
<img width="1347" height="600" alt="image" src="https://github.com/user-attachments/assets/4b6dba4a-1371-46b7-8a97-4e0d7de279a9" />

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
Faixa preta com o crédito: *© 2026 - Desenvolvido por: Vinícius Silva Rodrigues*.
<img width="1351" height="546" alt="image" src="https://github.com/user-attachments/assets/62cbf320-e91f-4e1c-85bc-590dc0b2584f" />

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


## Como rodar
 
O projeto é um site estático (HTML, CSS e Bootstrap). Não precisa instalar nada nem rodar servidor.
 
1. **Baixe o projeto.** No GitHub, clique em **Code > Download ZIP**. Se preferir usar o Git, rode `git clone <link-do-repositório>`.
2. **Extraia o ZIP** (se tiver baixado compactado), mantendo todas as pastas e arquivos juntos, sem mudar a organização. Mover só o HTML faz as imagens e os estilos pararem de carregar.
3. **Abra a pasta `bootstrap`.** O arquivo principal, o **`index.html`**, está dentro dela.
4. **Abra o `index.html` no navegador** com duplo clique (ou clique com o botão direito > Abrir com > Chrome, Edge ou Firefox).
**Dica (opcional):** para editar o código e ver as mudanças ao vivo, abra a pasta no VS Code e use a extensão **Live Server** (botão direito no `index.html` > *Open with Live Server*).
 
**Requisitos:**
 
- Um navegador atualizado (Chrome, Edge, Firefox ou Safari).
- Conexão com a internet, caso o projeto carregue o Bootstrap, as fontes ou os ícones por link externo (CDN). Sem internet, o visual pode aparecer sem estilo ou com fontes diferentes.

## Pontos de atenção

- **Conteúdo fictício:** nenhuma informação do site representa um escritório real. Se o layout for usado para um cliente de verdade, troque nome, OAB, textos, imagens e links, e confira as regras de publicidade da OAB.
- **Imagens:** use apenas imagens de uso livre (bancos gratuitos ou produzidas por você) e confira a licença antes de publicar.
- **Ícones de contato:** são só ilustração, sem link. Para que a troca de cor no hover funcione, os ícones precisam ser SVG inline com `fill="currentColor"` (ou Font Awesome). Com `<img>`, só a animação de subida funciona.

## Melhorias futuras

- **Responsividade:** o site **ainda não está totalmente responsivo**. O layout foi pensado principalmente para telas grandes e precisa de ajustes em tablets e celulares (menu, hero, cards das áreas de atuação, ícones de contato e espaçamentos). É algo para revisar daqui a um tempo.
- **Links reais** nos ícones de WhatsApp e Instagram, se o projeto deixar de ser só uma demonstração.

## Autoria

Desenvolvido por **Vinícius Silva Rodrigues**.
