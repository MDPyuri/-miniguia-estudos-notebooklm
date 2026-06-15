# -miniguia-estudos-notebooklm
## Estudo inicial de Python
Repositório criado para documentar o aprendizado e os testes a respeito das aulas de IA promovidas pela DIO utilizando um NotebookLM treinado para auxiliar um programador iniciante em Python.

### - Contexto e Objetivo: "Estudo inicial de Python"
Aproveitando o embalo do curso que utilizará Python como linguagem principal, decidi já criar em paralelo um NotebookLM treinado para me auxiliar nos estudos iniciais de Python, tendo como base de dados documentações, projetos, vídeo aulas, entre outras fontes relacionadas.

### - Curadoria de Fontes:
Dentre as fontes escolhidas como base de dados, destacam-se:
1. [Documentação da versão 3.14.6 da linguagem.](https://docs.python.org/3/)
2. [Playlist focada em Python do canal 'Curso em Vídeo' no YouTube.](https://www.youtube.com/playlist?list=PLvE-ZAFRgX8hnECDn1v9HNTI71veL3oW0)
3. [Página sobre a história de Python na WikiPedia.](https://en.wikipedia.org/wiki/History_of_Python)
4. [Página com as perguntas mais recentes sobre Python no Stack Overflow.](https://stackoverflow.com/questions/tagged/python?tab=Newest)
5. [Tutorial de Python da plataforma W3 Scgools.](https://www.w3schools.com/python/)

### - Engenharia de Prompts e "Cicatrizes":
1. O primeiro passo foi contextualizar o chatBot e solicitar uma breve introdução ao tema.
   > Estou iniciando minha jornada em Python, para isso você será meu auxiliador nos estudos e testes sobre esta linguagem.
     Deve considerar que já tenho noção em lógica de programação e experiência prévia com JS.
     Para começarmos eu quero saber porque pode ser vantajoso aprender Python e adicioná-la ao meu repertório de linguagens.
   <details>

       Seja bem-vindo à sua jornada com Python! Como você já possui experiência com JavaScript e lógica de programação, verá que Python é uma adição estratégica e poderosa ao seu repertório.

        Aprender Python oferece diversas vantagens competitivas, conforme detalhado nas fontes:

        *   **Sintaxe Simples e Legibilidade:** Python é amplamente reconhecido por sua **sintaxe limpa e próxima ao inglês**, o que reduz a curva de aprendizado e torna o código mais fácil de manter. Ao contrário de muitas linguagens, ela utiliza a indentação de forma obrigatória para definir blocos de código, resultando em um visual "descomplicado" e intuitivo.
        *   **A "Faca Suíça" da Programação:** Python é extremamente versátil, sendo utilizada desde o **desenvolvimento web e automação até inteligência artificial (IA) e análise de dados**. É considerada a linguagem de escolha para startups que precisam de prototipagem rápida e empresas que lidam com grandes pipelines de dados.
        *   **Domínio em IA e Ciência de Dados:** Atualmente, Python é a **língua franca da Ciência de Dados e do Aprendizado de Máquina (Machine Learning)**. Se o seu objetivo é entrar em áreas de inovação tecnológica, como sistemas inteligentes e modelos preditivos, Python possui os frameworks mais robustos, como TensorFlow, PyTorch e scikit-learn.
        *   **Ecossistema Rico e "Baterias Incluídas":** A linguagem possui uma **biblioteca padrão extensa** que oferece suporte imediato para diversas tarefas, como manipulação de arquivos, redes e protocolos de internet. Além disso, conta com mais de 600.000 pacotes de terceiros no PyPI, cobrindo praticamente qualquer necessidade de desenvolvimento.
        *   **Alta Produtividade:** Comparada a linguagens como C++, a Python prioriza a **produtividade do desenvolvedor**. Um algoritmo simples pode levar muito menos linhas de código em Python, permitindo ciclos de desenvolvimento mais rápidos.
        *   **Linguagem de Integração (Glue Language):** Python é frequentemente chamada de "linguagem cola" por sua capacidade de **integrar facilmente componentes escritos em outras linguagens** (como C, C++ ou Rust), permitindo que você use Python para a lógica de alto nível enquanto aproveita a velocidade de execução de módulos otimizados.
        *   **Modernização e Desempenho:** Versões recentes (3.13 e 3.14) introduziram melhorias críticas, como um **compilador JIT (Just-In-Time) experimental** e o suporte para **execução sem o Global Interpreter Lock (GIL)**, o que permite o uso real de múltiplos núcleos de CPU para tarefas paralelas.
        *   **Oportunidades de Carreira:** Python está consistentemente entre as linguagens mais populares e demandadas no mercado. O conhecimento em suas bibliotecas é frequentemente sinônimo de **empregabilidade**, especialmente para funções bem remuneradas em IA, APIs de backend e engenharia de dados.

        Como você já conhece JavaScript, notará que, enquanto o JS domina o ecossistema do navegador e o desenvolvimento full-stack voltado para a web, o **Python expandirá suas fronteiras para o mundo dos dados, automação de servidores e inteligência artificial**.
   </details>
2. Em seguida foi solicitado um planejamento inicial já com os temas a serem estudados.
   > Elabore um planejamento de estudos considerando 1h diária em cada dia útil da semana. 
     Este planejamento deve envolver pesquisas teóricas e exercícios práticos. Tudo separado por temas.
     Se necessário deixe sugestões.
   <details>
      Como você já possui experiência com JavaScript (JS) e lógica de programação, seu foco em Python deve ser a transição de sintaxe e o domínio das ferramentas exclusivas da linguagem, como o gerenciamento de ambientes e as bibliotecas de dados e IA.

        Abaixo, apresento um plano de 4 semanas, com **1 hora diária**, dividida entre **20-25 minutos de teoria/pesquisa** e **35-40 minutos de prática**.

        ---

        ### Semana 1: Transição e Fundamentos "Pythonic"
        *Foco: Adaptar o pensamento do JS para o Python e entender a filosofia da linguagem.*

        *   **Segunda: Filosofia e Ambiente**
          *   **Teoria:** Pesquise sobre o **Zen of Python (PEP 20)** e a história da linguagem. Entenda a importância da indentação obrigatória (regra de impedimento).
          *   **Prática:** Instale o Python 3.14.6. Configure o VS Code ou PyCharm e execute seu primeiro script verificando a versão instalada.
        *   **Terça: Variáveis e Tipagem Forte**
          *   **Teoria:** Python é dinâmico como o JS, mas tem **tipagem forte** (não permite somar string com número sem conversão). Estude os tipos básicos: `int`, `float`, `str`, `bool` e `None`.
          *   **Prática:** Crie variáveis, utilize o operador walrus (`:=`) e experimente **f-strings** para interpolação de strings.
        *   **Quarta: Estruturas de Controle**
          *   **Teoria:** Estude as diferenças de sintaxe no `if/elif/else`, `while` e `for`. Em Python, o `for` funciona mais como um *iterator* (semelhante ao `forEach` do JS).
          *   **Prática:** Converta algoritmos simples que você já fez em JS para Python, focando na ausência de chaves `{}` e uso de `:`.
        *   **Quinta: Listas e Tuplas (Arrays vs Iterables)**
          *   **Teoria:** Estude as **Lists** (mutáveis) e as **Tuples** (imutáveis). Aprenda sobre fatiamento (*slicing*) de arrays.
          *   **Prática:** Exercite a reversão de listas usando `reverse()` e `[::-1]`. Use a função `zip()` para iterar sobre duas listas simultaneamente.
        *   **Sexta: Funções e Escopo**
          *   **Teoria:** Definição com `def`, argumentos posicionais e nomeados (`*args`, `**kwargs`). Estude funções lambda (anônimas).
          *   **Prática:** Crie funções que aceitam múltiplos argumentos e utilize as funções `map()` e `filter()` para manipular listas.

        ---

        ### Semana 2: Estruturas Avançadas e Orientação a Objetos
        *Foco: Organização de código e paradigmas de dados.*

        *   **Segunda: Dicionários e Sets**
          *   **Teoria:** Estude **Dictionaries** (equivalente aos Objetos no JS) e **Sets** (conjuntos de valores únicos).
          *   **Prática:** Realize operações de união de dicionários e utilize *comprehensions* para criar dicionários e listas de forma concisa.
        *   **Terça: POO - Classes e Atributos**
          *   **Teoria:** Entenda o uso do `self` (diferente do `this` do JS). Estude o método especial `__init__`.
         *   **Prática:** Crie uma classe simples, como "Funcionario" ou "ContaBancaria", definindo atributos e métodos básicos.
        *   **Quarta: POO - Herança e Abstração**
          *   **Teoria:** Pesquise sobre herança, herança múltipla e o método `super()`. Entenda o conceito de abstração e polimorfismo em Python.
          *   **Prática:** Implemente uma subclasse que herda de uma classe pai e sobrescreve métodos existentes.
        *   **Quinta: Tratamento de Erros e Duck Typing**
          *   **Teoria:** Entenda o bloco `try/except/finally`. Pesquise o conceito de "Duck Typing" (se anda como pato, é um pato).
          *   **Prática:** Crie um código que trate diferentes exceções (como `ZeroDivisionError` ou `FileNotFoundError`) de forma específica.
        *   **Sexta: Manipulação de Arquivos e Context Managers**
          *   **Teoria:** Aprenda a ler e escrever arquivos usando a instrução `with`, que gerencia o fechamento automático de recursos.
          *   **Prática:** Escreva um script que leia um arquivo TXT, conte as palavras e salve o resultado em um novo arquivo.

        ---

        ### Semana 3: Ferramentas Modernas e Python 3.13/3.14
        *Foco: Ecossistema de desenvolvimento e novos recursos de performance.*

        *   **Segunda: Gerenciamento de Pacotes e uv**
          *   **Teoria:** Estude o `pip` e o novo gerenciador **uv** (escrito em Rust e extremamente rápido). Entenda o uso de ambientes virtuais (`venv`).
          *   **Prática:** Utilize o `uv` para criar um projeto isolado e instale bibliotecas externas.
        *   **Terça: Programação Assíncrona**
          *   **Teoria:** Estude `asyncio`, `async` e `await` (muito semelhante ao JS). Entenda o que é o **GIL** e as melhorias de **free-threading** no Python 3.14.
          *   **Prática:** Crie um script assíncrono simples que simula chamadas de rede simultâneas.
        *   **Quarta: Novos Recursos (3.14/3.15)**
          *   **Teoria:** Pesquise sobre **Lazy Imports** (PEP 810), que adiam o carregamento de módulos para acelerar o início do programa. Conheça as **t-strings** (template strings).
          *   **Prática:** Experimente com as novas melhorias de mensagens de erro e o novo REPL interativo que preserva o histórico multilinhas.
        *   **Quinta: Decoradores e Geradores**
          *   **Teoria:** Entenda como os decoradores modificam o comportamento de funções. Estude os geradores (`yield`) para processamento eficiente de dados.
          *   **Prática:** Implemente um decorador que calcula o tempo de execução de uma função e um gerador que lê uma lista gigante de números um por um.
        *   **Sexta: Testes e Qualidade de Código**
          *   **Teoria:** Estude os frameworks de teste **Pytest** e **Unittest**. Revise as diretrizes de estilo do **PEP 8**.
          *   **Prática:** Escreva testes unitários básicos para as funções que você desenvolveu na primeira semana.

        ---

        ### Semana 4: Bibliotecas, Data Science e IA
        *Foco: Aplicação prática em áreas onde Python domina.*

        *   **Segunda: Computação Numérica com NumPy**
          *   **Teoria:** Entenda por que o NumPy é a base de todo o ecossistema de dados, permitindo operações rápidas em matrizes.
          *   **Prática:** Realize operações matemáticas avançadas e manipulação de arrays multidimensionais.
        *   **Terça: Manipulação de Dados (Pandas vs Polars)**
          *   **Teoria:** Conheça o **Pandas** (padrão de mercado) e o **Polars** (alternativa Rust de alta performance). Entenda a diferença entre avaliação ávida (*eager*) e preguiçosa (*lazy*).
          *   **Prática:** Carregue um arquivo CSV, filtre linhas e realize agrupamentos (*groupby*) usando ambas as bibliotecas para comparar a sintaxe.
        *   **Quarta: APIs de Backend com FastAPI**
          *   **Teoria:** Python é amplamente usado para APIs. Pesquise sobre o **FastAPI**, reconhecido por sua alta performance e documentação automática.
          *   **Prática:** Crie uma API simples com uma rota GET que retorna um JSON, aproveitando seu conhecimento prévio de backend em JS/Node.
        *   **Quinta: IA e Aprendizado de Máquina**
          *   **Teoria:** Conheça as bibliotecas **Scikit-learn, TensorFlow e PyTorch**. Entenda o papel do Python na revolução da IA.
          *   **Prática:** Explore um exemplo básico de regressão linear no Scikit-learn para prever valores simples.
        *   **Sexta: IA Generativa e Agentes**
          *   **Teoria:** Estude o framework **LangChain** para sistemas baseados em LLMs e entenda a diferença entre IA Generativa e **IA Agêntica** (agentes que tomam decisões).
          *   **Prática:** Pesquise como integrar o Python com APIs de modelos de linguagem para automação de tarefas.

        ### Sugestões Finais:
        1.  **Use o REPL:** O novo terminal interativo do Python 3.14 é excelente para testes rápidos sem precisar criar arquivos `.py`.
        2.  **Mantenha o Foco no "Porquê":** Como você já sabe lógica, foque em entender as decisões de design do Python que priorizam a legibilidade sobre a velocidade bruta de execução.
        3.  **Portfólio no GitHub:** Ao final da Semana 4, escolha um projeto que integre o que aprendeu (ex: uma API que processa dados com Polars) e publique-o no GitHub.
   </details>
3. Após a definição de metas e planejamento, o chatBot deve ser usado como instrutor em cada tema abordado, sendo o primeiro "Filosofia e Ambiente".
   > Foi utilizada a ferramenta 'Resumo em vídeo' com o prompt "Crie um resumo sobre o Zen of Python (PEP 20) e a história da linguagem
. Destaque a importância da indentação obrigatória (regra de impedimento)."
   <details>
      O vídeo gerado permitiu ao aluno aprender o principal sobre a origem do Python e boas práticas segundo a filosofia PEP 20, como solicitado, gerando um conteúdo de qualidade e focado nas necessidades do aluno.
   </details>


### - Miniguia de Estudo (Entrega Final):
