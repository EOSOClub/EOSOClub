# 🐛 Bug Reports & Testing Guide

<p align="center">
  <strong>Help Us Build Better Bots • Clear Reports = Faster Fixes</strong>
</p>

---

## 🚨 How to Report Issues

### 📋 Choose the Right Place
- **For Technical Bugs:** [Open a GitHub Issue](https://github.com/Empire-of-Shadows/ImperialCodex/issues)
- **For Urgent/General Issues:** [Submit in Discord](https://discord.gg/Vfd2rykvMp) → `#bug-reports`

### 🎯 Priority Guide
| Issue Type | Where to Report | Response Time |
|------------|-----------------|---------------|
| **Bot is crashing** | Discord → `#bug-reports` | Immediate |
| **Feature not working** | GitHub Issues | 1-2 days |
| **Suggestion/Improvement** | Discord → `#suggestions` | 1 week |
| **General question** | Discord → `#bot-help` | A few hours |

---

## 📝 The Perfect Bug Report

### ✅ **DO: Provide Clear Information**
```markdown
**Bot:** Economy Bot
**Command:** /daily reward
**What Happened:** Command timed out, got "Interaction failed" error
**What Should Happen:** Should receive daily coins and confirmation
**When:** Today at 2:30 PM EST
**Steps to Reproduce:**
1. Type `/daily reward`
2. Press Enter
3. Wait 30 seconds
4. See error message
```

### ❌ **DON'T: Be Vague**
```markdown
**Bad Example:** "The bot is broken"
**Bad Example:** "Economy not working"
**Bad Example:** "I got an error"
```

---

## 🖼️ Including Images & Evidence

### ✅ **DO: Capture Helpful Screenshots**
- **Full error messages** with timestamps
- **Command usage** and responses
- **Relevant context** (channel, user roles, etc.)
- **Console errors** if available

### ❌ **DON'T: Share Unhelpful Images**
- **Blurry or cropped** screenshots
- **Personal information** or private messages
- **Unrelated content**

**Example Good Screenshot:**
> [Image showing clear error message, command used, and timestamp]

---

## 🔍 Testing New Features & Updates

### 🧪 **Before Reporting: Quick Checks**
- ✅ **Command syntax is correct** (check `/help`)
- ✅ **Try the command twice** to rule out temporary issues
- ✅ **Check if others have the same problem**

### 📊 **Performance Testing**
```markdown
**Response Time:** [Fast/Slow/Times out]
**Reliability:** [Works every time/Intermittent/Never works]
**User Impact:** [Affects everyone/Just me/Specific users]
```

---

## 🎯 Examples: Good vs Bad Reports

### ✅ **EXCELLENT REPORT**
```markdown
**Bot:** Music Bot  
**Issue:** Skip command not working in specific channel  
**Steps:**  
1. Join "General Voice" channel  
2. Play song with `!play https://youtube.com/...`  
3. Use `!skip` command  
4. Bot responds "No songs in queue" but song continues playing  
**Evidence:** [Screenshot showing queue and error]  
**Frequency:** Happens every time in this channel  
```

### ❌ **POOR REPORT**
```markdown
"music bot skip broken fix pls"
```

### ✅ **GOOD FEEDBACK**
```markdown
**Feature:** Level System  
**Observation:** Level up notifications are hard to see  
**Suggestion:** Add a brighter color or ping the user  
**Benefit:** Would make achievements more noticeable  
```

---

## 🔧 For Developers: Issue Labels

| Label | Meaning | Who Should Use |
|-------|---------|----------------|
| `bug` | Something is broken | Everyone |
| `enhancement` | Improvement to existing feature | Everyone |
| `feature-request` | New functionality request | Everyone |
| `help-wanted` | Need development assistance | Developers |
| `priority-high` | Critical issue affecting many users | Moderators+ |

---

## ⏰ Response Expectations

- **Critical Issues** (Bot down, security): < 24 hours
- **Major Bugs** (Feature broken): 1-3 days  
- **Minor Issues** (Cosmetic, small bugs): 1-2 weeks
- **Feature Requests**: Reviewed monthly

---

## 🎁 Rewards for Good Reports

**We appreciate detailed bug reports!**  
- I cant really do much but a pat on the back and a thank you!

---

## 📞 Emergency Contacts

**For urgent bot issues (complete downtime):**
- Ping `@EOSOfficial` in Discord
- Use `@Moderator` role for immediate attention

**For everything else:**
- Use the appropriate channels above
- Be patient - we're a small team!

---

<p align="center">
  <em>Your clear reports help us build a better experience for everyone! 🛠️</em>
</p>

<div align="center">

[![Report on GitHub](https://img.shields.io/badge/📝-Open%20GitHub%20Issue-4d0eb3?style=for-the-badge&logo=github&logoColor=white&labelColor=000000)](https://github.com/Empire-of-Shadows/ImperialCodex/issues)
[![Get Help on Discord](https://img.shields.io/badge/💬-Discord%20Support-4d0eb3?style=for-the-badge&logo=discord&logoColor=white&labelColor=333333)](https://discord.gg/Vfd2rykvMp)

</div>

This guide provides:
- Clear pathways for different issue types
- Specific examples of good vs bad reports
- Visual guidance for screenshots
- Testing checklist before reporting
- Realistic expectations for response times
- Rewards to encourage quality reporting

It's structured to help community members provide the exact information you need to efficiently debug and fix issues!
