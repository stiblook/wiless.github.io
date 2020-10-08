---
layout: article
title: Few learnings from integrating `ObservableHQ`, My blog and API service
---

# Few learnings Integration of API and ObservableHQ 

> This post is still work-in-progress !!

Lately, I have been tinkering around to convert some of <a href="https://github.com/wiless/cellular">cellular</a> library writen in `#golang` as REST API services. I am not from a web-development profession. I had to depend mainly on `google` for finding learning and understanding the issues thrown by browsers. In this blog, I will try to capture some solutions.


<div class="mermaid">
sequenceDiagram
    participant Client
    participant WebServer
    Client<<-WebServer: Load Static Pages
    loop Healthcheck
        Client->>WebServer: Fight against hypochondria
    end
    Note right of APIServer: Rational thoughts <br/>prevail!
    Client-->>APIserver: Authenticate Me!
    APIserver-->>Client: Returns a signed Token
    Client->>ObserverHQ: Import Module
    Bob-->>John: Jolly good!

</div>


