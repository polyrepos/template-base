# template bun

Template for creating bun projects

In your project's package.json set:

```json
{
  "polyCopy": {
    "@polyrepo/template-base": [
      ".github",
      "LICENSE",
      ".gitignore",
      "biome.json",
      ".husky",
      "tsconfig.json",
      "tsconfig.ci.json"
    ],
    "@polyrepo/template-full-stack": [
      ".gitignore",
      "biome.json",
      "tsconfig.json"
    ]
  }
}
```
