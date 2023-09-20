## Amazon OSPO Configuration for GitHub Dependency Review

The license lists within this repository are intended for use with the Dependency Review GitHub Action.

Typical Amazon projects should use the configuration file in the default/ directory. A typical project is one under Apache-2.0 license that has no plans to relocate to another location, such as an open source foundation.

Other projects should contact the Amazon OSPO internally. For example, if a project has potential plans for graduating to an open source foundation, we would review that foundation's licensing policies with you. Or if a project has alternative licensing than Apache-2.0, we would work with you to identify if a different set of license rules are required.

## Using the license lists

Please see [GitHub's documentation](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/configuring-dependency-review) for information on how to set up Depdendency Review and how to integrate the license lists:

Specifically, for our default list, you will be including the following:

```
config-file: amazon-ospo/dependency-review-config/default/dependency-review-config.yml@main
```

## Security

In the unlikely event of a security issue - please see [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the CC0-1.0 license.
