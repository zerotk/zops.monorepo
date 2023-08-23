# zops.monorepo

Usage:

source monorepo.lib.bash
monorepo__main <TARGET> [<SOURCE>]+

where:
  TARGET: The name of the target (monorepo) repository.
  SOURCE: A string with the format: <REPO_URL>[#<REPO_BRANCH],TARGET_DIR>
    REPO_URL: The full URL for this source repository.
    REPO_BRANCH: Optional branch. Defaults to master.
    TARGET_DIR: The target directory in the monorepo.
