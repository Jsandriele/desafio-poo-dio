📚 Desafio POO em Java – Sistema de Bootcamp

Este projeto é uma implementação de um sistema de gerenciamento de Bootcamp utilizando os princípios da Programação Orientada a Objetos (POO) em Java.

A aplicação simula o funcionamento de um bootcamp de tecnologia, onde desenvolvedores podem se inscrever, acessar conteúdos (cursos e mentorias), progredir nos estudos e acumular experiência (XP).

🚀 Tecnologias Utilizadas

☕ Java

📦 Programação Orientada a Objetos (POO)

🧠 Encapsulamento

🧩 Herança

🔁 Polimorfismo

🗂 Coleções Java (Set / List)

🏗 Estrutura do Projeto

O sistema é composto pelas seguintes classes:

📘 Conteúdo

Classe abstrata que representa os conteúdos disponíveis no bootcamp.

📗 Curso

Representa um curso dentro do bootcamp.

Atributos:

título

descrição

carga horária

🎓 Mentoria

Representa uma mentoria oferecida dentro do bootcamp.

Atributos:

título

descrição

data

🧑‍💻 Dev

Representa um desenvolvedor inscrito no bootcamp.

Funcionalidades:

inscrever em bootcamp

progredir nos conteúdos

visualizar conteúdos inscritos

visualizar conteúdos concluídos

calcular XP total

🏫 Bootcamp

Agrupa os conteúdos disponíveis e os desenvolvedores inscritos.

Atributos:

nome

descrição

conteúdos

desenvolvedores inscritos

⚙️ Funcionamento do Sistema

No arquivo Main, o sistema executa as seguintes etapas:

1️⃣ Criação de cursos e mentorias

Curso curso = new Curso();
curso.setTitulo("Curso java");
curso.setDescricao("descrição curso java");
curso.setCargaHoraria(12);

2️⃣ Criação de um Bootcamp

Bootcamp bootcamp = new Bootcamp();
bootcamp.setName("Bootcamp Java Developer");
bootcamp.setDescricao("Descrição Bootcamp Java Developer");

3️⃣ Adição de conteúdos ao bootcamp

Curso Java

Curso JavaScript

Mentoria Java

4️⃣ Inscrição de desenvolvedores

Dev devCamila = new Dev();
devCamila.setName("Camila");
devCamila.inscreverBootcamp(bootcamp);

5️⃣ Progresso nos estudos

devCamila.progredir();

6️⃣ Cálculo de experiência (XP)

devCamila.calcularTotalXp();
📊 Exemplo de Saída

O sistema mostra:

conteúdos inscritos

conteúdos concluídos

XP acumulado

Exemplo:

Conteudos inscritos Camila: [Curso Java, Curso JS, Mentoria Java]

Conteudos concluídos Camila: [Curso Java, Curso JS]

XP: 200
🎯 Objetivo do Projeto

Este projeto foi desenvolvido para praticar conceitos fundamentais de:

Programação Orientada a Objetos

Modelagem de domínio

Estruturação de classes

Uso de coleções em Java

👩‍💻 Autora

Jaqueline Oliveira

💻 Desenvolvedora Front-End em transição para Back-End Java
📚 Estudante de Análise e Desenvolvimento de Sistemas
