# 📦 Versionamento com Git e GitHub

> 🚀 Repositório dedicado ao estudo de **Git**, **GitHub** e das principais práticas de versionamento utilizadas no desenvolvimento de software moderno.

---

# 📚 Sobre o Projeto

Este repositório foi desenvolvido com foco educacional para auxiliar estudantes e desenvolvedores a aprenderem na prática como funciona o controle de versão utilizando Git e GitHub.

Aqui serão encontrados exemplos, exercícios, comandos úteis, anotações e simulações de fluxo de trabalho em equipe.

---

# 🎯 Objetivos do Projeto

✅ Aprender Git do básico ao avançado  
✅ Entender o funcionamento do GitHub  
✅ Trabalhar com branches e merges  
✅ Organizar histórico de commits  
✅ Simular trabalho colaborativo  
✅ Aprender boas práticas de versionamento  
✅ Criar documentação profissional  
✅ Resolver conflitos entre versões  
✅ Aplicar Git em projetos reais  

---

# 🧰 Tecnologias e Ferramentas

| Ferramenta | Função |
|---|---|
| 🐙 Git | Controle de versão |
| 🌐 GitHub | Hospedagem de repositórios |
| 💻 Terminal / CLI | Execução de comandos |
| 📝 Markdown | Documentação |
| ⚡ VS Code | Editor de código |
| 🔀 Git Bash | Terminal Git |

---

# 🗂️ Estrutura do Repositório

```bash
📁 versionamento/
│
├── 📄 README.md
│
├── 📁 docs/
│   ├── git-basico.md
│   ├── github.md
│   ├── branches.md
│   └── comandos.md
│
├── 📁 exemplos/
│   ├── commits/
│   ├── merges/
│   └── conflitos/
│
├── 📁 atividades/
│   ├── atividade01.md
│   ├── atividade02.md
│   └── desafios/
│
├── 📁 projetos/
│   ├── projeto-site/
│   └── projeto-api/
│
└── 📁 assets/
    ├── imagens/
    └── diagramas/
```

---

# ⚙️ Conceitos Abordados

## 🧾 Controle de Versão

Permite registrar todas as alterações realizadas em arquivos e projetos.

---

## 📌 Commits

Os commits funcionam como “salvamentos” do projeto, registrando mudanças feitas no código.

Exemplo:

```bash
git commit -m "feat: adiciona tela de login"
```

---

## 🌿 Branches

As branches permitem desenvolver funcionalidades separadamente sem afetar a versão principal.

---

## 🔀 Merge

Utilizado para unir alterações de diferentes branches.

---

## 🔁 Rebase

Reorganiza o histórico de commits para deixá-lo mais limpo e organizado.

---

## 📥 Pull Requests

Ferramenta utilizada no GitHub para revisão e integração de código.

---

## 🧩 Resolução de Conflitos

Conflitos acontecem quando duas alterações afetam a mesma parte do código.

---

## 🏷️ Tags

Usadas para marcar versões importantes do projeto.

Exemplo:

```bash
git tag v1.0
```

---

# 🚀 Como Começar

## 📥 Clonar o Repositório

```bash
git clone https://github.com/prof-andrericardo/versionamento.git
```

---

## 📂 Entrar na Pasta

```bash
cd versionamento
```

---

## 🔍 Verificar Arquivos

```bash
ls
```

---

# 🔄 Fluxo de Trabalho Básico

## 📌 Verificar Status

```bash
git status
```

---

## ➕ Adicionar Arquivos

```bash
git add .
```

---

## 📝 Criar Commit

```bash
git commit -m "feat: adiciona nova funcionalidade"
```

---

## 🚀 Enviar Alterações

```bash
git push origin main
```

---

# 🌿 Trabalhando com Branches

## 🌱 Criar Branch

```bash
git checkout -b nova-feature
```

---

## 🔄 Trocar de Branch

```bash
git checkout main
```

---

## 🔀 Fazer Merge

```bash
git merge nova-feature
```

---

# 📥 Atualizando Repositório

## ⬇️ Baixar Alterações

```bash
git pull origin main
```

---

# 🧪 Boas Práticas

✔️ Faça commits pequenos  
✔️ Utilize mensagens claras  
✔️ Organize o histórico  
✔️ Trabalhe em branches  
✔️ Documente alterações  
✔️ Revise o código antes do push  
✔️ Evite commits gigantes  
✔️ Atualize frequentemente o repositório  
✔️ Utilize Pull Requests  

---

# 🧠 Exemplos de Commits

```bash
feat: adiciona sistema de login
fix: corrige erro de autenticação
docs: atualiza README
style: melhora identação
refactor: reorganiza estrutura
test: adiciona testes unitários
```

---

# 🧩 Tipos de Commits (Conventional Commits)

| Tipo | Descrição |
|---|---|
| feat | Nova funcionalidade |
| fix | Correção de bugs |
| docs | Documentação |
| style | Formatação |
| refactor | Refatoração |
| test | Testes |
| chore | Manutenção |

---

# 📊 Fluxo Git Flow

```text
main → versão estável
develop → desenvolvimento
feature → novas funcionalidades
hotfix → correções urgentes
release → preparação de versão
```

---

# 🔐 Vantagens do Git

✅ Histórico completo  
✅ Segurança no código  
✅ Trabalho em equipe  
✅ Controle de alterações  
✅ Recuperação de versões antigas  
✅ Organização do desenvolvimento  

---

# 📚 Comandos Úteis

## 📌 Histórico de Commits

```bash
git log
```

---

## 📌 Ver Branches

```bash
git branch
```

---

## 📌 Remover Arquivo do Stage

```bash
git reset arquivo.txt
```

---

## 📌 Clonar Branch Específica

```bash
git clone -b main URL_DO_REPOSITORIO
```

---

## 📌 Criar Tag

```bash
git tag v1.0
```

---

# 📈 Benefícios do Versionamento

* Melhor organização
* Maior segurança
* Facilidade em equipes
* Controle de mudanças
* Histórico completo
* Recuperação de versões
* Desenvolvimento mais profissional

---

# 🤝 Colaboração em Equipe

O Git permite que várias pessoas trabalhem simultaneamente no mesmo projeto sem sobrescrever alterações.

---

# 📌 Como Contribuir

```bash
# Fork do projeto

# Criar branch
git checkout -b minha-contribuicao

# Fazer alterações
git add .

# Commit
git commit -m "feat: minha contribuição"

# Push
git push origin minha-contribuicao
```

---

# 🛠️ Sugestões Futuras

- [ ] Adicionar exemplos avançados
- [ ] Criar exercícios práticos
- [ ] Adicionar integração contínua
- [ ] Criar guia de GitHub Actions
- [ ] Adicionar exemplos de conflitos
- [ ] Criar mini projetos colaborativos

---

# 📄 Licença

📜 Este projeto está licenciado sob a licença MIT.

---

# 👨‍🏫 Autor

Desenvolvido para fins educacionais 💙

👨‍💻 Professor & Desenvolvedor

---

# 🌟 Considerações Finais

Aprender Git e GitHub é essencial para qualquer desenvolvedor moderno.  
O versionamento ajuda na organização, colaboração e evolução de projetos de software.

---

> 💬 *"Versionar não é apenas salvar código, mas registrar a evolução do conhecimento."* 🚀