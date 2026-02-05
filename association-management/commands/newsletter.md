# /newsletter

Create engaging member newsletters and email communications.

## Usage

```
/newsletter [type] [options]
```

## Arguments

- `type`: Newsletter type (weekly-digest, monthly, quarterly, special-announcement, advocacy-alert)
- `--audience`: Target segment (all-members, committee, chapter, tier-specific)
- `--theme`: Optional thematic focus
- `--tone`: Professional, conversational, urgent, celebratory

## What This Command Does

Generate publication-ready newsletter content:

### 1. Content Structure

**Header Section**
- Compelling subject line (A/B test variants)
- Preview text optimization
- Personalization tokens
- Brand-consistent header design guidance

**Opening**
- Executive message or letter (when appropriate)
- Hook that drives continued reading
- Table of contents for longer newsletters

**Feature Content**
- Lead story with strong headline
- Supporting visual recommendations
- Pull quotes for scanning
- Clear value proposition

**Regular Sections**
Based on newsletter type, include relevant sections:

*Member News*
- New member welcomes
- Member achievements/awards
- Career transitions
- Milestones (anniversaries, retirements)

*Association Updates*
- Program announcements
- Policy updates
- Staff news
- Governance updates

*Industry Intelligence*
- Regulatory updates
- Market trends
- Research summaries
- Competitive landscape

*Events & Education*
- Upcoming events with registration CTAs
- Webinar announcements
- Certification deadlines
- Conference updates

*Resources*
- New publications
- Tool releases
- Partner offerings
- Job board highlights

*Advocacy Corner*
- Legislative updates
- Call-to-action opportunities
- Wins and progress
- Key dates

**Closing**
- Summary of key CTAs
- Social media links
- Contact information
- Unsubscribe/preferences link

### 2. Subject Line Options

Generate 5-7 subject line variants optimized for:
- Open rate (curiosity, urgency, value)
- Deliverability (avoiding spam triggers)
- Brand voice consistency
- Mobile display (front-loaded key info)

### 3. Segmentation Recommendations

Suggest content variations for:
- Member tenure (new vs. long-term)
- Engagement level (active vs. lapsed)
- Membership tier
- Geographic region
- Interest areas

### 4. Visual Guidelines

Provide guidance on:
- Image placement and sizing
- Alt text for accessibility
- Color usage within brand
- Mobile responsiveness
- Dark mode compatibility

### 5. Metrics Framework

Include tracking recommendations:
- Open rate benchmarks by type
- Click-through goals
- Conversion tracking setup
- Heat map analysis suggestions
- A/B testing protocol

## Best Practices Applied

- 50/50 rule: 50% industry value, 50% association news
- Scannable format with clear hierarchy
- Single primary CTA per section
- Mobile-first design (60%+ opens on mobile)
- Accessibility compliance
- GDPR/CAN-SPAM compliance elements
- Personalization beyond "Dear [Name]"

## Output Formats

- HTML email template
- Plain text version
- Web archive version
- Social media snippets
- Content calendar entry

## Example

```
/newsletter monthly --audience=all-members --theme="annual conference preview" --tone=celebratory
```

Creates a monthly newsletter focused on building excitement for the upcoming annual conference.
