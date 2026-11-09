# DR 360° — Dodge Recian

## Visão geral

Aplicativo web para visualização de vídeos em 360 graus, com proposta de experiência imersiva, múltiplas perspectivas e controles de mídia.

Este repositório é uma implementação separada do projeto [dr-360](https://github.com/WalyRobert/dr-360). Os dois projetos têm objetivos semelhantes, mas estruturas e dependências diferentes. Consulte os respectivos códigos antes de tratá-los como versões equivalentes.

**Status:** implementação independente; compatibilidade e funcionalidades devem ser validadas na versão publicada.

## Funcionalidades descritas pelo projeto

- Visualização panorâmica 360°/180°/120°.
- Controles de reprodução, volume, velocidade e progresso.
- Suporte anunciado a modo VR e head tracking.
- Interface responsiva para desktop e dispositivos móveis.
- Reprodução de vídeos MP4, WebM e Ogg, conforme descrição do projeto.

> As funcionalidades acima refletem a documentação do projeto. O suporte efetivo a headsets, sensores e dispositivos específicos ainda precisa ser validado por testes.

## Tecnologias declaradas

- React 18
- TypeScript
- Three.js
- Lucide React
- Vite

## Instalação

**Pré-requisito:** Node.js e npm.

```bash
git clone https://github.com/WalyRobert/dr360-app.git
cd dr360-app
npm install
npm run dev
```

Para gerar o build:

```bash
npm run build
npm run preview
```

O script `deploy` utiliza a CLI do Vercel, que precisa estar instalada e configurada no ambiente:

```bash
npm run deploy
```

## Próximas etapas

- [ ] Documentar a arquitetura e os principais componentes.
- [ ] Confirmar a implementação de head tracking no código.
- [ ] Testar o modo VR nos dispositivos declarados como compatíveis.
- [ ] Adicionar testes automatizados e evidências de build.
- [ ] Registrar capturas de tela e vídeo demonstrativo.
- [ ] Explicar a relação e as diferenças em relação ao repositório `dr-360`.

## Demonstração

Projeto associado ao endereço informado na documentação original: https://dr360graus.com.br

A disponibilidade e o funcionamento do endereço devem ser verificados periodicamente.

## Autor / marca do projeto

Dodge Recian

Repositório mantido na conta GitHub WalyRobert.
