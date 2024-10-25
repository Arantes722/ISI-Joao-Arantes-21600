# ISI-Joao-Arantes-21600

# Projeto de Integração de Sistemas Informáticos - Meteorologia

## Descrição
Este projeto tem como objetivo a integração de dados meteorológicos obtidos através da API da Open Weather Map. Através de um processo de ETL (Extração, Transformação e Carga), os dados são extraídos, tratados e disponibilizados em formatos diversos (XML, TXT, Excel) para análise e visualização.

## Funcionalidades
- **Extração de Dados**: Coleta de informações meteorológicas em tempo real através da API da Open Weather Map.
- **Transformação de Dados**: Limpeza e normalização dos dados extraídos para garantir a sua integridade.
- **Exportação**: Disponibilização dos dados em formatos XML, TXT e Excel.
- **Automação de Processos**: Envio automático de dados por e-mail através de Jobs programados.
- **Demonstração**: Vídeo explicativo sobre o funcionamento do projeto disponível via QR Code.

## Estrutura do Projeto
- **Transformações**:
  - `ExtratMeteorologia`: Processa a extração e tratamento dos dados meteorológicos.
  - `Html`: Processa a extração de informações a partir de um ficheiro HTML.

- **Jobs**:
  - `Get_Meteorologia`: Automatiza a execução de processos de atualização e envio de dados.
  - Job Automatizado: Executa a transformação e o Job de envio de dados.

## Pré-requisitos
- Acesso à API da Open Weather Map.
- Pentaho Kettle instalado para execução das transformações e jobs.
- Um leitor de QR Code para visualizar a demonstração.

## Como Executar o Projeto
1. **Clone este repositório**:
   ```bash
   git clone https://github.com/teu-usuario/nome-do-repositorio.git
   cd nome-do-repositorio
