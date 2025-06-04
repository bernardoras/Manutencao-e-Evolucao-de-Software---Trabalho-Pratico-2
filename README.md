# Manutenção e Evolução de Software - DCC/UFMG - Avaliação de LLMs

#### Título: Manutenção Evolutiva com LLMs

#### Prof: Marco Túlio Valente

#### Membros do grupo: Artur Fonseca Costa, Bernardo Roberto Andrade Silva, Luiza Viana Afonso, Turi Andrade Vasconcelos Rezende

## Objetivo do trabalho

Avaliar a capacidade de compreensão e geração de código por uma LLM, especialmente em relação à manutenção evolutiva, utilizando-se de exemplo pequenos sistemas e levando em conta diferentes métricas

## Metodologia

#### Modelo utilizado
ChatGPT-3

#### Dataset
Programas extraídos do repositório abaixo e possivelmente de outros locais https://github.com/kyclark/tiny_python_projects/tree/master

#### Etapas:

Para cada sistema (a partir de um arquivo de implementação e um de testes), realizam-se as queries:

<ol>
<li>Pede-se à LLM uma explicação do funcionamento do sistema;</li>
<li>Com base no contexto dado, pede-se à LLM para adicionar uma feature específica juntamente a seus casos de testes;</li>
</ol>

#### Avaliação quantitativa dos resultados

<ul>
<li>Quantos dos testes da nova suite passam após a implementação;</li>
<li>Cobertura de código antes/depois;</li>
</ul>

#### Avaliação qualitativa dos resultados

<ul>
<li>Validação dos membros do grupo se, para cada projeto analisado, a nova feature realmente apresenta o comportamento esperado;</li>
<li>Se houverem, catálogo de melhorias não-solicitadas observadas (E.g. adição de comentários, melhorias de nomes, etc);</li>
</ul>



