# Changelog

<!-- insert new changelog below this comment -->

## [Unreleased]

### Added

- feat(core): add `specify core info --json` command that emits the baked-in commands, templates, and scripts as a deterministic JSON inventory (#4215)

## [1.0.3] - 2026-09-01

### Changed

- fix(workflows): reject malformed step config on remove (#4095)
- fix(workflows): reject malformed workflow config on remove (#4096)
- fix(events): skip unreadable extension manifests (#4089)
- docs(extensions): fix private catalog FAQ command (#4373)
- [extension] Add Vurnix Honest Gate extension to community catalog (#4388)
- fix(presets): fail closed on unreadable provenance (#4092)
- docs: explain how Spec Kit dogfoods itself (#4381)
- add --require-spec to check-prerequisites (#4367)
- fix(ci): harden PyPI release tag handling (#4386)
- fix(github-http): reject malformed explicit URL ports (#4372)
- fix: scaffold extension config when installing via bundler (#4285)
- fix: reject unknown setup-plan arguments (#4371)
- feat(docker-agent): add Docker Agent integration (#4302)
- fix(workflows): reject a condition that is spliced into text, not evaluated (#4292)
- fix(bundler): pass explicit workflow_add options from bundle install (#4284)
- test(bundle): join across wrap points in the build output-path assertion (#4280)
- chore(deps): bump the codeql-action group with 2 updates (#4357)
- [extension] Update Spec Kit Figma extension to v3.1.1 (#4377)
- fix(presets): reject falsy non-mapping catalog roots (#4088)
- chore: release 1.0.2, begin 1.0.3.dev0 development (#4379)

## [1.0.2] - 2026-08-31

### Changed

- [extension] Add Jira Mirror extension to community catalog (#4376)
- [extension] Add AgentDocx SpecKit V2 extension to community catalog (#4369)
- fix(bundler): reject non-string catalog entry tag members (#4318)
- fix(auth): reject malformed URL ports before credential matching (#4362)
- fix: decode feature.json as UTF-8 in Windows PowerShell (#4359)
- fix(events): stop falling back to a fake "pwsh" argv when no launcher exists (#4340)
- Add Pre-Spec Cards extension to community catalog (#4365)
- docs(workflows): document Python init script support (#4331)
- fix(presets): validate catalog URL port, not just hostname (#4341)
- Add Verified Codebase Context preset to community catalog (#4344)
- fix(events): stop `event run` crashing on every piped stdin payload (#4326)
- Add Taco Review extension to community catalog (#4322)
- Update SpecKit Grill Me extension to v1.0.1 (#4317)
- [extension] Update BDD extension to v1.0.3 (#4299)
- Update Parallel Autonomous Run Governance preset to v0.2.6 (#4304)
- Update SpecAssay bundle to v0.4.12 (#4257)
- Update SpecAssay preset to v0.4.12 (#4256)
- Update Archive Extension to v1.3.0 (#4298)
- Update Reconcile extension to v1.2.1 (#4297)
- chore: release 1.0.1, begin 1.0.2.dev0 development (#4266)

## [1.0.1] - 2026-08-21

### Changed

- docs: flatten project history navigation (#4265)
- docs: use Spec Kit branding on documentation site (#4264)
- docs: add existing project adoption guide (#4263)
- docs: add project history page (#4262)
- docs: mark Spec Kit's first anniversary (#4260)
- docs: add workflow quickstarts (#4258)
- chore(deps): bump astral-sh/setup-uv from 9.0.0 to 10.0.1 (#4244)
- Update SpecAssay Check extension to v0.4.12 (#4254)
- fix(workflows): require a 'cases' block on switch steps (#4144)
- fix(workflows): strip the resolved value before matching switch cases (#4143)
- fix(bundler): reject non-string manifest list members (#4091)
- fix(presets): reject non-mapping catalog mutations (#4094)
- fix(workflows): stop offering a condition correction that inverts it (#4230)
- fix: use chunked read for integration and preset manifest hash (#3843)
- docs: update landing page stats for 1.0.0 (#4251)
- Add Azure Cosmos DB extension to community catalog (#4247)
- chore(deps): bump actions/checkout from 6.0.3 to 7.0.1 (#4243)
- chore(deps): bump actions/setup-node from 6.4.0 to 7.0.0 (#4242)
- chore(deps): bump the codeql-action group with 2 updates (#4241)
- chore: release 1.0.0, begin 1.0.1.dev0 development (#4246)

## [1.0.0] - 2026-08-21

### Changed

- [extension] Update Security Review extension to v2.0.0 (#4223)
- fix(presets): reject duplicate provides.templates name+type entries (#4191)
- fix(bundler): decode a downloaded (non-zip) bundle manifest as UTF-8 (#4190)
- Update Intake Sequencing Governance preset to v0.2.3 (#4235)
- Update MAQA — Multi-Agent & Quality Assurance extension to v0.1.6 (#4234)
- [bug-fix] Fix qodercli-skills-migration: migrate QodercliIntegration to SkillsIntegration (#4205)
- [preset] Add Inventory Alignment preset to community catalog (#4229)
- [extension] Add Spec Inventory extension to community catalog (#4228)
- [extension] Update Architecture Guard extension to v2.3.6 (#4224)
- Update SpecKit Companion extension to v0.20.2 (#4225)
- fix(workflows): reject a condition that has no {{ }} block (#4182)
- fix: raise feature assessment credit budget (#4222)
- [extension] Add AgentDocx extension to community catalog (#4184)
- fix(integrations): report a falsy non-mapping integration descriptor as a shape error (#4187)
- Update Autonomous Run Governance preset to v0.4.1 (#4203)
- fix(workflows): validate dispatch defaults (#4181)
- Update Atlas extension display name in community catalog (#4202)
- Add Closed Vocabulary Check preset to community catalog (#4201)
- fix(utils): narrow bare except Exception in merge_json_files (#4189)
- chore: release 0.16.5, begin 0.16.6.dev0 development (#4206)
