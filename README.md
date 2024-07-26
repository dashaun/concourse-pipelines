# concourse-pipelinescle

### Login to Concourse

```bash
fly login -c https://kaiju.dashaun.cc -t kaiju
```

```bash
fly -t kaiju set-pipeline -p hello-world -c sample-pipelines/hello-world.yaml
```

### Create Team

```bash
fly -t kaiju set-team --team-name javagrunt-com --github-org=javagrunt-com --github-user=pinkemma --github-user=colabottles

fly -t kaiju set-team --team-name dashaun-demo --github-org=dashaun-demo --github-user=pinkemma --github-user=colabottles --github-user=thiagochirana
```