# Changelog - @tupynambalucas-dev/platform

<!-- changelog-start -->

## [1.1.0](https://github.com/tupynambalucas-dev/platform/compare/platform-v1.0.0...platform-v1.1.0) (2026-11-28)


### Features & Capabilities

* Add architecture plan for native Linux migration using Docker Engine, k3d, and Headlamp ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* Add portal configuration file for project-specific constants ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* Add release notes for v1.0.0 and update localization files for improved clarity and consistency ([f95106a](https://github.com/tupynambalucas-dev/platform/commit/f95106a53e8142cb8a647b36769ae2f8d3db1dfa))
* **agents:** consume agent-mesh umbrella package via node_modules ([#43](https://github.com/tupynambalucas-dev/platform/issues/43)) ([7c903be](https://github.com/tupynambalucas-dev/platform/commit/7c903bee0e6b4d2f43b174f41c2635774188bc0b))
* **corporate:** configure corporate workloads, multi-cluster overlays, and skaffold development pipeline ([f59bb7c](https://github.com/tupynambalucas-dev/platform/commit/f59bb7c6768e7012da4fc208f51d6a314b643325))
* **corporate:** migrate to [@tupynambalucas-dev](https://github.com/tupynambalucas-dev) corporate package scopes ([bb558a1](https://github.com/tupynambalucas-dev/platform/commit/bb558a1dbfce1bb0542197f05f008c526b888829))
* **cortex-gateway:** register google-workspace and appsheet mcp targets ([f32a359](https://github.com/tupynambalucas-dev/platform/commit/f32a35954ff8d0e18005e421994a8d95575107e4))
* **cortex:** eliminate mcp services in favor of zero-dockerfile manifests ([0472423](https://github.com/tupynambalucas-dev/platform/commit/04724237640bc73d36469d4534542d157519bf59))
* **cortex:** initialize cortex mcp packages workspace directory ([c0f6463](https://github.com/tupynambalucas-dev/platform/commit/c0f64636b247ba4b752acb29eb2b9ef3221d4891))
* Create migration plan for native Linux workspace using WSL2 and Podman ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* Establish plugin-expert skill for creating and updating Antigravity plugins ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* **hub:** align studio and cortex packages with enterprise scopes ([a0f878c](https://github.com/tupynambalucas-dev/platform/commit/a0f878cfd9ddb6ccef788864937d5ce8603ea6d2))
* implement collections architecture refactoring plan ([05a6337](https://github.com/tupynambalucas-dev/platform/commit/05a6337b5ae4d3ca5a4e486b07b89ea687d7ff64))
* Implement variables refactor plan to eliminate global config and replace tokens with actual values ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* Introduce cortex-fallback plugin for local execution of MCPs when AgentGateway is offline ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* **k8s:** document github app machine identity variables in env template ([#40](https://github.com/tupynambalucas-dev/platform/issues/40)) ([cd5c995](https://github.com/tupynambalucas-dev/platform/commit/cd5c99528e156acadc40352d24ad1d5909454269))
* **k8s:** harden cluster mcp manifests and restore playwright service ([#36](https://github.com/tupynambalucas-dev/platform/issues/36)) ([24a2798](https://github.com/tupynambalucas-dev/platform/commit/24a2798f9cc206eb12a960bf12dcd2e7b70b65c2))
* **kb:** add i18n-json translation tracking and unpacking architecture for react UI ([f1af787](https://github.com/tupynambalucas-dev/platform/commit/f1af78760b5dcd660107c7b25d771fe4469a3040))
* **observability:** add Grafana, Loki, Tempo, and Prometheus configurations ([bc6c5c1](https://github.com/tupynambalucas-dev/platform/commit/bc6c5c19ca6868842dd8cca879d679521e297d93))
* **studio-assets:** update brand marks and clean up vscode tooling ([2bd5ebc](https://github.com/tupynambalucas-dev/platform/commit/2bd5ebcb58068ec4d0b73b641ca7da3ab386b9b0))
* **vscode:** add antigravity cli task to launch in windows terminal via wsl ([9e8f033](https://github.com/tupynambalucas-dev/platform/commit/9e8f033a74071daf32a545ef1abd7e77ce3cc95f))


### Bug Fixes & Corrections

* **ignore:** remove trailing wildcard from .ignore and .rgignore ([#51](https://github.com/tupynambalucas-dev/platform/issues/51)) ([f774ad3](https://github.com/tupynambalucas-dev/platform/commit/f774ad3e09efe1f47f364cf5cde814e2a5c033f7))
* **kb:** map crowdin content types to docusaurus i18n structure to fix translated builds ([733736f](https://github.com/tupynambalucas-dev/platform/commit/733736f61397d011e8b0f10161558b6d59109435))
* remove hardcoded env domains from memory ingress and add dev patch ([0c4508f](https://github.com/tupynambalucas-dev/platform/commit/0c4508fc96489e515ee833c663af1380d8aced91))
* **vscode:** enable deep workspace search indexing without ignore file restrictions ([#34](https://github.com/tupynambalucas-dev/platform/issues/34)) ([37e0606](https://github.com/tupynambalucas-dev/platform/commit/37e060604f1e0e0920de5e40174ae88e811a74c0))


### Refactoring & Internal Architecture

* **.agents:** remove redundant plugins and skills in favor of agent-toolkit ([e7142c9](https://github.com/tupynambalucas-dev/platform/commit/e7142c99c44920dc3c1027209a442d13a2fd7a6d))
* **corporate:** decouple documentation hub and clean up redundant packages ([d711992](https://github.com/tupynambalucas-dev/platform/commit/d71199248c97f9f583633835bbc8036cf48b15d6))
* **cortex:** eliminate redundant packages dir in favor of services ([faaefa4](https://github.com/tupynambalucas-dev/platform/commit/faaefa4597309ff655841e42e480738e629f8221))
* **hooks:** migrate from husky to lefthook and purge lint-staged ([#55](https://github.com/tupynambalucas-dev/platform/issues/55)) ([1472f5b](https://github.com/tupynambalucas-dev/platform/commit/1472f5b573bf3335eea43f4b70928b911e10ebcf))
* **k8s:** decommission mcp-playwright from cluster infrastructure ([#35](https://github.com/tupynambalucas-dev/platform/issues/35)) ([d010a62](https://github.com/tupynambalucas-dev/platform/commit/d010a625856fcf944fa1513f9cf9d7f8ac2777d8))
* **k8s:** implement multi-cluster isolation, tunnel separation, and workspace readiness ([113373b](https://github.com/tupynambalucas-dev/platform/commit/113373b775d562de86ba93d3cc394f8a929bed20))
* **k8s:** separate helm and kustomize deployers in skaffold ([bec0ecc](https://github.com/tupynambalucas-dev/platform/commit/bec0ecca3312e98c44899359d0c7b347d7a2657d))
* **k8s:** standardize github app environment variable names in env template ([#41](https://github.com/tupynambalucas-dev/platform/issues/41)) ([a49c683](https://github.com/tupynambalucas-dev/platform/commit/a49c6835e8d6e5a5904d46f2dd34ade0179480a9))
* **kb:** rename i18n-json to messages for enterprise semantics ([ce10b2f](https://github.com/tupynambalucas-dev/platform/commit/ce10b2f6baf2781bb7d0128d68d296ec5488460a))
* **renderer:** isolate platform readme template to repository scope ([102f138](https://github.com/tupynambalucas-dev/platform/commit/102f1381e8c2fa6e05cb18f0c4f62cb829a74cfb))
* **typescript:** eliminate tsconfig.build and adopt modern solution-style project references ([5a432e8](https://github.com/tupynambalucas-dev/platform/commit/5a432e86e585bdd0914b6adbb431c4f3b5bdcc33))


### Documentation & Specifications

* Add Cortex Fallback Rules documentation for fallback MCP tools usage ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* **agents:** configure umbrella package catalog and docs ([#44](https://github.com/tupynambalucas-dev/platform/issues/44)) ([c155852](https://github.com/tupynambalucas-dev/platform/commit/c15585267ff565e01387526d0127892bb8dd5991))
* **agents:** document plan dual-storage and register plugins ([#48](https://github.com/tupynambalucas-dev/platform/issues/48)) ([a49c373](https://github.com/tupynambalucas-dev/platform/commit/a49c3732cfb00aef6fb7fac334ee9f423dc6cbb3))
* **agents:** enforce .agents/plans storage and clean ignore triad ([#50](https://github.com/tupynambalucas-dev/platform/issues/50)) ([9f2cb1f](https://github.com/tupynambalucas-dev/platform/commit/9f2cb1fc544a8983aed8a3b386dc48b07c375b34))
* **agents:** enforce exact directory name for bounded contexts ([928f735](https://github.com/tupynambalucas-dev/platform/commit/928f7356f009fe7184e3d0790d82adc7b2fd44c3))
* **agents:** update agent router rules, skills, and references for enterprise architecture ([464f8a0](https://github.com/tupynambalucas-dev/platform/commit/464f8a0c09319c686321b0b11034d844163c7a02))
* **architecture:** update context router and navigation references to org ([#59](https://github.com/tupynambalucas-dev/platform/issues/59)) ([0fe9714](https://github.com/tupynambalucas-dev/platform/commit/0fe971441b2100fcb0c7417e2d0e300e9ec685b4))
* **branding:** standardize enterprise brand to tupynambalucas.dev ([5393723](https://github.com/tupynambalucas-dev/platform/commit/5393723fa545a67c6ffc03880a5ff8ad318bcf3e))
* **changelog:** adopt docusaurus isolated link and committers standard ([#58](https://github.com/tupynambalucas-dev/platform/issues/58)) ([0e2e00e](https://github.com/tupynambalucas-dev/platform/commit/0e2e00e17361a08905e1d8e9099c2fd92daaa26e))
* **changelog:** align with docusaurus pull request link format ([#54](https://github.com/tupynambalucas-dev/platform/issues/54)) ([15deb5a](https://github.com/tupynambalucas-dev/platform/commit/15deb5ad395ba516fbe154e0e071dfbb9ad1b977))
* **changelog:** upgrade to keep a changelog format ([#53](https://github.com/tupynambalucas-dev/platform/issues/53)) ([e70334a](https://github.com/tupynambalucas-dev/platform/commit/e70334a87d01ee01fe7c7b90eb4184d97ce10dbc))
* **cortex:** refactor agentgateway reference to a single overview file ([9d57e11](https://github.com/tupynambalucas-dev/platform/commit/9d57e118ba7b30e88772cefbc85dd87632363e5d))
* **cortex:** restructure agentgateway reference to a directory with category index ([af7d9b6](https://github.com/tupynambalucas-dev/platform/commit/af7d9b61a388e4ac747c535b05e29f5224b0fcef))
* Create Antigravity plugin reference documentation detailing structure and management ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* Define complete specification for Agent Skills format and structure ([3b64505](https://github.com/tupynambalucas-dev/platform/commit/3b64505c01081e4fa6964329188949e15e5ed529))
* dynamically update code of conduct ([807b215](https://github.com/tupynambalucas-dev/platform/commit/807b215832eea6f1785cd1753b1530c3fec684ce))
* dynamically update code of conduct ([1f62223](https://github.com/tupynambalucas-dev/platform/commit/1f62223f422c6af2931afefbce534ad2a79bf501))
* dynamically update code of conduct ([155f058](https://github.com/tupynambalucas-dev/platform/commit/155f05890baa136ba0ccaec08e9491b577f7e283))
* dynamically update code of conduct ([7c408b6](https://github.com/tupynambalucas-dev/platform/commit/7c408b6bafa32c61c6f2407fd7b6736fa89758c9))
* dynamically update code of conduct ([29556b8](https://github.com/tupynambalucas-dev/platform/commit/29556b8e2172b8dab174964d2dc109549af9e55b))
* dynamically update code of conduct ([8da9690](https://github.com/tupynambalucas-dev/platform/commit/8da96907b599dc32e681da7e17996eb3c29210f3))
* dynamically update code of conduct ([bd3621a](https://github.com/tupynambalucas-dev/platform/commit/bd3621a6760b741062a82f3d2a77f92335ffd14e))
* dynamically update code of conduct ([59c73e3](https://github.com/tupynambalucas-dev/platform/commit/59c73e32181750a377c4ed112c55a79437b87e55))
* dynamically update license ([6c0c6f8](https://github.com/tupynambalucas-dev/platform/commit/6c0c6f86775862c529d5dabfc9b6719c629eff4e))
* dynamically update license ([da5ff50](https://github.com/tupynambalucas-dev/platform/commit/da5ff50e19f2a964ad2dedc07e4c371b23b5fc19))
* dynamically update license ([3908928](https://github.com/tupynambalucas-dev/platform/commit/3908928cc9e6070e34ce4a8a063188fdbb97dc4c))
* dynamically update license ([46979aa](https://github.com/tupynambalucas-dev/platform/commit/46979aafc8d11f0b2197002cdb59bbaece3f19c5))
* dynamically update license ([4174f5e](https://github.com/tupynambalucas-dev/platform/commit/4174f5ea46c316b820be6c59ee27a375bf0f7789))
* dynamically update license ([7bb6539](https://github.com/tupynambalucas-dev/platform/commit/7bb653969e57b3c80f89d1a7d26ebfc27d0e76bb))
* dynamically update license ([752cc13](https://github.com/tupynambalucas-dev/platform/commit/752cc138cd063683fe89f5ed9971696aa9528b75))
* dynamically update license ([f6f7016](https://github.com/tupynambalucas-dev/platform/commit/f6f70165f14975f86192e62c513ca186c2df2b3e))
* dynamically update root profile readme ([f6c6eae](https://github.com/tupynambalucas-dev/platform/commit/f6c6eaea43b53eac80fc2e56daae10e3e04322c1))
* dynamically update root profile readme ([bac4502](https://github.com/tupynambalucas-dev/platform/commit/bac4502efebf1f4fd804cfbecdb44bf2900b44dd))
* dynamically update root profile readme ([b6323d3](https://github.com/tupynambalucas-dev/platform/commit/b6323d3dd71d2d26279e486486356d6711ceb930))
* dynamically update root profile readme ([55b24fd](https://github.com/tupynambalucas-dev/platform/commit/55b24fdc34b5365386cd3829bc01c6395255f070))
* dynamically update root profile readme ([90b052a](https://github.com/tupynambalucas-dev/platform/commit/90b052a6d17feff6d77cbead3550c9f140a189f4))
* dynamically update root profile readme ([eb056a8](https://github.com/tupynambalucas-dev/platform/commit/eb056a874acb768b46cd20b659ffb9a6638c8274))
* dynamically update root profile readme ([bf54a65](https://github.com/tupynambalucas-dev/platform/commit/bf54a650af4fd777e125d23dd0b5a37035d9ebca))
* dynamically update root profile readme ([b127895](https://github.com/tupynambalucas-dev/platform/commit/b127895ad6df4ade45d1a55f342a999f9db73a5d))
* formalize explicit bounded context constraints in AGENTS.md ([3f6c1fb](https://github.com/tupynambalucas-dev/platform/commit/3f6c1fbbd5b8c429f0ea0418c2b32e27859be846))
* **k8s:** flatten gitops-architecture into k8s/references ([e2ff207](https://github.com/tupynambalucas-dev/platform/commit/e2ff2078bcd4991d161892601cbf2613786e2d88))
* **k8s:** rename references to reference and update plugin ([74ab967](https://github.com/tupynambalucas-dev/platform/commit/74ab967234803424f3bb10767d3069a5bc5ac87d))
* **k8s:** revert reference directory rename ([90aa841](https://github.com/tupynambalucas-dev/platform/commit/90aa841571943a26ef42fe10683004fe9184120b))
* **k8s:** scaffold gitops-architecture docs and k8s-expert plugin ([aa10cd5](https://github.com/tupynambalucas-dev/platform/commit/aa10cd5b3a89a629d1e2ef1189ff1cca39d4069f))
* **kb:** rewrite knowledge-base overview to reflect current architecture and gitops flow ([d3336f3](https://github.com/tupynambalucas-dev/platform/commit/d3336f3a79ab4f8994c85415a8722a4f0dd0e82c))
* **plans:** add enterprise repository transfer and local workspace runbook ([bd0f358](https://github.com/tupynambalucas-dev/platform/commit/bd0f358946606db3d1aa7d1448f42be6338195b4))
* **plans:** configure dedicated distro tupynambalucasdev-ubuntu and in-wsl antigravity cli ([08a2eaf](https://github.com/tupynambalucas-dev/platform/commit/08a2eaf1c6cc2a2299dd276b0c9a2664346f234d))
* **plans:** consolidate enterprise architecture artifacts, roadmap, and tunnel strategy ([4b96884](https://github.com/tupynambalucas-dev/platform/commit/4b9688401caf042aa340754e7b37ecd1a861e4c8))
* **plans:** document cluster lifecycle stop and resume procedures after reboot ([7e63d59](https://github.com/tupynambalucas-dev/platform/commit/7e63d59ae57df147c31feb9def1a671a8c0b772e))
* **plans:** document creative assets interoperability with windows adobe tools ([5ad99f5](https://github.com/tupynambalucas-dev/platform/commit/5ad99f5f6429c6c12a8e00decfe17dc7c5fe8fde))
* **plans:** link migration runbook at root of plans directory ([5b7e2c1](https://github.com/tupynambalucas-dev/platform/commit/5b7e2c10f580d7e9da0e1c2fe01400df3cbd7629))
* **plans:** pin k3d api ports and configure windows freelens kubeconfig sync ([ad7b4e0](https://github.com/tupynambalucas-dev/platform/commit/ad7b4e080769509a262b1caba34bb51b980cd54a))
* **plans:** unify ubuntu setup and readiness gates into single master runbook ([b9bf605](https://github.com/tupynambalucas-dev/platform/commit/b9bf6059cc88a0e393d9e8790f35a5616c7d9189))
* **plans:** update repository migration checklist to completed status ([392ae3b](https://github.com/tupynambalucas-dev/platform/commit/392ae3bcc2e0d1b65aaa6fd2a960ed85d8c9b030))
* **platform:** update root readme and agents context with secret governance ([9cc9e36](https://github.com/tupynambalucas-dev/platform/commit/9cc9e365a50e9cb7145243eecf213f6e8bcd3b1f))
* **portal:** update architecture guides and bounded context documentation ([8d2763e](https://github.com/tupynambalucas-dev/platform/commit/8d2763e22dfe9ae912d6df11308e33036343b13e))
* **readme:** standardize platform monorepo root documentation ([#49](https://github.com/tupynambalucas-dev/platform/issues/49)) ([bf8a3c8](https://github.com/tupynambalucas-dev/platform/commit/bf8a3c86f3db4ddc4fab40c4164f6dd74046a411))
* restructure platform README to focus exclusively on monorepo architecture ([2c3db07](https://github.com/tupynambalucas-dev/platform/commit/2c3db0791c02a6ad1df2b018728e4e3fb6adf1d9))
* update root CHANGELOG.md and ROADMAP.md [skip ci] ([e2f40ce](https://github.com/tupynambalucas-dev/platform/commit/e2f40ce33908e2a6f723bce355419c28ff237bcd))
* update root CHANGELOG.md and ROADMAP.md [skip ci] ([a7687e0](https://github.com/tupynambalucas-dev/platform/commit/a7687e0ec76d9fa9bd6355282bc32aa5bb078c0c))
* update root CHANGELOG.md and ROADMAP.md [skip ci] ([1a13ac9](https://github.com/tupynambalucas-dev/platform/commit/1a13ac941330648fafcf1ca1ec6f338bf52c6721))


### Maintenance

* **agents:** install agent-toolkit dependency and register plugin ([b7bddc6](https://github.com/tupynambalucas-dev/platform/commit/b7bddc65d4ec740d89d8c3c42b18997e88420f09))
* **agents:** prune deprecated plans and reference artifacts ([#37](https://github.com/tupynambalucas-dev/platform/issues/37)) ([167a8cb](https://github.com/tupynambalucas-dev/platform/commit/167a8cbf411716a0a6d03962897720558eb0f1b8))
* **arch:** finalize enterprise infrastructure refactor and corporate workloads ([8777896](https://github.com/tupynambalucas-dev/platform/commit/877789606ff74ab48efaa24ed52ae2086a36a8fd))
* complete k8s directory restructuring and context updates ([d2b464c](https://github.com/tupynambalucas-dev/platform/commit/d2b464c9f6480ec2d395ef14cd536667d68e812d))
* **deps:** bump follow-redirects from 1.16.1 to 1.16.2 ([#39](https://github.com/tupynambalucas-dev/platform/issues/39)) ([70bafa8](https://github.com/tupynambalucas-dev/platform/commit/70bafa8ddfa52a84020b43e7196d155d75e41648))
* **deps:** bump mongoose from 9.11.1 to 9.11.4 ([#46](https://github.com/tupynambalucas-dev/platform/issues/46)) ([1f8fd2a](https://github.com/tupynambalucas-dev/platform/commit/1f8fd2ae4ac92ebe9db9a097152c4fcb36e4e60e))
* **deps:** sync pnpm-lock.yaml lockfile ([#38](https://github.com/tupynambalucas-dev/platform/issues/38)) ([18134ee](https://github.com/tupynambalucas-dev/platform/commit/18134ee7ec8f142576fee3f125596b35b6273b78))
* **docker:** standardize multi-stage dev and prod profiles across services ([436ad64](https://github.com/tupynambalucas-dev/platform/commit/436ad642ca188abc9860d3dec1361a3ec3ae5050))
* **docs:** enforce backup strategy and git mv rules in migration plan ([4c36dda](https://github.com/tupynambalucas-dev/platform/commit/4c36dda836e521117035b974d691434cae4c5ba7))
* **docs:** enhance enterprise architecture plans with skaffold v2 and k3d best practices ([ffba897](https://github.com/tupynambalucas-dev/platform/commit/ffba8978268316bde4929779334322196e65eaa8))
* **docs:** update root AGENTS.md context routing ([a748b5d](https://github.com/tupynambalucas-dev/platform/commit/a748b5d7a0a5f89d1c92f53910e148bc0bfb6029))
* **env:** migrate CI_BOT_APP placeholders to AUTOMATION_APP and GUARDIAN_APP ([#60](https://github.com/tupynambalucas-dev/platform/issues/60)) ([0ca5d55](https://github.com/tupynambalucas-dev/platform/commit/0ca5d55fa6e979d76490f27e23061c7ff58f30a7))
* **git:** adopt lefthook for parallel pre-commit and commitlint ([#52](https://github.com/tupynambalucas-dev/platform/issues/52)) ([60bf619](https://github.com/tupynambalucas-dev/platform/commit/60bf619278d0f507d924bebcbe8ff22cdc4dd414))
* **git:** relocate husky hooks to platform root ([44dc004](https://github.com/tupynambalucas-dev/platform/commit/44dc004498f1af02f968eae2ee0389845d7099f1))
* **governance:** align licenses, k8s plugin, and redact secrets ([#33](https://github.com/tupynambalucas-dev/platform/issues/33)) ([0a759bd](https://github.com/tupynambalucas-dev/platform/commit/0a759bd8ff0db2b418d2ba091e59975a4f6a128c))
* **governance:** merge develop into main for github-flow transition ([cc9c6aa](https://github.com/tupynambalucas-dev/platform/commit/cc9c6aa580d3a2b0ed37a7b8281c2f7f92b67f19))
* **ignore:** standardize plans container ignore and indexing policy ([#45](https://github.com/tupynambalucas-dev/platform/issues/45)) ([b7ca7d8](https://github.com/tupynambalucas-dev/platform/commit/b7ca7d8ae796ee8f728b2c1620b7884d8e329049))
* **l10n:** completely remove localized files to reset translation state ([44fd868](https://github.com/tupynambalucas-dev/platform/commit/44fd868d960179548e7aeb376fd967cdd904ae44))
* **l10n:** optimize crowdin PR and commit messages ([e88392a](https://github.com/tupynambalucas-dev/platform/commit/e88392a04c164a98739739aae2d3ed22cc60ecf5))
* **l10n:** remove strict mdx type to allow default markdown parsing ([b8eede2](https://github.com/tupynambalucas-dev/platform/commit/b8eede2695ef3dbd410b196dbfb79d1be1e95f7b))
* **l10n:** set crowdin parser type to chrome for docusaurus json messages ([2382f21](https://github.com/tupynambalucas-dev/platform/commit/2382f213cb0a0a3624c7c13913f601915e7ba4b6))
* **l10n:** synchronize translations ([890b7a5](https://github.com/tupynambalucas-dev/platform/commit/890b7a5baf62dd6a5f334e8cf2843c15e00204be))
* **l10n:** synchronize translations ([79c357f](https://github.com/tupynambalucas-dev/platform/commit/79c357f29c6901120539f9103b4cf9e5b899bbcd))
* **l10n:** synchronize translations ([6c02689](https://github.com/tupynambalucas-dev/platform/commit/6c0268933ac54e34cc05045977732cb64074f767))
* **l10n:** synchronize translations ([03d4a1d](https://github.com/tupynambalucas-dev/platform/commit/03d4a1d9b16e435636429a09654f5ffa77d6e0fa))
* **mesh:** point agent dependencies to agent-mesh ([8aa84e1](https://github.com/tupynambalucas-dev/platform/commit/8aa84e1b07807511cb263f968fb4c0ebc09ca97e))
* **mesh:** update lockfile for agent-mesh dependency ([edaeefd](https://github.com/tupynambalucas-dev/platform/commit/edaeefd5943dcfac3adccffadcab51c10e32dfdf))
* **plans:** untrack plans and blueprints from git repository ([#47](https://github.com/tupynambalucas-dev/platform/issues/47)) ([f5bd4a7](https://github.com/tupynambalucas-dev/platform/commit/f5bd4a735ea8ed00d71a08a5ca3c92fd3825ba72))
* **pnpm:** update lockfile after mcp service removal ([695ca32](https://github.com/tupynambalucas-dev/platform/commit/695ca328eda3223f2ef8618ed5bf07d9e0ed3555))
* **portal:** align portal homepage components and tooling with design system ([e9973ac](https://github.com/tupynambalucas-dev/platform/commit/e9973aceefb465b788f520352db66d8e8b66ec24))
* **release:** deploy automated release-please workflow with ci-bot app token ([#56](https://github.com/tupynambalucas-dev/platform/issues/56)) ([130da43](https://github.com/tupynambalucas-dev/platform/commit/130da43786af829f04b9b792e5970efbe7c9f709))
* remove backup gitlink, update gitignore, and add studio logo marks ([2a0d980](https://github.com/tupynambalucas-dev/platform/commit/2a0d980ec4296f27786db86fcf6d820cf6ce3b16))
* **repo:** move hub to corporate and merge knowledge-base ([3830e9f](https://github.com/tupynambalucas-dev/platform/commit/3830e9f44ca0f5cd646fd665b3660c5e29f8d68d))
* **repo:** restructure platform, studio, cortex into hub and rename infrastructure to k8s ([05b3b0a](https://github.com/tupynambalucas-dev/platform/commit/05b3b0aae886727214c1cee3e3cb6d2d172e3042))
* **repo:** update lockfile and add untracked docusaurus assets ([7537ad1](https://github.com/tupynambalucas-dev/platform/commit/7537ad104640c97429224f5761a116c8b6a4ddfe))
* **repo:** update root architecture scripts, governance plugins and lockfile ([072a02a](https://github.com/tupynambalucas-dev/platform/commit/072a02a29de0219f96fb30bd306726d77c95cd71))
* **repo:** update workspace mapping for hub, corporate, and k8s ([2c5f675](https://github.com/tupynambalucas-dev/platform/commit/2c5f6759371bd56142015934188db5d0f2848ad1))
* **sync:** merge main into develop resolving legacy readme conflict ([14683bd](https://github.com/tupynambalucas-dev/platform/commit/14683bdc6b962c95eed3e9bba2c12030d60ee0cb))
* **workflows:** integrate ci-bot github app token ([#42](https://github.com/tupynambalucas-dev/platform/issues/42)) ([734b818](https://github.com/tupynambalucas-dev/platform/commit/734b818ff8340a2ff8bc5c0647b72d3d2432a170))


### Dependencies

* The following workspace dependencies were updated
  * devDependencies
    * @tupynambalucas-dev/shared-config bumped to 1.1.0

## [1.1.0] - 2026-11-20

### Features & Capabilities

- `platform`
  - [#43](https://github.com/tupynambalucas-dev/platform/pull/43) feat(agents): consume agent-mesh umbrella package via node_modules ([@tupynambalucas](https://github.com/tupynambalucas))
- `k8s`
  - [#40](https://github.com/tupynambalucas-dev/platform/pull/40) feat(k8s): document github app machine identity variables in env template ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#36](https://github.com/tupynambalucas-dev/platform/pull/36) feat(k8s): harden cluster mcp manifests and restore playwright service ([@tupynambalucas](https://github.com/tupynambalucas))

### Refactoring & Internal Architecture

- `k8s`
  - [#41](https://github.com/tupynambalucas-dev/platform/pull/41) refactor(k8s): standardize github app environment variable names in env template ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#35](https://github.com/tupynambalucas-dev/platform/pull/35) refactor(k8s): decommission mcp-playwright from cluster infrastructure ([@tupynambalucas](https://github.com/tupynambalucas))

### Documentation & Specifications

- `platform`
  - [#44](https://github.com/tupynambalucas-dev/platform/pull/44) docs(agents): configure umbrella package catalog and docs ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#48](https://github.com/tupynambalucas-dev/platform/pull/48) docs(agents): document plan dual-storage and register plugins ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#49](https://github.com/tupynambalucas-dev/platform/pull/49) docs(readme): standardize platform monorepo root documentation ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#50](https://github.com/tupynambalucas-dev/platform/pull/50) docs(agents): enforce .agents/plans storage and clean ignore triad ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#53](https://github.com/tupynambalucas-dev/platform/pull/53) docs(changelog): upgrade to keep a changelog format ([@tupynambalucas](https://github.com/tupynambalucas))

### Bug Fixes & Corrections

- `platform`
  - [#34](https://github.com/tupynambalucas-dev/platform/pull/34) fix(vscode): enable deep workspace search indexing without ignore file restrictions ([@tupynambalucas](https://github.com/tupynambalucas))
  - [#51](https://github.com/tupynambalucas-dev/platform/pull/51) fix(ignore): remove trailing wildcard from .ignore and .rgignore ([@tupynambalucas](https://github.com/tupynambalucas))

### Committers: 1

- Tupynambá Lucas V. R. ([@tupynambalucas](https://github.com/tupynambalucas))

---

## [1.0.0] - 2026-10-03

Welcome to the foundational release of `platform` (`v1.0.0`). This milestone establishes our core architecture, localization infrastructure, and unifies our content strategy.

### Features & Capabilities

- `corporate-web`
  - [49ae855](https://github.com/tupynambalucas-dev/platform/commit/49ae855) feat(content): unify content architecture, merging changelog and blog into a single chronological timeline ([@tupynambalucas](https://github.com/tupynambalucas))
  - [531ad0d](https://github.com/tupynambalucas-dev/platform/commit/531ad0d) feat(localization): enterprise localization pipeline extracting Docusaurus React UI strings into messages/ folder ([@tupynambalucas](https://github.com/tupynambalucas))
  - [dbcba51](https://github.com/tupynambalucas-dev/platform/commit/dbcba51) feat(i18n): deploy unified plugin to automatically unpack Crowdin translations directly into native locale structure ([@tupynambalucas](https://github.com/tupynambalucas))

### Refactoring & Internal Architecture

- `platform`
  - [8a18075](https://github.com/tupynambalucas-dev/platform/commit/8a18075) refactor(crowdin): map Crowdin properties for Docusaurus JSON (`type: chrome`), preventing translators from modifying system keys ([@tupynambalucas](https://github.com/tupynambalucas))

### Committers: 1

- Tupynambá Lucas V. R. ([@tupynambalucas](https://github.com/tupynambalucas))

[1.1.0]: https://github.com/tupynambalucas-dev/platform/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/tupynambalucas-dev/platform/releases/tag/v1.0.0
