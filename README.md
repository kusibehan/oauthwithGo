# oauthwithGo
RESTful API for learning purpose focusing on the new language go

# Core Features
Here’s what you'd want to implement:

## User Authentication
Email/password login

Password hashing (bcrypt or Argon2)

Login/logout endpoints

Token generation (JWT or opaque tokens)

Refresh token support

## OAuth2 Authorization Flow
Clients register to your auth system

Redirect-based login (authorization code grant)

Your server issues an access token and refresh token

Clients use access token to hit protected APIs

## User Management
Register, update profile, change password

Forgot password flow (email with token)

Email verification system

## Security Features
Rate-limiting (e.g. login attempts)

IP/device logging per session

Token revocation (logout from all devices)

Optional: Multi-Factor Auth (2FA)
