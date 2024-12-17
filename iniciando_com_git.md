
# 🚀 Iniciando com Git e GitHub para Hospedar Seu Portfólio

Este guia vai ajudar você a hospedar seu arquivo `index.html` usando **Git** e **GitHub Pages** para que qualquer pessoa possa visualizar seu portfólio online.

---

## **1. Instale o Git**
Se ainda não tiver o Git instalado:

1. Baixe e instale o Git:
   - [Download Git](https://git-scm.com/)

2. Verifique se o Git foi instalado corretamente:
   ```bash
   git --version
   ```

---

## **2. Crie uma Conta no GitHub**
1. Acesse [https://github.com](https://github.com).
2. Crie uma conta ou faça login.

---

## **3. Configure o Git no Seu Computador**

Abra o terminal (ou terminal integrado do VSCode) e execute os comandos:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@example.com"
```

**Verifique se foi configurado corretamente:**
```bash
git config --global user.name
git config --global user.email
```

---

## **4. Crie um Repositório no GitHub**

1. No GitHub, clique em **"New Repository"**.
2. Escolha um nome simples, como **"portfolio"**.
3. Selecione **Public** (público).
4. NÃO marque nenhuma opção extra (sem README, .gitignore ou licença).
5. Clique em **"Create Repository"**.

---

## **5. Suba Seu Arquivo `index.html`**

No terminal, vá até a pasta onde está seu arquivo `index.html`:

```bash
cd /caminho/da/sua/pasta
```

### **Passos para Enviar o Arquivo:**

1. Inicialize o Git na pasta:
   ```bash
   git init
   ```

2. Adicione o repositório remoto (substitua o link pelo seu repositório do GitHub):
   ```bash
   git remote add origin https://github.com/seu-usuario/portfolio.git
   ```

3. Adicione o arquivo `index.html`:
   ```bash
   git add index.html
   ```

4. Faça o commit do arquivo:
   ```bash
   git commit -m "Adiciona meu portfólio pessoal"
   ```

5. Envie o arquivo para o GitHub:
   ```bash
   git push -u origin master
   ```

---

## **6. Ative o GitHub Pages**

1. No GitHub, vá até **Settings** no repositório.
2. Role até a seção **"Pages"**.
3. Em **"Branch"**, selecione `master` e clique em salvar.

---

## **7. Acesse Seu Portfólio Online**

Depois de alguns segundos, seu site estará disponível em:

```
https://seu-usuario.github.io/portfolio
```

---

## **Dicas Extras**
- Caso precise atualizar seu site, edite o `index.html`, faça um novo commit e use `git push` novamente.
- Se encontrar algum problema, verifique se o Git está configurado corretamente com:
  ```bash
  git config --global --list
  ```

Pronto! 🎉 Agora seu portfólio está no ar. 🚀
