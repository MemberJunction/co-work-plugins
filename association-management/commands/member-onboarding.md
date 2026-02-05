# /member-onboarding

Create a comprehensive new member onboarding experience for your association.

## Usage

```
/member-onboarding [member-type] [options]
```

## Arguments

- `member-type`: Type of member being onboarded (individual, corporate, student, affiliate, etc.)
- `--tier`: Membership tier if applicable (basic, professional, premium, etc.)
- `--industry`: Member's industry or sector
- `--interests`: Known areas of interest

## What This Command Does

When invoked, guide the user through creating a complete onboarding package:

### 1. Welcome Communication Sequence

Create a multi-touch welcome series:

**Day 0 - Immediate Welcome**
- Personalized welcome email from Executive Director/CEO
- Login credentials and member portal walkthrough
- Quick-start guide to immediate benefits

**Day 3 - Benefits Deep Dive**
- Detailed benefits guide customized to member type
- Featured resources based on stated interests
- Upcoming events calendar

**Day 7 - Community Introduction**
- Introduction to committees, SIGs, or chapters
- Volunteer opportunity overview
- Member directory access and networking tips

**Day 14 - Engagement Check-in**
- Survey on onboarding experience
- Personalized recommendations based on profile
- Invitation to upcoming new member orientation

**Day 30 - Value Reinforcement**
- Summary of benefits accessed/unused
- Success stories from similar members
- Renewal timeline preview

### 2. Member Portal Setup Checklist

Generate a checklist covering:
- Profile completion (photo, bio, contact preferences)
- Communication preferences setup
- Committee/SIG interest indication
- Directory listing opt-in
- Event notification preferences
- Publication subscription selections

### 3. New Member Orientation Materials

Create or customize:
- Association history and mission overview
- Governance structure explanation
- Key staff contacts
- Member rights and responsibilities
- Code of ethics/conduct overview
- FAQ document

### 4. Engagement Pathway Recommendations

Based on member type and interests, recommend:
- Relevant committees or special interest groups
- Upcoming events (prioritized by relevance)
- Certification or education programs
- Volunteer opportunities
- Mentorship programs (as mentor or mentee)

## Output Format

Deliver materials in requested format:
- Email-ready HTML templates
- Word/Google Docs for editing
- PDF for distribution
- Markdown for CMS integration

## Best Practices Applied

- Personalization based on member type and interests
- Value demonstration within first 30 days
- Multiple touchpoints without overwhelming
- Clear calls-to-action at each stage
- Feedback loop integration
- Accessibility compliance (WCAG 2.1 AA)

## Example

```
/member-onboarding corporate --tier=premium --industry=healthcare --interests="advocacy,education"
```

This generates a complete corporate member onboarding package tailored to a premium healthcare industry member interested in advocacy and education programs.
