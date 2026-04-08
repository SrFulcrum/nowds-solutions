# Nowds Solutions

Site institucional estático da Nowds Solutions.

## Arquivos
- `index.html`
- `logo-nowds.png`
- `Dockerfile`
- `.dockerignore`

## Como usar no EasyPanel
1. Envie esses arquivos para um repositório no GitHub.
2. No EasyPanel, crie um **App** e conecte o repositório.
3. Como o projeto já possui `Dockerfile`, o EasyPanel vai buildar a imagem automaticamente.
4. Faça o deploy ou redeploy.
5. Configure o domínio no serviço.

## Observação
Se aparecer a tela padrão do Nginx, verifique se:
- o `index.html` está na raiz do repositório
- o `Dockerfile` está na raiz do repositório
- o repositório/branch corretos estão conectados no EasyPanel
- você executou o redeploy após o último commit
