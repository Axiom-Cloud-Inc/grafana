# portal

# Steps

- `brew install nvm`
- `nvm use 12` // Since this project uses late version of node 12
- `yarn install --pure-lockfile --no-progress`
- `./node_modules/.bin/grunt build`
- `docker build -t axcl/grafana-portal:v0.0.1 -f Dockerfile.axiom .`
