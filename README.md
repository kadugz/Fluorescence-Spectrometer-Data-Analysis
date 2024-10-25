# Fluorescence Spectrometer Data Analysis

Este repositório contém códigos para análise e visualização de dados provenientes de um espectrofluorímetro. Os scripts foram desenvolvidos para facilitar a compreensão e a visualização dos dados de fluorescência em gráficos 2D e 3D.

## Contribuição
Agradecimentos ao professor **Leandro das Merces Silva** pela contribuição na compreensão dos dados e pelo suporte durante o desenvolvimento deste repositório, em sua disciplina, **Laboratório Avançado III**, dada na instituição **ilum - Escola de ciência**.

## Estrutura do Repositório
- `code_2D.ipynb`: Notebook contendo apenas o código para gerar gráficos 2D das intensidades de fluorescência.
- `code_3D.ipynb`: Notebook contendo apenas o código para gerar gráficos 3D das intensidades de fluorescência.
- `analysis.ipynb`: Notebook contendo ambos os códigos em um formato explicativo e organizado.

Os códigos realizam o plot de dois gráficos, 2D e 3D, e geram sua imagem em um arquivo `.png`, à partir dos dados fornecidos pela máquina, no formato `.txt`. Além disso, os arquivos `code_2D.ipynb` e `code_3D.ipynb` foram pensados para usuários mais experientes, que buscam apeenas o código que irá fornecer seu gráfico. Ainda assim, indico que seja baixado o `analysis.ipynb` para uma maior compreensão do código em si, facilitando possíveis alterações para outros modelos de máquina.

## Como Usar
1. **Clone este repositório**:
   ```bash
   git clone https://github.com/kadugz/Fluorescence-Spectrometer-Data-Analysis.git
   ```
2. **Instale as dependências** (se necessário):
   ```bash
   pip install numpy matplotlib pandas mpl_toolkits
   ```

3. **Execute os Notebooks**:
   - Use um ambiente Jupyter Notebook para abrir e executar `code_2D.ipynb` ou `code_3D.ipynb` para análises específicas.
   - Para uma visão geral e explicativa, consulte o `analysis.ipynb`.

## Exemplo de Uso
- Certifique-se de que os arquivos de dados estão no formato correto (arquivo `.txt` conforme especificado nos códigos).
- Altere o nome do arquivo nos scripts, para que correspondam aos seus dados.
- Rode o arquivo `.pipynb` em uma pasta que contenha seu arquivo `.txt`.
- Aproveite seu belo gráfico!

## Referências
- Imagem presente no cabeçalho dos arquivos `code_2D.ipynb`, `code_3D.ipynb` e `analysis.ipynb` https://img.freepik.com/vetores-premium/fundo-de-linhas-de-contorno-do-mapa-topografico_389675-150.jpg
