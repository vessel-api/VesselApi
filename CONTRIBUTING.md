# Contributing to VesselAPI

This document explains how to contribute to VesselAPI.

## Ways to Contribute

### Reporting Bugs

If you've found a bug in the API, please help us fix it by opening an issue.

**Before submitting:**
1. Search [existing issues](https://github.com/vessel-api/VesselApi/issues) to avoid duplicates
2. Make sure you're using a supported API version

**When submitting:**
1. Use the [Bug Report template](https://github.com/vessel-api/VesselApi/issues/new?template=bug_report.yml)
2. Include the API endpoint affected
3. Provide request details (without your API key!)
4. Show the expected vs actual response
5. Mention your subscription tier

**Example of a good bug report:**
```
Endpoint: GET /v1/search/vessels
Request: ?filter.name=EVERGREEN&pagination.limit=10
Expected: Array of vessels matching "EVERGREEN"
Actual: Empty array returned, but vessels exist
Subscription: Pro
```

### Requesting Features

Have an idea for a new feature?

**Before submitting:**
1. Search existing issues for similar requests
2. Consider if this benefits the broader community

**When submitting:**
1. Use the [Feature Request template](https://github.com/vessel-api/VesselApi/issues/new?template=feature_request.yml)
2. Describe the problem you're trying to solve
3. Explain your proposed solution
4. Mention any alternatives you've considered

### Improving Documentation

Found something unclear or incorrect in our docs?

1. Use the [Documentation Issue template](https://github.com/vessel-api/VesselApi/issues/new?template=documentation.yml)
2. Link to the specific page
3. Explain what's wrong or missing
4. Suggest a correction if possible

### Contributing Code Examples

We welcome code examples in any programming language!

**Guidelines:**
1. Fork this repository
2. Create your example in the appropriate `examples/` subdirectory
3. Follow these standards:
   - Include clear comments explaining the code
   - Add a README.md for complex examples
   - Don't include API keys or sensitive data
   - Use environment variables for configuration
   - Include any required dependencies (requirements.txt, package.json, go.mod)
4. Submit a pull request

**Example structure:**
```
examples/
  your-language/
    your-example/
      README.md
      main.py (or appropriate extension)
      requirements.txt
```

## Pull Request Process

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-example`)
3. Make your changes
4. Ensure your code follows the existing style
5. Commit with a clear message (`git commit -m 'Add Python example for vessel tracking'`)
6. Push to your fork (`git push origin feature/amazing-example`)
7. Open a Pull Request

### PR Guidelines

- Keep PRs focused on a single change
- Update documentation if needed
- Add yourself to contributors if desired
- Be responsive to feedback

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md). We're committed to providing a welcoming and inclusive environment for everyone.

## Questions?

- **API questions**: Check our [Documentation](https://vesselapi.com/docs)
- **Account/billing issues**: Email support@vesselapi.com
- **Sales inquiries**: Email sales@vesselapi.com
- **Security issues**: Email security@vesselapi.com (see [SECURITY.md](SECURITY.md))

## Recognition

Contributors who submit accepted PRs will be:
- Added to our contributors list (if desired)
- Mentioned in release notes when applicable

Happy contributing.
