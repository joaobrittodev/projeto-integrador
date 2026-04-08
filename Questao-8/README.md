# Sistema de Recomendação de Filmes
![GitHub language count](https://img.shields.io/github/languages/count/joaobrittodev/projeto-integrador?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/joaobrittodev/projeto-integrador?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/license/mit)

![Comparação de Desempenho](https://private-us-east-1.manuscdn.com/sessionFile/4cNtcn5wkZO7LKCeRFihRH/sandbox/IL9mMIQXzcpDFsfoH0XD00-images_1775510842357_na1fn_L2hvbWUvdWJ1bnR1L21vZGVsX2NvbXBhcmlzb24.png?Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9wcml2YXRlLXVzLWVhc3QtMS5tYW51c2Nkbi5jb20vc2Vzc2lvbkZpbGUvNGNOdGNuNXdrWk83TEtDZVJGaWhSSC9zYW5kYm94L0lMOW1NSVFYemNwREZzZm9IMFhEMDAtaW1hZ2VzXzE3NzU1MTA4NDIzNTdfbmExZm5fTDJodmJXVXZkV0oxYm5SMUwyMXZaR1ZzWDJOdmJYQmhjbWx6YjI0LnBuZyIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTc5ODc2MTYwMH19fV19&Key-Pair-Id=K2HSFNDJXOU9YS&Signature=eOuSsra6YhMNKPqReQ1dhLU9rBF6EafCMBv2jjfDEJDKnE2KgJaqygBLfpgYnOJjUNIbJU9HiqpwEqUwEYAKmTUXjdg6EFfFl7WxGdi9S6lp0xW6sHr0jtZBxWP1qEorukjdQerDD0uLtiLifQ-92SjEHGHSt0JpyHHdQ-3I47jN4X~ZerLav5jrjUsgOZBcDVf459D7RhSjHBNWwpSWP0je7ZNUucCz2Ls~VcP4cPF-pKJx38Kb3NF5ZAfqmOIujkTfcY35yr-LxrZe4JZijy8VYGmV3tNFqlrC2eGa6Y7F7zYHPgaDTdlJXiqOzxWgSxXkDG8eda7M5doyYTqOhg__)

> Este projeto implementa e compara sistemas de recomendação de filmes utilizando o dataset MovieLens 100k. Avalia a eficiência da Filtragem Colaborativa e de modelos de Deep Learning (Autoencoders) para predição de avaliações.

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas para as seguintes tarefas:

- [ ] Implementar Sistemas Híbridos (Filtragem Colaborativa + Baseada em Conteúdo)

- [ ] Explorar Arquiteturas de Deep Learning mais avançadas (VAEs, GNNs)

- [ ] Incorporar Informações Contextuais (e.g., `timestamp`)

- [ ] Otimizar Hiperparâmetros dos modelos

- [ ] Adicionar funcionalidade de recomendação em tempo real

## 💻 Pré-requisitos

Antes de começar, certifique-se de ter o **Anaconda** ou **Miniconda** instalado. Este projeto foi desenvolvido e testado em um ambiente com **Python 3.11** no Windows, mas deve ser compatível com Linux e macOS.

## 🚀 Instalando o Sistema de Recomendação de Filmes

Para instalar e configurar o ambiente do projeto, siga estas etapas:

1. **Crie um novo ambiente Conda com Python 3.11:**

   ```bash
   conda create -n filmes python=3.11 -y
   ```

1. **Ative o novo ambiente:**

   ```bash
   conda activate filmes
   ```

1. **Instale todas as bibliotecas necessárias (incluindo Jupyter Notebook):**

   ```bash
   conda install -c conda-forge scikit-learn scikit-surprise pandas matplotlib seaborn pytorch notebook -y
   ```

   *Nota: O **`numpy`** será instalado automaticamente em uma versão compatível com **`scikit-surprise`**.*

1. **Verifique se as principais bibliotecas foram instaladas corretamente (opcional):**

   ```bash
   python -c "import sklearn; import surprise; import torch; print(\'Tudo instalado com sucesso!\')"
   ```

## ☕ Usando o Sistema de Recomendação de Filmes

Para usar o sistema de recomendação, siga estas etapas:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/joaobrittodev/projeto-integrador.git
   cd projeto-integrador
   ```

1. **Ative o ambiente Conda (se ainda não estiver ativado):**

   ```bash
   conda activate filmes
   ```

1. **Inicie o Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

   Nota: Caso não execute automaticamente tente a porta `localhost:8888`

1. No navegador, abra o arquivo `Recomendacao_Filmes_MovieLens.ipynb`.

1. Execute as células do notebook sequencialmente. A primeira célula de código fará o download e a extração do dataset MovieLens 100k automaticamente.

## 📝 Licença

Este projeto está licenciado sob a licença MIT.

