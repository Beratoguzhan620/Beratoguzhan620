<h1>Berat Oğuzhan Turğut</h1>

<p><b>Backend Developer</b> · C# and .NET · PostgreSQL · Samsun, Türkiye · looking for a junior .NET / backend role</p>

<p>
  <a href="https://beratoguzhan620.github.io/portfolio/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-beratoguzhan620.github.io-1F2A37?style=flat-square" /></a>
  <a href="https://www.linkedin.com/in/berat-oguzhan-turgut"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-berat--oguzhan--turgut-1F2A37?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:beratoguzhan620@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-beratoguzhan620%40gmail.com-1F2A37?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://beratoguzhan620.github.io/portfolio/cv-builder/"><img alt="CV builder" src="https://img.shields.io/badge/CV_builder-try_it-1F2A37?style=flat-square" /></a>
</p>

I build backends with ASP.NET Core and PostgreSQL, and the web apps in front of them with React and TypeScript. My recent projects each take one problem real systems get wrong and solve it so it holds under load: selling the same seat twice, money moving twice, a message lost between the database and the queue, two people booking the same day, work done offline on a phone.

**What the 13 recent projects have in common**

- **Correct under concurrency:** the database decides the races (row locks, exclusion constraints, triggers, idempotency keys), and a test proves it, for example 20 people taking the last seat at the same moment and exactly one getting it.
- **Tested against the real thing:** 1,470 automated tests in total, with integration tests running the real API against PostgreSQL, RabbitMQ or Redis in Testcontainers, and end-to-end runs against the whole stack in CI.
- **Measured:** a load test for each product, with the numbers and what they mean in the README.
- **Runs with one command:** `docker compose up` starts the database, the API and the web app.
- **Documented:** a README in English and Turkish with screenshots, a walkthrough GIF, architecture diagrams and the design decisions behind it.

---

