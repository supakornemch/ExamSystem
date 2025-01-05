# Project Structure
```
- app/
  - admin/
    - dashboard/
      - page.tsx
  - api/
    - auth/
      - login/
        - route.ts
      - logout/
        - route.ts
      - me/
        - route.ts
    - exams/
      - route.ts
    - questions/
      - route.ts
    - user/
      - exams/
        - route.ts
  - favicon.ico
  - globals.css
  - layout.tsx
  - login/
    - page.tsx
  - page.tsx
  - user/
    - dashboard/
      - page.tsx
    - exams/
      - [id]/
        - documents/
          - page.tsx
        - page.tsx
      - page.tsx
    - profile/
      - page.tsx
    - results/
      - page.tsx
- components/
  - AdminNavbar.tsx
  - ExamTimer.tsx
  - LogoutButton.tsx
  - Navbar.tsx
  - UserNavbar.tsx
  - admin/
    - ExamForm.tsx
- contexts/
  - AuthContext.tsx
- data/
  - mock.ts
- lib/
  - mongodb.ts
  - prisma.ts
- middleware.ts
- types/
  - auth.ts
  - index.ts
```