# Game Design Document (GDD) do Jogo Lendas do Nordeste

**Instituto Federal do Piauí - Campus Pedro II**

**Número do Grupo:** XX  
**Curso:** Análise e Desenvolvimento de Sistemas  
**Módulo:** III
**Disciplina:** Engenharia de Software II 
**Professor:** Willyams Moreira Saraiva

## Equipe de Desenvolvimento

| Matrícula       | Aluno             | Função                   | 
|-----------------|-------------------|--------------------------|
| 2023123TADS0040 | Ana Luiza         | Product Master           |
| 2023123TADS0005 | Esmeralda         | Product Master(auxiliar) |
| 2023123TADS0015 | Maithe Vitoria    | Sound Designer           |
| 2023123TADS0041 | Pedro Barroso     | Designer; Desenvolvedor 1|
| 2023123TADS0003 | Valdemiro         | Designer; Desenvolvedor 2|
| 2023123TADS0037 | Yara Beatriz      | Arquiteta                |

## Visão Geral do Projeto
  "Lendas do Nordeste" é um jogo de aventura e ação ambientados em um formato inspirado no estilo literário do cordel. Nele, os jogadores poderão assumir o papel de Lampião, o Rei do Cangaço. Em missão de resgatar Maria Bonita, sua amada, das garras das grandes lendas do folclore da cidade de Pedro II - Piauí. O jogo se desenvolve em uma vasta e árida paisagem da Caatinga, repleta de perigos e criaturas landárias. O jogo oferece encontros com criaturas lendárias e astutas  que habitam a região de Pedro II, além das lendas mais conhecidas do folclore brasileiro, como o Boitatá.  Ao longo da jornada, os jogadores encontrarão persongens icônicos, como -(EXEMPLO: SEREIA), que podem causar dano a Lampião em sua missâo. Os jogadores munidos com objetos de ajuda, como trajes de couro, café revigorante, pimenta e pistolas para defender-se e, ainda, contará com ajuda de jumentos ágeis e do famoso cuzcuz nordestino, sustento vital durante a missão de resgate. "Lendas do Nordeste" oferece uma experiência imersiva que mergulha os jogadores em um rica cultura e mitologia do Nordeste brasileiro, incluindo as lendas do povoamento de Pedro II, enquanto personificam o Rei do cangaço, acompanham e divertem-se com sua emocionante jornada para salvar sua amada Maria Bonita. 

## Objetivos do Projeto
- Regastar Maria Bonita e restaurar o sossego derrotando todas as lendas
- Passar de fase
- Derrrotar os inimigos
- Pegar os itens coletaveis

## Principal(is) Metodologia(s) Adotada(s)
- Scrum

## Metodologia Scrum
Explicação breve sobre como a metodologia Scrum está sendo aplicada no desenvolvimento do jogo. Isso pode incluir detalhes sobre sprints, reuniões diárias, revisões de sprint, etc.

## Principais Tecnologias Utilizadas e/ou Pretendidas
- Trello
- Construct 3
- MKDOCS
- NOTION
- Git,GitHub

## Cronograma de Desenvolvimento
|**SPRINT 0**                | **SPRINT 1**                        | **SPRINT 2**             | **SPRINT 3**       | **SPRINT 4**       | **ENTREGA**                      |
|----------------------------|-------------------------------------|--------------------------|--------------------|--------------------|----------------------------------|
|Tema do jogo                |Roteiro                              |Backgrounds(imagens/tiles)|Implementação part.1|Implementação part.2|Descrições/demostração            |
|Objetivos(geral, especifico)|Sprites (imagens/personagens/objetos)|                          |                    |                    |Criterios (documentação/feedbacks)|
|Historia                    |                                     |                          |                    |                    |Lancamento no III Opala Tec       |

## Recursos Necessários
Liste os recursos necessários para o desenvolvimento, incluindo recursos humanos, materiais, financeiros, etc.

## Desafios Antecipados
Identifique desafios que você antecipa ao longo do desenvolvimento e como planeja enfrentá-los.

## O Projeto está rodando?
(x) SIM () NÃO

## Screenshots
![Screenshot 1](URL_da_Imagem_1)
![Screenshot 2](URL_da_Imagem_2)
![Screenshot 3](URL_da_Imagem_3)


## Introdução

Este repositório traz um template de documentação a ser seguido pelos grupos.

## Tecnologia

A geração do site estático é realizada utilizando o [MkDocs](https://www.mkdocs.org/).

> "MkDocs is a fast, simple and downright gorgeous static site generator that's geared towards building project documentation."

### Instalando o MkDocs

Para instalar o MkDocs, você pode executar o comando:

```shell
pip install mkdocs
```

Para mais detalhes, consulte o [Guia de Instalação](#).

# Criando um Novo Projeto

Começar é super fácil. Para criar um novo projeto, execute o seguinte comando a partir da linha de comando:

```shell
mkdocs new meu-projeto
cd meu-projeto
```

Dê um momento para revisar o projeto inicial que foi criado para você.

## Estrutura Inicial do MkDocs

Existe um único arquivo de configuração chamado `mkdocs.yml` e uma pasta chamada `docs`, que conterá os arquivos de origem da sua documentação (o valor padrão para a configuração `docs_dir` é `docs`). No momento, a pasta `docs` contém apenas uma página de documentação, chamada `index.md`.

O MkDocs vem com um servidor de desenvolvimento integrado que permite visualizar sua documentação enquanto você trabalha nela. Certifique-se de estar no mesmo diretório do arquivo de configuração `mkdocs.yml` e, em seguida, inicie o servidor executando o comando `mkdocs serve`:

```shell
$ mkdocs serve
```

```shell
INFO    -  Construindo documentação...
INFO    -  Limpando o diretório do site
INFO    -  Documentação construída em 0.22 segundos
INFO    -  [15:50:43] Observando alterações nos caminhos: 'docs', 'mkdocs.yml'
INFO    -  [15:50:43] Servindo em http://127.0.0.1:8000/
```

Abra [http://127.0.0.1:8000/](http://127.0.0.1:8000/) no seu navegador, e você verá a página inicial padrão sendo exibida:

![O servidor MkDocs ao vivo](http://127.0.0.1:8000/)

O servidor de desenvolvimento também suporta recarregamento automático e reconstruirá sua documentação sempre que algo no arquivo de configuração, diretório de documentação ou diretório do tema for alterado.

Abra o documento `docs/index.md` no seu editor de texto preferido, altere o título inicial para "MkLorum" e salve suas alterações. Seu navegador recarregará automaticamente e você verá sua documentação atualizada imediatamente.

Agora tente editar o arquivo de configuração: `mkdocs.yml`. Altere a configuração `site_name` para "MkLorum" e salve o arquivo.

```yaml
site_name: MkLorum
site_url: https://example.com/
```
