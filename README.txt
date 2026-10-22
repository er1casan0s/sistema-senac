# 🏫 Sistema de Ocorrências - Médio Técnico Senac 2026

Sistema web completo e responsivo para registro, acompanhamento e gestão de ocorrências escolares e fichas de alunos do Médio Técnico Senac. Desenvolvido para ser rápido, seguro e funcionar até mesmo no celular.

## 🚀 Funcionalidades

*   **Autenticação Segura:** Acesso restrito por senha (`!Sen@c`) com bloqueio automático de tela caso o usuário minimize a janela ou troque de aba (segurança de dados).
*   **Gestão de Turmas:** Cadastro, edição e exclusão de turmas. O sistema já inicia com as turmas 1A, 1B (Manhã) e 2A, 2B (Tarde).
*   **Cadastro de Alunos:** Registro com nome, turma, turno e upload de foto.
*   **Filtros Avançados:** Busca de alunos por nome, turma e turno. Separação visual por cards de turmas.
*   **Registro de Ocorrências:** Sistema inteligente de busca de aluno (autocomplete). Classificação por códigos (F01, C01, A01, etc.) baseados na planilha institucional.
*   **Histórico Visual:** Cada aluno possui um card com o número de ocorrências. Ao clicar, exibe o histórico detalhado.
*   **Ficha do Aluno (Prontuário):** Página exclusiva com dados sensíveis (Data de Nascimento, Responsáveis, TDAH, TEA, Alergias). Possui botão de "Privacidade" (oculta os dados com desfoque) e modo de edição.
*   **PWA (App Offline):** O sistema pode ser instalado no celular como um aplicativo e carrega o layout mesmo sem internet.

## 💻 Tecnologias Utilizadas

*   **Backend:** Python (Flask)
*   **Banco de Dados:** SQLite
*   **Frontend:** HTML5, CSS3 (Design responsivo), JavaScript (Vanilla)
*   **Deploy:** Render

## 🛠️ Como rodar o projeto localmente

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/sistema-senac.git




### 💡 Como colocar isso no GitHub?
1. Vá no seu repositório no GitHub.
2. Clique no botão **"Add file"** e depois em **"Create new file"**.
3. No campo de nome, digite: `README.md` (com o ponto e o "md" no final).
4. Cole o texto acima dentro da área de texto.
5. Clique em **"Commit new file"** (botão verde).

Pronto! Agora quando você abrir a página do seu repositório, ele vai parecer um projeto super profissional e organizado.