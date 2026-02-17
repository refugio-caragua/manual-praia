# Guia Mestre de Consulta

Este e o seu Guia Mestre de Consulta. Ele resume todas as etapas tecnicas para transformar o arquivo local no site profissional Refugio Caragua.

---

## 📖 Guia Definitivo: Do HTML ao Site no GitHub Pages

### 1. Preparacao dos Arquivos (No Computador)
Antes de subir para a web, a organizacao dos arquivos e a regra de ouro:

- **Nome Principal:** o arquivo .html deve ser renomeado para `index.html` (sempre em minusculas).
- **Imagens:** coloque todas as fotos na mesma pasta do `index.html`.
- **Caminhos no Codigo:** a imagem deve ser chamada apenas pelo nome, por exemplo:
  - `<img src="foto.jpg">`
  - Nunca use caminhos que comecem com `C:\Users\...`.

### 2. Criando o "Lar" Profissional (Organizacao)
Para esconder o nome de usuario pessoal e dar um ar empresarial:

- No GitHub, clique no **+** (topo direito) > **New organization**.
- Escolha o plano **Free ($0)**.
- Dê o nome (ex: `refugio-caragua`). Isso define a primeira parte do seu link.

### 3. Criando o Repositorio e Subindo Arquivos
Dentro da organizacao:

- Clique em **New repository**.
- Nomeie como `manual-praia` (este sera o final do seu link). Deixe como **Public**.
- Clique em **uploading an existing file**.
- Arraste o `index.html` e as fotos para o quadrado cinza.
- No final da pagina, escreva um titulo no **Commit** e clique em **Commit changes**.

### 4. Ativando o Site (Publicacao)
O site nao fica online sozinho; voce precisa ligar o "interruptor":

- No repositorio, va na aba **Settings** (topo).
- No menu esquerdo, clique em **Pages**.
- Em **Branch**, mude de **None** para **main**. Clique em **Save**.
- O link aparecera em instantes no topo, por exemplo:
  - `https://refugio-caragua.github.io/manual-praia/`

### 5. Atualizando o Site (Nova Revisao)
Sempre que fizer alteracoes no VS Code e quiser publicar:

- Acesse o repositorio no GitHub.
- Clique em **Add file > Upload files**.
- Arraste o novo `index.html`. O GitHub substitui a versao antiga automaticamente.
- Clique em **Commit changes**.
- No navegador, use **Ctrl + F5** para ver as mudancas.

### 6. Comandos e Atalhos Uteis

- **Links de GPS:** use botao com o link:
  - `https://maps.google.com/?q=-23.6475,-45.4225`
- **Emojis no Codigo:** use exemplos como:
  - `<p>🔑 Texto</p>`
  - `<p>🌊 Texto</p>`
- **Seguranca (2FA):** acoes sensiveis como **Transfer** ou **Delete** exigirao aprovacao no GitHub Mobile.
- **Backup:** para baixar tudo, use **Code > Download ZIP**.

---

## Checklist de Erros Comuns (Troubleshooting)

- **Erro 404:** o arquivo nao se chama `index.html` ou o Pages nao foi ativado na branch `main`.
- **Imagem nao aparece:** o nome do arquivo no PC esta diferente do nome no codigo (ex: `Foto.jpg` vs `foto.jpg`). O GitHub diferencia maiusculas.
- **Site nao atualiza:** o navegador guardou a versao velha. Use **Ctrl + F5**.
