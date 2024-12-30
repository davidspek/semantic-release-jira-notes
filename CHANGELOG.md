## [1.0.2](https://github.com/davidspek/semantic-release-jira-notes/compare/v1.0.1...v1.0.2) (2024-12-30)


### Bug Fixes

* set public access ([fcf6251](https://github.com/davidspek/semantic-release-jira-notes/commit/fcf6251c88f391085b93498a1a7f44cecff08933))

## [1.0.1](https://github.com/davidspek/semantic-release-jira-notes/compare/v1.0.0...v1.0.1) (2024-12-30)


### Bug Fixes

* npm pkg ([a092f86](https://github.com/davidspek/semantic-release-jira-notes/commit/a092f86aa1905ca677f80dfdfaa69f9952ac741f))

# 1.0.0 (2024-12-30)


### Bug Fixes

* change all references ([9b74c83](https://github.com/davidspek/semantic-release-jira-notes/commit/9b74c83359e41c3419809bde6f7af80e8faa76c0))
* **generate-notes:** get notes from context ([d988d34](https://github.com/davidspek/semantic-release-jira-notes/commit/d988d345e63626ef0662d1a759a2b44a70ce59c6))
* **generate-notes:** use release-notes-generator plugin ([e7c0770](https://github.com/davidspek/semantic-release-jira-notes/commit/e7c0770d88727f397ddb62083598c3541a92239f))
* **package.json:** homepage url ([9555f48](https://github.com/davidspek/semantic-release-jira-notes/commit/9555f48881246917f802e64d46f9b519e6424efe))
* **verify:** error when ticketPrefixes is undefined ([283ff8f](https://github.com/davidspek/semantic-release-jira-notes/commit/283ff8f96fb7778a701871381b49d9eda0420b5b))


### Code Refactoring

* update project to ESM ([#5](https://github.com/davidspek/semantic-release-jira-notes/issues/5)) ([1d18aec](https://github.com/davidspek/semantic-release-jira-notes/commit/1d18aecf617dc7363a854a58577c2fcf4197016d))


### Features

* **generate-notes:** don't use release-notes-generator manually ([cd8cbe1](https://github.com/davidspek/semantic-release-jira-notes/commit/cd8cbe1ef89ede9608afdafde7c75a4a1e9c5ed5))
* initial fork release ([5f62690](https://github.com/davidspek/semantic-release-jira-notes/commit/5f62690cda01638d20be6d42fd350585c3352a1b))


### BREAKING CHANGES

* migrate imports from CommonJS to ESM
* **generate-notes:** users should now remove release-notes-generator
from their plugin list.
* **generate-notes:** release-notes-generator should now be defined in the
configuration file before semantic-release-jira-notes

# [4.0.0](https://github.com/iamludal/semantic-release-jira-notes/compare/3.0.0...4.0.0) (2024-05-28)


### Code Refactoring

* update project to ESM ([#5](https://github.com/iamludal/semantic-release-jira-notes/issues/5)) ([1d18aec](https://github.com/iamludal/semantic-release-jira-notes/commit/1d18aecf617dc7363a854a58577c2fcf4197016d))


### BREAKING CHANGES

* migrate imports from CommonJS to ESM

# [3.0.0](https://github.com/iamludal/semantic-release-jira-notes/compare/2.0.1...3.0.0) (2022-07-01)


### Bug Fixes

* **generate-notes:** use release-notes-generator plugin ([e7c0770](https://github.com/iamludal/semantic-release-jira-notes/commit/e7c0770d88727f397ddb62083598c3541a92239f))


### BREAKING CHANGES

* **generate-notes:** users should now remove release-notes-generator
from their plugin list.

## [2.0.1](https://github.com/iamludal/semantic-release-jira-notes/compare/2.0.0...2.0.1) (2022-06-30)


### Bug Fixes

* **generate-notes:** get notes from context ([d988d34](https://github.com/iamludal/semantic-release-jira-notes/commit/d988d345e63626ef0662d1a759a2b44a70ce59c6))

# [2.0.0](https://github.com/iamludal/semantic-release-jira-notes/compare/1.0.3...2.0.0) (2022-06-28)


### Features

* **generate-notes:** don't use release-notes-generator manually ([cd8cbe1](https://github.com/iamludal/semantic-release-jira-notes/commit/cd8cbe1ef89ede9608afdafde7c75a4a1e9c5ed5))


### BREAKING CHANGES

* **generate-notes:** release-notes-generator should now be defined in the
configuration file before semantic-release-jira-notes

## [1.0.3](https://github.com/iamludal/semantic-release-jira-notes/compare/1.0.2...1.0.3) (2022-06-28)


### Bug Fixes

* **verify:** error when ticketPrefixes is undefined ([283ff8f](https://github.com/iamludal/semantic-release-jira-notes/commit/283ff8f96fb7778a701871381b49d9eda0420b5b))
