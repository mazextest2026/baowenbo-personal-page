# TODO: Personal Homepage Update

## Summary
- Analyzed 17 conference notification emails
- Created tracking repository
- Need additional information to complete homepage update

## Actions Needed

### Phase 1: Information Gathering
- [ ] **Confirm email context**
  - Determine if `timothyb@mcp.com` is associated with Baowenbo
  - Locate actual personal email addresses
  - Identify if multiple email accounts are involved

- [ ] **Find actual acceptance notifications**
  - Search inbox for personal "Congratulations" emails
  - Filter by paper titles you've submitted
  - Look for emails addressed to "Dr. Baowenbo" or similar

- [ ] **Locate current homepage**
  - URL of personal homepage
  - Where papers are currently listed
  - What status shows for "preprint" and "under review" papers

- [ ] **Verify GitHub account**
  - Username for repositories
  - Check repositories for code
  - Identify which repositories correspond to which papers

### Phase 2: Status Confirmation
- [ ] **Match emails to papers**
  - Which paper titles are mentioned in accepted emails?
  - Which conference deadlines correspond to accepted papers?
  - What is the acceptance date/detail?

- [ ] **Verify repositories for accepted papers**
  - Only add repositories for papers that are accepted
  - Ensure repository is public
  - Confirm repository contains paper code/data

### Phase 3: Homepage Update
- [ ] **Update paper statuses**
  - Change "preprint" → "✅ Accepted to [Conference]"
  - Change "under review" → "✅ Accepted to [Conference]"
  - Add deadline/camera-ready information

- [ ] **Add repository links**
  - Only for accepted papers with public repositories
  - Format: `[GitHub Repository](url) ✅ Code released`

- [ ] **Maintain proper status flow**
  - Preprint → Under Review → Accepted → Code Released
  - Skip steps if not applicable

## Blockers

🚨 **Cannot proceed without:**
1. Confirmation of correct email address context
2. Actual acceptance notification emails (not newsletters)
3. Current homepage structure/format
4. GitHub username and repositories

## Resources Created

- 📊 [EMAIL_ANALYSIS.md](./EMAIL_ANALYSIS.md) - Complete email review
- 📋 [HOMEPAGE_UPDATE_GUIDE.md](./HOMEPAGE_UPDATE_GUIDE.md) - Update workflow
- 🗂️ [papers.json](./papers.json) - Paper tracking structure
- 📦 [REPOSITORIES.md](./REPOSITORIES.md) - Repository documentation

## Key Finding

**All 17 emails are generic newsletters** sent to `timothyb@mcp.com`
- They show camera-ready deadlines for COML, COLM, COAI 2026
- Greetings use "Dr. John Smith" (generic placeholder)
- **No personal acceptance notifications found**
- No paper titles you submitted are mentioned

## Recommendation

Check your actual email inbox for personal notifications containing:
- Your name
- Specific paper titles
- Content like: "Congratulations on the acceptance of your paper..."
- From: program chairs, conference organizers

These emails will provide the confirmation needed to update the home page accurately.

---

**Last Updated:** 2026-05-29  
**Status:** Blocked - Waiting for user context
