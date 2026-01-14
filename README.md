# Atividade Prática – Navegação Avançada e UX no React Native

### Navegação
- **Bottom Tab Navigator** com 2 abas:
  - Home
  - Profile
  
- **Stack Navigator** interno na aba Home:
  - Tela Home
  - Tela Details (com parâmetros)

#### Tela Home
-  **Loading**: Carregamento de dados com indicador
-  **Empty**: Estado vazio quando não há dados
-  **Success**: Exibição de dados carregados

#### Tela Details
-  **Loading**: Carregamento de detalhes
-  **Error**: Tratamento de erro com botão de retry
-  **Success**: Exibição dos dados com ID recebido via parâmetro

#### Tela Profile
- Tela estática com informações do usuário

###  Deep Linking
Configurado para aceitar o link: `meuapp://details/1`

## Executando

### 1. Instalar Dependências

Depois instale as dependências:
```bash
npm install
```


### 2. Iniciar o Projeto

```bash
npm start
```

Ou para plataformas específicas:
```bash
npm run android  # Para Android
npm run ios      # Para iOS
npm run web      # Para Web
```

