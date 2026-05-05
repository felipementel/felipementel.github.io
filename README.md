# Manutenção do Currículo

Este repositório contém um currículo estático em HTML e CSS, sem build, sem dependências locais e sem pipeline de geração. A manutenção é feita diretamente nos arquivos-fonte.

## Estrutura do projeto

- `index.html`: conteúdo principal do currículo
- `css/style.css`: estilos gerais, responsividade básica e regras de impressão
- `images/`: imagens usadas no site
- `images/certifications/`: logos e badges de certificações por provedor
- `images/favicon/`: favicon do site

## Como visualizar localmente

Como é um site estático, existem duas formas simples de validar alterações:

1. Abrir `index.html` diretamente no navegador.
2. Usar uma extensão como Live Server no VS Code para testar navegação e impressão com mais conforto.

## Fluxo de manutenção

Quando for atualizar o conteúdo, seguir esta ordem ajuda a evitar retrabalho:

1. Atualizar o conteúdo em `index.html`.
2. Ajustar estilos em `css/style.css` apenas se a mudança realmente exigir.
3. Validar a visualização normal no navegador.
4. Validar a versão de impressão com `Ctrl+P`.
5. Confirmar se links, datas, imagens e espaçamentos continuam consistentes.

## Seções do currículo

As seções principais são identificadas por `id` no `index.html` e também aparecem na navegação lateral.

Seções atuais:

- `Main`
- `About`
- `WorkProfile`
- `Education`
- `Certifications`
- `CommunityRecognition`
- `Contact`

Se uma nova seção for criada:

1. Adicionar o bloco HTML com um `id` único.
2. Adicionar o link correspondente no menu lateral.
3. Verificar se a nova seção precisa de comportamento especial na impressão.

## Atualização de conteúdo textual

O conteúdo principal fica em `index.html`.

Pontos que costumam exigir manutenção:

- resumo profissional em `About`
- experiências em `WorkProfile`
- formação em `Education`
- contatos e links sociais
- data de atualização no rodapé lateral (`Last update`)

Boas práticas para os textos:

- manter tom profissional e direto
- priorizar impacto, senioridade e especialidades
- evitar biografia longa demais
- revisar inglês sempre que houver mudança relevante

## Atualização de certificações

As certificações ficam na seção `Certifications` e seguem agrupamento por provedor.

Padrões atuais:

- Azure
- AWS
- GitHub
- Accenture
- Exin
- HashiCorp
- PeopleCert
- The Linux Foundation

### Convenções importantes

- Sempre que possível, exibir apenas a logo/badge e a data.
- Manter datas no formato `MM/YYYY`.
- Para badges sem data confirmada, o campo pode permanecer vazio temporariamente.
- Itens de reconhecimento de comunidade não devem ficar em `Certifications`; devem ir para `CommunityRecognition`.

### GitHub

As certificações do GitHub estão separadas em:

- `Core`
- `Delivery`
- `Sales`

Imagens relacionadas ficam em:

- `images/certifications/github/`
- `images/certifications/github/delivery/`
- `images/certifications/github/sales/`

Ao adicionar uma nova badge do GitHub:

1. Confirmar se ela pertence a `Core`, `Delivery` ou `Sales`.
2. Colocar a imagem na pasta correta.
3. Adicionar o bloco HTML no agrupamento correto.
4. Validar se o espaçamento visual ficou consistente com os demais badges.

## Community Recognition

Itens como reconhecimento de comunidade devem ficar separados das certificações formais.

Hoje esta seção concentra, por exemplo:

- Microsoft MVP
- Green Software Foundation
- Green Software Foundation Champion

Se surgirem novos reconhecimentos, adicionar nesta seção em vez de misturar com certificações.

## Regras de impressão

As regras de impressão ficam em `css/style.css`, dentro de `@media print`.

Comportamentos já implementados:

- oculta a barra lateral na impressão
- oculta o botão de impressão
- expande o conteúdo principal para largura total
- mostra links de forma textual na impressão
- permite controlar quebras de página com classes utilitárias

### Classes utilitárias de impressão

Estas classes podem ser aplicadas em blocos HTML para controlar paginação:

- `print-page-break-before`: força o início em uma nova página
- `print-page-break-after`: força quebra após o bloco
- `print-avoid-break-inside`: evita quebra no meio do bloco

Exemplo:

```html
<div class="section2 p-30 print-page-break-before" id="Education">
```

### Links na impressão

Para links que devem aparecer com texto na impressão, usar a classe `print-link`.

Exemplo:

```html
<a
  href="https://www.linkedin.com/in/felipementel/"
  class="print-link"
  data-print-label="LinkedIn"
>
```

Se quiser definir manualmente o valor impresso, usar `data-print-value`.

## Imagens e consistência visual

Ao adicionar ou trocar imagens:

- preferir arquivos com nome claro e previsível
- manter proporção visual consistente com os badges existentes
- validar se a imagem funciona bem tanto na tela quanto na impressão
- evitar mudar tamanhos globais no CSS para corrigir um único caso isolado

## Checklist rápido antes de publicar

- conteúdo atualizado
- `Last update` atualizado
- links funcionando
- datas no padrão `MM/YYYY`
- imagens novas referenciadas corretamente
- impressão validada
- quebras de página coerentes
- seção correta para cada item novo

## Sugestões para futuras melhorias

- criar uma convenção visual específica para separar melhor certificações e reconhecimentos
- reduzir repetição de markup em blocos de certificação
- adicionar uma pequena seção no README para histórico de decisões de layout
