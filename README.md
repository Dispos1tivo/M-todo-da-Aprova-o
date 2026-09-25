# Método da Aprovação · Combo da Aprovação PMMG 2027

Página de vendas do **Combo da Aprovação PMMG 2027** (cargo Soldado, banca CRS), junto com os documentos de identidade visual e as decisões de design usadas para construí-la.

## Estrutura

```
index.html                  Página de vendas (arquivo único: HTML, CSS e JS)
assets/
  deise.ogg                 Depoimento em áudio da Deise (32 s)
  deise.jpg                 Foto da Deise (player de áudio, bloco 07)
  maykon.png                Foto do Maykon Souza (depoimento, bloco 07)
  selos-pagamento.webp      Logos das formas de pagamento (oferta, bloco 14)
design/
  wireframe.html            Wireframe aprovado: 17 blocos e a copy oficial
  manual-identidade.html    Manual de identidade: cores, tipografia, ícones e animações
  logo.html                 Logo nova, versões e regras de uso
  capas.html                Capas dos 2 produtos e 5 bônus + composições do kit
  direcoes-visuais.html     As 3 direções propostas (escolhida: A · Operação)
  hero-mobile-opcoes.html   Opções da imagem do hero no celular (escolhida: 2)
  headline-opcoes.html      Opções da headline do hero (mantida a atual)
```

Para ver, basta abrir `index.html` no navegador. Não há build nem dependências: as fontes vêm do Google Fonts e todo o resto está no próprio arquivo. Para publicar, dá para usar o GitHub Pages (Settings → Pages → branch `main`, pasta raiz) ou qualquer hospedagem de arquivos estáticos.

## Identidade visual

| Item | Definição |
|---|---|
| Fundo | `#09090B`, com grade sutil de 44 px e brilhos amarelos difusos |
| Superfícies | `#141417` · `#1B1B1F` · `#26262B` |
| Cor principal | Amarelo Tático `#F6C111` (hover `#FFD43B`), cerca de 5% da página |
| Texto | `#FAFAFA` · `#D4D4D8` · `#A1A1AA` · `#71717A` |
| Cor de contraste | **Ainda não definida.** Sugestão: o verde-oliva da logo antiga (`#4A4B34`) |
| Títulos de impacto | Saira Condensed 800–900, caixa alta |
| Texto corrido | Inter 400–700 |
| Números e etiquetas | JetBrains Mono |
| Botão principal | Amarelo com texto preto, cantos de 8 px, caixa alta em Saira 700, reflexo animado |
| Ícones | Traço de linha (estilo Lucide), 2 px, dentro de quadrados com amarelo a 10% |

Referências usadas: pv.monsterconcursos.com.br (fundo, animações, gradientes, Inter), caveira.com (amarelo, Saira, animações) e metodogabaritando.com (ícones).

## Decisões da página

- **Direção A · Operação:** molduras com cantoneiras de mira e grade de fundo. As faixas amarelas de ponta a ponta nos blocos 03 e 17 vêm da direção B.
- **Copy:** exatamente a do wireframe. Não há etiquetas de "Fase".
- **Títulos:** misturam branco e amarelo. Quando há destaque, a frase-chave inteira fica em amarelo.
- **Hero:** no computador, a vitrine com os 7 livros em 3D. No celular (até 640 px), as Apostilas em destaque com o selo "+ 5 bônus".
- **Capas:** 1 capa resumida para as Apostilas e 1 para os Simulados, que na prática têm 5 volumes cada. Bônus 2 = "Planner de 30 Dias". Bônus 3 = "Planejamento de Estudos".
- **Oferta:** grade com as capas, lista de valores e caixa de preço.
- **Botões de compra:** "Quero garantir meu combo por R$ 47" (oferta) e "Sim, quero passar na PMMG 2027" (chamada final) levam ao checkout da Cakto: `https://pay.cakto.com.br/e5ah5n8_1006158`. Os outros 3 botões descem até a oferta.
- **Barra de compra fixa no celular:** foi removida de propósito, porque a página já tem os botões estratégicos.
- **Depoimentos do bloco 07:** 5 estrelas no topo de cada cartão.
- **Carrossel de depoimentos:** passa sozinho a cada 4,5 s e pausa com mouse, dedo ou teclado.
- **Linha da jornada (bloco 09):** cresce e recua com a rolagem.

## Pendências

- [ ] Parcelamento: acima do botão diz "6x de R$ 9,00" e abaixo diz "até 11x". Alinhar os dois.
- [ ] "Condição Exclusiva só HOJE!" precisa de um prazo real. Se não houver, trocar por "condição de lançamento".
- [ ] Conferir o salário de Soldado no edital vigente (texto da oferta).
- [ ] Foto do Caio Fernandes (depoimento, bloco 07).
- [ ] Áudio da Deise em MP3, para tocar em iPhones com iOS antigo (hoje está em `.ogg`).
- [ ] Confirmar a autorização de uso das fotos, do áudio e dos depoimentos.
- [ ] Cor de contraste do manual de identidade.
- [ ] Converter o texto da logo em curvas antes de mandar para gráfica.
- [ ] As 5 capas individuais de Apostilas e de Simulados (nome das matérias).
