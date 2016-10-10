
## .drone.yml 

```
build:
  run_tests:
    image: python:2-alpine
    commands:
      - python testing.py

publish:
  docker:
    repo: $$DOCKER_USERNAME/$$DOCKER_REPO
    tag: latest

deploy:
  webhook:
    image: plugins/drone-webhook
    urls:
      - https://$$MARATHON/marathon/v2/apps/$$APPNAME/restart
```

