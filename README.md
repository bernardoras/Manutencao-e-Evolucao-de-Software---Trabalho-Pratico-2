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
Programas extraídos do repositório https://github.com/kyclark/tiny_python_projects/tree/master

#### Etapas:

Para cada sistema (a partir de um arquivo de implementação e um de testes), realizam-se as queries:

<ol>
<li>Pede-se uma explicação do funcionamento do sistema;</li>
<li>Com base no contexto dado, pede-se para adicionar uma feature específica juntamente a casos de testes (pode-se ainda pedir à LLM para realizar outro tipo de manutenção breve antes para tornar a manutenção evolutiva mais viável, como utilizar algum padrão de projeto, adicionar ocultamento de informação, reduzir acoplamento, melhorar extensibilidade, etc);</li>
</ol>

#### Avaliação quantitativa dos resultados

<ul>
<li>Distribuição do número bugs encontrados após as modificações nos projetos;</li>
<li>Distribuição da diferença entre a porcentagem do número de testes passados depois e antes das modificações nos projetos;</li>
<li>Distribuição da diferença entre a cobertura de linhas pelos testes depois e antes das modificações nos projetos;</li>
</ul>

#### Avaliação qualitativa dos resultados

<ul>
<li>Validação dos membros do grupo se, para cada projeto analisado, a nova feature realmente apresenta o comportamento esperado;</li>
<li>Validação dos membros do grupo se outros fatores mais baixo nível além da feature, se houverem, como padrões de projeto, foram corretamente implementados;</li>
<li>Se houverem, agrupamento de melhorias não-solicitadas observadas (E.g. adição de comentários, melhorias de nomes, etc);</li>
</ul>



