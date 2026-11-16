# Portfólio Git

Repositório do **Projeto Integrador Final** do curso *Fundamentos de Git e GitHub* (CEFET-MG/UFCI-MG). Ele começou como a Atividade 2, para praticar os comandos básicos do Git, e evoluiu para um portfólio pessoal publicado na web, desenvolvido com Issues, branches e Pull Requests.

**Site publicado:** https://guicosta-0407.github.io/portfolio-git

## Sobre o projeto

O objetivo deste repositório é praticar o fluxo completo de controle de versão: registrar mudanças em commits, organizar o trabalho em branches, integrá-lo por Pull Request e publicar o resultado com o GitHub Pages. O conteúdo do portfólio (apresentação, projetos e contato) serve de material para esse treino.

### Comandos praticados

| Comando | Para que serve |
|---|---|
| `git init` | Cria um repositório Git na pasta |
| `git status` | Mostra o estado atual dos arquivos |
| `git add` | Seleciona mudanças para o próximo commit |
| `git commit` | Registra as mudanças no histórico |
| `git diff` | Mostra o que foi alterado em cada arquivo |
| `git log` | Lista o histórico de commits |
| `git switch -c` | Cria uma branch e muda para ela |
| `git push` | Envia os commits para o GitHub |

## Estrutura do repositório

```
portfolio-git/
├── index.html     # Página inicial do site
├── css/
│   └── style.css  # Estilos do site
├── README.md      # Apresentação do projeto
├── sobre.md       # Informações sobre mim
├── contato.md     # Canais de contato
├── reflexao.md    # Reflexão sobre o curso
├── LICENCA.md     # Licença do projeto
└── .gitignore     # Arquivos e pastas ignorados pelo Git
```

O `.gitignore` ignora arquivos `*.log` e a pasta `.vscode/`, que são locais e não precisam ir para o repositório.

## Fluxo de trabalho

Cada mudança neste repositório segue o mesmo ciclo:

1. Uma **Issue** descreve a tarefa.
2. Uma **branch** própria recebe o trabalho, sem afetar a `main`.
3. Um **Pull Request** leva a branch para a `main`.
4. O `Closes #N` no commit e no PR fecha a Issue automaticamente.

## Meus projetos

- [Lizard Adventures: TTT](https://github.com/ALTERAR/Lizard-Adventures-TTT)
- [Sistema MRP II](https://github.com/ALTERAR/Sistema-MRP-II)
- [ZAP!](https://github.com/amarildopuma/Zap-)
- [Batalha Naval em Python](https://github.com/guicosta-0407/batalha-naval-python)

## Habilidades

- Linguagens: C, Java e Python
- Versionamento: Git e GitHub
- Documentação: Markdown
- Web: HTML e CSS

## Convenções