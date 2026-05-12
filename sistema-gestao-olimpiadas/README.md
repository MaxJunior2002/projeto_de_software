# Sistema de Gestão das Olimpíadas (SGO)

[cite_start]Este repositório contém a modelagem técnica do **Sistema de Gestão das Olimpíadas (SGO)**, desenvolvido para a disciplina de **Projeto de Software** do curso de **Engenharia de Software** na **PUC Minas**[cite: 1, 4, 5].

## 📝 Descrição do Sistema
[cite_start]O SGO foi concebido para coordenar os aspectos logísticos e esportivos das Olimpíadas, incluindo o gerenciamento de competições, inscrições de atletas, alocação de locais e controle de resultados[cite: 6, 7].

## 👥 Histórias de Usuário (User Stories)
[cite_start]Conforme as regras de negócio estabelecidas[cite: 8, 39]:

* [cite_start]**US01 - Cadastro de Competições:** Como administrador, desejo cadastrar modalidades, datas, horários e locais para organizar o cronograma olímpico[cite: 9, 10].
* [cite_start]**US02 - Inscrição de Atletas:** Como delegado de país, desejo inscrever atletas em modalidades específicas, garantindo que cada atleta represente apenas uma nação por categoria[cite: 11, 12, 13].
* [cite_start]**US03 - Alocação de Locais:** Como gestor de logística, desejo alocar espaços para as provas evitando conflitos de horário, garantindo que um local receba apenas uma competição por vez[cite: 14, 15, 16].
* [cite_start]**US04 - Registro de Resultados:** Como juiz, desejo registrar os resultados das competições para determinar os vencedores das medalhas de ouro, prata e bronze[cite: 17, 18].
* [cite_start]**US05 - Relatório de Medalhas:** Como usuário do sistema, desejo visualizar o quadro de medalhas para acompanhar o desempenho dos países participantes[cite: 19, 20].

## 📊 Diagramas UML
[cite_start]Os diagramas abaixo foram desenvolvidos utilizando a ferramenta **PlantUML**[cite: 58].

### Diagrama de Caso de Uso
[cite_start]Modela os atores e as interações principais, como cadastros e registros[cite: 25, 26].
<img width="500px" height="500px" src="https://github.com/MaxJunior2002/projeto_de_software/blob/main/sistema-gestao-olimpiadas/imagens/diagrama-de-caso-de-uso.png"/>

### Diagrama de Classes
[cite_start]Reflete a estrutura de dados do sistema (Competição, Atleta, Local, Resultado e País)[cite: 27].
<img width="500px" height="500px" src="https://github.com/MaxJunior2002/projeto_de_software/blob/main/sistema-gestao-olimpiadas/imagens/diagrama-de-classes.png"/>

### Diagrama de Pacotes
[cite_start]Organiza as responsabilidades do sistema em pacotes lógicos[cite: 28].
<img width="500px" height="500px" src="https://github.com/MaxJunior2002/projeto_de_software/blob/main/sistema-gestao-olimpiadas/imagens/diagrama-de-pacotes.png"/>

### Diagrama de Componentes
[cite_start]Ilustra a interação entre a interface, módulos de inscrição, alocação e relatórios[cite: 29].
<img width="500px" height="500px" src="https://github.com/MaxJunior2002/projeto_de_software/blob/main/sistema-gestao-olimpiadas/imagens/diagrama-de-componentes.png"/>

### Diagrama de Implantação
[cite_start]Representa a arquitetura física e a distribuição da infraestrutura de TI[cite: 30].
<img width="500px" height="500px" src="https://github.com/MaxJunior2002/projeto_de_software/blob/main/sistema-gestao-olimpiadas/imagens/diagrama-de-implantação.png"/>