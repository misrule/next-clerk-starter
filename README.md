# Next-Clerk-Starter

NextJS 13.4 with Clerk Authentication (and Tailwind)

### Getting Started

Create repo from this template:
```
gh create repo <repo-name> --public --clone --template https://github.com/misrule/template-test-1.git
```

Create .env file and copy Clerk variables (dashboard.clerk.com)
```
# /.env.local

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=<your-key>
CLERK_SECRET_KEY=<your-secret>
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/auth/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/auth/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/dashboard
```

NPM install then run dev.
