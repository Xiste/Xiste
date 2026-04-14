<div align="center">

```
   ██████╗ █████╗ ██╗   ██╗ █████╗ ███╗   ██╗
  ██╔════╝██╔══██╗██║   ██║██╔══██╗████╗  ██║
  ██║     ███████║██║   ██║███████║██╔██╗ ██║
  ██║     ██╔══██║██║   ██║██╔══██║██║╚██╗██║
  ╚██████╗██║  ██║╚██████╔╝██║  ██║██║ ╚████║
   ╚═════╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝
```

### Sistemas de Informação · UFU · Minas Gerais

*Construindo pipelines de dados, explorando IA e acelerando tudo com CUDA.*

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/seu-usuario)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seu@email.com)

</div>

---

## Sobre mim

Sou estudante de Sistemas de Informação na **Universidade Federal de Uberlândia**, com foco em engenharia de dados, machine learning e computação de alto desempenho. Gosto de projetos que envolvam desde a coleta bruta até a análise final dos dados, passando por arquiteturas bem estruturadas e código limpo.

Atualmente explorando:
- Arquiteturas de pipelines ETL em camadas (Bronze → Silver → Gold)
- Análise de dados com Python (Pandas, Matplotlib, Seaborn)
- Machine Learning aplicado a dados reais

---

## Stack

<div align="center">

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Dados & ML**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)

**Ambiente**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)

</div>

---

## Projetos

### LoL Match Analytics Pipeline

> Pipeline ETL para coleta, transformação e análise de partidas de League of Legends.

Consome a **Riot Games API** e organiza os dados em uma arquitetura em camadas:

```
Riot API  →  Bronze (JSON bruto)  →  Silver (SQLite estruturado)
```

**O que é calculado por partida:**

| Métrica | Descrição |
|---|---|
| DPM | Dano por minuto |
| KP | Kill Participation por jogador |
| Vision Score | Placar de visão de mapa |
| CS total | Minions de rota + selva |

**Análise de dados** *(em desenvolvimento)*

Com os dados estruturados na camada Silver, estou estudando análise exploratória com Python para extrair insights das partidas — distribuição de desempenho por campeão e posição, correlação entre métricas (DPM × vitória, visão × resultado), e evolução do jogador ao longo das partidas. A ideia é evoluir para modelos preditivos de resultado com scikit-learn.

```
Silver (SQLite)  →  Pandas  →  Matplotlib / Seaborn  →  scikit-learn
```

**Stack:** Python · SQLAlchemy · SQLite · Pandas · Matplotlib · Seaborn · Riot API v5

---

<div align="center">
<sub>Feito com curiosidade e muito café ☕</sub>
</div>
