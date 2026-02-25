# Draft Email

Draft a professional email based on a described situation or purpose.

## Variables

- request: $ARGUMENTS (required — describe who the email is to, what it's about, and the desired tone or outcome, e.g., "follow up with client after proposal meeting, friendly but professional, remind them of next steps")

## Instructions

This command demonstrates a simple, high-frequency task command. Most knowledge workers write dozens of emails per week — this standardizes the process so Claude writes in your voice and context.

### Step 1: Context

Read `context/personal-info.md` to understand the user's role and how they relate to others. This informs tone, authority level, and what context the user would naturally have.

### Step 2: Draft

Write the email based on the request. Follow these principles:
- Match the tone specified (or default to professional and warm)
- Be concise — respect the recipient's time
- Include a clear call to action or next step where appropriate
- Write as the user, not as an AI assistant
- No filler phrases like "I hope this email finds you well" unless specifically requested

### Step 3: Output

Display the draft directly in the terminal for the user to review, copy, and send.

Format as:
```
Subject: [suggested subject line]

[email body]
```

Ask the user if they want any adjustments before considering the task complete.