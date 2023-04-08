<div align="center">
  <h3 align="center">
	<big>Publicodes language server</big>
  </h3>
  <p align="center">
   <a href="https://github.com/EmileRolley/publicodes-language-server/issues">Report Bug</a>
   •
   <a href="https://publi.codes">Publicodes</a>
   •
   <a href="https://marketplace.visualstudio.com/items?itemName=EmileRolley.publicodes-language-server">The VSCode extension</a>

  </p>

 :warning: <i>The project is in WIP and the server has only been tested with VSCode and the
[nosgestesclimat](https://github.com/datagir/nosgestesclimat) model.</i> :warning:

</div>

A language server for [Publicodes](https://publi.codes/) providing basic features:
- Completions based on current project rules and publicodes's mechanisms
- Diagnostics generated on each save

> Recognized extension files are: `.publi.yml`, `.publicodes.yml`,
> `.publi.yaml`, `.publicodes.yaml`, `.publi`, `.publicodes`.

## To run in local

In your terminal, run:

```
yarn
yarn watch
```

In VSCode: 
- select `Launch Client` from the drop down (if it is not already).
- press ▷ to run the launch config (F5).
