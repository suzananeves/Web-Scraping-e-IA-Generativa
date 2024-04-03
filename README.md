# Web Scraping e IA Generativa
Quando se procura um novo trabalho, é um questionamento comum querer saber se os seus conhecimentos estão de acordo com o que as vagas exigem.
Esse projeto tem como objetivo coletar as descrições de vagas abertas para analista de dados no site vagas.com.br, e então pedir para a IA generativa do Google, o Gemini, separar as "Hard Skills", pedidas pelas vagas. As informações geradas pela IA são então analisada com o python e são levantadas quantas vezes cada ferramenta aparece.

## Pré-Requisitos
### API do Gemini
Para que a Aplicação funcione, você irá precisar gerar uma chave e instalar a API do Gemini. A própria Google deisponibiliza um tutorial de como fazer isso e você pode conferir [aqui](https://ai.google.dev/tutorials/python_quickstart)

### Instalando Bibliotecas
#### Beautiful Soup
A biblioteca é util para lidar com HTML de sites, para instalar ela você pode usar o comando:
```bash
pip install beautifulsoup4
```
#### Requests
A biblioteca Requests também será útil na execução do projeto, para instalar ela:
```bash
pip install requests
```
## Projeto
Todo o código do projeto e a explicação de cada linha pode ser vista [aqui](https://github.com/suzananeves/Web-Scraping-e-IA-Generativa/blob/main/Analise.ipynb)

## Resultado
O projeto retorna um Dicionário Python ordenado do item com mais requisições, para o com menos. Foi selecionado os 20 primeiros itens e colocados na tabela abaixo:

| Ferramenta | Quantidade de vezes que ela aparece |
|--------------------------|------:|
| Excel                    |    10 |
| Power BI                 |     9 |
| SQL                      |     8 |
| Power Point              |     5 |
| Python                   |     4 |
| Excel avançado           |     3 |
| SQL Server               |     3 |
| Pacote Office            |     3 |
| Análise de Dados         |     2 |
| PowerBI                  |     2 |
| Modelagem de Dados OLTP  |     2 |
| Modelagem de Dados OLAP  |     2 |
| Conceitos Datalake       |     2 |
| Conceitos Lakehouse      |     2 |
| ETL/ELT                  |     2 |
| Metodologia Ágil         |     2 |
| Inglês leitura           |     2 |
| TOTVS                    |     2 |
| Oracle                   |     2 |
| Análise de dados         |     2 |

É possível ver que a Ferramenta Power BI Aparece 2 vezes na tabela, assim como excel que aparece como Excel e Excel Avançado, refazendo a tabela novamente, agrupando os iten iguais, temos:
 Ferramenta | Quantidade de vezes que ela aparece |
|--------------------------|------:|
| Excel                    |    13 |
| Power BI                 |    11 |
| SQL                      |     8 |
| Power Point              |     5 |
| Python                   |     4 |
| SQL Server               |     3 |
| Pacote Office            |     3 |
| Análise de Dados         |     2 |
| Modelagem de Dados OLTP  |     2 |
| Modelagem de Dados OLAP  |     2 |
| Conceitos Datalake       |     2 |
| Conceitos Lakehouse      |     2 |
| ETL/ELT                  |     2 |
| Metodologia Ágil         |     2 |
| Inglês leitura           |     2 |
| TOTVS                    |     2 |
| Oracle                   |     2 |
| Análise de dados         |     2 |

Assim, entre os 3 itens mais requisitados nessa amostra temos o Excel, Power BI e SQL


