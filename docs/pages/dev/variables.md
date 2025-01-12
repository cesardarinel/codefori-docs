We provide some context values and environment variables so extensions and managed environments can control Code for IBM i.

| Type                 | Name                                      | Values      | Comment                                                       |
| -------------------- | ----------------------------------------- | ----------- | ------------------------------------------------------------- |
| Context value        | `code-for-ibmi:libraryListDisabled`       | boolean     |                                                               |
| Context value        | `code-for-ibmi:connectionBrowserDisabled` | boolean     |                                                               |
| Context value        | `code-for-ibmi:helpViewDisabled`          | boolean     |                                                               |
| Context value        | `code-for-ibmi:objectBrowserDisabled`     | boolean     |                                                               |
| Context value        | `code-for-ibmi:ifsBrowserDisabled`        | boolean     |                                                               |
| Environment variable | `DEBUG_CA_PATH`                           | string path | PR pending, only uses when `DEBUG_MANAGED` is true            |
| Environment variable | `DB2I_DISABLE_CA`                         | boolean     | Specific to the Db2 for i extension to disable content assist |

## Sandbox environment variables

When these are set, Code for IBM i will automatically connect using these environment variables.

| Name             | Values |
| ---------------- | ------ |
| `SANDBOX_SERVER` | string |
| `SANDBOX_USER`   | string |
| `SANDBOX_PASS`   | string |