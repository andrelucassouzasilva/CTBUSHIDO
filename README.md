# C.T. Bushido — protótipo de site

Protótipo de proposta para o site do C.T. Bushido (Boxe, Jiu-Jitsu e Karatê-do), com foco no agendamento de aulas:

- Agendamento em 3 passos: modalidade e tipo de aula, dia e horário, confirmação
- Atalhos de um toque: primeira aula grátis e "repetir último treino"
- Vagas por turma, aviso de últimas vagas e lista de espera
- "Meus treinos" com remarcação e cancelamento
- Grade semanal clicável e barra fixa de agendamento no celular

É uma página estática (um único `index.html`, sem build). Horários, preços e vagas são ilustrativos, e os agendamentos ficam salvos só no navegador de quem testa.

## Publicar no Vercel

Importe o repositório no Vercel com o preset **Other** e sem comando de build. O `index.html` da raiz é servido como está.
