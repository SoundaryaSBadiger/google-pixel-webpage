# Google Pixel Webpage — Frontend UI Project
A multi-page frontend web application designed to replicate the user interface and navigation flow of a Google Pixel–style website. The project consists of interconnected HTML pages with dedicated CSS stylesheets, focusing on responsive UI design, page navigation, form layouts, and frontend user-flow implementation.

---

## Project Overview
This project demonstrates the development of a **static multi-page web interface** using core frontend technologies.
The application includes multiple screens representing common website and authentication flows:
- Home / Landing Page
- Login
- Sign Up
- OTP Verification
- Forgot Password
- Product / Webpage Interface
- Individual page styling
Each HTML page is paired with a dedicated CSS stylesheet to maintain **modularity, maintainability, and separation of concerns**.

---

## Application Workflow

```text
                    ┌──────────────────┐
                    │   Landing Page   │
                    │     hp.htm       │
                    └────────┬─────────┘
                             │
                ┌────────────┴────────────┐
                │                         │
                ▼                         ▼
        ┌──────────────┐          ┌──────────────┐
        │    Login     │          │   Sign Up    │
        │   login.htm  │          │ sign-up.htm  │
        └──────┬───────┘          └──────┬───────┘
               │                         │
               ▼                         ▼
        ┌──────────────┐          ┌──────────────┐
        │     OTP      │          │     OTP      │
        │    otp.htm   │          │    otp.htm   │
        └──────┬───────┘          └──────────────┘
               │
               ▼
        ┌──────────────────┐
        │   Web Content /  │
        │   Main Interface │
        └──────────────────┘

               Login
                 │
                 ▼
        ┌──────────────────┐
        │  Forgot Password │
        │   forgot.html    │
        └──────────────────┘

## How It Works (Workflow)

```text
Login
  │
  ├──► Enter Credentials
  │
  ├──► Authentication Interface
  │
  └──► OTP Verification
             │
             ▼
      Verification Interface


Forgot Password
       │
       ▼
Password Recovery Interface

Password Recovery Interface

