# Sistema de Boletim Escolar em Python

## 📌 Descrição do Projeto

O **Sistema de Boletim Escolar em Python** é um projeto desenvolvido para realizar o cadastro de estudantes, registrar notas e faltas por disciplina e gerar um boletim final com o desempenho escolar.

O sistema permite calcular a soma anual de pontos, a média bimestral, o total de faltas, o percentual de ausência e o status final do estudante em cada disciplina.

Este projeto foi desenvolvido com foco em praticar conceitos fundamentais de programação em Python, como funções, listas, dicionários, estruturas de repetição, estruturas condicionais, validação de dados e organização de código.

---

## 🎯 Objetivo

O objetivo do sistema é facilitar o controle de notas e frequência de um estudante, exibindo ao final um relatório organizado com a situação escolar em cada matéria.

---

## ⚙️ Funcionalidades

- Cadastro dos dados do estudante:
  - Nome;
  - Matrícula;
  - Quantidade de bimestres;
  - Total de aulas no período.

- Cadastro de notas por disciplina:
  - Nota do caderno;
  - Nota do trabalho;
  - Nota da prova.

- Validação das notas:
  - Caderno: de 0 a 2.5 pontos;
  - Trabalho: de 0 a 2.5 pontos;
  - Prova: de 0 a 5.0 pontos.

- Cadastro de faltas por bimestre.

- Cálculo automático:
  - Soma anual das notas;
  - Média bimestral;
  - Total de faltas;
  - Percentual de faltas.

- Definição do status final:
  - Aprovado;
  - Recuperação;
  - Reprovado por Nota;
  - Reprovado por Faltas.

- Geração de boletim final no terminal.

---

## 🧠 Como o Sistema Funciona

O programa inicia solicitando os dados básicos do estudante. Em seguida, percorre uma lista de disciplinas e solicita as notas e faltas de cada bimestre.

As disciplinas cadastradas no sistema são:

- Português;
- Matemática;
- Geografia;
- História;
- Artes;
- Educação Física.

Após o cadastro das informações, o sistema calcula os resultados e exibe um boletim final com os dados de cada matéria.

---

## 🧮 Critérios de Avaliação

O sistema utiliza os seguintes critérios para definir a situação final do estudante:

- **Reprovado por Faltas**: quando o percentual de faltas for maior que 60%;
- **Aprovado**: quando a soma anual de pontos for maior ou igual a 25;
- **Recuperação**: quando a média bimestral for maior ou igual a 6.0;
- **Reprovado por Nota**: quando nenhum dos critérios anteriores for atendido.

---

## 🛠️ Tecnologias Utilizadas

- Python 3;
- Terminal ou Prompt de Comando;
- Editor de código, como VS Code, PyCharm ou outro de sua preferência.

---

## 📁 Estrutura do Projeto

```bash
sistema-boletim-escolar/
│
├── project.py
└── README.md
```

---

## ▶️ Como Executar o Projeto

### 1. Clone este repositório

```bash
git clone https://github.com/dinizgustavo085-maker
```

### 2. Acesse a pasta do projeto

```bash
cd sistema-boletim-escolar
```

### 3. Execute o arquivo Python

```bash
python project.py
```

> Caso esteja usando Linux ou macOS, talvez seja necessário usar:

```bash
python3 project.py
```

---

## 💻 Exemplo de Uso

Durante a execução, o sistema solicitará informações como:

```text
Nome do estudante: Gustavo
Digite a matricula: 12345
Digite quantos bimestres quer (1 a 4): 4
Digite o total de aulas no período: 200
```

Depois, para cada disciplina, o sistema solicitará as notas e faltas:

```text
--- Lançando notas de: Matemática ---

> bimestre 1
Caderno (max 2.5): 2.0
Trabalho (max 2.5): 2.5
Prova (max 5.0): 4.0
Faltas no bimestre 1: 2
Total do bimestre: 8.50
```

Ao final, será exibido o boletim final do estudante com notas, faltas e status.

---

## 📊 Exemplo de Saída

```text
============================================================
BOLETIM FINAL: Gustavo (ID: 12345)
============================================================

Matéria: Matemática
Notas Bimestrais: [8.5, 7.0, 9.0, 8.0]
Soma Anual de Pontos: 32.50 / 40.0
Média Bimestral: 8.12
Faltas: 8 ausências (4.0%)
Status Final: Aprovado
------------------------------------------------------------
```

---

## 👨‍💻 Autor

**Gustavo Alves de Melo Diniz**  
Estudante do **Centro Universitário do Distrito Federal (UDF)**  

GitHub: [dinizgustavo085-maker](https://github.com/dinizgustavo085-maker)
