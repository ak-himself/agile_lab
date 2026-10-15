# HTA-16 — Health Dashboard Wireframe

**Jira story:** [HTA-16 — Health Dashboard Wireframes and Interactive Prototype](https://akhimself.atlassian.net/browse/HTA-16)  
**Status:** Design proposal for review; this is not a production UI implementation.

## Layout proposal

```text
┌──────────────────────────────────────────────────────────────┐
│ HealthTracker                                      Profile    │
├──────────────────────────────────────────────────────────────┤
│ Good morning                                                │
│ Your health overview                                        │
│                                                              │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐ │
│ │ Steps           │ │ Sleep           │ │ Heart rate      │ │
│ │ 6,240 / 8,000   │ │ 7 h 25 min      │ │ 72 bpm          │ │
│ │ [progress bar]  │ │ [duration bar]  │ │ [view trend]    │ │
│ └─────────────────┘ └─────────────────┘ └─────────────────┘ │
│                                                              │
│ Activity this week                                           │
│ [weekly chart with text labels and accessible description]   │
│                                                              │
│ Recent measurements                         [View all]       │
│ • Weight — latest recorded value and date                    │
│ • Blood pressure — latest recorded value and date             │
│                                                              │
│ Home       Trends       Measurements       Settings           │
└──────────────────────────────────────────────────────────────┘
```

## Interaction and accessibility notes

- Each metric card opens a detail view with history and the date/time of its latest measurement.
- Provide a clear empty state when no measurement has been recorded; do not invent sample values in the live product.
- Loading and error states must explain what happened and provide a retry action where appropriate.
- Charts need a text summary or tabular alternative; meaning must not rely on color alone.
- Use descriptive labels, keyboard-visible focus, adequate contrast, and controls with accessible names.
- On narrow screens, metric cards stack vertically and primary navigation remains usable without horizontal scrolling.
- Health data is sensitive: show only the signed-in user's authorized data and avoid exposing values in notifications by default.

## Acceptance checklist for review

- [ ] Product owner reviews the layout and metric-card hierarchy.
- [ ] Designer confirms responsive behavior for narrow and wide viewports.
- [ ] QA reviews empty, loading, error, and populated states.
- [ ] Accessibility review covers keyboard navigation, contrast, labels, and non-color chart interpretation.
- [ ] Any implementation pull request links back to HTA-16 and is merged before the story can be considered Done.

## Scope note

This file is a low-fidelity design proposal to review in the pull request. It does not claim that a working frontend or interactive prototype has been implemented.