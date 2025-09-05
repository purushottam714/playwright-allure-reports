# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - generic [ref=e3]:
    - generic [ref=e4]:
      - img "Background pattern" [ref=e6]
      - img "Rainyday Parents Logo" [ref=e8]
    - generic [ref=e9]:
      - generic [ref=e10]:
        - heading "Login with OTP" [level=1] [ref=e11]
        - paragraph [ref=e12]:
          - text: Enter the 6-digit code sent to
          - generic [ref=e13]: admin.devrainyday@yopmail.com
        - generic [ref=e14]:
          - textbox [ref=e15]
          - textbox [ref=e16]
          - textbox [ref=e17]
          - textbox [ref=e18]
          - textbox [ref=e19]
          - textbox [ref=e20]
        - button "Resend Code" [ref=e21] [cursor=pointer]:
          - img [ref=e22] [cursor=pointer]
          - text: Resend Code
      - button "Go Back" [ref=e28] [cursor=pointer]
  - region "Notifications (F8)":
    - list
  - alert [ref=e29]
```