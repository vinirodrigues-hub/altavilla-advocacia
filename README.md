# Dorneles Advocacia — Landing Page

Landing page institucional do escritório **Dorneles Advocacia** (OAB/DF 73.360), com o lema *Estratégia • Técnica • Resultados*.

O objetivo do site é apresentar o advogado e o escritório, mostrar as áreas de atuação e levar o visitante a entrar em contato (WhatsApp ou Instagram).

> **Sobre o projeto:** a marca Dorneles Advocacia pertence a um familiar (primo) do desenvolvedor. O site foi criado como um trabalho para ele. Logo, textos, imagens e identidade visual pertencem ao escritório e não devem ser reutilizados sem autorização.

---

## Estrutura da página

A página é de rolagem única e tem 5 partes, de cima para baixo.

### 1. Cabeçalho (menu)
Barra preta fixa no topo, com a logo do escritório à esquerda (balança, "DORNELES ADVOCACIA" e o número da OAB) e o menu de navegação.

| Item do menu | O que faz |
|---|---|
| **Início** | Leva ao topo da página (seção principal). |
| **Sobre** | Leva à seção "Sobre mim". |
| **Áreas de atuação** | Leva à seção com os cards das áreas do direito. |
| **Contato** | Leva à seção de contato, no final da página. |

### 2. Início (hero)
Seção de abertura com fundo escuro, detalhes em dourado e foto do advogado ao lado de uma estátua da Justiça.

- **Rótulo:** "DORNELES ADVOCACIA"
- **Título:** "Seus direitos merecem uma defesa à altura."
- **Texto de apoio:** apresenta a atuação baseada em ética, transparência e dedicação.
- **Botão "Agende sua consulta ->"** (dourado): é a principal chamada para ação (CTA) do site e deve levar o visitante ao contato com o escritório. *(Destino a confirmar: seção de contato ou link direto do WhatsApp.)*
<img width="1347" height="604" alt="image" src="https://github.com/user-attachments/assets/ed9bf120-36db-49dd-b75d-4d6eed8979df" />

### 3. Sobre mim
Fundo bege claro, em duas colunas: à esquerda o título "Compromisso, ética e dedicação à justiça."; à direita três parágrafos em primeira pessoa sobre a forma de trabalhar do advogado (atendimento personalizado, estratégia construída com cuidado, segurança jurídica). Seção apenas informativa, sem botões.
<img width="1349" height="610" alt="image" src="https://github.com/user-attachments/assets/c9d621e5-9215-4a04-8f06-583930f58d3b" />

### 4. Áreas de atuação
Título "Áreas de atuação" com o rótulo "COMO PODEMOS AJUDAR" e uma breve introdução. Abaixo, três cards com cantos retos e borda fina:

| Nº | Área | Resumo |
|---|---|---|
| 01 | **Direito Bancário** | Contratos bancários, empréstimos, financiamentos, tarifas abusivas e conflitos com instituições financeiras. |
| 02 | **Direito Civil** | Contratos, responsabilidade civil, indenizações e relações jurídicas do cotidiano. |
| 03 | **Direito Previdenciário** | Informações e acompanhamento em demandas relacionadas a benefícios previdenciários. |

Os cards não são botões. Ao passar o mouse, o card aumenta levemente, ganha sombra suave e a borda fica dourada (efeito apenas visual). O terceiro card fica centralizado e mais estreito, de propósito.
<img width="1347" height="605" alt="image" src="https://github.com/user-attachments/assets/8d5ce1e9-ffa4-4ace-9640-7703b6d22dce" />

### 5. Entre em contato
Fundo bege, rótulo "ENTRE EM CONTATO" e o título "Vamos conversar sobre o seu caso?". À direita, dois ícones clicáveis:

| Ícone | O que faz |
|---|---|
| **WhatsApp** | Abre uma conversa com o escritório. Principal canal de atendimento. |
| **Instagram** | Abre o perfil do escritório na rede social. |

Ao passar o mouse, os ícones sobem levemente e ganham uma sombra dourada.

### Rodapé
Faixa preta com: *© 2026 Dorneles Advocacia - Todos os Direitos Reservados :: Desenvolvido por: Vinícius Rodrigues*.
<img width="1350" height="601" alt="image" src="https://github.com/user-attachments/assets/83f556ea-8ab5-4e19-90ff-0b4fd91830d9" />

---

## Identidade visual

| Elemento | Valor |
|---|---|
| Dourado (rótulos, bordas no hover, botão) | `#B8903F` |
| Fundo escuro (menu, hero, rodapé) | preto, em torno de `#0b0b0b` |
| Fundo claro das seções | bege suave |
| Fonte dos títulos | Playfair Display (serifada) |
| Fonte dos textos | DM Sans |
| Estilo | Sóbrio, cantos retos, bordas finas, bastante espaço em branco |

## Tecnologias

- HTML5
- CSS3 (transições, hover, `filter: drop-shadow`)
- Bootstrap (sistema de grid: `row` e `col-lg-*`)
- Google Fonts (Playfair Display e DM Sans)

## Melhorias futuras
- Responsividade: é preciso melhorar a responsividade do site. O layout foi pensado principalmente para telas grandes e ainda precisa de ajustes em tablets e celulares (menu, hero, cards das áreas de atuação, ícones de contato e espaçamentos).

## Autoria

Desenvolvido por **Vinícius Rodrigues** para **Dorneles Advocacia**.
