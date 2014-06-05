# rails-geo-cookbook

Let's make it a delight to spin up a modern batteries-included
Ruby/Rails platform suitable for developing and hosting GeoSpatial
applicaions.

## Supported Platforms

# ubuntu

## Attributes

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['rails-geo']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### rails-geo::default

Include `rails-geo` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[rails-geo::default]"
  ]
}
```

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (i.e. `add-new-recipe`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request

## License and Authors

Author:: Michael Kirk (<michael.john.kirk@gmail.com>)
