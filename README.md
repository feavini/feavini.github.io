[![Netlify Status](https://api.netlify.com/api/v1/badges/57e15324-df6d-4687-8ed1-a36133b8bf16/deploy-status)](https://app.netlify.com/sites/elated-joliot-4425bf/deploys)

# Local development

## Dependencies

```bash
sudo dnf install -y install ruby-devel redhat-rpm-config

bundle install --path vendor/bundle
```

## Run

```bash
bundle exec jekyll serve --incremental
```
