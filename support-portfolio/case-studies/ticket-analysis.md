# Ticket Analysis Case Study: Identifying Recurring Issues Through Data

## 📋 Background

| **Company** | Vezir |
| **Role** | Customer Support |
| **Period** | Dec 2022 – Dec 2023 |

---

## 🎯 The Goal

As part of my role reviewing Jira tickets before escalation, I noticed that certain issues kept appearing repeatedly. I decided to analyze ticket data to:

- Identify the most common issues
- Find patterns in when and why they occurred
- Suggest process improvements to reduce ticket volume
- Help developers prioritize fixes

---

## 📊 Data Collection

### Step 1: Exporting Ticket Data

I exported all Jira tickets from the last 3 months:

| Metric                 | Value                                                |
| ---------------------- | ---------------------------------------------------- |
| Total tickets reviewed | 487                                                  |
| Time period            | 3 months                                             |
| Categories analyzed    | Issue type, priority, team assigned, resolution time |

---

### Step 2: Categorizing Issues

I created categories in Excel to group similar issues:

| Category             | Description                              | Ticket Count | % of Total |
| -------------------- | ---------------------------------------- | ------------ | ---------- |
| Budget filter issues | Filter not working, wrong prices showing | 48           | 9.9%       |
| Swipe/save issues    | Right swipes not saving to Liked list    | 35           | 7.2%       |
| Login problems       | Users unable to log in                   | 28           | 5.8%       |
| Payment failures     | Transactions not processing              | 25           | 5.1%       |
| App crashes          | App freezing or closing                  | 22           | 4.5%       |
| Search not working   | No results for valid searches            | 18           | 3.7%       |
| Other                | Miscellaneous issues                     | 311          | 63.8%      |

---

## 🔍 Analysis Findings

### Finding 1: Top 3 Issues Made Up 22% of All Tickets

| Rank | Issue                | Tickets | Impact |
| ---- | -------------------- | ------- | ------ |
| 1    | Budget filter issues | 48      | High   |
| 2    | Swipe/save issues    | 35      | High   |
| 3    | Login problems       | 28      | Medium |

**Action:** Focused on investigating these top issues first.

---

### Finding 2: Budget Filter Tickets Peaked at Specific Times

I created a weekly breakdown:

| Week   | Budget Filter Tickets | Notes                |
| ------ | --------------------- | -------------------- |
| Week 1 | 12                    | Normal volume        |
| Week 2 | 14                    | Increase noticed     |
| Week 3 | 11                    | Steady               |
| Week 4 | 9                     | Before escalation    |
| Week 5 | 3                     | After fix (75% drop) |
| Week 6 | 2                     | Continued drop       |
| Week 7 | 1                     | 90% reduction        |
| Week 8 | 1                     | Stable               |

**Insight:** Tickets dropped significantly after the fix was deployed.

---

### Finding 3: Swipe/Save Issues Were Most Common on Fridays and Saturdays

| Day       | Swipe Issues | % of Weekly Total |
| --------- | ------------ | ----------------- |
| Monday    | 3            | 8.6%              |
| Tuesday   | 2            | 5.7%              |
| Wednesday | 4            | 11.4%             |
| Thursday  | 5            | 14.3%             |
| Friday    | 8            | 22.9%             |
| Saturday  | 9            | 25.7%             |
| Sunday    | 4            | 11.4%             |

**Insight:** Issues peaked on weekends when user activity was highest.

---

### Finding 4: Average Resolution Time by Issue Type

| Issue Type           | Avg Resolution Time |
| -------------------- | ------------------- |
| Login problems       | 2 hours             |
| Budget filter issues | 4 hours             |
| Payment failures     | 6 hours             |
| Swipe/save issues    | 8 hours             |
| App crashes          | 12 hours            |

**Insight:** Swipe/save issues took the longest to resolve because they required developer investigation.

---

## 📈 Recommendations Made

Based on my analysis, I suggested:

### Recommendation 1: Fix Budget Filter First

- **Reason:** 48 tickets, high frequency, quick fix identified
- **Result:** 90% reduction after fix

### Recommendation 2: Add Weekend Monitoring for Swipe Issues

- **Reason:** Issues peaked on Friday/Saturday
- **Result:** Dev team added weekend monitoring, faster response times

### Recommendation 3: Create FAQ for Common Login Issues

- **Reason:** 28 tickets could be self-resolved
- **Result:** FAQ reduced login tickets by 40%

---

---

## 📈 Results & Impact

| Metric                     | Before   | After    | Improvement       |
| -------------------------- | -------- | -------- | ----------------- |
| Budget filter tickets/week | 10-15    | 1-2      | **90% reduction** |
| Swipe issues on weekends   | 8-9      | 2-3      | **70% reduction** |
| Login tickets              | 28/month | 17/month | **40% reduction** |
| Total tickets/month        | 160+     | 100      | **38% reduction** |

---

## 🛠️ Tools Used

| Tool           | Purpose                          |
| -------------- | -------------------------------- |
| **Jira**       | Ticket export and tracking       |
| **Excel**      | Data categorization and analysis |
| **Slack**      | Sharing findings with team       |
| **Confluence** | Documenting recommendations      |

---

## 💡 Skills Demonstrated

| Skill                   | How It Was Demonstrated                          |
| ----------------------- | ------------------------------------------------ |
| **Data Analysis**       | Categorized 487 tickets to find patterns         |
| **Pattern Recognition** | Identified peak times for swipe issues           |
| **Process Improvement** | Made recommendations that reduced tickets by 38% |
| **Reporting**           | Created clear charts and summaries               |
| **Communication**       | Shared findings with team and developers         |

---

> **Note**: All customer data anonymized. The actual work was performed at Vezir using their internal systems.

---

## 📌 Key Takeaways

- **Data-driven approach** helped identify the biggest problems
- **Top 3 issues** made up 22% of all tickets
- **Fixing the budget filter** reduced tickets by 90%
- **Weekend monitoring** caught swipe issues faster
- **38% overall reduction** in tickets after recommendations implemented
