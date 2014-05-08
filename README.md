ohs Cookbook
============
This cookbook installs and configures [Oracle HTTP Server](http://www.oracle.com/technetwork/middleware/ias/index-091236.html).

Supported Versions
------------------
- 12c

Requirements
------------
* Chef 11 or higher
* Ruby 1.9 (preferably from the Chef full-stack installer)

Attributes
----------
TODO: List your cookbook attributes here.

e.g.
#### ohs::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['ohs']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### ohs::default
TODO: Write usage instructions for each cookbook.

e.g.
Just include `ohs` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[ohs]"
  ]
}
```

License and Authors
-------------------
- Author:: Michael Goetz (<mpgoetz@getchef.com>)

```text
Copyright:: 2014 Chef Software, Inc

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
