# Personal Homepage Update Guide

## Template for Homepage Updates

Based on email analysis, here's how your homepage should be updated when acceptance information becomes available:

### Before Acceptance Info Available

If you cannot confirm which papers have been accepted yet:

```markdown
## Publications

### Under Review
- **Paper Title** (under review)
  - Conference: TBD
  - Status: Under Review
  - Preprint: [Link to arXiv/OpenReview]

### Preprint
- **Paper Title** 
  - Status: Preprint
  - Conference: TBD
  - Preprint: [Link to preprint]
```

### After Acceptance Confirmation

Once you have confirmable acceptance emails:

#### For Accepted Papers

```markdown
### Conference Name (Year)

**Paper Title**
- **Status:** ✅ Accepted to Conference Name (Camera-ready deadline: MM/DD/YYYY)
- **Authors:** Your Name et al.
- **Venue:** Conference Name (YYYY)
- **Links:**
  - [OpenReview](link)
  - [arXiv](link) | [Preprint](link)
- **Code:** [GitHub Repository](url) *(add only when repository is released)*
- **Keywords:** machine learning, computer vision, etc.
```

#### Code Open-Source Status Update Rule

**Only update code availability when:**
1. Paper is accepted ✅
2. Associated GitHub repository is publicly available
3. Repository contains code related to the paper

**Do NOT add code links if:**
- Paper is still under review
- No repository exists for the paper
- Repository is private/not released

### Example Scenario

**Week 1 (Emails show camera-ready deadlines, but no personal confirmations):**
```markdown
### COML 2026
- [Paper A] - Status TBD (camera-ready deadline passed, waiting for acceptance notice)
- [Paper B] - Status TBD (check personal acceptance email)
```

**Week 2 (Personal acceptance email received):**
```markdown
### COML 2026 ✅

**Paper A Title** *(update to actual title)*
- **Status:** ✅ Accepted to COML 2026
- **Authors:** Baowenbo et al.
- **Venue:** Conference on Machine Learning (COML) 2026
- **Links:**
  - [OpenReview](https://openreview.net/...)
  - [arXiv:XXXX.XXXXX](https://arxiv.org/...)
  - [GitHub Repository](https://github.com/username/repo) *(only if released)*
```

**Week 3 (Repository released):**
```markdown
**Paper A Title**
- **Code:** [GitHub Repository](https://github.com/username/repo) ✅ Code released
```

## Step-by-Step Process

### Step 1: Identify Accepted Papers
1. Search your actual email inbox (not the newsletter emails)
2. Look for: "Congratulations!", "accepted", specific paper title
3. Verify author name matches your name

### Step 2: Update Paper Status
1. Change status from "preprint/under review" to "accepted"
2. Add conference name and year
3. Add acceptance date or camera-ready deadline
4. Update preprint link (may change from arXiv to conference version)

### Step 3: Link GitHub Repository (Only for Accepted Papers)
1. Check if paper has associated GitHub repository
2. Verify repository is public
3. Add "Code: [GitHub Link]" under paper details
4. Repository should contain code/materials related to the paper

### Step 4: Regular Home Page Maintenance
- Check emails weekly for acceptance notifications
- Update status immediately upon receipt
- Maintain draft versions of updates for batch processing

## File Structure Recommendation

```
website/
├── publications/
│   ├── preprint.md          # Papers as preprint
│   ├── under_review.md      # Papers under review
│   └── accepted.md          # Accepted papers (updated from preprint/under_review)
├── _config.yml             # Publication status tracking
└── index.md               # Master publication list
```

## GitHub Integration Checklist

- [ ] Paper acceptance confirmed via personal email
- [ ] Paper repository identified and public
- [ ] Repository URL matches paper title
- [ ] README includes citation instructions
- [ ] Repository contains paper code/data
- [ ] Home page updated with acceptance status
- [ ] Code link added (after repository release)

## Troubleshooting

### Problem: Emails are generic newsletters
**Solution**: Filter your inbox for terms like "Congratulations", paper titles, your name

### Problem: No GitHub repository found
**Solution**: 
1. Check if repository exists under different name
2. Search for related repositories that might contain paper code
3. Consider creating repository after acceptance

### Problem: Multiple papers submitted to same conference
**Solution**: List each paper separately with conference name + year

### Problem: Repository created before acceptance
**Solution**: Note "Code repository created" without making it publicly available until acceptance

## Current Status Tracking

| Paper Title | Current Status | Acceptance Confirmed | Repository | Update Needed |
|-------------|----------------|----------------------|------------|---------------|
| Paper 1     | preprint       | ⏳ Pending           | ❌ None    | Update        |
| Paper 2     | under review   | ⏳ Pending           | ❌ None    | Update        |
| ...         | ...            | ...                  | ...        | ...          |

## Next Update Priority

1. Locate and read actual acceptance emails (not newsletters)
2. Cross-reference with homepage current "preprint/under review" listings
3. Identify corresponding GitHub repositories
4. Apply updates systematically

---

**Generated:** 2026-05-29  
**Repository:** https://github.com/mazextest2026/baowenbo-personal-page  
**Based on Email Analysis:** `EMAIL_ANALYSIS.md`
