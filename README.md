policy.csv: |
    # p, role:developer, applications, get, myproject/*, allow
    # │  │               │             │   │             │
    # │  │               │             │   │             └── allow or deny
    # │  │               │             │   └── WHERE
    # │  │               │             └── ACTION
    # │  │               └── RESOURCE
    # │  └── role name
    # └── p means policy
    p, role:developer, applications, get, myproject/*, allow


Below is a table that summarizes all possible resources and which actions are valid for each of them.
<img width="749" height="451" alt="Screenshot 2026-06-03 at 6 27 04 AM" src="https://github.com/user-attachments/assets/3a29fbbc-e67a-4bd3-beb9-421b58adb5b2" />
