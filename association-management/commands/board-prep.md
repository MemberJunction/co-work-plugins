# /board-prep

Prepare comprehensive board meeting materials and executive briefings.

## Usage

```
/board-prep [meeting-type] [options]
```

## Arguments

- `meeting-type`: Type of board meeting (regular, annual, special, strategic, executive-session)
- `--date`: Meeting date for timeline planning
- `--format`: In-person, virtual, or hybrid
- `--duration`: Expected meeting length
- `--focus`: Primary focus areas for this meeting

## What This Command Does

Generate complete board meeting preparation materials:

### 1. Meeting Agenda

Create a structured agenda including:

**Consent Agenda Items**
- Previous meeting minutes approval
- Committee reports (written)
- Routine policy renewals
- Financial statements (if no discussion needed)

**Discussion Items**
- Strategic initiatives updates
- Policy decisions requiring debate
- Budget considerations
- Member feedback summaries

**Action Items**
- Motions requiring votes
- Resolution considerations
- Election/appointment matters

**Executive Session** (if needed)
- Personnel matters
- Legal issues
- Sensitive negotiations

**Time allocations** for each section with buffer time built in

### 2. Board Book/Packet

Compile comprehensive pre-read materials:

**Executive Summary**
- Key decisions needed (1-page max)
- Critical metrics dashboard
- Risk/opportunity highlights

**Financial Reports**
- Statement of financial position
- Statement of activities (budget vs. actual)
- Cash flow summary
- Investment portfolio update
- Variance explanations for items >10%

**Operational Reports**
- Membership metrics (acquisition, retention, engagement)
- Program performance summaries
- Staff updates
- Technology/infrastructure status

**Committee Reports**
- Standardized format for each committee
- Recommendations requiring board action
- Upcoming committee activities

**Strategic Plan Progress**
- Goal-by-goal status update
- KPI dashboard
- Adjustment recommendations

### 3. Pre-Meeting Communications

Draft communications for:
- Meeting notice (with logistics)
- Board packet distribution cover memo
- RSVP and dietary/accessibility requests
- Pre-meeting preparation suggestions
- Conflict of interest reminder

### 4. Meeting Support Materials

Prepare:
- Attendance/quorum tracking sheet
- Voting record template
- Action item capture template
- Parking lot for deferred items
- Robert's Rules quick reference (if applicable)

### 5. Post-Meeting Templates

- Draft minutes template
- Action item summary for distribution
- Board member follow-up assignments
- Communication to staff/members (if applicable)

## Governance Best Practices Applied

- Consent agenda for routine items (saves 30%+ meeting time)
- Executive summary for busy board members
- Clear distinction between information, discussion, and action items
- Appropriate lead time for material distribution (7-10 days minimum)
- Accessibility of materials (readable fonts, alt text, etc.)

## Output Formats

- PDF board book with hyperlinked table of contents
- Individual documents for CMS upload
- Presentation slides for hybrid meetings
- Mobile-friendly summary version

## Example

```
/board-prep regular --date="2024-03-15" --format=hybrid --duration=3h --focus="budget approval, strategic plan review"
```

Generates complete board packet for a 3-hour hybrid meeting focused on budget approval and strategic plan review.

---

*Powered by [Sidecar](https://sidecar.ai) — AI for Associations*
