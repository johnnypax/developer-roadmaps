# Java Developer Roadmap

**Junior → Job-Ready → Mid**

> Roadmap pratica per diventare sviluppatore Java: cosa studiare, in che ordine, e quali progetti fare.
> Ogni sezione ha un obiettivo e una checklist. Quando hai spuntato l’essenziale sei già “job-ready”.

---

## 0) Setup & strumenti (Fondamenta operative)
**Obiettivo:** essere produttivo in un ambiente reale.

- [ ] IDE (IntelliJ / Eclipse), shortcut, debug step-by-step
  - **📺 Playlist: IN ARRIVO**
- [ ] Git (branch, merge, pull request, conflict)
  - **📺 Playlist: [Dominare GIT](https://www.youtube.com/playlist?list=PLoZNHBEyxFQFc2fn3raEjovUK_BLWS0kO)**
- [ ] Maven o Gradle (dipendenze, build, test)
  - **📺 Playlist: IN ARRIVO**
- [ ] Logging (SLF4J + Logback), livelli log
  - **📺 Playlist: IN ARRIVO**
- [ ] Docker basics (run, compose, env, network) *(consigliato)* 
  - 📺 **Playlist: [Docker Rapido](https://www.youtube.com/playlist?list=PLoZNHBEyxFQEw0Zzxe-EGFppZrbqGXJdB)** 
  - **📺 Playlist: [Docker Desktop](https://www.youtube.com/playlist?list=PLoZNHBEyxFQFM-bBq4G0c8eZEQsUk95WB)**

---

## 1) Core Java (Obbligatorio)
**Obiettivo:** scrivere codice pulito e prevedibile.

- [ ] Tipi, OOP, incapsulamento, ereditarietà, polimorfismo
- [ ] Collections (List/Map/Set), equals/hashCode
- [ ] Exception handling (checked/unchecked, best practice)
- [ ] Generics (uso pratico)
- [ ] I/O, JSON basics
- [ ] Date/Time (java.time)
- [ ] Stream API *quanto basta* (map/filter/collect)

**Job-ready minima**: sai implementare logica, modellare dati, strutturare classi e pacchetti.

📺 Playlist: **IN ARRIVO**

---

## 2) SQL & Database (Obbligatorio)
**Obiettivo:** lavorare con dati in modo solido.

- [ ] SQL CRUD (SELECT/INSERT/UPDATE/DELETE)
- [ ] JOIN (INNER/LEFT), GROUP BY, HAVING
- [ ] Indici: cosa sono e quando servono
- [ ] Vincoli (PK/FK/UNIQUE/NOT NULL)
- [ ] Normalizzazione: concetti base
- [ ] Transazioni (ACID, commit/rollback)

📺 Playlist: 

- **[Da ER a MySQL](https://www.youtube.com/playlist?list=PLoZNHBEyxFQGY4UO3Cetegq6XHlEm4IUo) **
- **[Integra Java e MySQL](https://www.youtube.com/playlist?list=PLoZNHBEyxFQFpzIKFyt_Wu85NSs0ZHA-B)**

---

## 3) Web Fundamentals (Obbligatorio)
**Obiettivo:** capire come ragiona un backend.

- [ ] HTTP (metodi, status code, headers)
- [ ] REST: risorse, idempotenza, paginazione
- [ ] JSON (request/response)
- [ ] CORS (cos’è e perché “rompe tutto”)
- [ ] Cookie vs Token (concetto)

📺 Playlist: **[Video introduttivo](https://youtu.be/JNom9MPSErY)**

---

## 4) Java Web: Servlet / JSP / MVC (Molto utile per basi “vere”)
**Obiettivo:** capire cosa succede sotto Spring.

- [ ] Servlet lifecycle (init/service/destroy)
- [ ] Request/Response, parametri, redirect vs forward
- [ ] Sessione, cookie
- [ ] JSP: perché evitare scriptlet (JSTL + EL)
- [ ] Pattern MVC (Controller/Service/DAO)

📺 Playlist: **[Java Servlet e Apache Tomcat](https://www.youtube.com/playlist?list=PLoZNHBEyxFQF_RJByMd7A48VaGwdlCmp_)**

---

## 5) Spring Core (Obbligatorio nel mercato)
**Obiettivo:** costruire app manutenibili.

- [ ] IoC / DI (component scan, @Bean, @Autowired)
- [ ] Configurazione (application.yml / properties, profiles)
- [ ] Layering: Controller / Service / Repository
- [ ] Validazione input (Jakarta Validation)
- [ ] Error handling (ControllerAdvice)
- [ ] DTO vs Entity (perché separare)

📺 Playlist: **[Corso base Spring Boot](https://www.youtube.com/playlist?list=PLoZNHBEyxFQHFkgxYwri50YEmbiRADl-O)**

---

## 6) Spring Boot + REST API (Obbligatorio)
**Obiettivo:** produrre API “da lavoro”.

- [ ] CRUD REST completo (con DTO)
- [ ] Pagination & sorting
- [ ] OpenAPI/Swagger (documentazione)
- [ ] Logging + correlation id (base)

📺 Playlist: **[Corso base Spring Boot](https://www.youtube.com/playlist?list=PLoZNHBEyxFQHFkgxYwri50YEmbiRADl-O)**

---

## 7) Persistenza in Spring (Obbligatorio)
**Obiettivo:** saper parlare con un DB in modo professionale.

- [ ] JDBC vs JPA/Hibernate (pro/contro)
- [ ] Spring Data JPA (Repository, query method)
- [ ] Entity mapping (OneToMany/ManyToOne) senza disastri
- [ ] Migrazioni DB (Flyway o Liquibase) **- Playlist: IN ARRIVO**
- [ ] Transazioni (@Transactional)

📺 Playlist: **[Corso base Spring Boot](https://www.youtube.com/playlist?list=PLoZNHBEyxFQHFkgxYwri50YEmbiRADl-O)**

---

## 8) Security (Fondamentale per “produzione”)
**Obiettivo:** non esporre API “aperte” per errore.

- [ ] Spring Security basics - **Playlist: [Spring Boot Security Lab](https://www.youtube.com/playlist?list=PLoZNHBEyxFQEf1BdxjHnY5efaMQaTHBBl)**
- [ ] AuthN vs AuthZ
- [ ] JWT (login, refresh concettuale)
- [ ] Ruoli/permessi su endpoint

---

## 9) Testing (Molto richiesto)
**Obiettivo:** essere assumibile e scalabile in team.

- [ ] JUnit + Assert
- [ ] Mockito (mock/stub, verify)
- [ ] Test slice (WebMvcTest, DataJpaTest)
- [ ] Integration test (Testcontainers consigliato)

📺 Playlist: **IN ARRIVO**

---

## 10) Frontend templating: Thymeleaf (Se fai web “server-side”)
**Obiettivo:** creare UI semplice senza SPA.

- [ ] Template, fragments, layout
- [ ] Form binding + validation errors
- [ ] Rendering liste/dettaglio

📺 Playlist: **[Thymeleaf con Spring Boot](https://www.youtube.com/playlist?list=PLoZNHBEyxFQHql3K9V3uurW2bs6lOBx-S)**

> Nota: se punti a backend puro, Thymeleaf è “nice to have”, non obbligatorio.

---

## 11) Deployment & DevOps basics (Differenziante)
**Obiettivo:** far girare davvero il progetto.

- [ ] Dockerfile + Docker Compose (app + db) - **PLAYLIST: Docker compose IN ARRIVO**
- [ ] Env vars e config per ambienti
- [ ] CI semplice (build + test)
- [ ] Observability base (log strutturati)

📺 Playlist: **[Spring Boot su Docker](https://www.youtube.com/playlist?list=PLoZNHBEyxFQGdNvr_5mMikHxuv2YHPjDz)** - **CI/CD Su GitLab: IN ARRIVO**

---

# Progetti consigliati (Portfolio)
Fai 2–3 progetti completi, piccoli ma “veri”.

## Project A — CRUD API “pulita”
- Users/Products/Orders
- DTO, validation, pagination, Swagger, error handling

## Project B — App con login (JWT)
- Ruoli: USER/ADMIN
- Endpoint protetti + refresh token concettuale

## Project C — App deployabile
- Docker Compose con DB + migrazioni
- README con istruzioni di avvio

---

# Cosa è “abbastanza” per lavorare?
Se sai fare queste cose, sei già in traiettoria “junior job-ready”:

- API CRUD con Spring Boot
- DB con JPA + migrazioni
- Validazione, error handling, logging
- Git + build + test base
- Deploy con Docker Compose (anche minimale)

---

# Skill Matrix

| Livello   | Cosa sai fare                         |
| --------- | ------------------------------------- |
| Junior    | CRUD REST + DB                        |
| Job-Ready | Security + Testing + Deploy           |
| Mid       | Performance + CI/CD + Design avanzato |

# Extra (quando hai già una base)

- Kafka / RabbitMQ
- Microservizi (vero motivo + trade-off)
- Caching (Redis)
- Performance tuning e indici avanzati
- Cloud (AWS/GCP/Azure)
- Clean Architecture / DDD (se serve davvero)

---

## Come usare questa roadmap
1) Parti dall’alto, spunta le checklist.
2) Fai almeno 2 progetti completi.
3) Se ti manca un argomento: vai ai link playlist o recuperalo altrove.