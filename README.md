Descrição:

Este repositório contém um componente do código de simulação de um sistema cap-and-trade para o cenário brasileiro. O modelo foi desenvolvido como parte de uma dissertação de mestrado em economia, na subárea de Microeconomia Aplicada e Economia Ambiental. De forma geral, um sistema de cap-and-trade pode ser definido como o design de um mercado artificial e unidirecional, que reflete as decisões do regulador ao estabelecer um critério regulatório de forma exógena ao modelo.

O Modelo:

O modelo adotado é um modelo de equilíbrio intertemporal com múltiplos agentes, abrangendo 11 períodos e incorporando:

• Mecanismo de poupança de permissões;

• Condição de exaustão (preço e poupança iguais a zero no último período).

O objetivo da simulação é analisar a dinâmica do sistema sob diferentes configurações, buscando minimizar o custo de conformidade do sistema regulado.

Implementação:

A implementação foi realizada utilizando o pacote Pyomo, uma biblioteca de programação em Python. O Pyomo é uma ferramenta flexível que permite a formulação de modelos de otimização de diferentes tipos, incluindo programação não linear (PNL) e problemas de equilíbrio com restrições matemáticas.

Principais ferramentas utilizadas:

• Pyomo.dae → Extensão do Pyomo usada para a modelagem de equações diferenciais algébricas (DAEs);

• IPOPT → Solver open source baseado em métodos de pontos interiores, utilizado para resolver problemas de otimização não linear.

Dados:

O modelo considera 14 subsetores econômicos, distribuídos entre os setores de Energia, Processos Industriais e Uso de Produtos e Resíduos As emissões subsetoriais modeladas representam aproximadamente 26% das emissões líquidas de GEE no Brasil em 2022. Para definir o cap (limite superior de emissões), adotou-se como referência a Contribuição Nacionalmente Determinada (NDC) do Brasil.
