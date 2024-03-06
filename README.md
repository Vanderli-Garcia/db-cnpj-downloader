# db-cnpj-downloader
Programa em python que baixa uma base de dados (publicos) de CNPJ's do governo e transforma em 2 arquivo SQLITE, um arquivo intermediário `data_raw.db` com a mesma configuração de tabelas do governo, outro arquivo `data.db` com 4 tabelas (Empresas, Simples, Socios e Estabelecimentos).
---

# Como instalar
> Instalar o [Python](https://www.python.org/).

> Isntale os requerimentos com o comando a baixo.
```bash
pip install -r requirements.txt
```
> Clone o repositório.
```bash
git clone https://github.com/GennysonJunior/db-cnpj-downloader
```
---
# Como usar
> Entrar no diretório com o comando abaixo.
```bash
cd /db-cnpj-downloader
```
> Rode o seguinte comando para iniciar.
```bash
py db_download.py start
```
> Você pode usar o seguinte comando para listar as opções de comandos, e usar as opções que desejar.
```bash
py db_download.py -?
```
> Ao terminar, o programa cria duas pasta, uma `/db` onde fica os arquivos SQLITE e outra `/download` onde é baixado os dados (csv) publicos do governo.
