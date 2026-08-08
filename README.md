<h1 align="center">Hey there 👋, I'm Arkadiusz Biel</h1>

<p align="center">
  <b>.NET Developer · Open-Source Author · Conference Speaker</b>
</p>

<p align="center">
  <a href="https://bielu.pl"><img src="https://img.shields.io/badge/Website-bielu.pl-4C1D95?logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://www.linkedin.com/in/bielu"><img src="https://img.shields.io/badge/LinkedIn-bielu-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://www.nuget.org/profiles/bielu"><img src="https://img.shields.io/badge/NuGet-bielu-004880?logo=nuget&logoColor=white" alt="NuGet"></a>
  <a href="https://github.com/sponsors/bielu"><img src="https://img.shields.io/badge/Sponsor-❤️-ea4aaa?logo=github-sponsors&logoColor=white" alt="GitHub Sponsors"></a>
</p>

---

### 🧑‍💻 About Me

I'm a .NET developer building open-source infrastructure libraries. My current focus is on the parts of a system that live *between* services:

- 📜 &nbsp;**API description tooling** — AsyncAPI, Arazzo and Overlay for .NET, with the same developer experience `Microsoft.AspNetCore.OpenApi` gives you for REST
- 📬 &nbsp;**Persistent queues & store-and-forward messaging** — durable, pluggable-storage queueing for .NET
- 🏗️ &nbsp;**.NET Aspire** — resources, secret providers and orchestration extensions for local and CI topologies
- 🔭 &nbsp;**Observability & infrastructure** — OpenTelemetry instrumentation, container-runtime abstractions, Roslyn analyzers

