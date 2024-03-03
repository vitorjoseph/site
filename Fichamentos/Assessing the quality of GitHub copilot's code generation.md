# Assessing the quality of GitHub copilot’s code generatio


Yetistiren, Burak, Isik Ozsoy, and Eray Tuzun. "Assessing the quality of GitHub copilot’s code generation." Proceedings of the 18th International Conference on Predictive Models and Data Analytics in Software Engineering. 2022. Leia o artigo completo [aqui](https://dl.acm.org/doi/pdf/10.1145/3558489.3559072)

## 1. Fichamento de Conteúdo


O artigo aborda a introdução do GitHub Copilot, uma ferramenta de geração de código que utiliza inteligência artificial (IA) para auxiliar programadores, tendo como objetivo principal do estudo avaliar a qualidade do código gerado pelo GitHub Copilot, bem como o impacto da qualidade e variedade dos parâmetros de entrada fornecidos à ferramenta. A metodologia utilizada envolve a criação de um ambiente experimental para avaliar o código gerado em termos de validade, correção e eficiência, onde foram definidas várias perguntas de pesquisa para orientar a avaliação, incluindo a qualidade das sugestões de código, o efeito do uso de docstrings e nomes de funções apropriados, entre outros aspectos. Os resultados obtidos mostram que o GitHub Copilot foi capaz de gerar código válido com uma taxa de sucesso de 91,5%. Em relação à correção do código, 28,7% das soluções foram corretas, 51,2% parcialmente corretas e 20,1% incorretas, além disso, foi observado que o GitHub Copilot conseguiu corresponder principalmente à eficiência das soluções escritas por humanos. No que diz respeito às ameaças à validade do estudo, foram discutidos vários fatores, incluindo a versão do modelo OpenAI Codex utilizado, soluções triviais geradas, a maneira como o código foi gerado e a cobertura dos problemas avaliados. O estudo também analisa trabalhos relacionados, destacando a importância da avaliação da qualidade do código gerado pelo GitHub Copilot e outras ferramentas de geração de código. Em conclusão, os resultados indicam que o GitHub Copilot é uma ferramenta promissora, mas são necessárias avaliações mais abrangentes no futuro. O artigo sugere futuras melhorias na metodologia experimental, incluindo o aumento do número e diversidade dos problemas avaliados, bem como a avaliação da qualidade do código utilizando métricas de manutenibilidade e confiabilidade.

## 2. Fichamento Bibliográfico 

* _GitHub Copilot_ é uma ferramenta de geração de código que utiliza uma variedade de tecnologias, incluindo uma IDE compatível e o modelo OpenAI Codex (página 1).
* _Codex Model_ é uma parte fundamental do GitHub Copilot, desenvolvido pela OpenAI, que gera o código com base nos exemplos fornecidos pelos usuários (página 1).
* _Experimental Setup_ refere-se ao método utilizado para avaliar o desempenho do GitHub Copilot na geração de código, incluindo a seleção dos problemas, a execução dos testes e a análise dos resultados (página 2).
* _Code Validity_ (validade do código) é a capacidade de o código gerado ser válido e executável (página 3).
* _Code Correctness_ (correção do código) refere-se à precisão e exatidão do código gerado em relação à solução esperada (página 4).
* _Dummy Function Names_ (nomes de funções fictícias) são identificadores temporários ou genéricos usados ​​para avaliar o impacto do nome da função na geração de código (página 10).


## 3. Fichamento de Citações 


* _"GitHub Copilot can be installed and used as an extension to Visual Studio Code, Neovim, IDEs developed by JetBrains [6], and GitHub Codespaces."_
* _"To systematically evaluate GitHub Copilot, we propose to construct an experimental setup to assess the generated code in terms of validity, correctness, and efficiency."_
* _"We observed that for 28.7% of the problems, GitHub Copilot managed to generate the correct code for the given problem, whereas it completely failed to provide a correct solution for 20.1% of the problems."_
* _"Using dummy function names instead of meaningful ones reduces the performance of GitHub Copilot."_
* _"GitHub Copilot is capable of generating valid code 9 out of 10 times."_
* _"Our results show that without the supervision of a programmer, GitHub Copilot has a lower chance of generating correct code; but with further input provided by the programmer, the correctness of the generated code can be increased."_
* _"In terms of correctness, Java had the highest (57%) and JavaScript was the lowest (27%) score."_






