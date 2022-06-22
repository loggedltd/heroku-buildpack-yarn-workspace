# heroku-buildpack-yarn-workspace

**Heroku buildpack to install, build, and run within a specified yarn workspace**

## Usage

Add a `YARN2_WORKSPACE_PATH` environment variable that points to the directory of the workspace you want to build e.g.

```
YARN2_WORKSPACE_PATH="packages/server"
```

## Testing locally

```bash
./test
```
