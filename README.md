# 🎤 Show Todo Mundo no Rio

**Dashboard de Análise — Megashows em Copacabana**

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

---

## 📌 Sobre o Projeto

Este projeto analisa e compara os três maiores megashows realizados na Praia de Copacabana, Rio de Janeiro:

| Evento | Ano | Público | Agentes |
|--------|-----|---------|---------|
| 🎵 Madonna | 2024 | 1,6 M | 3.200 |
| 🎵 Lady Gaga | 2025 | 2,1 M | 7.475 |
| 🎵 Shakira | 2026 | 2,0 M | 7.927 |

A partir de dados históricos reais, o dashboard gera visualizações que revelam tendências de público, evolução do aparato de segurança e eficiência operacional — além de projeções estratégicas para o show de **2027**.

---

## 📊 Visualizações Geradas

O script gera um dashboard **2x2** com os seguintes gráficos:

- 📊 **Público Estimado** — barras comparando o público em milhões por artista
- 📈 **Evolução do Efetivo de Segurança** — linha temporal de 2024 a 2026
- 🔵 **Correlação Policiamento vs Ocorrências** — scatter plot com tamanho proporcional ao público
- 🔮 **Projeção 2027** — estimativa de público e necessidade de policiamento

---

## 💡 Insight Principal

> O uso de **tecnologia de reconhecimento facial** no show da Shakira (2026) reduziu as ocorrências em ~50%, mesmo com o maior público da série histórica. Para 2027, o foco deve estar em **contenção de fluxo**, não apenas no aumento do efetivo repressivo.

---

## 🚀 Como Executar

### Pré-requisitos

```bash
pip install pandas matplotlib seaborn numpy
```

### Execução

```bash
git clone https://github.com/seu-usuario/show-todomundonorio.git
cd show-todomundonorio
python show_todomundonorio.py
```

O dashboard abre automaticamente e os insights são impressos no terminal.

---

## 📁 Estrutura do Projeto

```
show-todomundonorio/
│
├── show_todomundonorio.py   # Script principal
├── README.md                # Este arquivo
└── assets/                  # (opcional) Imagens do dashboard
```

---

## 🔮 Projeção para 2027

A projeção é calculada com base nas tendências históricas:

- **Público estimado:** média dos três anos × 1,05
- **Policiamento necessário:** máximo histórico × 1,10

---

## 🛠️ Tecnologias Utilizadas

- **Python 3** — linguagem principal
- **Pandas** — manipulação e estruturação dos dados
- **Matplotlib** — criação dos gráficos
- **Seaborn** — estilização e temas visuais
- **NumPy** — suporte a cálculos numéricos

---

## 👤 Autora

Projeto desenvolvido por **Maria Claudia Renault Gonçalves** como análise de dados de eventos públicos de grande porte no Rio de Janeiro.

[![GitHub](https://img.shields.io/badge/GitHub-Maria54--star-181717?style=flat&logo=github)](https://github.com/Maria54-star)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Maria%20Claudia%20Renault%20Gonçalves-0A66C2?style=flat&logo=linkedin)](https://www.linkedin.com/in/maria-claudia-renault-goncalves-b30a1a296)

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<p align="center">Feito com 💚 e dados reais | Rio de Janeiro</p>
