
# 📝 Projeto Colaborativo: Nossa Turma

Bem-vindo ao repositório oficial da turma! Este é um projeto **colaborativo** onde todos iremos trabalhar juntos no mesmo código.

O objetivo deste exercício é prático: vamos simular um ambiente real de desenvolvimento onde várias pessoas contribuem para um mesmo software.

## 🎯 Objetivos
* Entender o fluxo de trabalho com **Git** e **GitHub** (Fork, Clone, Commit, Push e Pull Request).
* Praticar **HTML** básico (links e estrutura de páginas).
* Aprender a não ter medo de "quebrar" o código (e como consertar se acontecer).

---


## 🚀 Como Participar (Passo a Passo)

Siga as instruções abaixo com atenção:

### 1. Faça um Fork
No canto superior direito desta página, clique no botão **Fork**. Isso criará uma cópia deste repositório no seu próprio perfil do GitHub.

### 2. Clone o Repositório
Vá para o **seu** perfil, entre no repositório que você acabou de "forkar" e clone-o para sua máquina:

```bash
git clone https://github.com/SEU-USUARIO/NOME-DO-REPO.git
```



### 3. Crie sua branch e crie sua Página Pessoal
Dentro da pasta do projeto, crie sua branch para incluir sua contribuição.
```
git branch feature/seu-nome
git switch feature/seu-nome
```

Agora, crie um arquivo HTML com o seu nome (ex: joao-silva.html).

Coloque um conteúdo básico sobre você (pode ser um "Olá, Mundo", seus hobbies, etc).

Use apenas HTML.

### 4. Atualize a Lista Principal
Abra o arquivo index.html que já existe.
<br>
Procure a lista de alunos (`<ul>`).
<br>
Adicione um novo item (`<li>`) com o seu nome.
<br>
Importante: Crie um link (`<a>`) apontando para o arquivo que você criou no passo 3.

Exemplo:

```html
<li><a href="joao-silva.html">João Silva</a></li>
```

### 5. Envie suas alterações
Agora vamos subir o código para o seu GitHub:

```bash
git add .
git commit -m "Adicionando página do Aluno [Seu Nome]"
git push origin feature/seu-nome
```

### 6. Abra um Pull Request (PR)
Volte para a página do seu repositório no GitHub.

Você verá um aviso de que seu ramo está à frente. Clique em Compare & pull request.

Revise se está tudo certo, a branch de destino é a DEVELOP, e confirme o envio.

### ⚠️ Regras Importantes
Respeite o código do colega: Ao editar o index.html, cuidado para não apagar a linha de outra pessoa. Adicione a sua linha no final da lista.

Nomes de arquivo: Não use espaços ou caracteres especiais no nome do seu arquivo.

✅ maria-souza.html

❌ maria souza.html

❌ mari@.html

Mantenha simples: Não adicione CSS ou Scripts agora. Vamos focar no HTML puro.


Bom código a todos! 🚀

