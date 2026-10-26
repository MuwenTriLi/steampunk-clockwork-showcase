# 01 / Clockwork

**Turn original modeled components into linked mechanisms and an editable Blender motion library.**

**[Open the Superhive product →](https://superhivemarket.com/products/steampunk-clockwork-animated-assets)** · [Build process](docs/process.md) · [Controls](docs/controls.md) · [Workflow Skill](docs/workflow-skill.md) · [Validation](docs/validation.md) · [All projects](https://github.com/MuwenTriLi/creative-workflows#selected-work)

<table><tr>
<td width="46%" align="center"><a href="media/collection-hero-4k.jpg"><img src="media/collection-hero-4k.jpg" height="180" alt="Clockwork: original modeled collection"></a><br><b>Source language → reusable collection</b></td>
<td width="27%" align="center"><a href="docs/controls.md"><img src="media/motion-clk08.gif" height="180" alt="Clock gear motion"></a><br><b>Linked motion</b></td>
<td width="27%" align="center"><a href="docs/controls.md"><img src="media/motion-clk32.gif" height="180" alt="Controlled opening assembly"></a><br><b>Editable rhythm</b></td>
</tr></table>

## Input → output

| Input | Output |
| --- | --- |
| My original modeled geometry, organized references and motion/design requirements | 46 animated Blender assets with linked motion, root controls, previews and documentation |
| A selected assembly, shot brief and reviewed parameter changes | An adapted mechanism in a new composition, preserving its controller dependencies |

The production problem is repeatable adaptation: a detailed form becomes useful when another creator can place it, change its timing and preserve how its parts move together.

## How it was built

```text
Original modeling + design rules
  → organized inputs for AI-assisted inspection and development
  → native Blender drivers, hierarchies and constraints
  → creator-facing controls
  → motion review + Asset Browser packaging
```

I modeled the source collection, organized the inputs, directed the visual and mechanical relationships and reviewed the results. Codex assisted file inspection, development of related structures, linkage implementation and packaging. Supplying modeled data as context is **not** a claim of training a model.

The 46-asset library is the shipped outcome. The [production case](docs/production-case.md) explains the hypothesis and design decisions; the [build process](docs/process.md) separates the creative work from implementation assistance.

## Use the product

1. Obtain the Blender library through the [product page](https://superhivemarket.com/products/steampunk-clockwork-animated-assets).
2. Register its Asset Library folder in Blender and place a complete collection.
3. Select the root controller. Adjust a documented input such as speed or phase; retain the driven hierarchy.
4. Review a complete motion cycle and inspect the rendered result for the intended shot.

Controls vary by asset. Use the [controller reference](docs/controls.md) before changing calculated outputs or separating animated components. The [component reuse guide](docs/component-reuse.md) explains dependencies to preserve.

## Automation and creator control

Native drivers propagate accepted inputs to connected parts. The creator determines the form, motion intent, speed, phase and final acceptance. The later [clockwork-assembly Skill](skills/clockwork-assembly/SKILL.md) records an inspection/adaptation/checking procedure; a [checked CLK32 speed adjustment](docs/control-study.md) now records the actual input, working-copy change, compatibility failure and verification results. Broader recomposition is not established by that narrow test.

## Evidence and next decision

Available evidence includes the commercial library, original renders, motion excerpts, Blender recordings and documented historical release checks. [Validation scope](docs/validation.md) distinguishes historical release checks from the new, single-asset [control study](docs/control-study.md).

The new control study changes speed from 1.0 to 0.75 with the driver graph preserved. Independent creator success, broader recomposition and time savings have not been measured.

## Repository map

```text
steampunk-clockwork-showcase/
├── README.md                      Project purpose, workflow and entry points
├── docs/
│   ├── process.md                 Input preparation and AI-assisted development
│   ├── production-case.md         Hypothesis, decisions and next experiment
│   ├── controls.md                Actual controller inputs and dependencies
│   ├── component-reuse.md         How to preserve or rebuild linked motion
│   ├── workflow-skill.md          Instruction workflow and execution boundary
│   ├── validation.md              Historical evidence and unverified scope
│   └── visual-tour.md             Extended collection, motion and Blender tour
├── skills/clockwork-assembly/     Public adaptation instructions
└── media/                         Approved renders and recordings
```

[Extended visual tour](docs/visual-tour.md) · [Render gallery](docs/render-gallery.md) · [Films](docs/showcase-films.md)

The commercial Blender source is distributed through Superhive, not this repository. Presentation media retains its existing rights. This repository is the project's workflow and evidence companion.

<details><summary>Previously shared gallery sections</summary>

<a id="a-control-system-behind-each-assembly"></a>
[A control system behind each assembly](docs/visual-tour.md#a-control-system-behind-each-assembly)

<a id="finished-collection"></a>
[Finished collection](docs/visual-tour.md#finished-collection)

<a id="the-reusable-workflow-behind-the-assets"></a>
[The reusable workflow behind the assets](docs/visual-tour.md#the-reusable-workflow-behind-the-assets)

<a id="structure--material"></a>
[Structure → material](docs/visual-tour.md#structure--material)

<a id="the-collection-in-motion"></a>
[The collection in motion](docs/visual-tour.md#the-collection-in-motion)

<a id="mechanisms-in-focus"></a>
[Mechanisms in focus](docs/visual-tour.md#mechanisms-in-focus)

<a id="motion-is-part-of-the-design"></a>
[Motion is part of the design](docs/visual-tour.md#motion-is-part-of-the-design)

<a id="selected-forms"></a>
[Selected forms](docs/visual-tour.md#selected-forms)

<a id="inside-blender-from-library-to-moving-assembly"></a>
[Inside Blender: from library to moving assembly](docs/visual-tour.md#inside-blender-from-library-to-moving-assembly)

<a id="components-for-a-new-design"></a>
[Components for a new design](docs/visual-tour.md#components-for-a-new-design)

<a id="from-design-rules-to-a-usable-product"></a>
[From design rules to a usable product](docs/visual-tour.md#from-design-rules-to-a-usable-product)

<a id="browse--place--adjust--animate"></a>
[Browse / place / adjust / animate](docs/visual-tour.md#browse--place--adjust--animate)

<a id="repository-map"></a>
[Repository map](docs/visual-tour.md#repository-map)

</details>
