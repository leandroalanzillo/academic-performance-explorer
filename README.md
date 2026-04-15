# 📚 Academic Performance Explorer

Análise exploratória de dados sobre hábitos de estudantes e seu impacto no desempenho acadêmico.

## 🎯 Objetivo

Investigar quais hábitos do dia a dia — como horas de estudo, uso de redes sociais, qualidade do sono e alimentação — mais influenciam a nota dos alunos.

## ❓ Perguntas analisadas

- Quais hábitos impactam mais o desempenho dos alunos?
- Alunos que estudam mais de 5h/dia têm notas melhores que os que estudam menos de 2h?
- O tempo gasto em redes sociais afeta o desempenho?
- Alunos mais saudáveis têm melhores resultados?

## 📊 Dataset

O dataset utilizado é o `student_habits_performance.csv`, contendo **1000 registros** e **16 colunas**, incluindo:

| Coluna | Descrição |
|---|---|
| `student_id` | ID do aluno |
| `age` | Idade |
| `gender` | Gênero |
| `study_hours_per_day` | Horas de estudo por dia |
| `social_media_hours` | Horas em redes sociais |
| `netflix_hours` | Horas de streaming |
| `part_time_job` | Possui emprego part-time |
| `attendance_percentage` | Frequência nas aulas |
| `sleep_hours` | Horas de sono |
| `diet_quality` | Qualidade da alimentação |
| `exercise_frequency` | Frequência de exercícios |
| `mental_health_rating` | Saúde mental (escala) |
| `exam_score` | Nota no exame final |

## 🛠️ Tecnologias utilizadas

- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🚀 Como executar

1. Clone o repositório:
```bash
git clone https://github.com/leandroalanzillo/academic-performance-explorer.git
```

2. Instale as dependências:
```bash
pip install pandas matplotlib seaborn
```

3. Abra o notebook:
```bash
jupyter notebook main.ipynb
```

## 📈 Principais conclusões

- Alunos que estudam **mais de 5h/dia** têm média de **~90 pontos**, enquanto os que estudam **menos de 2h** têm média de **~45 pontos**
- O uso excessivo de redes sociais está associado a **notas mais baixas**
- Hábitos saudáveis (exercício, alimentação e saúde mental) apresentam correlação positiva com o desempenho

## 🔗 Acesse

<div align="center">
  <a href="https://github.com/leandroalanzillo/academic-performance-explorer">
    <img src="https://img.shields.io/badge/Ver%20Repositório-000000?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
  <a href="https://github.com/leandroalanzillo/academic-performance-explorer/blob/main/main.ipynb">
    <img src="https://img.shields.io/badge/Ver%20Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/leandroalanzillo/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</div>
