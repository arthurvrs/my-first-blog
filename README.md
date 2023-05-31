# Django-Girls-Tutorial

> Aprendendo a mexer no Django.

## Instalando o Python e o Django

- Primeiramente, baixar e instalar o [Python](https://www.python.org/).

- Após isso, no diretório escolhido, criar um ambiente virtual (virtual environment ou venv):
	```sh
    python -m venv nome_do_ambiente_virtual
    ```

- Ativar o venv:
	```sh
    myvenv\Scripts\activate
    ```

- Checar se o pip está instalado e atualizado:
	```sh
    python -m pip install --upgrade pip
    ```
    Para ver a versão:
    ```sh
    pip --version
    ```

- Criar um arquivo .txt chamado requirements e adicionar a seguinte linha:
    ```sh
    Django~=3.2.10
    ```

- Após isso, instale com:
    ```sh
    pip install -r requirements.txt
    ```

- Pronto, o Django estará instalado caso nada tenha dado errado :D

> ## Fonte com mais informações: [Django Girls Tutorial](https://tutorial.djangogirls.org/en/)