### Products

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Beratoguzhan620/gise"><img src="assets/gise.png" alt="Gişe seat map during a sale" /></a>
      <h4><a href="https://github.com/Beratoguzhan620/gise">Gişe</a></h4>
      <p>Event ticketing: a seat map that never sells a seat twice, a fair waiting room for the rush and signed QR tickets checked offline at the gate.<br /><b>1,000 buyers at once: 330 seats held, none twice.</b></p>
      <p><sub>ASP.NET Core · PostgreSQL · ECDSA · React · Docker</sub></p>
      <p><a href="https://github.com/Beratoguzhan620/gise">Code</a> · <a href="https://github.com/Beratoguzhan620/gise/blob/main/docs/screenshots/demo.gif">Walkthrough</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Beratoguzhan620/yoldas"><img src="assets/yoldas.png" alt="Yoldaş search along a route" /></a>
      <h4><a href="https://github.com/Beratoguzhan620/yoldas">Yoldaş</a></h4>
      <p>Ride sharing along the driver's route: search with PostGIS, a fair price by distance, seats counted per part of the route by a database trigger, the car followed live.<br /><b>400 bookings in 2 s, no part of any route over full.</b></p>
      <p><sub>ASP.NET Core · PostGIS · SignalR · React</sub></p>
      <p><a href="https://github.com/Beratoguzhan620/yoldas">Code</a> · <a href="https://github.com/Beratoguzhan620/yoldas/blob/main/docs/screenshots/walkthrough.gif">Walkthrough</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Beratoguzhan620/kuryo"><img src="assets/kuryo.png" alt="Kuryo dispatcher map" /></a>
      <h4><a href="https://github.com/Beratoguzhan620/kuryo">Kuryo</a></h4>
      <p>Courier dispatch: timed offers to the nearest free courier, a live map over SignalR and Redis, a courier PWA and a tracking link for the customer.<br /><b>314 requests a second with no errors; order to first offer p95 35 ms.</b></p>
      <p><sub>ASP.NET Core · PostGIS · SignalR · Redis · React</sub></p>
      <p><a href="https://github.com/Beratoguzhan620/kuryo">Code</a> · <a href="https://github.com/Beratoguzhan620/kuryo/blob/main/docs/screenshots/walkthrough.gif">Walkthrough</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Beratoguzhan620/emanet"><img src="assets/emanet.png" alt="Emanet rental listing" /></a>
      <h4><a href="https://github.com/Beratoguzhan620/emanet">Emanet</a></h4>
      <p>Peer-to-peer rentals: a calendar the database will not let anyone double-book, card holds, a double-entry ledger, handovers with codes and damage claims.<br /><b>300 requests for the same days: none booked twice, ledger balanced.</b></p>
      <p><sub>ASP.NET Core · PostGIS · MinIO · React</sub></p>
      <p><a href="https://github.com/Beratoguzhan620/emanet">Code</a> · <a href="https://github.com/Beratoguzhan620/emanet/blob/main/docs/screenshots/walkthrough.gif">Walkthrough</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/Beratoguzhan620/sahada"><img src="assets/sahada.png" alt="Sahada day board" /></a>
      <h4><a href="https://github.com/Beratoguzhan620/sahada">Sahada</a></h4>
      <p>Field service: a day board that suggests the right technician, an offline-first technician app that syncs an operation log, signed PDF service reports.<br /><b>40 phones syncing at once; 400 resent operations, none applied twice.</b></p>
      <p><sub>ASP.NET Core · PostgreSQL · MinIO · React · Docker</sub></p>
      <p><a href="https://github.com/Beratoguzhan620/sahada">Code</a> · <a href="https://github.com/Beratoguzhan620/sahada/blob/main/docs/screenshots/walkthrough.gif">Walkthrough</a></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Beratoguzhan620/microservices-shop"><img src="assets/microservices-shop.png" alt="Microservices Shop order flow" /></a>
      <h4><a href="https://github.com/Beratoguzhan620/microservices-shop">Microservices Shop</a></h4>
      <p>Six .NET services behind a YARP gateway, with an order saga over RabbitMQ that reserves stock, charges and compensates.<br /><b>60 customers, the last 10 units: exactly 10 sold, the other 50 never charged.</b></p>
      <p><sub>ASP.NET Core · RabbitMQ · MassTransit · YARP · React</sub></p>
      <p><a href="https://github.com/Beratoguzhan620/microservices-shop">Code</a> · <a href="https://github.com/Beratoguzhan620/microservices-shop/blob/main/docs/screenshots/demo.gif">Walkthrough</a></p>
    </td>
  </tr>
</table>

### Backend services

