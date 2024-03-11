**Issue Summary:**

- **Duration:** 
  - Start Time: March 10, 2024, 8:00 PM (WAT)
  - End Time: March 11, 2024, 2:00 AM (WAT)
- **Impact:** 
  - The service outage affected 80% of users.
  - Users experienced connectivity issues and slower response times.
- **Root Cause:** 
  - A database deadlock caused by a misconfigured caching layer.

**Timeline:**

- **9:00 PM:** Issue detected through monitoring alerts.
- **9:15 PM:** Alx Engineers initiated investigation.
- **10:00 PM:** Initial assumption of network-related issue.
- **11:00 PM:** Database queries found to be slow.
- **12:00 AM:** Suspected hardware failure.
- **1:00 AM:** Alx Engineers identified misconfigured caching layer as root cause.
- **2:00 AM:** Incident resolved by reconfiguring caching layer.

**Root Cause and Resolution:**

- **Root Cause Explanation:** 
  - Misconfigured caching layer led to database deadlocks.
  - Deadlocks occurred due to conflicting processes.
- **Resolution Details:** 
  - Caching layer reconfigured to prevent deadlocks.
  - Database queries optimized to reduce future issues.

**Corrective and Preventative Measures:**

- **Improvements/Fixes:**
  - Implement automated monitoring for database deadlocks.
  - Regular audits of caching configurations.
- **Tasks to Address the Issue:**
  - Update caching layer configurations to avoid conflicts.
  - Deploy additional monitoring tools for faster detection.
  - Schedule routine performance audits to maintain system stability.
