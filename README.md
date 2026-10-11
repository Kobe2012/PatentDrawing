# Patent Drawing Examples & AI Prompt Guide

**Practical prompts and review checklists for patent-style line drawings, product views, and invention diagrams.**

[**Try PatentDrawing.app**](https://patentdrawing.app/) · [Photo to Patent Drawing](https://patentdrawing.app/tools/photo-to-patent-drawing) · [Sketch to Patent Drawing](https://patentdrawing.app/tools/sketch-to-patent-drawing)

> **About this repository:** An official examples and prompt-guide repository for [PatentDrawing.app](https://patentdrawing.app/), a hosted AI patent drawing generator. It contains documentation and example prompts—not the application's source code or a local drawing engine.

## What is PatentDrawing?

PatentDrawing helps inventors, product designers, and technical teams turn written invention descriptions, product photos, rough sketches, and CAD screenshots into **patent-style drawing drafts**. Users can request black-and-white line art, perspective views, exploded views, and functional block diagrams, then review and download high-resolution **PNG** images.

It is designed for **drafting and communication**, not for automatically certifying patent-office compliance. A generated perspective view is a 2D image, not a 3D CAD model.

## Common use cases

| Workflow | Starting point | Example guide |
| --- | --- | --- |
| Photo to patent-style line drawing | Product photograph | [Citrus press example](examples/photo-to-line-art.md) |
| Sketch cleanup | Hand-drawn invention concept | [Adjustable lamp example](examples/sketch-to-drawing.md) |
| Exploded assembly drawing | Component description or reference | [Filter bottle example](examples/exploded-view.md) |

Other possible workflows include orthographic-view drafts, mechanism illustrations, and system flowcharts. Always verify that every requested feature appears correctly in the output.

## How to use

1. Open [PatentDrawing.app](https://patentdrawing.app/).
2. Describe your invention, or upload a photo, sketch, or CAD screenshot you have permission to use.
3. Specify the desired view, the parts to preserve, and whether the image should be monochrome line art.
4. Generate a draft and inspect its geometry, component relationships, and labels.
5. Refine the description or reference and generate a revised draft if necessary.
6. Download the PNG and carry out any further drafting or filing-format work separately.

## Example prompt: product photo to patent line art

```text
Using the uploaded reference photo of a manual citrus press, create a clean
black-and-white patent-style perspective line drawing on a white background.
Preserve the actual shape and relative position of the lever, pivot joint,
pressing cone, bowl, frame, and base. Use consistent thin outlines, with no
shading, decorative texture, shadows, or background objects. Do not invent
hidden components. Where the reference is ambiguous, leave the detail simple
rather than adding an unsupported mechanism.
```

**Review checklist:** Does the lever attach to the pivot? Is the pressing cone aligned with the bowl? Are the proportions consistent with the reference? Has the model invented a hinge, spring, or fastener?

## Prompt-writing tips

- **Name the view:** perspective, front, side, top, sectional, or exploded.
- **Describe critical parts:** distinguish visible, hidden, and removable components.
- **Specify line-art style:** monochrome, clean outlines, no photographic effects.
- **Separate facts from guesses:** avoid asking AI to fill in an unknown mechanism.
- **Review each view independently:** AI-generated views may disagree with one another.

## Important limitations

- Outputs are currently **PNG images**, not native CAD geometry or guaranteed editable vector files.
- The generator does not guarantee dimensional accuracy, consistent reference numerals, or conformity with USPTO, EPO, or other patent-office rules.
- AI-generated drawings may omit or invent mechanical details. Check the images against the real invention and consult a qualified patent professional or draftsperson when appropriate.
- Do not upload confidential invention materials without first reviewing the service's applicable privacy terms and your own disclosure obligations.

## More examples

- [Photo to patent-style line art](examples/photo-to-line-art.md)
- [Sketch to patent-style drawing](examples/sketch-to-drawing.md)
- [Exploded-view patent-style illustration](examples/exploded-view.md)

## Project scope and feedback

This repository documents reproducible **prompt patterns and review criteria** for the hosted PatentDrawing service. It is not an open-source implementation or a patent-filing service. To suggest an example, open a GitHub issue describing the use case and desired view; **do not include confidential inventions or unpublished sensitive materials**.

**Official website:** https://patentdrawing.app/
