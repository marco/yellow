<div align="center">
    <img src="https://github.com/skunkmb/yellow/raw/master/readme-logo.png" width="60%" alt="Yellow: An Opinionated ESLint Configuration" />
</div>

Yellow is an opinionated ESLint Configuration prioritizing **readability**,
**brevity**, and **clarity**. It supports both JavaScript and Typescript.

## Some Rules

| Topic        | Rule      |
|--------------|-----------|
| Semicolons?  | Yes       |
| Indentation? | 2 Spaces  |
| Quotes?      | Single    |
| Line length? | 79        |

## Usage

**Installation**:

```bash
npm i -D eslint-config-yellow
```

**Setup**:

In your `.eslintrc`, include

```json
{
    "extends": "eslint-config-yellow"
}
```

To access the additional TypeScript rules, use

```json
{
    "extends": "eslint-config-yellow/ts"
}
```
