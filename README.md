r<p align="center">
    <img src="https://raw.githubusercontent.com/stylescape/brand/master/src/logo/logo-transparant.png" width="20%" height="20%" alt="Stylescape Logo">
</p>
<h1 align="center" style='border-bottom: none;'>Stylescape</h1>
<h3 align="center">Design Framework</h3>

<br/>

<div align="center">

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fwww.scape.style&up_message=Up&up_color=354351&down_message=Down&down_color=354351&style=flat-square&logo=Firefox&logoColor=FFFFFF&label=Website&labelColor=354351&color=354351)
](https://www.scape.style)
[![NPM Version](https://img.shields.io/npm/v/stylescape?style=flat-square&logo=npm&logoColor=FFFFFF&label=NPM&labelColor=354351&color=354351&link=https%3A%2F%2Fwww.npmjs.com%2Fpackage%2Fstylescape)](https://www.npmjs.com/package/stylescape)
[![devContainer](https://img.shields.io/badge/devContainer-23354351?style=flat-square&logo=Docker&logoColor=%23FFFFFF&labelColor=%23354351&color=%23354351)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/stylescape/stylescape)
[![StackBlitz](https://img.shields.io/badge/StackBlitz-23354351?style=flat-square&logo=StackBlitz&logoColor=%23FFFFFF&labelColor=%23354351&color=%23354351)](https://stackblitz.com/github/stylescape/stylescape/tree/main?file=src%2Findex.html)
[![GitHub License](https://img.shields.io/github/license/stylescape/stylescape?style=flat-square&logo=readthedocs&logoColor=FFFFFF&label=&labelColor=%23354351&color=%23354351&link=LICENSE)](https://github.com/stylescape/stylescape/blob/main/LICENSE)

</div>

<div align="center">

[![Report a Bug](https://img.shields.io/badge/Report%20a%20Bug-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23D2D9DF)](https://github.com/stylescape/stylescape/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=bug_report.yml)
[![Request a Feature](https://img.shields.io/badge/Request%20a%20Feature-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23D2D9DF)](https://github.com/stylescape/stylescape/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=feature_request.yml)
[![Ask a Question](https://img.shields.io/badge/Ask%20a%20Question-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23D2D9DF)](https://github.com/stylescape/stylescape/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=question.yml)
[![Make a Suggestion](https://img.shields.io/badge/Make%20a%20Suggestion-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23D2D9DF)](https://github.com/stylescape/stylescape/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=suggestion.yml)
[![Start a Discussion](https://img.shields.io/badge/Start%20a%20Discussion-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23D2D9DF)](https://github.com/stylescape/stylescape/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=discussion.yml)

</div>

---

<br/>

## A powerful design framework for concise and high-quality web development

Stylescape is a modular, scalable, and customizable design framework dedicated to streamlining style and layout design for both web and print media. Written in SCSS and TypeScript, it aimes to bridge the gap between visual design and code. Whether you’re a designer or developer, Stylescape provides a robust toolkit that empowers you to create harmonious, scalable, and accessible designs efficiently.

---

``` mermaid
graph TD
    %% Styles for the diagram
    classDef main fill:#041B26,stroke:#FFFFFF,stroke-width:2px,color:#FFFFFF,font-size:16px,font-weight:bold;
    classDef module fill:#1e3d59,stroke:#FFFFFF,stroke-width:1px,color:#FFFFFF,font-size:14px,font-weight:normal;
    classDef focus fill:#028090,stroke:#FFFFFF,stroke-width:1px,color:#FFFFFF,font-size:12px,font-style:italic;

    %% Main node
    A[Stylescape]:::main

    %% Modules
    A --> B[unit.gl]:::module
    A --> C[hue.gl]:::module
    A --> D[icon.gl]:::module
    A --> E[font.gl]:::module
    A --> F[move.gl]:::module
    A --> G[page.gl]:::module
    A --> H[pack.gl]:::module

    %% Descriptions and focus areas for each module
    B --> B1[Dynamic Layout Engine]:::focus
    B1 --> B2[Fluid Typography]:::focus
    B1 --> B3[Responsive Design]:::focus

    C --> C1[Perceptual Color System]:::focus
    C1 --> C2[Color Management Toolkit]:::focus

    D --> D1[Modular Icon Library]:::focus
    D1 --> D2[Various Integration Options]:::focus

    E --> E1[Variable Font Collection]:::focus
    E1 --> E2[Typography Base]:::focus

    F --> F1[User Experience Toolkit]:::focus
    F1 --> F2[Interactives and Immersives]:::focus

    G --> G1[Page Layout Library]:::focus
    G1 --> G2[Rapid Prototyping]:::focus

    H --> H1[Package Pipeline Manager]:::focus
    H1 --> H2[Asset and Code Bundling]:::focus
    H1 --> H3[Streamlined Deployment]:::focus
```

---

## Quickstart

### Installation

You can install Stylescape using npm:

```bash
npm install stylescape
```

Or via unpkg:

```html
<link rel="stylesheet" href="https://unpkg.com/stylescape@0.0.10/dist/css/stylescape.css">
```

### Getting Started

After installing, you can include Stylescape's SCSS and TypeScript files into your project:

```javascript
import 'stylescape/dist/stylescape.css';
import 'stylescape/dist/stylescape.js';
```

---

## Documentation

For more detailed setup and usage instructions, refer to our official website: [scape.style](https://scape.style).

---

## Contribution

Contributions are always welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for ways to get started.

---

<p align="center">
    <b>Made with ❤️ by <a href="https://www.scape.agency" target="_blank">Scape Agency</a></b>
</p>
