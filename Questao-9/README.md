# Classificação de Pneumonia em Raio-X com CNN

![GitHub language count](https://img.shields.io/github/languages/count/joaobrittodev/projeto-integrador?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/joaobrittodev/projeto-integrador?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/joaobrittodev/projeto-integrador?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](https://opensource.org/license/mit)

> Este projeto utiliza Redes Neurais Convolucionais (CNN) para classificar imagens de raio-X de tórax entre saudáveis e com pneumonia, focando em superar desafios de desbalanceamento de dados médicos.

### Ajustes e melhorias

O projeto foca na implementação de um pipeline robusto de Deep Learning. As próximas etapas de desenvolvimento incluem:

- [x] Processamento do dataset NIH Chest X-rays (Data_Entry_2017.csv)
- [x] Implementação de Data Augmentation para imagens médicas
- [x] Treinamento com Transfer Learning (MobileNetV2)
- [ ] Ajuste de Pesos de Classe para lidar com desbalanceamento
- [ ] Implementação de Grad-CAM para interpretabilidade visual
- [ ] Testes com arquiteturas mais profundas (ResNet/EfficientNet)

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Você instalou a versão mais recente de `Python 3.10+` e `pip`.
* Você tem uma máquina `Windows / Linux / Mac` com suporte a `TensorFlow 2.x`.
* Você possui o dataset de imagens de raio-X e o arquivo `Data_Entry_2017.csv`.
> Tanto o dataset quanto as imagens podem ser encontrados em [Train Simple XRay CNN](https://www.kaggle.com/code/kmader/train-simple-xray-cnn)

## 🚀 Instalando as dependências

Para instalar as dependências necessárias, siga estas etapas:

Linux, macOS e Windows:
```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
```

## ☕ Usando o Projeto

Para usar o notebook de classificação, siga estas etapas:

1. Certifique-se de que o arquivo `Data_Entry_2017.csv` está na raiz do projeto.
2. Abra o arquivo `Q9-Imagens-Cnn.ipynb` no Jupyter Notebook ou VS Code.
3. Ajuste a variável `IMAGE_DIR` para o caminho da sua pasta de imagens:
   ```python
   IMAGE_DIR = r'C:\Caminho\Para\Suas\Imagens'
   ```
4. Execute todas as células para treinar e avaliar o modelo.

## 📫 Contribuindo para o projeto

Para contribuir, siga estas etapas:

1. Faça um fork
2. Crie um branch: `git checkout -b feature-nova-melhoria`.
3. Faça suas alterações e confirme-as: `ex: git commit -m 'Adicionando nova técnica de augmentation'`.
4. Envie para o branch original: `git push origin feature-nova-melhoria`.
5. Crie a solicitação de pull.

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <sub><b>João Victor(creator)</b></sub><br>
      <a href="https://github.com/joaobrittodev">João Victor</a>
    </td>
  </tr>
</table>

## 📝 Licença

Esse projeto está sob licença MIT.
