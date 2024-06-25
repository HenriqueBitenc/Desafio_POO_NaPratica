# Bootcamp Java Project

### Descrição

Este projeto é uma simulação de um sistema de gerenciamento de bootcamps, onde desenvolvedores (Devs) podem se inscrever em cursos e mentorias. O sistema calcula a experiência (XP) adquirida pelos desenvolvedores com base nos conteúdos concluídos.

## Estrutura do Projeto

O projeto é composto pelas seguintes classes:

### 1. BootCamp:
Representa um bootcamp, que contém informações como nome, descrição, data de início, data de término, desenvolvedores inscritos e conteúdos oferecidos.

### 2. Conteudo:
Classe abstrata que representa um conteúdo do bootcamp, como um curso ou uma mentoria. Contém métodos para calcular a experiência (XP) que um desenvolvedor ganha ao concluir o conteúdo.

### 3. Curso:
Extende a classe Conteudo e adiciona uma carga horária específica. A experiência (XP) é calculada multiplicando o XP padrão pela carga horária.

### 4. Mentoria:
Extende a classe Conteudo e adiciona uma data específica. A experiência (XP) é calculada somando um valor fixo ao XP padrão.

### 5. Dev:
Representa um desenvolvedor inscrito no bootcamp. Contém métodos para inscrever-se em bootcamps, progredir nos conteúdos e calcular o total de XP adquirido.



