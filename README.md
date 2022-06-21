# ansible-role-resource-limits

Configures system resource limits

## Requirements

None

## Role Variables

| Name                              | Description                                                                                 | Default           |
| --------------------------------- | ------------------------------------------------------------------------------------------- | ----------------- |
| `resource_limits_global.hard`     | A dictionary containing hard limit configuration                                            | `See defaults...` |
| `resource_limits_global.soft`     | A dictionary containing soft limit configuration                                            | `See defaults...` |
| `resource_limits_remove_existing` | A flag indicating whether to remove any configurations found under `/etc/security/limits.d` | `false`           |

## Dependencies

None

### Example Requirements File

How you use the role within a given project

    - src: https://github.com/companieshouse/ansible-role-resource-limits
      name: resource-limits
      version: "n.n.n"

## License

MIT
