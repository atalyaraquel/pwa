# Resumo 

## Info:

**Nome** : Atalya Raquel Freire Tindó

**Livro** : Progressive web app

## Objetivo:
- Resumir 1º cap. do livro.

## Meu resumo:

Foram abordados conceitos e fundamentos das aplicações progressivas ao decorrer desse primeiro capítulo. Como por exemplo: O que seria uma
PWA, o que ela deve atender e o mais importante o porquê implementá-los.	

Obs.: PWA vem da ideia de Progressive Enchacement, que significa melhoria progressiva. Ela diz respeito a criação de experiência cujos 
usuários terão acesso interrupto sem restrição tecnológica. Ou seja, ela desenvolve com melhoria progressiva é um padrão em que a aplicação
está disponível para todos os usuários, sejam eles de smartphones ou microcomputadores. O melhor, tudo isso sem necessariamente conexão com
a internet, tudo isso trazendo novos desafios para os desenvolvedores do back e front end, tendo em vista que as melhorias só vão crescendo.

Alguns conceitos importantes também foram estudados como:

Requisitos de uma aplicação progressiva:
1-Requisitar um Service Woorker: Service Woorker é um padrão da w3c que executa todos os códigos da linguagem javaScript de forma continua. 
Para usa-lo devemos ter em mente que a aplicação deve funcionar off-line  com todos os recursos oferecidos pelo service woorker 


2-Resposta com status 200 mesmo estando desabilitado: Isso significa que haverá sucesso na solicitação de solicitações dos browsers. 
Ela simula o status mesmo estando off-line. Isso pode ocorrer via local (através de dados), IndexedDB (através de dados), Application Cache
(através de arquivos) ou ainda do próprio Service Worker.

3-Conteúdos são exibidos mesmo quando o JavaScript estiver desabilitado: JavaScript deve ter sempre uma resposta para caso ele esteja 
desabilitado ou não suportado, mesmo que seja uma simples mensagem informando a não disponibilidade de uso da aplicação. Coisa simples, mas
quase sempre ignorado pelos desenvolvedores.

4-Usar HTTPS: O HTTPS é obrigatório para uma aplicação progressiva, pois ela não pode ter seus dados transmitidos em claro. Ou seja: não
há transmissão de dados entre o front-end e o back-end. O back-end transmite arquivos estáticos que são armazenados localmente no 
navegador por esse motivo não há acesso remoto.


Vários outros conceitos foram aprendidos ao longo do capitulo e aprendidos, é importante lembrar que a proposta do livro é salientar a construção da parte progressiva usando front-end React. Os requisitos são organizados em épicos e em histórias, como os casos especiais de uma PWA.
