# License Recommendation

## Current Source Repository License

The current private source repository contains an MIT license.

That license should not be copied into this showcase repository automatically.

## Recommendation

Recommend: **no license for now**

## Applied Default For This Publish Step

This showcase repository is being published without a `LICENSE` file.

## Rationale

This showcase repository is primarily composed of:

- product documentation
- sanitized screenshots
- non-operational examples
- positioning material for investors and technical partners

Because the repository is intended to explain the product rather than grant broad reuse rights, a temporary no-license posture is the safest default. It preserves flexibility while the company decides what reuse, derivative work, and redistribution permissions it actually wants to allow.

## Trade-Offs

### No License

- Safest option when the repository is mostly view-only showcase material
- Avoids unintentionally granting broad reuse rights
- Means others do not have permission to reuse or redistribute the contents by default

### MIT

- Simple and widely understood
- Good for permissive reuse of lightweight sample code
- May grant more freedom than desired for showcase material and branded assets

### Apache-2.0

- Also permissive, with explicit patent language
- Better than MIT when shipping meaningful code artifacts
- Still broader than necessary for a documentation-first showcase

## Practical Path

1. Publish the showcase repo without a `LICENSE` file
2. Revisit licensing if the repo later includes reusable sample code or SDK material
3. Consider Apache-2.0 only if the public repo evolves into a genuine developer resource
