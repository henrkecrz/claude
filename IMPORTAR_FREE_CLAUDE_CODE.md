# Importar free-claude-code

Este repositório foi preparado para receber o projeto público:

https://github.com/Alishahryar1/free-claude-code.git

## Comando recomendado para importar o conteúdo completo

Rode no seu computador:

```bash
git clone https://github.com/Alishahryar1/free-claude-code.git claude
cd claude

git remote remove origin
git remote add origin https://github.com/henrkecrz/claude.git

git branch -M main
git push -u origin main --force
```

## Observação

A tentativa de executar o clone diretamente neste ambiente falhou porque o terminal não consegue resolver `github.com`. A criação de um workflow automático de importação também foi bloqueada pela camada de segurança do conector.
