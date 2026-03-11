# Living Around

Experiência web multipágina inspirada no lifestyle de digital nomads, pensada para cruzar trabalho remoto, viagem, liberdade de movimento e descoberta de destinos através de uma identidade visual ligada ao universo van life.

**Live demo:** https://catirato.github.io/Living_around/

## Sobre o projeto

O **Living Around** foi desenvolvido no contexto do módulo de **Programação Web** do **CESAE Digital**, em **2025**. A proposta foi criar uma aplicação front-end estática com identidade própria, foco visual forte e uma navegação simples entre diferentes áreas da experiência.

Mais do que uma landing page, este projeto apresenta um pequeno ecossistema de páginas ligadas entre si: homepage, alojamento, locais, contacto e detalhe de produto. O objetivo foi construir uma interface coerente, com storytelling visual, hierarquia clara e pequenos comportamentos em JavaScript para tornar a navegação mais dinâmica.

## Funcionalidades

- Homepage com hero section, navegação principal e chamadas para ação
- Página de acomodação com cards de carrinhas, preços e principais características
- Página de detalhe em formato modal para uma das opções de alojamento
- Página de locais com seleção de país e cidade
- Redirecionamento automático para uma página de destino específica
- Página dedicada ao Porto com mapa incorporado e contactos locais
- Página de contactos com formulário e feedback visual de envio
- Menu mobile com comportamento responsivo usando `<details>` e `<summary>`

## Stack utilizada

- HTML5
- CSS3
- Bootstrap 5.3
- JavaScript vanilla
- Google Fonts

## Direção visual

O projeto foi pensado com uma abordagem mais editorial e atmosférica do que funcional no sentido clássico de produto. A construção visual apoia-se em:

- Imagens de grande escala para reforçar contexto e emoção
- Combinação tipográfica entre serif e sans serif geométrica
- Blocos visuais amplos com contraste forte
- Navegação direta entre secções principais
- Estética associada a liberdade, estrada, natureza e trabalho remoto

## Destaques técnicos

- Estilo centralizado num único ficheiro: [`style_index.css`](/Users/catarinarato/Desktop/Living_around/style_index.css)
- Layout multipágina com consistência visual entre secções
- Uso de Bootstrap para apoio de grelha e componentes utilitários
- Interações simples em JavaScript para redirecionamento e confirmação de formulário
- Estrutura estática pronta para publicação em GitHub Pages

## Estrutura do projeto

```text
Living_around/
├── index.html
├── Page_Acomodação.html
├── Page_Locais.html
├── Page_Locais_Porto.html
├── Page_Contatos.html
├── Page_Contatos_Alert.html
├── Modal.html
├── style_index.css
└── Imagens/
```

## Como correr localmente

Por ser um projeto estático, não existe build step.

1. Clonar o repositório
2. Abrir [`index.html`](/Users/catarinarato/Desktop/Living_around/index.html) no browser

Se preferires, também podes usar um servidor local simples, como o Live Server do VS Code.

## Aprendizagens

- Estruturação de um projeto front-end multipágina
- Construção de layouts responsivos com HTML, CSS e Bootstrap
- Criação de consistência visual entre páginas diferentes
- Aplicação de interações simples com JavaScript
- Desenvolvimento de uma identidade visual coerente para um projeto web

## Próximos passos possíveis

- Substituir links placeholder por conteúdo real
- Melhorar semântica e acessibilidade da interface
- Adicionar validação mais robusta ao formulário
- Criar mais páginas de detalhe para destinos e acomodações
- Otimizar imagens e performance geral
- Evoluir o projeto para uma versão com componentes reutilizáveis

## Autora

**Catarina Rato**

Projeto desenvolvido no módulo de **Programação Web** do **CESAE Digital**.
