# pt-to-github
Import Pivotal Tracker export CSV's into GitHub Issues

## Usage

Install the required dependencies:

```bash
bundle install
```

Run the script:

```bash
GITHUB_ACCESS_TOKEN=<github-token> bin/migrate <path_to_pivotal_csv> <github_repo>
```

