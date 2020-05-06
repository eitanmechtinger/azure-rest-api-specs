## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_quantum
package-version: 2019-11-04
azure-arm: true
```

### Tag: package-2019-11-04 and ruby

These settings apply only when `--tag=package-2019-11-04 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2019-11-04' && $(ruby)
namespace: Microsoft.Quantum
output-folder: $(ruby-sdks-folder)/quantum
```