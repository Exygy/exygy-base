# Release Cycle

This is ultimately decided by the team and it is often useful to have it coincide with a sprint, for ideally at the end of each sprint you have tested and shippable code. You may find it useful to have staggered releases. For example, at the end of your sprint you perform a release to a staging environment. This gives the team more time to ensure the release is stable. This only really works well if that environment is getting used on a regular basis. Then, after some time, maybe a few days or the following week, you promote the release from staging to production.

## Tools

There are many tools that can help ease the burden of creating releases and bumping versions of your product. Tools like [Commitizen](https://github.com/commitizen/cz-cli), which help your team write conventional commits, and [lerna](https://github.com/lerna/Lerna), which can help publish your packages are recommended.

### Examples
The [Bloom Affordable Housing System](https://github.com/bloom-housing/bloom) is continuously iterating on its processes, and thanks to [@emilyjablonski](https://github.com/emilyjablonski), the team has these tools in place to auto update the changelogs and publish a pre-release when branches are merged into Bloom's dev environment.
