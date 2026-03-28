### Ticket #2: Identify the Attacker
The server was targeted by a brute-force attack. There is a massive log file named `server_access.log` in your home directory.

**Your Tasks:**
1. Use the `grep` command to search for the word **"FAILED"** inside the log.
2. Identify the **IP Address** and the **Timestamp** of the failed attempt.

**Command Hint:** `grep "TEXT_TO_FIND" filename`
