# Changelog - @tupynambalucas-dev/k8s

<!-- changelog-start -->

## [1.1.0](https://github.com/tupynambalucas-dev/platform/compare/k8s-v1.0.0...k8s-v1.1.0) (2026-11-28)


### Features & Capabilities

* **corporate:** configure corporate workloads, multi-cluster overlays, and skaffold development pipeline ([f59bb7c](https://github.com/tupynambalucas-dev/platform/commit/f59bb7c6768e7012da4fc208f51d6a314b643325))
* **cortex-gateway:** register google-workspace and appsheet mcp targets ([f32a359](https://github.com/tupynambalucas-dev/platform/commit/f32a35954ff8d0e18005e421994a8d95575107e4))
* **cortex:** eliminate mcp services in favor of zero-dockerfile manifests ([0472423](https://github.com/tupynambalucas-dev/platform/commit/04724237640bc73d36469d4534542d157519bf59))
* **hub:** align studio and cortex packages with enterprise scopes ([a0f878c](https://github.com/tupynambalucas-dev/platform/commit/a0f878cfd9ddb6ccef788864937d5ce8603ea6d2))
* **k8s:** document github app machine identity variables in env template ([#40](https://github.com/tupynambalucas-dev/platform/issues/40)) ([cd5c995](https://github.com/tupynambalucas-dev/platform/commit/cd5c99528e156acadc40352d24ad1d5909454269))
* **k8s:** harden cluster mcp manifests and restore playwright service ([#36](https://github.com/tupynambalucas-dev/platform/issues/36)) ([24a2798](https://github.com/tupynambalucas-dev/platform/commit/24a2798f9cc206eb12a960bf12dcd2e7b70b65c2))
* **observability:** add Grafana, Loki, Tempo, and Prometheus configurations ([bc6c5c1](https://github.com/tupynambalucas-dev/platform/commit/bc6c5c19ca6868842dd8cca879d679521e297d93))


### Bug Fixes & Corrections

* remove hardcoded env domains from memory ingress and add dev patch ([0c4508f](https://github.com/tupynambalucas-dev/platform/commit/0c4508fc96489e515ee833c663af1380d8aced91))


### Refactoring & Internal Architecture

* **hooks:** migrate from husky to lefthook and purge lint-staged ([#55](https://github.com/tupynambalucas-dev/platform/issues/55)) ([1472f5b](https://github.com/tupynambalucas-dev/platform/commit/1472f5b573bf3335eea43f4b70928b911e10ebcf))
* **k8s:** decommission mcp-playwright from cluster infrastructure ([#35](https://github.com/tupynambalucas-dev/platform/issues/35)) ([d010a62](https://github.com/tupynambalucas-dev/platform/commit/d010a625856fcf944fa1513f9cf9d7f8ac2777d8))
* **k8s:** implement multi-cluster isolation, tunnel separation, and workspace readiness ([113373b](https://github.com/tupynambalucas-dev/platform/commit/113373b775d562de86ba93d3cc394f8a929bed20))
* **k8s:** separate helm and kustomize deployers in skaffold ([bec0ecc](https://github.com/tupynambalucas-dev/platform/commit/bec0ecca3312e98c44899359d0c7b347d7a2657d))
* **k8s:** standardize github app environment variable names in env template ([#41](https://github.com/tupynambalucas-dev/platform/issues/41)) ([a49c683](https://github.com/tupynambalucas-dev/platform/commit/a49c6835e8d6e5a5904d46f2dd34ade0179480a9))


### Documentation & Specifications

* **agents:** enforce exact directory name for bounded contexts ([928f735](https://github.com/tupynambalucas-dev/platform/commit/928f7356f009fe7184e3d0790d82adc7b2fd44c3))
* **changelog:** adopt docusaurus isolated link and committers standard ([#58](https://github.com/tupynambalucas-dev/platform/issues/58)) ([0e2e00e](https://github.com/tupynambalucas-dev/platform/commit/0e2e00e17361a08905e1d8e9099c2fd92daaa26e))
* **changelog:** align with docusaurus pull request link format ([#54](https://github.com/tupynambalucas-dev/platform/issues/54)) ([15deb5a](https://github.com/tupynambalucas-dev/platform/commit/15deb5ad395ba516fbe154e0e071dfbb9ad1b977))
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
* **plans:** consolidate enterprise architecture artifacts, roadmap, and tunnel strategy ([4b96884](https://github.com/tupynambalucas-dev/platform/commit/4b9688401caf042aa340754e7b37ecd1a861e4c8))


### Maintenance

* **arch:** finalize enterprise infrastructure refactor and corporate workloads ([8777896](https://github.com/tupynambalucas-dev/platform/commit/877789606ff74ab48efaa24ed52ae2086a36a8fd))
* complete k8s directory restructuring and context updates ([d2b464c](https://github.com/tupynambalucas-dev/platform/commit/d2b464c9f6480ec2d395ef14cd536667d68e812d))
* **env:** migrate CI_BOT_APP placeholders to AUTOMATION_APP and GUARDIAN_APP ([#60](https://github.com/tupynambalucas-dev/platform/issues/60)) ([0ca5d55](https://github.com/tupynambalucas-dev/platform/commit/0ca5d55fa6e979d76490f27e23061c7ff58f30a7))
* **governance:** align licenses, k8s plugin, and redact secrets ([#33](https://github.com/tupynambalucas-dev/platform/issues/33)) ([0a759bd](https://github.com/tupynambalucas-dev/platform/commit/0a759bd8ff0db2b418d2ba091e59975a4f6a128c))
* **repo:** restructure platform, studio, cortex into hub and rename infrastructure to k8s ([05b3b0a](https://github.com/tupynambalucas-dev/platform/commit/05b3b0aae886727214c1cee3e3cb6d2d172e3042))
* **sync:** merge main into develop resolving legacy readme conflict ([14683bd](https://github.com/tupynambalucas-dev/platform/commit/14683bdc6b962c95eed3e9bba2c12030d60ee0cb))

## [1.1.0] - 2026-11-20

### Features & Capabilities

- [#40](https://github.com/tupynambalucas-dev/platform/pull/40) feat(k8s): document github app machine identity variables in env template ([@tupynambalucas](https://github.com/tupynambalucas))
- [#36](https://github.com/tupynambalucas-dev/platform/pull/36) feat(k8s): harden cluster mcp manifests and restore playwright service ([@tupynambalucas](https://github.com/tupynambalucas))

### Refactoring & Internal Architecture

- [#41](https://github.com/tupynambalucas-dev/platform/pull/41) refactor(k8s): standardize github app environment variable names in env template ([@tupynambalucas](https://github.com/tupynambalucas))
- [#35](https://github.com/tupynambalucas-dev/platform/pull/35) refactor(k8s): decommission mcp-playwright from cluster infrastructure ([@tupynambalucas](https://github.com/tupynambalucas))

### Committers: 1

- Tupynambá Lucas V. R. ([@tupynambalucas](https://github.com/tupynambalucas))

---

## [1.0.0] - 2026-10-03

### Features & Capabilities

- [49ae855](https://github.com/tupynambalucas-dev/platform/commit/49ae855) feat(k8s): establish Helm manifests, Traefik ingress routes, and Infisical secret operator ([@tupynambalucas](https://github.com/tupynambalucas))

### Committers: 1

- Tupynambá Lucas V. R. ([@tupynambalucas](https://github.com/tupynambalucas))
