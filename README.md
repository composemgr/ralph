# Ralph

A self-hosted ralph application.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/ralph/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/ralph" ~/.local/srv/docker/ralph
cd ~/.local/srv/docker/ralph
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install ralph
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
