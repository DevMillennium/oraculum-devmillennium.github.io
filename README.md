# Oraculum GitHub Pages

Repositório para configuração do GitHub Pages do app Oraculum, contendo arquivos necessários para integração com AdMob.

## 📁 Estrutura do Projeto

```
oraculum.github.io/
├── .nojekyll          # Desabilita processamento Jekyll
├── app-ads.txt        # Configuração AdMob
├── index.html         # Página inicial
└── README.md          # Este arquivo
```

## 🔧 Configuração AdMob

### Arquivo app-ads.txt
- **URL**: https://oraculum.github.io/app-ads.txt
- **Publisher ID**: pub-193234911051112
- **Conteúdo**: `google.com, pub-193234911051112 DIRECT, f84742a0`

### Status de Verificação
- ✅ **GitHub Pages**: Ativo
- ✅ **HTTPS**: Configurado automaticamente
- ✅ **CORS**: Permitido para AdMob
- ✅ **Cache**: Otimizado pela CDN do GitHub

## 🌐 URLs do Projeto

- **Site Principal**: https://oraculum.github.io/
- **app-ads.txt**: https://oraculum.github.io/app-ads.txt

## 📋 Configuração GitHub Pages

- **Branch**: main
- **Diretório**: / (raiz)
- **Domínio**: oraculum.github.io
- **HTTPS**: Automático
- **Jekyll**: Desabilitado (.nojekyll presente)

## 🔍 Verificação de Status

Para verificar se o arquivo está acessível:

```bash
curl -I https://oraculum.github.io/app-ads.txt
```

**Resposta esperada:**
```
HTTP/2200content-type: text/plain; charset=utf-8
```

## 🚀 Deploy

O site é atualizado automaticamente quando alterações são enviadas para a branch `main`.

### Comandos para atualizar:
```bash
git add .
git commit -m "Atualização do site"
git push origin main
```

## 📞 Suporte

Para problemas com o GitHub Pages ou configuração AdMob, verifique:
1. Status do GitHub Pages nas configurações do repositório
2. Logs de build no GitHub Actions
3Cache da CDN (pode levar até 10 minutos para atualizar)

---
**Oraculum** - Configuração AdMob via GitHub Pages 