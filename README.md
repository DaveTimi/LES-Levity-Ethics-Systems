# LES — Levity Ethics Systems

> LES — Levity Ethics Systems, a product of Dave Timi Tech Systems.

LES is a modern, multi-tenant **Education Operating System** for schools. It unifies school management, student information, academic operations, finance, communication, virtual classrooms, analytics, and AI-assisted learning into one scalable SaaS platform.

This repository is built incrementally, folder by folder, following a strict architectural and security discipline. Every commit is intended to be reproducible from the folder-by-folder build instructions.

---

## Product Scope

LES targets the following audiences with granular, backend-enforced permissions:

1. LES Super Admin
2. School Owner
3. School Administrator
4. Principal
5. Vice Principal
6. Teacher
7. Bursar / Finance Officer
8. Staff
9. Parent / Guardian
10. Student

Major capability areas:

- School Management System
- Student Information System (Student 360)
- Academic Management (sessions, terms, classes, subjects, timetables)
- Attendance
- Assignments and Submissions
- Assessments, Exams, Results, Report Cards
- School Finance (fees, invoices, payments, receipts)
- Communication (announcements, notifications, messaging)
- Virtual Classroom
- Documents and Learning Materials
- Reports and Analytics
- AI Educational Assistant (Cloudflare Workers AI — GPT-6 Astra)
- Subscription Management and Online Payments
- Manual Activation and Activation Codes
- Public School Websites
- LES Public Marketing Website

---

## Architecture Overview

LES is a monorepo composed of applications and shared packages.
