# IPDBscan

**A ferramenta permite consultar a reputação de múltiplos IPs rapidamente, conectando à API do AbuseIPDB, lendo a chave API a partir de um arquivo de configuração e gera um relatório detalhado em Excel com os resultados das verificações, basta salvar os IPs em um arquivo e executar o programa.**

<p align="center">
<a href="https://github.com/SecZeroR/IPDBscan/releases/download/ipdbscan0.3/IPDBscan0.3.zip">Baixe a última versão aqui</a>
</p>

## Versão 0.3

---

## Utilização

### Pré-requisitos
1. **Python**: Certifique-se de ter a última versão do Python instalada. [Baixar Python](https://www.python.org/downloads/)
2. **Chave de API**: Registre-se no [AbuseIPDB](https://www.abuseipdb.com) e crie uma chave API em [https://www.abuseipdb.com/account/api](https://www.abuseipdb.com/account/api).
3. **Configuração**: Insira a chave no arquivo `API_KEY.ini`.

### Passos para Executar

1. **Descompacte o Arquivo**: Extraia `IPDBscan0.3.zip`.
2. **Inicie o Programa**: Abra o arquivo `scan.exe`.

### Modos de Execução

#### 1. Utilizando um Arquivo de IPs
   - Clique em "Localizar Arquivo" e selecione o arquivo com os IPs a serem verificados.
   - Clique em "Executar Arquivo".
   - Os resultados serão gerados em um arquivo Excel chamado `resultados.xlsx`, localizado na pasta da ferramenta.

#### 2. Inserção Manual de IPs
   - Copie e cole os IPs manualmente, um abaixo do outro.
   - Clique em "Executar Manualmente".
   - Os resultados serão gerados em um arquivo Excel chamado `resultados.xlsx`, localizado na pasta da ferramenta.

---
