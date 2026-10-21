# Sistema de Controle de Arquivo Morto

## Sobre o projeto

Este projeto foi desenvolvido a partir da identificação de uma dificuldade operacional no controle de documentos físicos armazenados em caixas.

O processo utilizado anteriormente apresentava limitações na organização, localização e acompanhamento das caixas, tornando algumas consultas e movimentações pouco práticas no dia a dia.

Com o objetivo de melhorar esse processo, desenvolvi um sistema web para centralizar as informações e facilitar o gerenciamento do arquivo morto.

## Objetivo

Criar uma ferramenta simples e prática para organizar os documentos físicos, facilitar sua localização e manter um histórico das movimentações realizadas.

## Funcionalidades

- Cadastro e consulta de empresas.
- Cadastro e gerenciamento de caixas.
- Identificação do tipo e período dos documentos armazenados.
- Registro da localização física de cada caixa.
- Controle de retiradas, devoluções e entregas.
- Histórico de movimentações.
- Pesquisa por código, empresa, CNPJ e localização.
- Identificação de códigos de caixas duplicados.
- Geração de relatórios.
- Exportação de dados para CSV, compatível com Excel.
- Armazenamento de registros em arquivos JSON.
- Verificação de alterações concorrentes no mesmo registro.
- Cópia de segurança dos registros excluídos.

## Tecnologias utilizadas

- HTML5 para a estrutura da aplicação.
- CSS3 para a interface e responsividade.
- JavaScript para a lógica e as funcionalidades.
- JSON para o armazenamento dos registros.
- File System Access API para leitura e gravação de arquivos e pastas autorizados pelo usuário.

## Funcionamento

A aplicação permite cadastrar empresas e vincular caixas aos respectivos registros, identificando o conteúdo, o período e a localização física.

Também permite registrar movimentações, acompanhar a situação das caixas e consultar relatórios.

Os dados são armazenados em arquivos JSON dentro de uma pasta `dados`, organizada em subpastas para empresas, caixas, movimentações, configurações e registros excluídos.

A aplicação foi desenvolvida para utilização em ambiente interno, com acesso à pasta de dados mediante autorização do navegador.

## Problema identificado

A necessidade de melhorar a organização e o controle do arquivo físico motivou o desenvolvimento desta solução.

A proposta foi substituir um processo pouco prático por uma ferramenta que facilite as consultas, padronize os registros e permita acompanhar as movimentações com maior clareza.

## Resultados esperados

- Redução do tempo necessário para localizar caixas.
- Melhor organização das informações.
- Maior facilidade para acompanhar retiradas e devoluções.
- Padronização do cadastro de documentos.
- Facilidade na geração de relatórios e consultas.
- Maior rastreabilidade das movimentações.

## Observações

O sistema utiliza recursos de acesso a arquivos disponibilizados pelo navegador e depende das permissões concedidas pelo usuário. O funcionamento em pastas de rede pode variar conforme o navegador, as permissões e a configuração do ambiente.

Este repositório apresenta um projeto de desenvolvimento voltado à melhoria de processos administrativos.

