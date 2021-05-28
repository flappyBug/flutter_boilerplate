# flutter_boilerplate

A flutter boilerplate setup with reasonable CI, CD

# Planned Features

- Git Hooks
  
  We need run `git config core.hooksPath .githooks/` in project root dir for the first time to setup hooks.
  - [x] pre-commit
    - [x] lint
      - [ ] incremental?
    - [x] format
      - [ ] incremental?
  - [x] pre-push
    - [x] test
- CI/CD (Using github actions)
  - [ ] test
  - [ ] coverage
  - [ ] build apk & publish to release
  - [ ] cache
- Badges
  - [ ] test
  - [ ] coverage
