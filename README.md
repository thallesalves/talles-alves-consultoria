# Landing Page | Consultoria Talles Alves

Landing page da consultoria online de treinamento para pessoas com diabetes. O projeto apresenta o serviço, o método de acompanhamento, os planos disponíveis e direciona os visitantes para uma conversa no WhatsApp.

## Tecnologias

- HTML5 para a estrutura e o conteúdo
- CSS3 para identidade visual, layout e responsividade
- JavaScript para atualizar automaticamente o ano exibido no rodapé

O projeto não depende de framework, biblioteca JavaScript, banco de dados ou processo de compilação.

## Estrutura do projeto

```text
talles-alves-consultoria/
├── css/
│   └── style.css
├── images/
│   ├── logo.png
│   ├── talles-camisa-branca.jpg
│   └── talles-capa.jpg
├── js/
│   └── script.js
├── .gitignore
├── index.html
└── README.md
```

## Como abrir no VS Code

1. Extraia a pasta do projeto.
2. Abra o VS Code.
3. Acesse **Arquivo > Abrir Pasta**.
4. Selecione a pasta `talles-alves-consultoria`.
5. Abra o arquivo `index.html`.

## Como executar localmente

### Opção 1: Live Server

1. Instale a extensão **Live Server** no VS Code.
2. Clique com o botão direito em `index.html`.
3. Selecione **Open with Live Server**.

### Opção 2: abrir diretamente

Também é possível abrir `index.html` diretamente no navegador. Como o projeto é estático, as funcionalidades atuais continuarão funcionando.

## Arquivos principais

### `index.html`

Contém a estrutura semântica da página, os textos, links, seções e referências aos demais arquivos.

### `css/style.css`

Concentra a identidade visual, cores, tipografia, espaçamento, responsividade e enquadramento das fotografias.

### `js/script.js`

Atualiza o ano do rodapé automaticamente com base na data do dispositivo.

## Personalização

As principais cores estão organizadas como variáveis no início de `css/style.css`:

```css
:root {
  --navy: #0b3d57;
  --navy-deep: #062b40;
  --teal: #0ba7a5;
  --teal-bright: #16c1b8;
}
```

O link do WhatsApp está inserido diretamente nos botões comerciais do arquivo `index.html`.

## Próximas etapas

- Revisar a página localmente em diferentes tamanhos de tela
- Criar o repositório Git
- Publicar o código no GitHub
- Escolher e configurar a hospedagem
- Conectar um domínio próprio, se necessário

## Responsável

Talles Alves  
Profissional de Educação Física  
CREF MG-037405
