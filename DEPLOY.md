# 🚀 Deploy no GitHub Pages

## Configuração Inicial

### 1. Configurar o Repositório

1. **Fork** este repositório ou clone para seu GitHub
2. **Ative o GitHub Pages** nas configurações do repositório:
   - Vá em `Settings` > `Pages`
   - Selecione `Deploy from a branch`
   - Escolha a branch `main`
   - Clique em `Save`

### 2. Configuração Automática

O projeto já está configurado com:
- ✅ Arquivo `.nojekyll` para desabilitar Jekyll
- ✅ Workflow de deploy automático
- ✅ Estrutura de arquivos otimizada

### 3. Deploy Manual (se necessário)

Se o deploy automático não funcionar:

```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/Site-Amostra.git
cd Site-Amostra

# Adicione as alterações
git add .
git commit -m "Deploy para GitHub Pages"
git push origin main
```

## 📁 Estrutura para GitHub Pages

```
Site-Amostra/
├── index.html          # Página principal
├── css/
│   └── main.css        # Estilos
├── images/             # Imagens (já configuradas)
├── .nojekyll           # Desabilita Jekyll
├── .github/workflows/  # Deploy automático
└── README.md           # Documentação
```

## 🔧 Solução de Problemas

### Problema: Página não carrega
- ✅ Verifique se o arquivo `.nojekyll` existe
- ✅ Confirme que a branch `main` está selecionada
- ✅ Aguarde alguns minutos para o deploy

### Problema: CSS não carrega
- ✅ Verifique os caminhos relativos no HTML
- ✅ Confirme que o arquivo `main.css` está na pasta `css/`

### Problema: Imagens não carregam
- ✅ Verifique se as imagens estão na pasta `images/`
- ✅ Confirme os caminhos relativos

## 🌐 URLs de Acesso

Após o deploy, sua página estará disponível em:
- **URL Principal**: `https://SEU-USUARIO.github.io/Site-Amostra/`
- **URL Alternativa**: `https://SEU-USUARIO.github.io/Site-Amostra/index.html`

## 📊 Monitoramento

Para verificar o status do deploy:
1. Vá em `Actions` no seu repositório
2. Verifique se o workflow `Deploy to GitHub Pages` está funcionando
3. Em caso de erro, verifique os logs

## 🔄 Atualizações

Para atualizar a página:
1. Faça as alterações nos arquivos
2. Commit e push para a branch `main`
3. O GitHub Pages fará o deploy automaticamente

## 📞 Suporte

Se encontrar problemas:
1. Verifique a documentação do GitHub Pages
2. Consulte os logs de deploy em `Actions`
3. Verifique se todos os arquivos estão corretos
