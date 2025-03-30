# Organizador de Arquivos por Extensão

Este script Python organiza automaticamente os arquivos no diretório de Downloads com base na extensão do arquivo. Arquivos com a mesma extensão são movidos para subdiretórios separados, enquanto os arquivos sem extensão são movidos para uma pasta chamada SemExtensao. Ele também inclui logging para rastrear o progresso e erros durante a execução.

📌 Funcionalidades

✅ Organização automática: O script verifica todos os arquivos no diretório de Downloads e os move para subpastas de acordo com suas extensões.

✅ Pastas para extensões: Para cada tipo de arquivo, uma pasta correspondente à extensão é criada, e os arquivos são movidos para lá.

✅ Arquivos sem extensão: Arquivos sem extensão são movidos para uma pasta chamada SemExtensao.

✅ Logging: O script utiliza o módulo de logging para gerar mensagens informativas durante a execução e registrar erros caso ocorram.

📂 Pré-requisitos

Python 3.x

Bibliotecas padrão do Python (pathlib, logging)

🚀 Como Usar

1️⃣ Clone o repositório:

 git clone https://github.com/Lucas-Brito-Dev/organizador-arquivos.git
 cd organizador-arquivos

2️⃣ Configuração do diretório de downloads:

O script está configurado para trabalhar com o diretório de Downloads no Windows (caminho c:\Users\lucas\Downloads). Se necessário, altere a variável downloads_path no código para apontar para o diretório correto em seu sistema.

3️⃣ Executando o script:

Após configurar o caminho para o diretório de downloads, basta executar o script:

 python organizador_arquivos.py

4️⃣ Verificando os resultados:

O script cria subpastas no diretório de Downloads para cada extensão de arquivo encontrada, e os arquivos são movidos para as pastas correspondentes.

📁 Exemplo de Estrutura de Diretórios

Após a execução do script, o diretório de Downloads pode ter a seguinte estrutura:
Downloads/
    pdf/
        arquivo1.pdf
        arquivo2.pdf
    jpg/
        imagem1.jpg
        imagem2.jpg
    SemExtensao/
        arquivo1
        arquivo2
