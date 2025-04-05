# Ignite UI Design System

[![Deploy docs](https://github.com/AIemao/DesignSystem/actions/workflows/deploy-docs.yaml/badge.svg)](https://github.com/AIemao/DesignSystem/actions/workflows/deploy-docs.yaml)

Um Design System moderno e acessível criado com React, contendo componentes reutilizáveis para aplicações web.

## 📚 Documentação

Acesse nossa documentação e playground de componentes em [https://aiemao.github.io/DesignSystem/](https://aiemao.github.io/DesignSystem/)

## 🧩 Componentes

O Design System inclui os seguintes componentes:

- ✅ Button - Botões de ação em diferentes variantes
- ✅ Heading - Componente para títulos e cabeçalhos
- ✅ Text - Componente para textos em diferentes variações
- ✅ TextInput - Campos de entrada de texto
- ✅ Textarea - Áreas de texto expandidas
- ✅ Checkbox - Caixas de seleção
- ✅ Avatar - Componente para exibição de avatares de usuário
- ✅ MultiStep - Indicador de etapas para formulários multi-etapas

## 🚀 Instalação

```bash
npm install @ignite-ui/react
```

## 💻 Uso

```jsx
import { Button, Text } from '@ignite-ui/react'

export function App() {
  return (
    <>
      <Text>Hello world</Text>
      <Button>Click me</Button>
    </>
  )
}
```

## 🛠️ Desenvolvimento

### Pré-requisitos

- Node.js 16.x
- npm ou yarn

### Configurando o ambiente

1. Clone o repositório:

```bash
git clone https://github.com/AIemao/DesignSystem.git
cd DesignSystem
```

2. Instale as dependências:

```bash
npm ci --legacy-peer-deps
```

3. Execute o Storybook para desenvolvimento:

```bash
npm run dev
```

### Build

```bash
npm run build
```

> **Nota:** Para problemas de compatibilidade, use Node.js 16 com a flag `--legacy-peer-deps`.

## 📄 Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes.