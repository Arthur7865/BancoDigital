# 📘 Descrição do Projeto

Este projeto implementa um modelo de Bootcamp em Java utilizando os fundamentos avançados da Programação Orientada a Objetos (POO). O objetivo é criar uma simulação realista de um Bootcamp, integrando cursos e mentorias, onde desenvolvedores (Devs) podem se inscrever, progredir em suas atividades e acumular experiência (XP). ✨

## 🎯 Classes Principais

1. **Conteudo (Classe Abstrata)**
   - Representa o conteúdo genérico de um Bootcamp.
   - **Atributos**: `titulo`, `descricao`.
   - **Método Abstrato**: `calcularXp`.

2. **Curso (Subclasse de Conteudo)**
   - Representa um curso oferecido no Bootcamp.
   - **Atributos**: `cargaHoraria`.
   - **Método**: Implementação de `calcularXp`.

3. **Mentoria (Subclasse de Conteudo)**
   - Representa uma sessão de mentoria dentro do Bootcamp.
   - **Atributos**: `data`.
   - **Método**: Implementação de `calcularXp`.

4. **Bootcamp**
   - Representa a entidade central do Bootcamp.
   - **Atributos**: `nome`, `descricao`, `dataInicial`, `dataFinal`, `conteudos`, `devsInscritos`.

5. **Dev (Desenvolvedor)**
   - Representa um desenvolvedor participante do Bootcamp.
   - **Atributos**: `nome`, `conteudosInscritos`, `conteudosConcluidos`.
   - **Métodos**: `inscreverBootcamp`, `progredir`, `calcularTotalXp`.

## 🛠️ Classe Principal (Main)

O método `main` é responsável pela execução do programa, seguindo os seguintes passos:

1. **Criação de Cursos**
   - Dois cursos (`curso1` e `curso2`) são instanciados com seus respectivos atributos definidos.

2. **Criação de Mentoria**
   - Uma mentoria (`mentoria`) é instanciada com seus atributos definidos.

3. **Configuração do Bootcamp**
   - Um Bootcamp (`bootcamp`) é instanciado e configurado com cursos e mentorias.
   - Os conteúdos são adicionados à lista de conteúdos do Bootcamp.

4. **Inscrição e Progresso dos Devs**
   - Dois desenvolvedores (`devCamila` e `devJoao`) são instanciados e inscritos no Bootcamp.
   - Os desenvolvedores progridem nos conteúdos (cursos e mentorias) e acumulam XP.

5. **Exibição de Resultados**
   - Conteúdos inscritos e concluídos, bem como o total de XP ganho, são exibidos no console.

## 📈 Resumo do Processo

- **📚 Criação de Conteúdos**: Definição de cursos e mentorias.
- **🏫 Configuração do Bootcamp**: Instanciação do Bootcamp e adição de conteúdos.
- **👩‍💻👨‍💻 Inscrição de Devs**: Inscrição de desenvolvedores e acompanhamento do progresso.
- **💪 Cálculo de XP**: Cálculo do XP total com base nos conteúdos concluídos.
- **📊 Exibição de Resultados**: Exibição das inscrições, progresso e XP no console.
