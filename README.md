# Thesis Template

[![ci](https://github.com/unitn-drive/thesis/actions/workflows/ci.yaml/badge.svg)](https://github.com/unitn-drive/thesis/actions/workflows/ci.yaml)

Thesis Template for Computer Science at the [University of Trento](https://www.unitn.it)

## Development

> [!TIP]
> It is highly recommended to use [`Visual Studio Code`](https://code.visualstudio.com) editor

### Requirements

| **Name**   | **Homepage**                  |
| ---------- | ----------------------------- |
| `TeX Live` | <https://www.tug.org/texlive> |
| `Node.js`  | <https://nodejs.org>          |
| `npm`      | <https://www.npmjs.com>       |

### Preparation

1. Clone

   ```sh
   git clone https://github.com/unitn-drive/thesis.git
   cd thesis
   ```

1. Install Dependencies

   ```sh
   npm ci
   ```

### Build

```sh
npm run build
```

### Scripts

> **Note**: Execute with `npm run <NAME>`

| **Name** | **Description**  |
| -------- | ---------------- |
| `build`  | Build PDF        |
| `check`  | Check for errors |
| `clean`  | Clean            |
| `fix`    | Fix errors       |

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license \
See [LICENSE](./LICENSE) file for details
