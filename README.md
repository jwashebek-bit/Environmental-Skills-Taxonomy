Environmental Management Skills Taxonomy (EMST)
Workforce Forecasting Infrastructure for Environmental Management Professions
Version: 0.9 (Pre-Delphi Release)
Maintained by: Environmental Policy Innovation Center (EPIC)
Fellowship: Digital Service for the Planet, New America
Status: Open for community review and Delphi validation — see Contributing below

WHAT IT IS

The Environmental Management Skills Taxonomy is a structured, open dataset of 215 competencies spanning the environmental management workforce across six primary domains and one cross-cutting integration layer, organized into 45 skill areas across 15 profession families — from Ecological & Scientific Knowledge to Technical & Technological Skills to Policy & Regulatory Skills. Each competency is classified at the task level, with three defined job tasks carrying independent automation exposure ratings across five dimensions: automation type, tacit knowledge density, career ladder position, automation vector, and time horizon.
The taxonomy is designed to function as workforce forecasting infrastructure — a shared reference architecture for analyzing how AI and automation are affecting environmental management professions at the level of specific tasks, rather than at the level of job titles or broad occupational categories. It captures what the project terms "jagged disruption": the pattern by which automation affects individual tasks within a competency unevenly, such that a single competency may simultaneously contain human-essential tasks and tasks under active substitution pressure. Secondary applications include hiring and position classification, curriculum alignment, professional standards development, and labor market analysis.

WHAT IT'S FOR
The environmental management workforce faces a convergence of pressures that current data infrastructure cannot adequately describe. Ecological knowledge pipelines are changing faster than professional preparation systems can track. Automation is reshaping which tasks require human judgment and which do not — but occupational classification systems built around job titles rather than task-level skill profiles cannot see this disruption clearly. And the governance demands placed on environmental practitioners — navigating regulatory systems, tribal consultation requirements, environmental justice obligations, and adaptive management frameworks — are expanding in complexity precisely as AI tools are entering practice.
At the same time, the ethical dimensions of environmental management practice are systematically underspecified in current professional standards. Analysis of the taxonomy's competency set found that more than 95% of ethically-bearing content in existing standards is implicit rather than explicitly named — a gap with direct implications for professional preparation, practitioner accountability, and the governance of AI-assisted decision-making in environmental contexts.
The taxonomy is an attempt to make these dynamics visible with enough precision that they can be measured, validated, and acted on.

ANALYTICAL ARCHITECTURE
The taxonomy organizes competencies across three analytical frameworks applied at the task level.

A craft framework distinguishes three types of professional contribution: Fieldcraft, whose irreducible deliverable is embodied, place-based ecological judgment; Datacraft, whose irreducible deliverable is verified analytical characterization; and Statecraft, whose irreducible deliverable is navigating or designing institutional frameworks. These categories clarify what automation actually threatens in each competency — substituting Datacraft tasks looks different from substituting Fieldcraft tasks, and conflating them produces misleading forecasts.

A stability tier framework classifies each competency as Stable, Transition, or Emergent based on regulatory reform sensitivity and disruption pressure. Reform sensitivity flags track five active federal regulatory reform vectors — NEPA timeline changes, digital permitting, categorical exclusion scope, interagency consultation, and One Federal Decision — allowing the taxonomy to signal which competency clusters are most exposed to near-term policy-driven disruption.

An ethical lens framework applies five dimensions — Equity & Justice, Cultural Rights & Self-Determination, Transparency & Accountability, Intervention Ethics, and Professional Integrity — to surface where ethical obligations are embedded in practice but absent from explicit professional preparation.

WHAT'S IN THE REPO
The /core folder contains the foundational competency architecture: competency definitions, proficiency indicators at four levels (Foundational through Expert), job task examples, sector applicability, and the domain structure summary. This content is stable and has been developed through extensive practitioner knowledge and literature review.

The /signals folder contains faster-moving analytical attributes: task-level automation exposure classifications, regulatory reform sensitivity flags, stability tier assessments, craft assignments, ethical lens ratings, and labor market crosswalk mappings to BLS SOC codes. These are flagged as provisional pending Delphi validation.

The /docs folder contains the data dictionary, schema documentation, and field-level controlled vocabularies.
Each versioned release is tagged. The current release (v0.9) represents the pre-Delphi state of the taxonomy — substantive enough for use, clearly labeled where expert validation is pending.

HOW TO USE THE TAXONOMY
The taxonomy is designed for multiple audiences and interaction modes. Practitioners, educators, and HR professionals are best served by the navigable interface at [GitBook link]. Workforce analysts and researchers can work directly with the CSV exports in /core and /signals. Technical integrators building skills matching tools or AI governance systems can reference the schema documentation in /docs. Organizations wishing to adopt the taxonomy for curriculum alignment, position classification, or accreditation standards review should start with the Profession Family View and the Proficiency Indicators table.

CONTRIBUTING AND DELPHI VALIDATION
This taxonomy is a field resource, not a proprietary product. Its long-term value depends on validation and adoption by the professional community — federal agencies, tribal natural resource departments, professional societies, academic programs, conservation organizations, and private sector environmental practitioners.

We are currently organizing the first formal Delphi validation round, targeting expert panels across the taxonomy's 15 profession families and six primary domains. Validation will address contested craft assignments, high-implicit ethical content, task-level automation classifications, and profession family boundary cases. If you represent an organization with relevant expertise and are interested in participating in validation, proposing amendments, or adopting the taxonomy for your own workforce systems, please open an Issue in this repository or contact [jwashebek@policyinnovation.org].

LICENSE
Released under Creative Commons Attribution 4.0 International (CC BY 4.0). You are free to use, adapt, and redistribute with attribution. We ask that derivative works reference the version number and note any modifications to the core competency structure.

CITATION
[JR Washebek]. (2026). Environmental Management Skills Taxonomy (v0.9). Environmental Policy Innovation Center / New America Digital Service for the Planet Fellowship.
