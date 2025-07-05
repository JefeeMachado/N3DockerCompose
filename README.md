# N3DockerCompose
Trabalho Invidual, aluno Jeferson Eduardo Moreira Machado. Sobre a N3 da disciplina Redes de Computadores sobre Docker Compose


Implementa os 4 serviços interconectados abaixo utilizando o Docker Compose.

Serviços:
wordpress: A aplicação web, acessível apenas via Nginx no caminho /prova
nginx: Atuará como um servidor proxy reverso, direcionando o tráfego para o WordPress. Ele será configurado para servir o WordPress a partir do caminho /prova.
phpmyadmin: Uma interface web para gerenciar o banco de dados MySQL.
mysql 5.7: O banco de dados para o WordPress e o phpMyAdmin.

Aplique 'docker compose up -d' para iniciar.
