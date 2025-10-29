# Content Standard: Moderately Serious Tone Voice

## Metadata
```yaml
id: TONE-204
type: tone_voice
level: Global
source: Tone Analysis Engine
owner: Jason
version: 1.0
last_updated: 2025-10-24
related_standards: []
```

## Context
- **Domain**: UX content
- **Content type**: Onboarding
- **Field**: Playful vs. Serious tone positioning
- **Primitive**: Text strings, labels, interface copy

## Tone Definition
**Moderately Serious Tone**: Content should maintain a moderately serious approach across the playful vs. serious spectrum. This tone is positioned at 76% on the scale, creating formal, authoritative content that prioritizes precision and trustworthiness.

## Guidance

### Primary Tone Characteristics
- **Playful vs. Serious**: Moderately emphasis toward serious (76/100)
- **Consistency**: Maintain consistent tone positioning across similar content contexts
- **Context Awareness**: Adapt intensity while preserving core serious characteristics

### Linguistic Device Usage
- **Structural**: Use Complete sentences, Structured syntax, Longer sentences
- **Conversational**: Use Formal punctuation, Measured tone, Factual statements, Professional language, Consistent rhythm


### Content Application Rules
- Apply moderately serious approach to all onboarding
- Ensure tone consistency across user journey touchpoints
- Balance serious characteristics with clarity and usability
- Consider context appropriateness when applying tone guidelines

## Examples

### Correct Usage
#### In Interface Text:
- "Please complete your account setup."
- "Your progress has been recorded."
- "An error has occurred. Please contact support for assistance."

#### In Notifications:
- "File upload completed successfully"
- "Session will expire in 5 minutes"

### Incorrect Usage
#### Tone Misalignment:
- "Yay! We totally got your request!" (Too casual/playful)
- "Oopsie! Something went a bit wonky" (Inappropriate informality)

## Implementation

### Validation Rules
```json
{
  "tone_positioning": {
    "spectrum": "playful-serious",
    "target_range": [66, 86],
    "required_devices": ["Formal punctuation","Complete sentences","Structured syntax"],
    "context_appropriateness_threshold": 75
  }
}
```

### Automated Checks
```yaml
content_rules:
  - name: tone_spectrum_check
    trigger: content_analysis
    validation: tone_position_within_range
    error: "Content tone does not match moderately serious positioning"
    
  - name: device_usage_validation
    trigger: linguistic_analysis
    validation: required_devices_present
    warning: "Consider using recommended serious devices"
```

## Testing Criteria
- [ ] Content maintains moderately serious positioning (76 ±10 points)
- [ ] Required linguistic devices are appropriately used
- [ ] Tone consistency across similar content contexts
- [ ] Context appropriateness score above 75%
- [ ] No conflicting tone signals from opposing spectrum side

## Related Terms
- **Playful Characteristics**: Opposite positioning
- **Serious Characteristics**: Primary alignment
- **Spectrum Balance**: Positioned at 76% toward serious

---
*Standard applies to: Onboarding, ux content contexts, global-level implementation*

**Approval**: Jason, Content Standards Review Board  
**Review cycle**: Quarterly review, triggered by major tone positioning changes

---

Generated on 2025-10-24 using Interactive Tone Spectrum Analysis Tool
Spectrum: Playful vs. Serious | Position: 76/100 | Characteristic: Moderately Serious