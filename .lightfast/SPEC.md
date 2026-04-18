# Lightfast Organization Spec

Lightfast is building AI agent orchestration tools. We care deeply about deployment reliability and fast incident response.

When events come in from connected providers (GitHub, Vercel, Linear, Sentry), prefer running a skill whenever the event is a meaningful signal about shipping quality — deploy failures, production errors, or merged PRs that touch critical paths. Routine noise (dependabot deploys, forks, unrelated status pings) should be skipped.
