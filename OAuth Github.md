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
curl -L \ -H "Accept: application/vnd.github+json" \ -H "X-GitHub-Api-Version: 2022-11-28"  \ "https://api.github.com/search/repositories?q=java+language:java&sort=stars&order=desc"

# GitHub CLI api
# https://cli.github.com/manual/gh_api

curl -L \ -H "Accept: application/vnd.github+json" \ -H "X-GitHub-Api-Version: 2022-11-28" \ https://api.github.com/rate_limit