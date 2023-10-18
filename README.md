# Projeto Starter Kit com TurboRepo

Este é um projeto starter kit que utiliza o TurboRepo para gerenciar um monorepo. O monorepo é estruturado com as pastas `apps` para aplicativos e `packages` para pacotes compartilhados. Neste projeto, você encontrará os seguintes aplicativos e pacotes:

## Estrutura de Diretórios

```text
/
|-- apps/
| |-- docs/
| |-- web/
|
|-- packages/
| |-- eslint-config-custom/
| |-- tsconfig/
| |-- ui/
|
|-- .turboignore
|-- .turborepo.json
|-- README.md
```

- **`apps/`**: Esta pasta contém os aplicativos do projeto.
  - **`docs/`**: Aplicativo de documentação.
  - **`web/`**: Aplicativo da web.

- **`packages/`**: Esta pasta contém pacotes compartilhados usados pelos aplicativos.
  - **`eslint-config-custom/`**: Configuração personalizada do ESLint.
  - **`tsconfig/`**: Configuração personalizada do TypeScript.
  - **`ui/`**: Componentes de interface do usuário compartilhados.

- **`.turboignore`**: Arquivo de configuração para especificar quais arquivos e pastas devem ser ignorados pelo TurboRepo.

- **`.turborepo.json`**: Arquivo de configuração principal do TurboRepo para definir as configurações do monorepo.

## Configuração

Certifique-se de que você tem o TurboRepo instalado globalmente no seu sistema.

```bash
npm install -g @turbo/turbo
```

### Uso

1 - Clone este repositório

```bash
git clone https://github.com/JonatasMSantos/turborepo-starter.git
```

2 - Instale as dependências em todos os aplicativos e pacotes:
```bash
npm install
```


