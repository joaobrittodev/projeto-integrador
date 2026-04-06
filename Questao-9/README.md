# Classificação de Pneumonia em Raio-X com CNN

![GitHub repo size](https://img.shields.io/github/repo-size/seu-usuario/xray-pneumonia-classification?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/seu-usuario/xray-pneumonia-classification?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/seu-usuario/xray-pneumonia-classification?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/seu-usuario/xray-pneumonia-classification?style=for-the-badge)

<img src="roc_curve.png" alt="Exemplo de Curva ROC do Modelo" width="400px">

> Este projeto utiliza Redes Neurais Convolucionais (CNN) para classificar imagens de raio-X de tórax entre saudáveis e com pneumonia, focando em superar desafios de desbalanceamento de dados médicos.

### Ajustes e melhorias

O projeto foca na implementação de um pipeline robusto de Deep Learning. As próximas etapas de desenvolvimento incluem:

- [x] Processamento do dataset NIH (Data_Entry_2017.csv)
- [x] Implementação de Data Augmentation para imagens médicas
- [x] Treinamento com Transfer Learning (MobileNetV2)
- [x] Ajuste de Pesos de Classe para lidar com desbalanceamento
- [ ] Implementação de Grad-CAM para interpretabilidade visual
- [ ] Testes com arquiteturas mais profundas (ResNet/EfficientNet)

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

* Você instalou a versão mais recente de `Python 3.10+` e `pip`.
* Você tem uma máquina `Windows / Linux / Mac` com suporte a `TensorFlow 2.x`.
* Você possui o dataset de imagens de raio-X e o arquivo `Data_Entry_2017.csv`.

## 🚀 Instalando as dependências

Para instalar as dependências necessárias, siga estas etapas:

Linux, macOS e Windows:
```bash
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
```

## ☕ Usando o Projeto

Para usar o notebook de classificação, siga estas etapas:

1. Certifique-se de que o arquivo `Data_Entry_2017.csv` está na raiz do projeto.
2. Abra o arquivo `pneumonia_classification.ipynb` no Jupyter Notebook ou VS Code.
3. Ajuste a variável `IMAGE_DIR` para o caminho da sua pasta de imagens:
   ```python
   IMAGE_DIR = r'C:\Caminho\Para\Suas\Imagens'
   ```
4. Execute todas as células para treinar e avaliar o modelo.

## 📫 Contribuindo para o projeto

Para contribuir, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b feature-nova-melhoria`.
3. Faça suas alterações e confirme-as: `git commit -m 'Adicionando nova técnica de augmentation'`.
4. Envie para o branch original: `git push origin feature-nova-melhoria`.
5. Crie a solicitação de pull.

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="#" title="Desenvolvedor Principal">
        <img src="https://avatars.githubusercontent.com/u/1" width="100px;" alt="Foto do Desenvolvedor"/><br>
        <sub>
          <b>Seu Nome</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 📝 Licença

Esse projeto está sob licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
