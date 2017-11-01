# git2consul
Data files for NG consul

# Validation
Before you submit your pull request, ensure that the yaml is properly formatted. Feel free to use whichever yaml tool you'd like, but here's a recommendation:

1) install js-yaml
  - brew install npm
  - npm install js-yaml
2) validate yaml returns valid json:
  - node-modules/js-yaml/bin/js-yaml.js 'stackname-to-validate'.yaml
