# CircleCI Sample

Following repo contains some sample circleci configurations. Some of the features used in samples are:

- Workflow -> Job -> Commands declarations.
- Environment variables usage. See [docs](https://circleci.com/docs/2.0/env-vars/).
- Persist information between jobs using workspaces. See [docs](https://circleci.com/docs/2.0/configuration-reference/#persist_to_workspace).
- Commands usage to reuse code . See [docs](https://circleci.com/docs/2.0/configuration-reference/#commands-requires-version-21).

For a more real world sample configuration See [conf](https://github.com/ederfduran/react-slingshot/tree/master/.circleci) where I described the most common jobs in a CI workflow.
  * build/lint
  * test
  * analyze
  
