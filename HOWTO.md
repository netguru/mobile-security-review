# How to generate output for a new release?

1. Install GitBoook CLI.

  ```bash
  $ npm install -g gitbook-cli
  ```

  **Note**: The command above requires npm. If you are missing npm, then [install it](https://www.npmjs.com/get-npm).

1. Run the following command in the main directory of this repository to install missing plugins.

  ```bash
  $ gitbook install
  ```

1. Run the following command in the main directory of this repository to generate output in all available formats.

  ```bash
  $ gitbook pdf . ./NMSR.pdf && gitbook epub . ./NMSR.epub && gitbook mobi . ./NMSR.mobi
  ```
