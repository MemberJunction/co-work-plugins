# /retention-campaign

Design and execute member retention and renewal campaigns.

## Usage

```
/retention-campaign [campaign-type] [options]
```

## Arguments

- `campaign-type`: Type of campaign (renewal-series, win-back, at-risk, loyalty, anniversary)
- `--segment`: Target member segment
- `--timeline`: Campaign duration or renewal period
- `--channels`: Communication channels to use
- `--incentive`: Available incentive budget/type

## What This Command Does

Generate comprehensive retention campaign materials:

### 1. Member Analysis Framework

**Retention Metrics Baseline**
- Current retention rate by segment
- Churn patterns and timing
- Lifetime value by member type
- Cost of acquisition vs. retention
- Revenue at risk

**At-Risk Indicators**
- Engagement scoring model
- Warning sign identification:
  - Declining event attendance
  - Reduced email engagement
  - No login activity
  - Lapsed CE/certification
  - Payment issues
  - Complaint history
  - No committee/volunteer involvement

**Segmentation Strategy**
- High-value/high-risk priority
- Engagement-based segments
- Tenure-based segments
- Tier/type segments
- Geographic segments

### 2. Renewal Campaign Series

**Pre-Renewal Phase (90-60 days)**

*Touch 1: Value Summary*
- Personalized benefit utilization report
- ROI calculator/demonstration
- Member success stories
- Upcoming opportunities preview

*Touch 2: Engagement Invitation*
- Relevant event invitation
- Committee/volunteer opportunity
- Exclusive content offer
- Peer connection opportunity

**Active Renewal Phase (60-0 days)**

*Touch 3: Renewal Notice*
- Clear renewal call-to-action
- Pricing information
- Easy renewal process
- Early renewal incentive (if applicable)

*Touch 4: Reminder*
- Deadline emphasis
- Benefit reminder
- Testimonial from peer
- Support offer

*Touch 5: Urgency*
- Final deadline warning
- What you'll miss messaging
- Last chance incentive
- Personal outreach trigger

**Grace Period (0-30 days post-expiration)**

*Touch 6: We Miss You*
- Acknowledgment of lapse
- Easy reinstatement offer
- Feedback request
- Benefits suspension notice

*Touch 7: Final Opportunity*
- Last retention offer
- Exit survey invitation
- Door left open messaging

### 3. Win-Back Campaign

For lapsed members (30+ days expired):

**Reactivation Series**
- "We want you back" outreach
- Changes since departure
- Special return offer
- Peer testimonial
- Easy rejoining process

**Win-Back Offers**
- Discounted dues
- Extended trial period
- Bonus benefits
- Payment flexibility
- Complimentary event access

### 4. At-Risk Intervention

Proactive outreach for identified at-risk members:

**High-Touch Approach**
- Personal call from staff
- Board member outreach
- Peer-to-peer connection
- Customized value review
- Problem resolution

**Re-Engagement Tactics**
- Exclusive content access
- Event invitation with incentive
- Mentorship opportunity
- Leadership pathway
- Recognition opportunity

### 5. Loyalty Program Design

Rewarding engaged members:

**Recognition Tiers**
- Tenure milestones
- Engagement levels
- Contribution recognition
- Ambassador status

**Loyalty Benefits**
- Exclusive access
- Priority registration
- Pricing advantages
- Recognition opportunities
- VIP experiences

### 6. Communication Templates

**Email Templates**
- Each touch in renewal series
- Win-back messages
- At-risk outreach
- Loyalty recognition

**Phone Scripts**
- Renewal call guide
- At-risk intervention
- Win-back conversation
- Exit interview

**Direct Mail**
- Renewal package
- At-risk personal letter
- Loyalty recognition

**Digital**
- Website banners
- Portal notifications
- SMS reminders (if opted in)
- Social media retargeting

### 7. Feedback Integration

**Renewal Survey**
- Satisfaction assessment
- Value perception
- Improvement suggestions
- Testimonial opportunity

**Exit Survey**
- Reason for non-renewal
- Competitive intelligence
- What would bring you back
- Final feedback

**At-Risk Survey**
- Engagement barriers
- Unmet needs
- Improvement priorities

### 8. Campaign Metrics Dashboard

Track and measure:
- Renewal rate by segment
- Response rates by channel
- Conversion rates by touch
- Incentive effectiveness
- Revenue retained
- Cost per save
- Net Promoter Score changes

## Best Practices Applied

- Start early (90+ days pre-expiration)
- Personalize based on engagement data
- Multi-channel approach
- Value demonstration over asking
- Make renewal easy (one-click, auto-renew)
- Human touch for high-value members
- Test and optimize continuously
- Learn from exits

## Output Formats

- Complete campaign calendar
- Email templates (HTML ready)
- Phone scripts
- Direct mail designs
- Reporting dashboard template

## Example

```
/retention-campaign renewal-series --segment="professional tier members" --timeline="Q4 renewals" --channels="email,phone,direct-mail" --incentive="early bird discount"
```

Creates a multi-channel renewal campaign for professional tier members renewing in Q4.

---

*Powered by [Sidecar](https://sidecar.ai) — AI for Associations*