Alongside that: **85+ published NuGet packages** with 190k+ downloads, conference speaking (Umbraco Poland Festival & more),
and an [Arctic Code Vault](https://archiveprogram.github.com/arctic-vault/) contribution.

---

### 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/C%23-239120?logo=csharp&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white" alt=".NET">
  <img src="https://img.shields.io/badge/ASP.NET_Core-512BD4?logo=dotnet&logoColor=white" alt="ASP.NET Core">
  <img src="https://img.shields.io/badge/.NET_Aspire-512BD4?logo=dotnet&logoColor=white" alt=".NET Aspire">
  <img src="https://img.shields.io/badge/AsyncAPI-2E7D32?logo=asyncapi&logoColor=white" alt="AsyncAPI">
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?logo=opentelemetry&logoColor=white" alt="OpenTelemetry">
  <img src="https://img.shields.io/badge/SignalR-512BD4?logo=dotnet&logoColor=white" alt="SignalR">
  <img src="https://img.shields.io/badge/gRPC-244C5A?logo=grpc&logoColor=white" alt="gRPC">
  <img src="https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white" alt="Kafka">
  <img src="https://img.shields.io/badge/EF_Core-512BD4?logo=dotnet&logoColor=white" alt="EF Core">
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" alt="Kubernetes">
  <img src="https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white" alt="GitHub Actions">
  <img src="https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white" alt="Terraform">
</p>

---

### 🚀 What I'm Building

#### 📜 API Descriptions for .NET

**[Bielu.AspNetCore.ApiDescriptions](https://github.com/bielu/Bielu.AspNetCore.ApiDescriptions)** · [📖 apidescriptions.bielu.pl](https://apidescriptions.bielu.pl/)

Code-first **AsyncAPI**, **Arazzo** and **Overlay** document generation for ASP.NET Core — the `Microsoft.AspNetCore.OpenApi` developer experience, applied to event-driven and workflow specifications.

| Area | Packages |
|------|----------|
| Core | `Bielu.AspNetCore.AsyncApi` · `.Attributes` · `.Extensions` · `.Versioning` · `.Merger` |
| Protocol bindings | SignalR · gRPC · SSE · WebRTC |
| Interactive UI | `.Scalar` (+ SignalR / gRPC / Aspire variants) |
| Workflows & overlays | `Bielu.Arazzo.NET` · `Bielu.Overlay.NET` · `Bielu.AspNetCore.Arazzo` |
| Tooling | `.Cli` · `.Templates` · `.ApiDescription.Server` (build-time generation) |

#### 📬 Messaging & Infrastructure

| Project | Description |
|---------|-------------|
| [**Bielu.PersistentQueues**](https://github.com/bielu/Bielu.PersistentQueues) | High-performance, store-and-forward persistent message queue for .NET with pluggable storage backends and strongly-typed messages |
| [**Bielu.Aspire.Common**](https://github.com/bielu/Bielu.Aspire.Common) | .NET Aspire extensions — file-store resources, plus 1Password and Infisical secret integrations |
| [**bielu.microservices.orchestrator**](https://github.com/bielu/bielu.microservices.orchestrator) | Unified abstraction over Docker, Podman, containerd and Kubernetes — swap the container runtime with one line of config |
| [**Bielu.OnePassword.AspNetCore**](https://github.com/bielu/Bielu.OnePassword.AspNetCore.Configuration.Secrets) | 1Password Connect secrets provider for `Microsoft.Extensions.Configuration` |

#### 🧰 Libraries & Developer Tooling

| Project | Description |
|---------|-------------|
| [**bielu.entityframework.extensions**](https://github.com/bielu/bielu.entityframework.extensions) | Provider-agnostic EF Core extensions — content versioning without temporal tables, triggers or provider-specific SQL |
| [**bielu.aspnetcore.identity**](https://github.com/bielu/bielu.aspnetcore.identity) | LDAP identity provider for ASP.NET Core — authenticate and resolve roles against OpenLDAP, Active Directory & friends, no local database |
| [**bielu.staticcode.analyzers**](https://github.com/bielu/bielu.staticcode.analyzers) | Roslyn analyzers enforcing conventions across the bielu ecosystem |
| [**Bielu.Common.Libraries**](https://github.com/bielu/Bielu.Common.Libraries) | Priority-based decorator registration for Scrutor — deterministic decorator ordering across modules |
| [**bielu.dotnet.templates**](https://github.com/bielu/bielu.dotnet.templates) | `dotnet new` templates wired up with Aspire, OpenTelemetry and analyzers out of the box |

---

### 🤝 Upstream Contributions

I don't just consume these specs — I help build the tooling and the specs themselves.

| Project | What I've contributed |
|---------|----------------------|
| [**scalar/scalar**](https://github.com/scalar/scalar) | Drove **AsyncAPI support** into Scalar — document-wide auth rendering, protocol bindings, broker security schemes, and AsyncAPI 3.1 mocking over WebSocket & SSE. Also added the **Azure Functions** and **AWS Lambda** .NET integrations, a plugin system loadable from URLs, and repo-wide Central Package Management. |
| [**ByteBardOrg/AsyncAPI.NET**](https://github.com/ByteBardOrg/AsyncAPI.NET) | Deserialization validation and spec-conformance fixes to the official continuation of `LEGO.AsyncAPI.NET`. |
| [**OAI/Overlay-Specification**](https://github.com/OAI/Overlay-Specification) | Proposed target document format declaration (`targetFormat`) so Overlay can address non-OpenAPI documents. |

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=bielu&show_icons=true&theme=default&hide_border=true&count_private=true" alt="GitHub Stats" height="170">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=bielu&layout=compact&hide_border=true&langs_count=8" alt="Top Languages" height="170">
</p>

---

### 💬 Let's Connect

- 🌐 **Website:** [bielu.pl](https://bielu.pl)
- 🔗 **LinkedIn:** [linkedin.com/in/bielu](https://www.linkedin.com/in/bielu)
- 📦 **NuGet packages:** [nuget.org/profiles/bielu](https://www.nuget.org/profiles/bielu)
- 💖 **Sponsor my work:** [github.com/sponsors/bielu](https://github.com/sponsors/bielu)

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=bielu&label=Profile+Views&color=blue&style=flat" alt="Profile Views">
</p>
