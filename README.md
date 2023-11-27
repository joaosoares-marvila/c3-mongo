# Instruções para Configurar e Executar o Projeto

Este projeto requer a configuração das credenciais de acesso ao banco de dados mongo e a criação de coleções com dados de mercado para funcionar corretamente.

## Configuração das Credenciais do Banco de Dados Mongo

As credenciais de acesso ao banco de dados estão localizadas no código, no seguinte diretório: `src/conexion/passphrase/authentication.mongo`. O usuário é 'labdatabase' e a senha é 'labDatabase2022'. Certifique-se de ajustar essas credenciais de acordo com suas configurações.

## Criação de Coleções e Inserção de Documentos

Após configurar as credenciais e verificar os arquivos SQL, você pode iniciar a execução dos scripts. Certifique-se de que o Python 3.9 esteja instalado em sua máquina com o seguinte comando:

```bash
python --version
````

Abra um terminal no diretório do projeto.
Crie um ambiente virtual com o seguinte comando:

```bash
python3 -m venv venv
````

Ative o ambiente virtual com o comando:

```bash
source venv/bin/activate
````

Instale as dependências com o seguinte comando:

```bash
pip install -r requirements.txt
````

Após a instalação das dependências, execute o seguinte comando para criar as Coleções e inserir os documentos:

```bash
python3.9 createCollectionsAndData.py
````

Por fim, execute o programa principal com o seguinte comando:

```bash
python3.9 principal.py
````

Lembre-se de que é necessário ter o Python 3.9 instalado em sua máquina para executar o projeto com sucesso.

## Vídeo de execução

CLique [aqui](https://www.youtube.com/watch?v=oa_AFW3yi-M) para assistir o vídeo de execução do código.



