# BancoDigital

Descrição do Projeto
Este projeto implementa um modelo de Bootcamp em Java usando os princípios da Programação Orientada a Objetos (POO). O objetivo é simular um Bootcamp com cursos e mentorias, onde desenvolvedores (Devs) podem se inscrever, progredir nos cursos e calcular seu total de experiência (XP).

Classes Principais
Conteudo (Classe Abstrata)

Representa o conteúdo genérico de um Bootcamp.
Atributos: titulo, descricao.
Método abstrato: calcularXp.
Curso (Subclasse de Conteudo)

Representa um curso dentro do Bootcamp.
Atributos: cargaHoraria.
Método: calcularXp (implementado).
Mentoria (Subclasse de Conteudo)

Representa uma mentoria dentro do Bootcamp.
Atributos: data.
Método: calcularXp (implementado).
Bootcamp

Representa o Bootcamp em si.
Atributos: nome, descricao, dataInicial, dataFinal, conteudos, devsInscritos.
Dev (Desenvolvedor)

Representa um desenvolvedor inscrito no Bootcamp.
Atributos: nome, conteudosInscritos, conteudosConcluidos.
Métodos: inscreverBootcamp, progredir, calcularTotalXp.
Classe Principal (Main)
O método main executa o programa com os seguintes passos:

Criação de Cursos

Dois cursos (curso1 e curso2) são criados e seus atributos são definidos.
Criação de Mentoria

Uma mentoria (mentoria) é criada e seus atributos são definidos.
Criação de Bootcamp

Um Bootcamp (bootcamp) é criado e seus atributos são definidos.
Cursos e mentoria são adicionados à lista de conteúdos do Bootcamp.
Inscrição e Progresso dos Devs

Dois desenvolvedores (devCamila e devJoao) são criados e inscritos no Bootcamp.
Desenvolvedores progridem nos conteúdos (concluem cursos e mentorias).
O total de XP é calculado para cada desenvolvedor.
Impressão dos Resultados

Conteúdos inscritos e concluídos, além do total de XP ganho, são impressos no console.
Resumo do Processo
Criar Conteúdos: Definir cursos e mentorias.
Criar Bootcamp: Criar o Bootcamp e adicionar conteúdos.
Inscrever Devs: Inscrever desenvolvedores e fazê-los progredir.
Calcular XP: Calcular XP total com base nos conteúdos concluídos.
Exibir Resultados: Exibir inscrições, progresso e XP no console.
