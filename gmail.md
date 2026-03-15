# Configure Subject-Based Forwarding

1.  **Add Forwarding Address:** Go to **Settings** (gear icon) > **See all settings** > **Forwarding and POP/IMAP** tab. Click **Add a forwarding address**, enter the email, and verify it via the confirmation email.
    
2.  **Create Filter for Specific Subject:** In **Settings**, go to **Filters and Blocked Addresses** and click **Create a new filter**.
    
3.  **Define Subject Criteria:** In the "Subject" field, enter the specific words or phrases you want to filter (e.g., "ChatGPT code").
    
4.  **Set Action:** Click **Create filter**. Check the box **Forward it to:** and select the verified email address.
    
5.  **Save:** Click **Create filter** to activate the rule.

# Search filter
 - View only unread emails

```
   is:unread
```

 - View archive emails

```
   -in:Sent -in:Draft -in:Inbox has:nouserlabels

```
