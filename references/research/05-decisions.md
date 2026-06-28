# 05 - Decisions, Actions, and Research Portfolio

## Portfolio-Level Decisions

### Decision 1: Build around human-product fit, not generic design aesthetics

Evidence:

- Early and high-cited work includes shoe-last design, head-shape comparison, 3D Chinese head / face modeling, sizing and grading for wearable products, and head templates.
- Later projects extend the same logic into eyewear, helmets, masks, facewear, and headwear customization.

Sources: OpenAlex top works; PolyU profile.
Confidence: high.

Inferred decision logic:

- If a product physically interfaces with the body, the design problem starts with morphology and pressure / contact / comfort, not visual preference alone.

### Decision 2: Treat population difference as first-class design data

Evidence:

- Chinese vs Caucasian head shape comparison (2010).
- Chinese children and adult head datasets in the RAE2026 PDF.
- Official research interests include cultural difference and anthropometry.

Sources: https://doi.org/10.1016/j.apergo.2010.02.002; PolyU RAE2026 PDF; PolyU profile.
Confidence: high.

Inferred decision logic:

- A good design system should avoid "average user" assumptions when known population variance materially affects fit or safety.

### Decision 3: Convert subjective comfort into predictive design information

Evidence:

- RAE2026 project built comfort prediction models for children's eyeglasses linking perceived comfort to nose-pad width, temple clamping force, head parameters, and product parameters.
- Related publication: "A 3D anthropometry-based quantified comfort model for children's eyeglasses design."

Source: https://doi.org/10.1016/j.apergo.2023.104054 and RAE2026 PDF.
Confidence: high.

Inferred decision logic:

- User discomfort should not remain anecdotal; it should become measurable enough to guide design iteration.

### Decision 4: Move from measurement to automated customization systems

Evidence:

- "Customize my helmet" uses 3D head prediction for helmet customization.
- AI-driven ergonomic headwear customization integrates facial landmarking, head prediction, and automated parametric design.
- "Face2Wear" and 3DCMM continue the pipeline from consumer-scale capture to product personalization.

Sources: https://doi.org/10.1016/j.cad.2022.103271; https://doi.org/10.1016/j.cad.2025.103888; https://doi.org/10.1109/TMM.2024.3521835
Confidence: high.

Inferred decision logic:

- Measurement only matters if it changes the product. The end state is a repeatable CAD / AI workflow.

### Decision 5: Study trust and social perception as design variables

Evidence:

- Systematic review of facial anthropomorphic trustworthiness for social robot design.
- Experiments on facial features, robot face ratio, emotional expressions, contextual cues, healthcare conversational agents, and artificial faces.

Sources: https://doi.org/10.3390/s20185087; https://doi.org/10.1016/j.apergo.2021.103420; https://doi.org/10.1016/j.chb.2020.106620; https://doi.org/10.2196/44479
Confidence: high.

Inferred decision logic:

- In AI / robot / interface systems, people respond to perceptual and social cues. Trust is designed through measurable cues, not only through technical correctness.

## Recent Project Timeline as Action Evidence

- 2015 / 2016: 3D human head and face model with soft tissue deformation, funded by RGC Early Career Scheme.
- 2016 / 2017: Sizing and comfort study for ear-related product design, funded by RGC GRF.
- 2019 / 2020: 3D face sizing template of Chinese children for face-related products, funded by RGC GRF.
- 2020: AI enhanced 3D head scanning technology and related products development, funded by Laboratory for Artificial Intelligence in Design and ITF.
- 2021 / 2022: Parametric biomechanical head models for product design and evaluation, funded by RGC GRF.
- 2022 / 2023: 3D dynamic human head, neck, and shoulder modelling for product design, funded by RGC GRF.
- 2023 / 2024: Social traits perception model on 3D human faces for face-related product design, funded by RGC GRF.
- 2024 / 2025: 4D head movement prediction model for product design and evaluation, funded by RGC GRF.
- 2025: AI powered ergonomic product design for neck and back health, funded by Laboratory for Artificial Intelligence in Design.

Source: PolyU profile project list.
Confidence: high.

## Portfolio Pattern

The decisions show a stable expansion path:

1. Measure the body.
2. Build statistical / digital models.
3. Link model parameters to comfort, trust, safety, or usability.
4. Build parametric design tools.
5. Validate through product examples and user studies.
6. Extend into AI where automation reduces friction.
