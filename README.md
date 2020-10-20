# cdk-lib-starter

My [AWS CDK][aws-cdk] library template repository.

## Features and prerequisites

### Hosting documentation on GitHub Pages

**prerequisites**: GitHub Pages must be enabled.

The documentation are generated by [typedoc][typedoc].

URL is `https://{owner}.github.io/{repo}` (e.g. https://aereal.github.io/cdk-lib-starter)

### Auto-publish to NPM

**prerequisites**:
- Set your `auth-and-publish` level access token as `NPM_TOKEN` secret.
- Create `main` and `release` branches

The changes on `main` and `release` branches will be published to NPM automatically.

The releases from `main` branch are marked as developer preview.

[aws-cdk]: https://github.com/aws/aws-cdk
[typedoc]: https://typedoc.org/
