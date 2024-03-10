<div style='height: 48px; margin: 10px 0px;'>
  <img src='docs/modules/ROOT/assets/images/eagle_red_128px.png' style='margin-right: 10px; float: left;'>
  <h1>Eagle Fang Kubernetes - Observer Package</h1>
</div>

Some words about Eagle Fang Kubernets and what the Observer Package is.

<div style='height: 48px; margin: 10px 0px;'>
  <img src='docs/modules/ROOT/assets/images/syn_128px.png' style='margin-right: 10px; float: left;'>
  <h1>Project Syn</h1>
</div>

Project Syn is a set of tools helping to securely manage a fleet of Kubernetes clusters.
It brings a hierarchical configuration management based on GitOps principles, reusable components and an inventory of information about all Kubernetes clusters.

* **Commodore**: Generate and deploy configurations 👉 https://syn.tools/commodore/
* **Lieutenant Operator**: Manage inventories of `Clusters` and `Tenants` 👉 https://syn.tools/lieutenant-operator/
* **Lieutenant API**: REST API for Lieutenant Operator 👉 https://syn.tools/lieutenant-api/
* **Steward**: In-cluster agent for bootstrapping and reporting to Lieutenant 👉 https://syn.tools/steward/

## Documentation

Documentation for this package is written using [Asciidoc][asciidoc] and [Antora][antora].
It is located in the [docs/](docs) folder.
The [Divio documentation structure](https://documentation.divio.com/) is used to organize its content.

Run the `make docs-serve` command in the root of the project, and then browse to http://localhost:2020 to see a preview of the current state of the documentation.

After writing the documentation, please use the `make docs-vale` command and correct any warnings raised by the tool.

## Contributing and license

This library is licensed under [BSD-3-Clause](LICENSE).
For information about how to contribute see [CONTRIBUTING](CONTRIBUTING.md).

[commodore]: https://syn.tools/commodore/
[asciidoc]: https://asciidoctor.org/
[antora]: https://antora.org/
