- [ ] Celery task registered name isn't consistent between class and decorated registrations.
- [ ] Celery task signature changing not being appropriatly handled
- [ ] Passing a list as an argument in [Python](https://docs.python-guide.org/writing/gotchas/)
- [ ] Writing big functions, write it as a class with smaller tests
- [ ] Not using timezones when they should be used
- [ ] Itterating over large iterables, yield generators instead
- [ ] During valuable and large changes, eg emails, notifications, old endpoints which are implemented in weird ways, get lots of coverage. Add this to the repo. Then start dev.
- [ ] Cache timeouts during deployment, these aren't fun
- [ ] Is there a paid service which has the desired functionality?
- [ ] Managing depencies sucks, add them as infrequently as possible. 
- [ ] Reimplementing features sucks. Making it a depenency can reduce the cost
- [ ] Write simple code, check how to do things on known objects. Eg:// `formState.errors && Boolean(formState.errors.__all__)`
or
`formState.errors && formState.errors.__all__ && formState.errors.__all__.length > 0`
- [ ] Migrations matter, Queries matter, Default values matter, update concurrency is very important, think it through
- [ ] Branching off branches means you'll get merge/rebase issues. Treat these with kid gloves (tests should catch these)
- [ ] UX Improvements are easy and good. Add them in as a matter of practice.