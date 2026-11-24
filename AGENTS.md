# AGENTS.md — Customer Relationship Management

## Project context
Customer Relationship Excellence deliverable: an actionable CRM and reputation plan plus lightweight tools and a demonstrable pilot, not a full CRM SaaS application. Company adoption and any live customer contact are optional and subject to approval.

## Working agreement
- Read README.md, the relevant requirements/decisions and existing code before editing. Treat proposed features and unverified assumptions as such.
- Keep changes focused on the assigned issue. Do not silently change scope, architecture, interfaces, or dependencies; record consequential decisions as ADRs and seek team review.
- Use descriptive branches (feat/, fix/, docs/, test/, chore/), small commits and reviewed pull requests. Do not push directly to protected branches, deploy, publish, or change repository settings without authorization.
- Match established conventions. Prefer simple, maintainable implementations over speculative abstractions; do not introduce microservices or infrastructure without a demonstrated need.
- Add or update relevant tests and documentation. Run the checks available in the repository; report commands, actual outcomes and anything not run. Never claim unverified success.
- Never commit credentials, production environment files, real customer/supplier data, unapproved company assets, raw interview transcripts or confidential business records. Use synthetic fixtures and .env.example with placeholders.
- Keep the public portfolio and company handover distinct; publication, licensing and production access require approval. Do not infer that a project is open source.
- Do not implement cross-repository integrations without a documented agreement; each deliverable must remain independently adoptable.

## Scope and organization
- Store strategy and customer lifecycle plans in strategy/, process maps and SOPs in workflows/, reusable forms/messages/registers in templates/, synthetic examples and optional implementation tools in pilot/. Do not turn this deliverable into a full CRM application unless approved.
- Cover post-installation and post-repair follow-ups, feedback capture, complaint logging/escalation, service recovery, review requests, customer retention and practical ownership. Define an actionable rollout and handover plan that can work with existing tools.
- Treat underrepresentation of satisfied customers in Google reviews as a hypothesis, not a proven cause of the rating. Document public observations, review dates, limitations and alternative explanations; do not dismiss negative feedback or invent results.

## Ethical customer engagement and privacy
- Invite honest reviews consistently from eligible customers regardless of sentiment; no review gating, incentives, fabricated reviews, pressure or suppression. Do not instruct customers to change or remove honest reviews. Keep complaint resolution independent of review requests.
- Use placeholders in message templates. Do not send customer communications, alter listings, scrape personal data or start a live pilot without company authorization. Use opt-in or other appropriate permissions for contact, respect opt-outs, restrict access and retention, and avoid unnecessary personal information.
- Use synthetic, clearly labeled sample data for demos; no real contact details or reviewer identifiers in Git. Do not claim that a pilot was adopted, that reviews increased or that ratings improved without evidence.

## Validation
- Check that each workflow specifies trigger, owner, steps, escalation, expected output and metric. Check templates for neutral language and realistic handover instructions.
- If scripts or dashboards are added, document actual toolchain, dependencies and reproducible test commands in pilot/README.md. Test with sample data; document limitations and whether any live validation was authorized and completed.

## Definition of done
Acceptance criteria addressed, appropriate checks performed or explicitly marked not run, relevant documentation updated, and limitations disclosed. A human reviewer decides whether the change is ready to merge.
