# PTP CSharp

Exercícios da aula de C# (Windows Forms).

**Stack:** C# · Windows Forms · .NET

**Documentação:**
- [Issue de organização](https://github.com/ClavioBahama/PTP_CSharp/issues/1) — revisão e sugestões

---

## 0. Pré-requisitos

Visual Studio com a carga de trabalho .NET Desktop Development.
.NET SDK compatível com a solução (`.slnx`).

## 1. Instalação e Execução

```powershell
Abrir o Visual Studio   #  abrir a solução e compilar (F6)
dotnet build   # alternativa por linha de comando, se o SDK suportar `.slnx`
```

## 2. Estrutura do Projeto

```text
PTP_CSharp/
├── Aula_1_CSharp.exe     # executável gerado
├── Form1.cs              # formulário principal
└── Program.cs            # ponto de entrada
```

## 3. Funcionalidades

- Exercício de aula de C#.
- Interface Windows Forms (Form1).
- Executável de exemplo incluído.

## 4. Arquivos e pontos de entrada

- `Form1.cs` — interface do formulário.
- `Program.cs` — inicialização da aplicação.

## 5. Segurança

Nenhuma credencial identificada no repositório.

## 6. Problemas Comuns

Arquivos `.exe` compilados não devem ser versionados — use `.gitignore` para `bin/` e `obj/`.
Se o SDK não reconhecer `.slnx`, abra a solução no Visual Studio atualizado.

## 7. Observações (organização)

> Revisão realizada em 17/11/2026 durante a padronização dos repositórios, inspirada no README do FreelaMZ.
- Material de aula de C#; contém um executável compilado no repositório.
- Sugestão: versionar apenas o código-fonte e adicionar `.gitignore` para `bin/`, `obj/` e `.exe`.

## 8. Licença

Projeto pessoal/acadêmico. Verifique a licença de templates ou bibliotecas de terceiros antes de uso comercial.

