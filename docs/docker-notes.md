# Docker Notes — Day 9

## Docker Version

Output of `docker version`:

```bash
[paste output here]
```

Output of `docker info`:

```bash
[paste output here]
```

## Hello World Test

Output of `docker run hello-world`:

```bash
[paste output here]
```

## Postgres Container

Command used:

```bash
docker run -d --name pg-prework -e POSTGRES_PASSWORD=prework -p 5432:5432 postgres:15-alpine
```

### Startup Logs

Output of `docker logs pg-prework`:

```bash
[paste full output here]
```

Startup confirmation line found:

`LOG:  database system is ready to accept connections`

## Stop and Restart

Output of `docker stop pg-prework`:

```bash
[paste output here]
```

Output of `docker restart pg-prework`:

```bash
[paste output here]
```

Output of `docker logs pg-prework` after restart:

```bash
[paste output here]
```

## Issues Encountered

None