# Sistema de Gestão de Cestas Básicas

Este projeto é um sistema interativo para gerenciar doações e distribuições de cestas básicas. Ele permite registrar entradas e saídas, visualizar o estoque atual e gerar relatórios gráficos.

## Funcionalidades

* **Registro de Doações:** Permite adicionar novas doações ao estoque, especificando a data, responsável e quantidade.
* **Registro de Distribuições:** Permite registrar a distribuição de cestas, decrementando o estoque.
* **Visualização de Estoque:** Exibe a quantidade atual de cestas em estoque, o total recebido e o total distribuído.
* **Relatórios Gráficos:** Apresenta gráficos da evolução do estoque ao longo do tempo.
* **Estatísticas Regionais:** *(Funcionalidade Futura)* Um botão está reservado para buscar estatísticas regionais, mas a funcionalidade precisa ser implementada.

## Como Usar

1.  **Executar o Notebook:** Abra o arquivo `Gestao Cestas Basicas Alura- Projeto.ipynb` em um ambiente Jupyter (como o Jupyter Notebook, JupyterLab ou Google Colab).
2.  **Interagir com a Interface:** Preencha os campos de data, responsável e quantidade para registrar doações ou distribuições.
3.  **Utilizar os Botões:**
    * `Registrar Doação`: Adiciona a doação ao sistema.
    * `Registrar Distribuição`: Remove as cestas distribuídas do sistema.
    * `Mostrar Relatório`: Exibe o estoque atual e os gráficos.
    * `Buscar Estatísticas Regionais`: *(Ainda não funcional)* Pretende buscar dados estatísticos.

## Requisitos

* Python 3.x
* Bibliotecas Python:
    * `ipywidgets`
    * `matplotlib`
    * `pandas`
    * `IPython.display` (para `clear_output`)

## Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)
    cd [nome do repositório]
    ```
    
2.  **Instale as dependências (recomendado usar um ambiente virtual):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Linux/macOS
    venv\Scripts\activate  # No Windows
    pip install ipywidgets matplotlib pandas
    jupyter notebook  # Ou jupyter lab
    ```

    ## Notas

* O projeto utiliza `ipywidgets` para criar uma interface interativa diretamente no notebook Jupyter.
* Os dados são armazenados em listas na memória, ou seja, os dados são perdidos ao reiniciar o kernel do Jupyter. Para persistência de dados, seria necessário implementar um banco de dados ou salvar em arquivos.
* A funcionalidade de "Buscar Estatísticas Regionais" está presente na interface, mas a lógica para buscar e exibir esses dados ainda precisa ser desenvolvida.

## Contribuição

Contribuições são bem-vindas! Se você tiver ideias para melhorar o projeto, como adicionar persistência de dados, implementar a funcionalidade de estatísticas regionais ou otimizar a interface, sinta-se à vontade para abrir uma issue ou enviar um pull request.
