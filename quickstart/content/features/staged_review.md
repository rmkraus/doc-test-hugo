+++
title = 'Staged Review'
date = 2025-01-27T12:00:00-00:00
draft = false
+++

# Staged Review

Built-in content staging system for review workflows.

## Draft Metadata

Control content visibility with the `draft` parameter in front matter:

```yaml
+++
title = 'My Page'
date = 2025-01-27T12:00:00-00:00
draft = true
+++
```

## How It Works

- **`draft = true`** - Page excluded from production builds
- **`draft = false`** - Page included in all builds
- **Development mode** - All pages visible regardless of draft status
- **Production builds** - Only non-draft pages published

Perfect for content review processes, allowing authors to prepare content without immediate publication.