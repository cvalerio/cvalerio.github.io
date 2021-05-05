---
title: Usare docker come ambiente di sviluppo (Parte 1)
layout: post
---

## Introduzione

Docker è uno strumento fantastico per gli sviluppatori, ma molti lo usano ad una
frazione delle sue potenzialità.

Normalmente, infatti, si fa uso di Docker per far girare un qualche server database,
come MySql, o qualche servizio la cui installazione può essere noiosa o complessa,
come Redis o ElasticSearch.

Ma le possibilità che Docker permette agli sviluppatori sono molte altre, soprattutto
se si lavora in team e si sta progettando un'applicazione basata su microservizi.

Immaginate, infatti, di essere un piccolo (o grande, perché no?) team di sviluppatori,
ognuno assegnatario di un aspetto dell'applicazione.

Ci sarà ad esempio un web designer, che si occuperà della progettazione dell'aspetto
grafico e della UX/UI, uno sviluppatore di frontend, che realizzerà l'interfaccia utente,
e magari uno o due sviluppatori API che si occuperanno di sviluppare il backend.

