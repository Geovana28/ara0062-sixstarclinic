# Os 6 Fantásticos — SixStar Clinic

Projeto da disciplina **ARA0062 · Desenvolvimento Web em HTML5, CSS, JavaScript
e PHP** — Centro Universitário Newton Paiva, 2026/2.

## Tema do projeto

Website institucional e sistema de agendamento de consultas da **SixStar Clinic**, uma clínica médica de alto padrão localizada na Savassi em Belo Horizonte (MG). O portal permite aos pacientes conhecerem o corpo clínico multidisciplinar (Cardiologia, Dermatologia, Neurologia, Ortopedia, Cirurgia Plástica e Oftalmologia), consultarem datas e escalas de atendimento, alternarem entre os modos visual Claro e Escuro (com detalhes dourados) e realizarem solicitações de agendamento de consultas com atendimento exclusivo.

## Equipe

**Líder:** Geovana Moreira

| Foto | Nome completo | Matrícula | GitHub | Papel |
| :---: | :--- | :---: | :--- | :---: |
| <img src="https://github.com/Geovana28.png" width="40px" style="border-radius:50%"> | Geovana Moreira | `202603656934` | [@Geovana28](https://github.com/Geovana28) | **líder** |
| <img src="https://github.com/Devfrzz.png" width="40px" style="border-radius:50%"> | Gabriel Ferraz | `202601484478` | [Devfrzz](https://github.com/Devfrzz) | integrante |
| 👤 | Daniel Santos| `202602575281` | [@Daizen-Creator](https://github.com/Daizen-Creator) | integrante |
| 👤 | Maria Eduarda Nascimento Silva | `202601547003 ` | [@Mariaeduarda137](https://github.com/Mariaeduarda137) | integrante |
| 👤 | Angelina Damasceno | `202602060418` | [@Angesty](https://github.com/Angesty) | integrante |
| 👤 | [Nome Completo] | `2026xxxxx` | [@usuario-github](https://github.com) | integrante |

Cada integrante acrescenta ou confirma a **sua própria linha** nesta tabela, pelo GitHub.
Esse é o commit que registra a sua participação.

## Estrutura do projeto

Estrutura obrigatória da disciplina. Não renomeie pastas nem arquivos.

O projeto é separado em duas metades: **`frontend/`** guarda o que roda no
navegador (HTML, CSS, JavaScript e imagens) e **`backend/`** guarda o que roda
no servidor (PHP).

```
.
├─ README.md               este arquivo
├─ frontend/               tudo o que roda no navegador
│   ├─ index.html          a página principal
│   ├─ css/
│   │   └─ estilo.css      estilos do site (a partir da aula 04)
│   ├─ js/
│   │   └─ script.js       comportamento da página (a partir do ciclo 6)
│   └─ img/
│       └─ .gitkeep        arquivo vazio que segura a pasta no Git
└─ backend/                tudo o que roda no servidor
    ├─ config/
    │   └─ conexao.php     conexão com o banco (a partir do ciclo 8)
    └─ processa-contato.php  recebe o formulário (a partir do ciclo 8)
```

Os dois arquivos `.php` começam vazios, só com um comentário dentro. Eles
existem desde já para que o lugar do código de servidor esteja combinado quando
o PHP chegar.

## Como abrir o projeto

1. Baixe ou clone o repositório.
2. Abra a pasta no VS Code (*Arquivo → Abrir Pasta* — a pasta do projeto
   inteira, com `frontend/` e `backend/` dentro).
3. Abra `frontend/index.html` e clique em **Go Live** (extensão Live Server).

Como o `index.html` está dentro de `frontend/`, os caminhos dele ficam assim:

| Para chegar em | Escreva no `index.html` |
|---|---|
| a folha de estilos | `css/estilo.css` |
| o script | `js/script.js` |
| uma imagem | `img/foto.jpg` |
| um arquivo do backend | `../backend/processa-contato.php` |

Os dois pontos (`..`) sobem uma pasta: saem do `frontend/` antes de entrar no
`backend/`.

## Andamento por ciclo

- [x] Ciclo 3 — repositório, equipe e estrutura do projeto
- [x] Ciclo 3 — `frontend/`: página com listas, tabela e formulário de contato/agendamento
- [x] Ciclos 4 e 5 — `frontend/css/`: identidade visual com dois temas (Escuro/Claro)
- [ ] Ciclos 6 e 7 — `frontend/js/`: interação, validação e dados via JSON
- [ ] Ciclos 8 a 10 — `backend/`: formulário que grava e lista do banco
