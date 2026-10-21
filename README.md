# Awesome Site Reliability Engineering Tools with stars

<!--lint ignore no-dead-urls--> 

A curated list of Site Reliability and Production Engineering tools - Maintained by [Raghu Chinnannan](https://twitter.com/RaghuChinnannan) and [Squadcast](https://www.squadcast.com/)

## Contents

* [Development](#development)
  * [Source Code Management](#source-code-management)
  * [Project Management & Issue Tracking Software](#project-management--issue-tracking-software)
  * [Bug / Defect Tracking Software](#bug--defect-tracking-software)
  * [Code Editors and IDE's](#code-editors-and-ides)
* [Continuous Testing](#continuous-testing)
* [Continuous Integration](#continuous-integration)
  * [Build](#build)
  * [Integration](#integration)
* [Continuous Delivery](#continuous-delivery)
  * [Deployment](#deployment)
  * [Infrastructure orchestration](#infrastructure-orchestration)
  * [Container](#container)
  * [Container Registry](#container-registry)
  * [Container Orchestration](#container-orchestration)
* [Continuous Monitoring](#continuous-monitoring)
* [Incident Management / Incident Response / IT Alerting / On-Call](#incident-management--incident-response--it-alerting--on-call)
  * [IT Service Management](#it-service-management)
  * [Incident Communication](#incident-communication)
* [Internal Developer Portal](#internal-developer-portal)
* [AI SRE Tools & SRE Copilots](#ai-sre-tools--sre-copilots)

## Development

### Source Code Management

* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)
* [Gitlab](https://about.gitlab.com/)
* [Bitbucket](https://bitbucket.org/)
* [Fossil](https://www.fossil-scm.org/)
* [Mercurial](https://www.mercurial-scm.org/)
* [Perforce Helix Core](https://www.perforce.com/products/helix-core/)
* [Subversion (SVN)](https://subversion.apache.org/)

### Project Management & Issue Tracking Software

* [Jira](https://www.atlassian.com/software/jira)
* [Trello](https://trello.com/)
* [Zoho Sprints](https://www.zoho.com/sprints/)
* [Taiga](https://taiga.io/)
* [Wrike](https://www.wrike.com/)
* [Asana](https://asana.com/)
* [Monday.com](https://monday.com/)
* [Clickup](https://clickup.com/)
* [Basecamp](https://basecamp.com/)
* [Rally](https://www.broadcom.com/products/software/value-stream-management/rally)
* [Teamwork](https://www.teamwork.com/)
* [Redmine](https://www.redmine.org/)
* [Freedcamp](https://www.freedcamp.com/)
* [Shortcut](https://www.shortcut.com/)
* [Azure Boards](https://azure.microsoft.com/en-us/products/devops/boards/)
* [GitHub Projects](https://github.com/features/project-management)
* [GitLab Boards](https://docs.gitlab.com/ee/user/project/issue_board.html)
* [Bitbucket Issues](https://bitbucket.org/product/features/issues)
* [Linear](https://linear.app/)

### Bug / Defect Tracking Software

* [Bugzilla](https://www.bugzilla.org/)
* [Bugsee](https://www.bugsee.com/)
* [Instabug](https://instabug.com/)
* [Zoho BugTracker](https://www.zoho.in/bugtracker/)
* [Bugasura](https://bugasura.io)
* [Mantis Bug Tracker](https://www.mantisbt.org/)
* [Github Issues](https://docs.github.com/en/issues/tracking-your-work-with-issues)

### Code Editors and IDEs

* [LibreDB Studio](https://github.com/libredb/libredb-studio) ⭐ 1,244 | 🐛 56 | 🌐 TypeScript | 📅 2026-10-20
* [GNU Emacs](https://www.gnu.org/software/emacs/)
* [Notepad++](https://notepad-plus-plus.org/)
* [Atom](https://atom.io/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Sublime Text](https://www.sublimetext.com/)
* [Vim](https://www.vim.org/)
* [Neovim](https://neovim.io/)
* [Eclipse](https://www.eclipse.org/downloads/)
* [GNU Nano](https://www.nano-editor.org/)
* [UltraEdit](https://www.ultraedit.com/)
* [TextMate](https://macromates.com/)
* [gedit](https://gitlab.gnome.org/GNOME/gedit/)
* [WebStorm](https://www.jetbrains.com/webstorm/)
* [IntelliJ IDEA](https://www.jetbrains.com/idea/)
* [PyCharm](https://www.jetbrains.com/pycharm/)
* [Eclipse Che](https://www.eclipse.org/che/)
* [Bluefish](https://bluefish.openoffice.nl/index.html)

## Continuous Testing

* [Agent QA](https://github.com/vostride/agent-qa) ⭐ 912 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-03
* [flakybin](https://github.com/mikluko/flakybin) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2026-06-07
* [Retry Jitter Lab](https://github.com/KRISHNAMMurarka/retry-jitter-lab) ⭐ 1 | 🐛 4 | 🌐 Python | 📅 2026-10-19 - Experimental Python simulator for comparing retry backoff and jitter policies during a modeled outage and recovery.
* [DriftWire](https://github.com/Haswell119/driftwire) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-23
* [Selenium](https://www.seleniumhq.org/)
* [JUnit](https://junit.org/)
* [TestNG](https://testng.org/doc/index.html)
* [NUnit](https://nunit.org/)
* [TestSigma](https://testsigma.com/)
* [Unified Functional Testing (UFT)](https://www.microfocus.com/en-us/products/unified-functional-automated-testing/overview)
* [Tricentis Tosca](https://www.tricentis.com/products/automate-continuous-testing-tosca/)
* [IBM Rational Functional Tester](https://www.ibm.com/in-en/marketplace/rational-functional-tester)
* [TestComplete](https://smartbear.com/product/testcomplete/overview/)
* [Waitr](http://watir.com/)
* [Zephyr](https://www.getzephyr.com/)
* [accelQ](https://www.accelq.com/)
* [Apache jMeter](https://jmeter.apache.org/)
* [Appium](http://appium.io/)
* [steadybit](https://www.steadybit.com/)
* [k6](https://k6.io/)
* [Apache JMeter](https://jmeter.apache.org/)
* [Gatling](https://gatling.io/)
* [Cypress](https://www.cypress.io/)
* [TestRail](https://www.gurock.com/testrail/)
* [Bencher](https://bencher.dev)
* [Keploy](https://keploy.io/)

## Continuous Integration

### Build

* [Ninja](https://ninja-build.org/)
* [Meson](https://mesonbuild.com/)
* [CMake](https://cmake.org/)
* [Autotools/Automake](https://www.gnu.org/software/automake/)
* [premake](https://premake.github.io/)
* [Maven](https://maven.apache.org/)
* [Ant](https://ant.apache.org/)
* [Gradle](https://gradle.org/)
* [Make](https://www.gnu.org/software/make/)
* [Cake](https://cakebuild.net/)
* [Rake](https://ruby.github.io/rake/)
* [MS Build](https://www.microsoft.com/en-us/build)
* [Drill](https://gitlab.com/aki237/drill)
* [Hydra](https://nixos.org/hydra/)
* [Bazel](https://bazel.io)
* [Azure DevOps](https://azure.microsoft.com/en-us/services/devops/)

### Integration

* [Abstruse CI](https://github.com/bleenco/abstruse) ⭐ 962 | 🐛 36 | 🌐 Go | 📅 2026-09-04
* [Badwolf](https://github.com/bosondata/badwolf) ⚠️ Archived
* [CI Health Audit](https://github.com/sdxiaomage/ci-health-audit) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-11 - Zero-dependency GitHub Actions and CLI static audit for workflow security and reliability risks, with Markdown/JSON output and configurable severity gates.
* [Jenkins](https://jenkins.io/)
* [Bamboo](https://www.atlassian.com/software/bamboo)
* [Hudson](http://hudson-ci.org/)
* [CircleCI](https://circleci.com)
* [TeamCity](https://www.jetbrains.com/teamcity/)
* [Gitlab CI](https://about.gitlab.com/product/continuous-integration/)
* [Travis CI](https://travis-ci.org/)
* [AWS CodeStar](https://aws.amazon.com/codestar/)
* [Buildbot](http://buildbot.net/)
* [Semaphore CI](https://semaphoreci.com/)
* [Concourse CI](https://concourse-ci.org/)
* [Appcenter](https://appcenter.ms/)
* [Appveyor](https://ci.appveyor.com/)
* [Assertible](https://assertible.com/)
* [Britise](http://bitrise.io/)
* [Buildkite](https://buildkite.com/)
* [Chrono CI](http://www.chronoci.com/)
* [Codacy](https://www.codacy.com/)
* [CodeClimate](https://www.codeclimate.com/)
* [CodeFresh](https://codefresh.io/)
* [Codeship](https://www.codeship.io/)
* [Continuousphp](https://continuousphp.com/)
* [Drone](https://drone.io/)
* [Hound CI](https://houndci.com/)
* [Probo.CI](https://probo.ci/)
* [Solano CI](https://xebialabs.com/technology/solano-ci/)
* [Visual Studio Team Services](https://www.visualstudio.com/team-services/)
* [Go CD](https://www.gocd.org/)

## Continuous Delivery

### Deployment

* [kzero](https://github.com/hrodrig/kzero) ⭐ 4 | 🐛 1 | 🌐 Go | 📅 2026-09-27 - Declarative Kubernetes down/up/reset CLI for bastion maintenance playbooks (scale, Helm, PVC, jobs) with dry-run and notify.
* [AWS CodeDeploy](https://aws.amazon.com/codedeploy/)
* [ElectricFlow](http://electric-cloud.com/products/electricflow/)
* [Octopus Deploy](https://octopus.com/)
* [IBM UrbanCode](http://www-03.ibm.com/software/products/en/ucdep)
* [DeployBot](https://deploybot.com/)
* [Shippable](https://app.shippable.com/)
* [Codar Continuous Delivery](https://www.microfocus.com/en-us/products/codar-continuous-deployment/overview)
* [Wercker](https://app.wercker.com/)
* [Humanitec](https://humanitec.com/)
* [ArgoCD](https://argo-cd.readthedocs.io/en/stable/)
* [Buddy Works](https://buddy.works/)
* [werf](https://werf.io/)
* [Google Cloud Build](https://cloud.google.com/build)
* [Qovery](https://www.qovery.com/) - Enterprise Kubernetes management platform for deploying applications, databases, Helm charts, and Terraform modules on AWS, GCP, Azure, and Scaleway.

### Infrastructure orchestration

* [Terrateam](https://github.com/terrateamio/terrateam) ⭐ 1,308 | 🐛 113 | 🌐 OCaml | 📅 2026-10-20
* [Vagrant](https://www.vagrantup.com/)
* [Puppet](https://puppet.com/)
* [Chef](https://www.chef.io/)
* [SaltStack](https://www.saltstack.com/)
* [Ansible](https://www.ansible.com/)
* [Terraform](https://www.terraform.io/)
* [AWS CloudFormation](https://aws.amazon.com/cloudformation/)
* [Rundeck](https://www.rundeck.com/)
* [Spacelift](https://spacelift.io/)
* [Selefra](https://www.selefra.io/)
* [Scalr](https://www.scalr.com/)
* [Stategraph](https://stategraph.com)
* [Pulumi](https://www.pulumi.com/)
* [Google Cloud Deployment Manager](https://cloud.google.com/deployment-manager/)
* [OPS](https://ops.city)
* [Kratix](https://www.kratix.io/)

### Container

* [Docker](https://www.docker.com/)
* [Turbo.NET](https://turbo.net/)
* [WinDocks](https://windocks.com/)
* [Podman](https://podman.io/)
* [containerd](https://containerd.io/)
* [OpenShift](https://www.openshift.com/)
* [Unikraft](https://unikraft.org)

### Container Registry

* [Docker Hub](https://hub.docker.com/)
* [Google Container Registry](https://cloud.google.com/container-registry/)
* [Amazon ECR](https://aws.amazon.com/ecr/)
* [Gitlab Container Registry](https://about.gitlab.com/2016/05/23/gitlab-container-registry/)
* [JFrog Artifactory](https://jfrog.com/artifactory/)
* [Quay.io](https://quay.io/)
* [Azure Container Registry](https://azure.microsoft.com/en-in/services/container-registry/)
* [Oracle Container Registry](https://container-registry.oracle.com)
* [Nexus Container Registry](https://help.sonatype.com/repomanager3/formats/docker-registry)
* [Harbor](https://goharbor.io/)

### Container Orchestration

* [Kubernetes](https://kubernetes.io/)
* [Docker Swarm](https://docs.docker.com/engine/swarm/)
* [Apache Mesos](http://mesos.apache.org/) - with [Marathon](https://mesosphere.github.io/marathon/)

## Continuous Monitoring

* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics/) ⭐ 17,887 | 🐛 793 | 🌐 Go | 📅 2026-10-20
* [Streamdal](https://streamdal.com) - Code-Native Data Privacy - embed privacy controls in your application code to detect and monitor PII. [![Streamdal](https://img.shields.io/github/stars/streamdal/streamdal?style=flat-square\&logo=github\&labelColor=%230D1117\&color=%23161B22)](https://github.com/streamdal/streamdal) ⚠️ Archived
* [LynxDB](https://github.com/lynxbase/lynxdb) ⭐ 286 | 🐛 8 | 🌐 Go | 📅 2026-08-15 - Lightweight columnar log analytics database for SRE workflows, with a pipe-style query language inspired by SPL for investigating production logs.
* [DoctorGPT](https://github.com/ingyamilmolinar/doctorgpt) ⭐ 209 | 🐛 0 | 🌐 Go | 📅 2023-05-10 - Brings GPT into production for application log error monitoring
* [agenttrace](https://github.com/luoyuctl/agenttrace) ⭐ 148 | 🐛 6 | 🌐 Rust | 📅 2026-10-19 - TUI observability for AI coding agents. Track cost, tokens, tool failures, latency, anomalies, health, diffs, and CI gates across Claude Code, Codex CLI, Gemini CLI, Aider, and Cursor exports.
* [KubeStellar Console](https://console.kubestellar.io) - Open-source multi-cluster Kubernetes dashboard with AI-powered operations, MCP server bridging kubeconfig to LLM agents, and real-time observability across edge and cloud clusters. CNCF Sandbox. [![KubeStellar Console](https://img.shields.io/github/stars/kubestellar/console?style=flat-square\&logo=github\&labelColor=%230D1117\&color=%23161B22)](https://github.com/kubestellar/console) ⭐ 147 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-20
* [cloud-audit](https://github.com/gebalamariusz/cloud-audit) ⭐ 72 | 🐛 11 | 🌐 Python | 📅 2026-10-14 - AWS security auditing CLI that runs 17 checks across IAM, S3, EC2, VPC, and RDS with built-in remediation engine generating AWS CLI commands and Terraform snippets.
* [Telemetry Tracker](https://github.com/Telemetry-Tracker/telemetry-tracker) ⭐ 35 | 🐛 45 | 🌐 TypeScript | 📅 2026-10-20 - Open-source, self-hostable error tracker for side projects and small teams, with grouped errors, source maps and alerts.
* [SSL Certificate Monitor](https://github.com/brancogao/ssl-certificate-monitor) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-18 - Open-source SSL/TLS certificate expiry monitoring tool with email alerts
* [net-benchmark](https://github.com/net-benchmark/net-benchmark) ⭐ 13 | 🐛 8 | 🌐 Python | 📅 2026-10-16 - DNS/HTTP/SSL benchmarking with CSV, Excel, PDF, and JSON exports.
* [OpenClaw Monitor](https://github.com/flik2002/openclaw-monitor) ⭐ 13 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-14 - Real-time AI agent monitoring dashboard for OpenClaw agents. Track Gateway status, sessions, token usage & trends.
* [Faultline](https://github.com/faultline-cli/faultline) ⭐ 6 | 🐛 0 | 🌐 Go | 📅 2026-06-05 - Deterministic CI failure analysis CLI that classifies build logs into explainable failure types with evidence and fix steps.
* [gghstats](https://github.com/hrodrig/gghstats) ⭐ 6 | 🐛 4 | 🌐 Go | 📅 2026-10-16 - Self-hosted GitHub traffic stats beyond the 14-day API window (SQLite dashboard + Head-to-Head compare).
* [Vectory](https://github.com/416rehman/Vectory) ⭐ 6 | 🐛 0 | 🌐 Rust | 📅 2026-10-07 - Self-hosted dashboard for editing Vector pipelines, deploying versioned configurations and tracking the configuration running on each host.
* [Rasptele](https://github.com/maddhruv/rasptele) ⭐ 2 | 🐛 11 | 🌐 Python | 📅 2026-09-29 - Open-source monitoring and control bot for Raspberry Pi Docker servers, with host and container health checks, stateful Telegram alerts, and allowlisted container restarts.
* [DNS Propagation Checker](https://github.com/brancogao/dns-propagation-checker) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-18 - Open-source DNS propagation monitoring tool with global DNS server coverage
* [gha-deadman](https://github.com/GeiserX/gha-deadman) ⭐ 1 | 🐛 0 | 🌐 Shell | 📅 2026-10-06 - Dead-man's switch on free GitHub Actions that probes a URL on a schedule from outside your network and sends a Telegram alert when it goes down, reminders while it stays down, and a message on recovery.
* [MB3R Stack](https://github.com/MB3R-Lab/mb3r-stack) ⭐ 1 | 🐛 5 | 🌐 Python | 📅 2026-10-15 - Open-source model-based resilience toolchain using telemetry-driven topology discovery and virtual failure simulation for continuous resilience assessment and pre-release risk analysis.
* [Seitendiff Watcher](https://github.com/peppe1337/seitendiff) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-13 - GitHub Actions template that watches a CSS-selected fragment of a public page and opens an issue in a repository you own when that fragment changes. No server and no account elsewhere. MIT.
* [agent-watch](https://github.com/soul-sol/agent-watch) ⭐ 0 | 🐛 0 | 🌐 Shell | 📅 2026-09-17 - POSIX shell scripts that classify background coding-agent jobs as RUNNING, DONE, FAILED, or STALL and preflight transport versus authentication failures.
* [AWS CloudWatch](https://aws.amazon.com/cloudwatch/)
* [Nuberio Audit](https://www.nuberio.com/audit) - Free, read-only AWS account scan for missing/noisy CloudWatch alarms, GuardDuty/Security Hub findings, and AWS Config compliance gaps.
* [DebugBear](https://www.debugbear.com/)
* [Prometheus](https://prometheus.io/)
* [StackDriver](https://cloud.google.com/stackdriver/)
* [Sensu](https://sensu.io/)
* [Sentry](https://sentry.io/welcome/)
* [CopperEgg](https://www.idera.com/infrastructure-monitoring-as-a-service)
* [Crashlytics](https://fabric.io/kits/android/crashlytics)
* [Kapacitor](https://www.influxdata.com/time-series-platform/kapacitor/)
* [loggly](https://www.loggly.com/)
* [logmatic](https://logmatic.io/)
* [Logstash](https://www.elastic.co/products/logstash)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
* [MongoDB Cloud Manager](https://www.mongodb.com/cloud/cloud-manager)
* [NewRelic](https://newrelic.com/)
* [ReleaseRun Vulnerability Scanner](https://releaserun.com/tools/vulnerability-scanner/)
* [Papertrail](https://papertrailapp.com/)
* [PageGuard](https://pageguard.org) - Free all-in-one website health scanner. Core Web Vitals, SEO, WCAG 2.1 accessibility, and best practices. AI-generated action plan. No signup required.
* [Pingdom](https://tools.pingdom.com/)
* [ServerDensity](https://www.serverdensity.com/)
* [Zabbix](https://www.zabbix.com/)
* [InsightOps](https://www.rapid7.com/products/insightops/)
* [AppSignal](https://appsignal.com)
* [Grafana](https://grafana.com)
* [Chaos Genius](https://www.chaosgenius.io/)
* [Cloud Waste Scanner](https://cloud-waste-scanner.com) - Detects cloud waste and helps DevOps/platform teams identify quick cloud cost optimization opportunities.
* [Thanos](https://thanos.io/)
* [Mimir](https://grafana.com/oss/mimir/)
* [Hydrozen.io](https://hydrozen.io) - Uptime monitoring & Statuspages
* [whatbroke.today](https://whatbroke.today) - AI-powered outage aggregator tracking 100+ cloud services with Telegram alerts
* [Prismix](https://prismix.dev) - Real-time status dashboard for 75+ AI services (OpenAI, Anthropic, Gemini, Mistral, etc.) with starring, email/webhook alerts, 30-day uptime history, and embeddable SVG badges.
* [Steampipe.io](https://steampipe.io) - Universal SQL interface to any cloud API
* [Better Stack](https://betterstack.com/)
* [Netdata](https://netdata.cloud)
* [Dynatrace](https://www.dynatrace.com/)
* [Datadog](https://www.datadoghq.com/)
* [DevHelm](https://devhelm.io) - Developer-first uptime monitoring with HTTP, DNS, TCP, ICMP, and heartbeat checks, dependency intelligence for 80+ providers, hosted status pages, incident management, and a full developer surface (CLI, SDKs, Terraform provider, MCP server).
* [Elastic APM](https://www.elastic.co/apm)
* [Healthchecks.io](https://healthchecks.io)
* [OnlineOrNot](https://onlineornot.com/) - Uptime monitoring for websites, APIs, and cron jobs, with integrated status pages.
* [Uptrack](https://uptrack.app) - Uptime monitoring with 30-second checks on free tier, consecutive-check alert confirmation to cut false positives, hosted status pages, and a built-in MCP server for AI agents.
* [Dash0](https://www.dash0.com/) - OpenTelemetry Native Observability, built on CNCF Open Standards such as PromQL, Perses and OTLP with full cost control. Supporting Metrics, Traces and Logs with full custom dashboarding and alerting capabilities.
* [CICube](https://cicube.io/) - AI DevOps monitoring platform by monitoring your CI workflows, detect anomalies, and provide actionable fixes.
* [Middleware](https://middleware.io) - A Full-Stack Cloud Observability Platform designed to empower developers and organizations to monitor, optimize, and streamline their applications and infrastructure in real-time.
* [Shipfox](https://www.shipfox.io/) - Boost GitHub Actions speed by 2x and cut costs by up to 75%, with smarter caching, deep CI insights, and zero-config setup.
* [Ingero](https://github.com/ingero-io/ingero) - eBPF-based GPU causal observability agent. Traces CUDA APIs and host kernel events to build causal chains explaining GPU latency. Includes MCP server for AI-assisted incident investigation.
* [FlareWarden](https://flarewarden.com/monitoring) - Uptime, content, and dependency monitoring with multi-region verification, status pages, and incident management.
* [Phare](https://phare.io) - Shockingly good uptime monitoring, alerts, incident management, and status pages.
* [API Status Check](https://apistatuscheck.com/) - Aggregated status dashboard for 285 developer APIs and services across 29 categories, including AWS, Stripe, GitHub, and OpenAI.
* [Apitally](https://apitally.io) - API monitoring, analytics, and request logging for REST APIs, with lightweight open-source SDKs for Python, Node.js, Go, .NET, and Java.
* [Riftmap](https://riftmap.dev) - Cross-repo infrastructure dependency discovery and change impact analysis for multi-repo environments using Terraform, Docker, Helm, and more.
* [Oack](https://oack.io) - HTTP monitoring with TCP kernel telemetry, 6-phase latency breakdown, Server-Timing header capture, Cloudflare CDN enrichment, and built-in incident management with on-call scheduling.
* [Prismix](https://prismix.dev) - Real-time status monitoring and incident tracking for 75+ AI services (OpenAI, Anthropic, Google Gemini, Cursor, Groq). Free REST API, email/webhook alerts, 30-day uptime history.
* [sunwatch](https://sunwatch.sunfamily.xyz/) - Crypto-paid uptime monitoring for side projects. Pay per monitor with USDC on Base; webhook alerts on down/up state changes.
* [Drumbeats](https://drumbeats.io) - Cron, heartbeat, and HTTP uptime monitoring for background jobs and services, with concurrent-job (run\_id) correlation, duration/hang alerts, LOG pings for mid-run progress, incident management, and status pages. One curl ping instruments a job; no agent or SDK. Free tier: 50 monitors, 200K Beats/mo, all notification channels.
* [OpenChainBench](https://openchainbench.com) - Continuous monitoring of blockchain RPC providers, bridges and oracles. Multi-region Prometheus probes of latency, tx-landing success and finality with public dashboards and open methodology.
* [Respan](https://www.respan.ai/ai-gateway) - Observability platform for LLM and AI agent applications, with tracing, evals, prompt management, and a gateway across 250+ models.
* [Oh Dear](https://ohdear.app) - Monitoring for uptime, performance, broken links, SSL certificates, and DNS, with hosted status pages.
* [Yorker](https://yorkermonitoring.com) - OpenTelemetry-native synthetic monitoring with HTTP and Playwright browser checks, monitoring-as-code via YAML and CLI, and enriched OTLP export to any OTel backend.
* [CronAlive](https://cronalive.com) - Heartbeat monitoring for cron jobs, HTTP uptime checks with multi-region confirmation, and TLS certificate expiry alerts. Free tier with 10 checks.
* [Merlonix](https://merlonix.com) - SSL, DNS, and uptime monitoring for agencies, with per-client white-label hosted status pages, alert routing, and a built-in remote MCP server for AI agents.
* [OpsCanopy](https://opscanopy.com) - Browser-based testers for Prometheus relabel\_configs, Alertmanager routing and Loki alert rules; runs client-side with no upload.
* [LastPing](https://lastping.dev) - Dead man's switch monitoring for cron jobs, CI/CD pipelines and AI agents. A job checks in with one HTTP request after it runs; an incident opens when it goes silent, stalls or fails. Free for individuals, with a REST API, MCP server and Terraform provider.
* [Fivenines](https://fivenines.io/features/linux-server-monitoring) - Hosted Linux server monitoring with an open-source agent, historical metrics and alert workflows.
* [Manifest API Bot](https://manifest.build/api-bot/) - GitHub App that checks the third-party APIs your code calls for changes every day and opens a pull request with the code fix when a change affects your code.
* [SolidPing](https://solidping.io) - Open-source uptime monitoring with 40 check types, multi-region workers, private agents, status pages, incidents and on-call escalation. Self-hosted single binary (AGPL-3.0) or hosted, with a built-in MCP server.
* [RealUptime Monitor](https://realuptime.io/monitor) - Uptime, heartbeat/cron and SSL monitoring from multiple regions, with a free plan of 10 monitors at 60-second checks.
* [Tá Rodando](https://tarodando.com.br) - HTTP uptime monitoring with a public status page and incidents, in Portuguese. Alerts by email, Telegram, web push and Slack/Discord/Google Chat webhooks, and a remote MCP server for AI agents. Free plan available.
* [exit1.dev](https://exit1.dev/) - Uptime monitoring for websites, APIs and servers (HTTP, TCP, UDP, WebSocket, ICMP) with SSL and domain expiry alerts and public status pages.
* [Status Harbor](https://www.statusharbor.io) - Uptime, SSL, DNS and cron checks with host and Kubernetes cluster metrics from a single agent, private-network monitoring over outbound HTTPS, chat alerts and hosted status pages.
* [OutageDeck](https://outagedeck.com) - Tracks vendor-published status, incidents, and observed uptime for cloud and SaaS vendors from their official feeds, with alerts, a JSON API, CLI, remote MCP server, and GitHub Action.
* [Hyperping](https://hyperping.com) - Uptime, API, cron and server monitoring from 18 locations, with Playwright browser checks and hosted status pages.
* [ReqKey](https://www.reqkey.com) - API key authentication, usage credits, rate limiting, and request analytics for your own APIs, via a single verify call from your middleware rather than a proxy or gateway. SDKs for Python, Node.js, Go, Rust, PHP, .NET, and Java.
* [Screpy](https://screpy.com/) - Monitors website availability, page speed, and Core Web Vitals alongside technical SEO checks.

## Incident Management / Incident Response / IT Alerting / On-Call

* [Keep - CLI for alerting](https://github.com/keephq/keep) ⭐ 12,427 | 🐛 665 | 🌐 Python | 📅 2026-09-28
* [HolmesGPT](https://github.com/robusta-dev/holmesgpt) ⭐ 3,646 | 🐛 454 | 🌐 Python | 📅 2026-10-20 - Investigate Prometheus alerts, Jira/Pagerduty/Opsgenie tickets automatically using AI.
* [OpenDuty](https://github.com/ustream/openduty) ⚠️ Archived
* [SLO exporter](https://github.com/seznam/slo-exporter) ⭐ 190 | 🐛 15 | 🌐 Go | 📅 2026-03-19
* [SLO Calculator](https://github.com/last9/slo-computer) ⭐ 132 | 🐛 1 | 🌐 Go | 📅 2025-03-04
* [Regen](https://github.com/FluidifyAI/Regen) ⭐ 91 | 🐛 23 | 🌐 Go | 📅 2026-10-18 - Open-source, self-hosted incident management with alert ingestion, on-call scheduling, escalation policies, AI-powered post-mortems, and Slack/Teams integration. AGPLv3 — self-hosted alternative to PagerDuty and Grafana OnCall.
* [groot](https://github.com/hrodrig/groot) ⭐ 23 | 🐛 0 | 🌐 Go | 📅 2026-10-19 - Read-only Kubernetes diagnostics CLI that collects pod logs, events, and API context into one .tar.gz archive for incident response and RCA.
* [NthLayer](https://github.com/rsionnach/nthlayer) ⭐ 17 | 🐛 33 | 🌐 Shell | 📅 2026-10-20 - Reliability Shift Left platform. Generate dashboards, alerts, SLOs from YAML. Verify metrics exist before deploy. Block deploys when error budget exhausted.
* [Rootly CLI](https://github.com/rootlyhq/rootly-cli) ⭐ 9 | 🐛 5 | 🌐 Go | 📅 2026-10-20 - Open-source CLI to manage Rootly incidents, alerts, services, teams, and on-call schedules from the terminal.
* [OpenRunbook](https://github.com/edgex11/OpenRunbook) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-09-03 - Open-source DevOps question answering over a graph database. Ask an on-call question in plain English, get triage commands in order, what to look for in each output, causes and fixes. No LLM. MIT.
* [Squadcast](https://www.squadcast.com)
* [PagerDuty](https://www.pagerduty.com/)
* [VictorOps](https://victorops.com/)
* [OpsGenie](https://www.opsgenie.com/)
* [AlertOps](https://alertops.com/)
* [ITOC360](https://itoc360.com)
* ~~[Blameless](https://www.blameless.com/)~~ Now [FireHydrant](https://www.firehydrant.com)
* [Jira Ops](https://www.atlassian.com/software/jira/ops)
* [OnPage](https://www.onpage.com/)
* [PagerTree](https://pagertree.com/)
* [Cabot](https://cabotapp.com/)
* [AlertAgility](http://www.alertagility.com/)
* [xMatters](https://www.xmatters.com/)
* [Derdack Enterprise Alert](https://www.derdack.com/)
* [Bigpanda](https://www.bigpanda.io/)
* [ngDesk](https://www.ngdesk.com/)
* [Geneos](https://www.itrsgroup.com/products/geneos)
* [FireHydrant](https://www.firehydrant.com)
* [Rootly](https://www.rootly.io)
* [Grafana OnCall](https://grafana.com/oss/oncall/)
* [Better Stack](https://betterstack.com/)
* [Everbridge](https://www.everbridge.com/)
* [Moogsoft](https://www.moogsoft.com/)
* [incident.io](https://incident.io/)
* [Next9.ai](https://next9.ai/)
* [Merlinn](https://github.com/merlinn-co/merlinn) - Open-source AI on-call developer
* [Calmo](https://getcalmo.com/) - Debug Production x10 faster with AI.
* [Runframe](https://runframe.io) - Incident management platform with on-call scheduling, real-time collaboration, and automated escalations.
* [Incidentary](https://incidentary.com) - Shared causal traces for incident response. Captures pre-alert causal chains across services and assembles them into a shared, replayable artifact before the war room starts—open-source SDKs.
* [Spike](https://spike.sh) - Incident management and on-call alerting.
* [CallHeim](https://callheim.com/) - On-call and incident response: escalation policies, on-call schedules, alert deduplication and an incident timeline, with rule-based alert handling and published thresholds.
* [Hyperping](https://hyperping.com) - On-call schedules, escalation policies and alerting via SMS, Slack, Microsoft Teams and webhooks, with status page incident updates.

### IT Service Management

* [FreshService](https://freshservice.com/)
* [ServiceNow](https://www.servicenow.com/)
* [BMC Remedy](http://www.bmcsoftware.in/it-solutions/remedy-itsm.html)
* [Jira Service Management(formerly Jira Service Desk)](https://www.atlassian.com/software/jira/service-management)
* [Samanage](https://www.samanage.com/)
* [Cherwell](https://www.cherwell.com/products/it-service-management/)
* [SysAid](https://www.sysaid.com/it-service-management-software)
* [ManageEngine Servicedesk plus](https://www.manageengine.com/products/service-desk/)
* [Zendesk](https://www.zendesk.com/)

### Incident Communication

* [Squadcast Statuspages](https://www.squadcast.com/statuspage)
* [StatusPal](https://statuspal.io/?utm_source=github.com\&utm_medium=referral\&utm_campaign=awesome-devops) - communicate incidents and maintenance effectively with a beautiful hosted status page.
* [Hydrozen.io Statuspages](https://hydrozen.io)
* [whatbroke.today](https://whatbroke.today) - AI-powered outage aggregator tracking 100+ cloud services with Telegram alerts
* [Atlassian Statuspages](https://www.atlassian.com/software/statuspage)
* [Instatus Statuspages](https://instatus.com) - Quick and beautiful status page.
* [Cachet](https://cachethq.io/)
* [InBrief](https://inbrief.sh) - Hosted status pages with HTTP, TCP and DNS monitors, subscriber updates by email, Slack, Discord, Telegram, Microsoft Teams and RSS, custom domains, multilingual pages, maintenance mode, and per-feature pricing instead of fixed tiers.
* [RealUptime Status](https://realuptime.io/status) - Hosted status pages, with one status page on the free plan.
* [NextReset](https://nextreset.ai/) - Independent AI service incident timeline with official source links and separate Codex reset history.

## Internal Developer Portal

* [Port](https://www.getport.io/)
* [Backstage Software Catalog](https://backstage.io/)
* [OpsLevel](https://www.opslevel.com/)
* [Cortex](https://www.cortex.io/)

## AI SRE Tools & SRE Copilots

* [Radar](https://github.com/skyhook-io/radar) ⭐ 3,877 | 🐛 119 | 🌐 Go | 📅 2026-10-21 - Open source Kubernetes visibility tool with a built-in MCP server for AI-assisted cluster operations — topology, service traffic, events, logs, and a 31-check best-practices audit.

* [Darkmoon](https://github.com/ASCIT31/Dark-Moon) ⭐ 1,120 | 🐛 8 | 🌐 Python | 📅 2026-10-01 - Open source autonomous AI penetration testing platform covering web, API, Active Directory and Kubernetes, fully self hosted and local

* [IncidentFox](https://github.com/incidentfox/incidentfox) ⚠️ Archived (open source)

* [Aurora](https://github.com/Arvo-AI/aurora) ⭐ 438 | 🐛 64 | 🌐 Python | 📅 2026-10-20 - Open source (Apache 2.0) AI SRE agent that autonomously investigates incidents and performs root cause analysis across AWS, Azure, GCP, and Kubernetes. Self-hosted via Docker Compose or Helm, works with major LLM providers or local models via Ollama.

* [OrcaReplay](https://github.com/Continuum-AI-Corp/OrcaReplay) ⭐ 286 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-01 - Records an AI agent's model-provider exchange and replays it offline for postmortems, with no provider contacted; replay can fork from any step onto a different model to isolate what the model caused.

* [Cynative](https://github.com/cynative/cynative) ⭐ 224 | 🐛 27 | 🌐 Go | 📅 2026-10-20 - Deep research agent for your infra - sandboxed, read-only, covers AWS, GCP, Azure, Kubernetes, GitHub and GitLab.

* [OpenSRE (opensre.in)](https://github.com/swapnildahiphale/OpenSRE) ⭐ 166 | 🐛 29 | 🌐 Python | 📅 2026-10-20 - Self-hosted AI SRE platform for incident investigation with episodic memory, a Neo4j knowledge graph, Web UI, Slack, and Teams.

* [KubeStellar Console](https://github.com/kubestellar/console) ⭐ 147 | 🐛 11 | 🌐 TypeScript | 📅 2026-10-20 - AI-powered multi-cluster Kubernetes management console with MCP server (kc-agent) for AI-assisted cluster operations, pod inspection, deployment management, and real-time observability across distributed environments.

* [YYLO](https://github.com/yylo-dev/yylo) ⭐ 65 | 🐛 15 | 🌐 Python | 📅 2026-10-17 - Command-line orchestrator for coding agents, repeatable workflows, and receipt-backed repository changes. Each task freezes the protected target SHA and creates a dedicated branch/worktree behind typed task, validation, merge, and release-readiness boundaries; the merge queue owns risk-based review, and workflow runs retain declared receipt hashes and terminal manifests. MIT, on npm as @yylo/cli; orchestrates Pi and Codex subagents.

* [tailscale-mcp](https://github.com/YawLabs/tailscale-mcp) ⭐ 34 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-15 - MCP server with 52 tools for managing Tailscale tailnets from AI assistants like Claude Code and Cursor.

* [KubeIntellect](https://github.com/MSKazemi/kubeintellect) ⭐ 34 | 🐛 22 | 🌐 Python | 📅 2026-10-17 - Open source (AGPL-3.0) multi-agent Kubernetes SRE agent. Investigates a live cluster via kubectl, Prometheus (PromQL) and Loki (LogQL) and explains root cause in plain English. Every mutating operation stops for human approval enforced at the tool boundary, with role-based access control and a hash-chained decision log.

* [ai-economics-mcp](https://github.com/pich/ai-economics-mcp) ⭐ 1 | 🐛 6 | 🌐 JavaScript | 📅 2026-10-17 - MCP server that prices agent operations before they run: token cost across vendors, fully-loaded agent-hour cost including human review, model-routing savings, and the reviewer capacity a given agent fleet actually needs. 12 calculators by Michał Piszczek ([piszczek.pl/tools](https://piszczek.pl/tools)), MIT, free keyless API.

* [Chronicle](https://github.com/shlokkokk/Chronicle) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-24 - AI-native incident response and operational memory platform featuring alert deduplication, multi-source ingestion, host telemetry, semantic runbook and historical incident retrieval, SLA automation, and AI-assisted root cause analysis.

* [OpsMate (itops.sh)](https://www.itops.sh/) - AI-assisted server operations tool for small teams and solo developers: an SSH terminal and AI chat on one page, continuous patrols with Telegram alerts, and blocking of dangerous commands. The [desktop client](https://github.com/vincent-lxc/opsmate-desktop) ⭐ 0 | 🐛 26 | 🌐 TypeScript | 📅 2026-10-20 is open source (MPL-2.0).

* [heliograph](https://github.com/dbhq-uk/heliograph) ⭐ 0 | 🐛 66 | 🌐 Shell | 📅 2026-10-12 (open source) - CLI and agent skill for debugging hosts you have no access to, for air-gapped, client-owned and change-controlled estates. Diagnostic steps go out over a private git repo, an on-site operator or an unattended runner executes them, and the logs come back the same way with every line timestamped in UTC.

* [Sherlocks.ai](https://www.sherlocks.ai)

* [Resolve.ai](https://resolve.ai/)

* [Deductive.ai](https://www.deductive.ai/)

* [Ingero](https://github.com/ingero-io/ingero) - eBPF-based GPU causal observability agent. Traces CUDA APIs and host kernel events to build causal chains explaining GPU latency. Includes MCP server for AI-assisted incident investigation.

* [metoro.io](https://metoro.io/)

* [Ops AI by Middleware](https://middleware.io/product/ops-ai/)

* [Anyshift](https://www.anyshift.io/) - AI SRE built on a versioned resource graph of your infrastructure, for root cause analysis and predicting the impact of changes before they ship.

* [KnoxOps](https://knoxops.app/?invite_token=GITHUB26) - AI-native ops agent that gives agents production-safe execution with human review and a built-in knowledge graph.

* [NudgeBee](https://nudgebee.com) - Unified AI agentic platform for cloud ops, offering AI SRE, AI FinOps, AI Kubernetes Ops, and AI CloudOps assistants that automate alert triage, root-cause analysis, and cost optimization.

* [Hyground](https://hyground.ai) - Self-hosted AI SRE agent that goes beyond on-call incident resolution.

* [Corelayer](https://corelayer.com) - Agentic production support platform that proactively investigates, resolves, and prevents incidents, with BYOC and on-prem support for regulated environments.

* [Nexus Shell Agent Bridge](https://nexusshell.app/agent-bridge) - Local macOS MCP bridge that lets approved AI agents operate visible SSH terminals, transfer files, and inspect read-only server and network monitoring without receiving stored passwords or private keys.

* [Aiden for SRE](https://stackgen.com/product/aiden-for-sre) - Aiden that acts autonomously on recurring incidents and works complex ones alongside your team through to resolution — policy-bound and fully auditable.

* [Aient AI](https://aient.ai) - OpenTelemetry-native AI SRE agent that ingests logs, metrics, and traces, groups errors into problems, investigates root cause, and opens a GitHub pull request with a fix, then monitors production telemetry for recurrence. Integrates with GitHub, Slack, and Linear, and exposes a hosted MCP server. ([docs](https://docs.aient.ai))

## Related Lists

* [Awesome Performance Engineering](https://github.com/be-next/awesome-performance-engineering) ⭐ 38 | 🐛 0 | 📅 2026-10-06 - Observability and performance testing tools and resources for performance engineering.
* [Wyrcan Engineering Roadmap](https://github.com/Wyrcan-io/roadmap) ⭐ 17 | 🐛 0 | 🌐 HTML | 📅 2026-09-10 - Text-first 12-stage curriculum covering systems, Linux, SRE observability, failure testing, and incident postmortems.

## Stargazers over time

[![Stargazers over time](https://starchart.cc/SquadcastHub/awesome-sre-tools.svg)](https://starchart.cc/SquadcastHub/awesome-sre-tools)

## Licence

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a [Creative Commons Attribution 4.0 International
License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/

[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png

[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-21._
