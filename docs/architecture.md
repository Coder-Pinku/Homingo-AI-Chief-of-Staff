┌─────────────────────────────────────────────┐
│                  USER                       │
│  Chat | Voice | Dashboard Interaction       │
└─────────────────────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────┐
│           React Frontend Dashboard          │
│                                             │
│ • Daily Briefing                            │
│ • Tasks & Reminders                         │
│ • Email Summary                             │
│ • Calendar View                             │
│ • Notifications                             │
└─────────────────────────────────────────────┘
                      │
                REST API
                      │
                      ▼
┌─────────────────────────────────────────────┐
│             FastAPI Backend                 │
└─────────────────────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────┐
│         CHIEF OF STAFF AGENT                │
│                                             │
│ • Understand User Intent                    │
│ • Plan Actions                              │
│ • Delegate Work                             │
│ • Combine Results                           │
└─────────────────────────────────────────────┘
           │           │           │
           │           │           │
           ▼           ▼           ▼
┌──────────────┐ ┌──────────────┐ ┌──────────────┐
│ Email Agent  │ │ Task Agent   │ │CalendarAgent│
└──────────────┘ └──────────────┘ └──────────────┘
           │           │           │
           ▼           ▼           ▼
    Email Analysis  Task Creation  Scheduling

                      │
                      ▼

             ┌───────────────┐
             │Reminder Agent │
             └───────────────┘
                      │
                      ▼
              Smart Alerts
              Daily Briefing
              Due Reminders

──────────────────────────────────────────────

              External Integrations

          ┌─────────────────────┐
          │ Gmail / Outlook     │
          └─────────────────────┘

          ┌─────────────────────┐
          │ Google Calendar     │
          │ Outlook Calendar    │
          └─────────────────────┘

          ┌─────────────────────┐
          │ Notification APIs   │
          └─────────────────────┘

──────────────────────────────────────────────

              Intelligence Layer

          ┌─────────────────────┐
          │ Gemini / OpenAI     │
          │ LLM Processing      │
          └─────────────────────┘

──────────────────────────────────────────────

                Data Layer

          ┌─────────────────────┐
          │ SQLite Database     │
          │                     │
          │ Users               │
          │ Tasks               │
          │ Reminders           │
          │ Agent Logs          │
          │ Preferences         │
          └─────────────────────┘
