# 🛠️ Desenvolvimento Local

## Pré-requisitos

- **Node.js** (versão 14 ou superior)
- **Git** para controle de versão
- **Editor de código** (VS Code recomendado)

## 🚀 Configuração do Ambiente

### 1. Clone o Repositório

```bash
git clone https://github.com/SEU-USUARIO/Site-Amostra.git
cd Site-Amostra
```

### 2. Instalar Dependências (Opcional)

```bash
npm install
```

### 3. Executar Servidor Local

```bash
# Opção 1: Usando npm
npm start

# Opção 2: Usando Python (se disponível)
python -m http.server 8080

# Opção 3: Usando Node.js diretamente
npx http-server . -p 8080
```

### 4. Acessar a Aplicação

Abra seu navegador e acesse:
- **URL Local**: `http://localhost:8080`
- **URL Alternativa**: `http://127.0.0.1:8080`

## 📁 Estrutura do Projeto

```
Site-Amostra/
├── index.html              # Página principal
├── css/
│   └── main.css            # Estilos da aplicação
├── images/                 # Imagens e assets
│   ├── LOGO.png
│   ├── LOGO DEITADA.png
│   └── ...
├── .github/workflows/      # GitHub Actions
├── .nojekyll              # Configuração GitHub Pages
├── README.md              # Documentação principal
├── DEPLOY.md              # Instruções de deploy
├── DEVELOPMENT.md         # Este arquivo
└── package.json           # Configuração do projeto
```

## 🎨 Tecnologias Utilizadas

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos e responsivos
- **JavaScript** - Interatividade e navegação

### Bibliotecas Externas
- **Font Awesome** - Ícones
- **Google Fonts** - Tipografia (Inter, Montserrat)

### Ferramentas de Desenvolvimento
- **Git** - Controle de versão
- **GitHub Pages** - Hospedagem
- **GitHub Actions** - Deploy automático

## 🔧 Comandos Úteis

### Desenvolvimento
```bash
# Iniciar servidor local
npm start

# Verificar arquivos
ls -la

# Verificar status do git
git status
```

### Git
```bash
# Adicionar alterações
git add .

# Commit com mensagem
git commit -m "Descrição da alteração"

# Push para GitHub
git push origin main

# Verificar branch atual
git branch
```

## 🐛 Debugging

### Problemas Comuns

#### 1. CSS não carrega
- ✅ Verifique se o arquivo `main.css` está na pasta `css/`
- ✅ Confirme o caminho no HTML: `./css/main.css`

#### 2. Imagens não aparecem
- ✅ Verifique se as imagens estão na pasta `images/`
- ✅ Confirme os caminhos relativos

#### 3. JavaScript não funciona
- ✅ Abra o console do navegador (F12)
- ✅ Verifique se há erros JavaScript

#### 4. Responsividade
- ✅ Teste em diferentes tamanhos de tela
- ✅ Use as ferramentas de desenvolvedor do navegador

## 📱 Testes

### Testes de Responsividade
1. **Desktop**: 1920x1080, 1366x768
2. **Tablet**: 768x1024, 1024x768
3. **Mobile**: 375x667, 414x896

### Navegadores Suportados
- ✅ Chrome (última versão)
- ✅ Firefox (última versão)
- ✅ Safari (última versão)
- ✅ Edge (última versão)

## 🚀 Deploy

### Deploy Automático
1. Faça push para a branch `main`
2. O GitHub Pages fará o deploy automaticamente
3. Aguarde alguns minutos
4. Acesse: `https://SEU-USUARIO.github.io/Site-Amostra/`

### Deploy Manual
1. Vá em `Settings` > `Pages`
2. Selecione `Deploy from a branch`
3. Escolha a branch `main`
4. Clique em `Save`

## 📊 Monitoramento

### GitHub Actions
- Vá em `Actions` no seu repositório
- Verifique o status do workflow `Deploy to GitHub Pages`
- Em caso de erro, consulte os logs

### GitHub Pages
- Vá em `Settings` > `Pages`
- Verifique o status do deploy
- Confirme a URL de acesso

## 🤝 Contribuição

### Fluxo de Trabalho
1. **Fork** o repositório
2. **Clone** seu fork
3. **Crie** uma branch para sua feature
4. **Faça** suas alterações
5. **Commit** e **push**
6. **Abra** um Pull Request

### Padrões de Código
- **HTML**: Semântico e acessível
- **CSS**: Responsivo e moderno
- **JavaScript**: Limpo e documentado
- **Commits**: Mensagens descritivas

## 📞 Suporte

Para dúvidas sobre desenvolvimento:
1. Consulte a documentação
2. Verifique os logs de erro
3. Abra uma issue no GitHub
4. Entre em contato com a equipe