| Project | What it does | Measured |
|---|---|---|
| [Mini Banking API](https://github.com/Beratoguzhan620/mini-banking-api) | A double-entry ledger with idempotent, concurrency-safe transfers | 100 transfers at once from one account: never below zero, never moved twice |
| [Background Jobs](https://github.com/Beratoguzhan620/background-jobs) | Scheduled, recurring and retryable jobs with Hangfire on PostgreSQL | a run handed to two workers at once is done once |
| [Notification Service](https://github.com/Beratoguzhan620/notification-service) | Email and in-app delivery over RabbitMQ with an outbox, retries, dead-letter replay and tracing | 122 tests against PostgreSQL, RabbitMQ and Mailpit in containers |
| [Log Analytics](https://github.com/Beratoguzhan620/log-analytics-api) | Log ingestion, search, alerts and a dashboard on partitioned PostgreSQL | 30,294 events a second accepted; 500,000 stored in 22.5 s |
| [Realtime Chat](https://github.com/Beratoguzhan620/realtime-chat) | SignalR chat with read receipts and presence, two instances on a Redis backplane | 2,000 open WebSockets; 215,802 of 215,802 messages delivered |
| [Multi-Tenant SaaS](https://github.com/Beratoguzhan620/multi-tenant-saas) | A help desk many companies share, isolated by PostgreSQL row-level security | 2,000 tickets under load; every company saw only its own |
| [Knowledge Base](https://github.com/Beratoguzhan620/knowledge-base-api) | Answers from a team's own documents with citations: pgvector hybrid search, Ollama, streamed answers | hit@3 97%; 32 of 32 answers cite the right passage |

---

### Earlier projects

[Marketly](https://github.com/Beratoguzhan620/marketly) (multi-seller marketplace, ASP.NET Core MVC) ·
[Stockly](https://github.com/Beratoguzhan620/stockly) (stock management for a small shop) ·
[EduTrack](https://github.com/Beratoguzhan620/EduTrack) (classroom app) ·
[Inkwell](https://github.com/Beratoguzhan620/inkwell) (multi-author blog) ·
[EventTracker](https://github.com/Beratoguzhan620/event-tracker) (events with a waiting list) ·
[Rollcall](https://github.com/Beratoguzhan620/rollcall) (attendance and grades) ·
[Kawaii Friend](https://beratoguzhan620.github.io/kawaii-friend/) (Expo, Firebase) ·
[CafeMap](https://beratoguzhan620.github.io/cafe-map/) (Expo, maps) ·
[CineList](https://beratoguzhan620.github.io/cinelist/) (Expo, Redux Toolkit) ·
[Bugün Ne Yapalım?](https://beratoguzhan620.github.io/bugun-ne-yapalim/) (Expo) ·
[Student CLI](https://github.com/Beratoguzhan620/student-cli) (console app) ·
[Portfolio](https://github.com/Beratoguzhan620/portfolio) (Astro portfolio and a CV builder)

---

### Tech stack

**Backend**<br />
<img alt="C#" src="https://img.shields.io/badge/C%23-1F2A37?style=flat-square" />
<img alt=".NET" src="https://img.shields.io/badge/.NET-1F2A37?style=flat-square&logo=dotnet&logoColor=white" />
<img alt="ASP.NET Core" src="https://img.shields.io/badge/ASP.NET_Core-1F2A37?style=flat-square" />
<img alt="Entity Framework Core" src="https://img.shields.io/badge/EF_Core-1F2A37?style=flat-square" />
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-1F2A37?style=flat-square&logo=postgresql&logoColor=white" />
<img alt="PostGIS" src="https://img.shields.io/badge/PostGIS-1F2A37?style=flat-square" />
<img alt="pgvector" src="https://img.shields.io/badge/pgvector-1F2A37?style=flat-square" />
<img alt="Row-level security" src="https://img.shields.io/badge/Row--level_security-1F2A37?style=flat-square" />
<img alt="Hangfire" src="https://img.shields.io/badge/Hangfire-1F2A37?style=flat-square" />
<img alt="RabbitMQ" src="https://img.shields.io/badge/RabbitMQ-1F2A37?style=flat-square&logo=rabbitmq&logoColor=white" />
<img alt="MassTransit" src="https://img.shields.io/badge/MassTransit-1F2A37?style=flat-square" />
<img alt="YARP" src="https://img.shields.io/badge/YARP-1F2A37?style=flat-square" />
<img alt="OpenTelemetry" src="https://img.shields.io/badge/OpenTelemetry-1F2A37?style=flat-square&logo=opentelemetry&logoColor=white" />
<img alt="SignalR" src="https://img.shields.io/badge/SignalR-1F2A37?style=flat-square" />
<img alt="Redis" src="https://img.shields.io/badge/Redis-1F2A37?style=flat-square&logo=redis&logoColor=white" />
<img alt="MinIO" src="https://img.shields.io/badge/MinIO-1F2A37?style=flat-square&logo=minio&logoColor=white" />
<img alt="Serilog" src="https://img.shields.io/badge/Serilog-1F2A37?style=flat-square" />
<img alt="SQL Server" src="https://img.shields.io/badge/SQL_Server-1F2A37?style=flat-square" />
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-1F2A37?style=flat-square&logo=sqlite&logoColor=white" />

**Mobile and web**<br />
<img alt="React" src="https://img.shields.io/badge/React-1F2A37?style=flat-square&logo=react&logoColor=white" />
<img alt="React Native" src="https://img.shields.io/badge/React_Native-1F2A37?style=flat-square&logo=react&logoColor=white" />
<img alt="Expo" src="https://img.shields.io/badge/Expo-1F2A37?style=flat-square&logo=expo&logoColor=white" />
<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-1F2A37?style=flat-square&logo=typescript&logoColor=white" />
<img alt="Redux Toolkit" src="https://img.shields.io/badge/Redux_Toolkit-1F2A37?style=flat-square&logo=redux&logoColor=white" />
<img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_%2F_NativeWind-1F2A37?style=flat-square&logo=tailwindcss&logoColor=white" />
<img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-1F2A37?style=flat-square&logo=bootstrap&logoColor=white" />
<img alt="Leaflet" src="https://img.shields.io/badge/Leaflet-1F2A37?style=flat-square&logo=leaflet&logoColor=white" />
<img alt="Astro" src="https://img.shields.io/badge/Astro-1F2A37?style=flat-square&logo=astro&logoColor=white" />
<img alt="Firebase" src="https://img.shields.io/badge/Firebase-1F2A37?style=flat-square&logo=firebase&logoColor=white" />

**Testing and delivery**<br />
<img alt="xUnit" src="https://img.shields.io/badge/xUnit-1F2A37?style=flat-square" />
<img alt="Testcontainers" src="https://img.shields.io/badge/Testcontainers-1F2A37?style=flat-square" />
<img alt="Vitest" src="https://img.shields.io/badge/Vitest-1F2A37?style=flat-square&logo=vitest&logoColor=white" />
<img alt="Playwright" src="https://img.shields.io/badge/Playwright-1F2A37?style=flat-square&logo=playwright&logoColor=white" />
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-1F2A37?style=flat-square&logo=githubactions&logoColor=white" />
<img alt="Docker" src="https://img.shields.io/badge/Docker-1F2A37?style=flat-square&logo=docker&logoColor=white" />
<img alt="Git" src="https://img.shields.io/badge/Git-1F2A37?style=flat-square&logo=git&logoColor=white" />

---

<details>
<summary><b>Türkçe</b></summary>

<br />

**Backend geliştiriciyim.** ASP.NET Core ve PostgreSQL ile backend, React ve TypeScript ile önündeki web uygulamalarını geliştiriyorum. Junior .NET / backend pozisyonu arıyorum. Son projelerimin her biri, gerçek sistemlerin sık yanlış yaptığı bir problemi ele alıp yük altında da doğru kalacak şekilde çözüyor: aynı koltuğun iki kez satılması, paranın iki kez taşınması, veritabanı ile kuyruk arasında kaybolan mesaj, aynı günün iki kişiye kiralanması, telefonda çevrimdışı yapılan işin senkronu.

- **Eşzamanlılıkta doğru:** yarışları veritabanı belirliyor (satır kilitleri, exclusion constraint'ler, tetikleyiciler, idempotency anahtarları) ve bunu bir test kanıtlıyor; örneğin son koltuğu aynı anda alan 20 kişiden tam biri alıyor.
- **Gerçeğine karşı test:** toplam 1.470 otomatik test; entegrasyon testleri gerçek API'yi Testcontainers'taki PostgreSQL, RabbitMQ ya da Redis'e karşı çalıştırıyor, CI'da tüm ortam uçtan uca deneniyor.
- **Ölçülmüş:** her üründe bir yük testi; sonuçlar ve ne anlama geldikleri README'de.
- **Tek komutla çalışır:** `docker compose up` veritabanını, API'yi ve web uygulamasını başlatıyor.
- **Belgelenmiş:** İngilizce ve Türkçe README, ekran görüntüleri, tanıtım GIF'i, mimari diyagramlar ve tasarım kararları.

Projelerin tamamı, canlı demolar ve tarayıcıda çalışan CV oluşturucu portföyümde: [beratoguzhan620.github.io/portfolio](https://beratoguzhan620.github.io/portfolio/). Sayfanın sağ üstündeki düğmeyle Türkçeye geçebilirsin.

İletişim: [beratoguzhan620@gmail.com](mailto:beratoguzhan620@gmail.com) · [LinkedIn](https://www.linkedin.com/in/berat-oguzhan-turgut)

</details>
