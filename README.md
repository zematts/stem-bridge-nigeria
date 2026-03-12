# 🌍 STEM Bridge Nigeria — Empowering the Next Generation of Female STEM Leaders

> A digital platform supporting girls in Nigeria and across developing countries with STEM education, mentorship, scholarships, and career pathways — bridging the gender gap in Science, Technology, Engineering, and Mathematics.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Mission & Vision](#mission--vision)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Programs & Initiatives](#programs--initiatives)
- [Impact](#impact)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

STEM Bridge Nigeria is a web platform for an NGO dedicated to empowering girls from developing countries — particularly Nigeria — to pursue and thrive in STEM careers. The platform serves as a hub for scholarship applications, mentorship matching, bootcamp registration, learning resources, and community building.

The platform was built to extend the reach of STEM Bridge's on-the-ground programs digitally, making resources, role models, and opportunities accessible to girls regardless of their geographic location or economic background.

---

## Mission & Vision

**Mission:** To empower, support, and encourage girls from developing countries interested in STEM and inspire the next generation of female leaders.

**Vision:** A future where every girl, regardless of background, has equal access to STEM education, mentorship, and career opportunities.

**Core Pillars:**

| Pillar | Description |
|--------|-------------|
| 🎓 Empower | Create pathways for girls to emerge into STEM fields |
| 💰 Support | Provide financial investment through scholarships for girls from disadvantaged backgrounds |
| 🌱 Encourage | Expand learning, leadership, and mentorship opportunities |
| 📢 Awareness | Increase awareness of STEM careers and generate enthusiasm among girls |

---

## Features

### 🎓 Scholarship Portal
- Online application for the STEM Bridge Women's Scholarship
- Eligibility screening (JSS3/Grade 9 girls transitioning to SSS1/Grade 10)
- Application status tracking
- Document upload for academic records
- Review dashboard for scholarship committee members

### 👩‍🏫 Mentorship Matching
- Profile creation for mentors (women in STEM careers) and mentees (high school girls)
- Interest-based and career-path matching algorithm
- Secure in-platform messaging between mentor and mentee
- Session scheduling and goal-tracking tools
- Featured mentor spotlights (e.g., CEOs, engineers, researchers)

### 🖥️ Bootcamp & Events Registration
- Browse upcoming STEM bootcamps, workshops, and nationwide programs
- One-click registration with confirmation emails
- Bootcamp curriculum previews (coding, robotics, AI, mathematics)
- Certificate tracking for completed programs

### 📚 Learning Resources Hub
- Curated STEM resources organized by subject and grade level
- Video lessons, articles, and practice problems
- Links to free external resources (Khan Academy, Coursera, etc.)
- Downloadable study guides and career guides

### 🌟 Community & Role Models
- Stories and profiles of successful Nigerian women in STEM
- Student success stories and testimonials
- Discussion forums organized by subject and career interest
- Peer support groups for girls facing similar challenges

### 📊 Impact Dashboard
- Live statistics on girls reached, scholarships awarded, and bootcamps run
- Regional breakdown of program participation across Nigeria
- Alumni tracking — where are STEM Bridge graduates now?

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | React 18 (JSX, Hooks) |
| Styling | Tailwind CSS / Inline CSS |
| Backend (recommended) | Node.js + Express or Next.js API routes |
| Database (recommended) | PostgreSQL or Firebase Firestore |
| Auth (recommended) | Firebase Auth or Auth0 |
| AI Features | Anthropic Claude API |
| File Storage | AWS S3 or Cloudinary |
| Email | SendGrid or Mailchimp |
| Hosting | Vercel, Netlify, or AWS |

---

## Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn
- (Optional) Anthropic API key for AI-powered features

### Installation

```bash
# Clone the repository
git clone https://github.com/your-org/stem-bridge-nigeria.git
cd stem-bridge-nigeria

# Install dependencies
npm install

# Copy environment variables template
cp .env.example .env

# Fill in your environment variables
# (API keys, database URLs, etc.)

# Start the development server
npm run dev
```

### Environment Variables

```env
# Anthropic API (for AI features)
VITE_ANTHROPIC_API_KEY=your_key_here

# Database
DATABASE_URL=your_database_url

# Authentication
AUTH_SECRET=your_auth_secret

# Email
SENDGRID_API_KEY=your_sendgrid_key

# File Storage
AWS_S3_BUCKET=your_bucket_name
AWS_ACCESS_KEY_ID=your_access_key
AWS_SECRET_ACCESS_KEY=your_secret_key
```

### Build for Production

```bash
npm run build
npm run start
```

---

## Project Structure

```
stem-bridge-nigeria/
├── src/
│   ├── components/
│   │   ├── ScholarshipPortal/     # Application forms and status tracking
│   │   ├── MentorshipHub/         # Mentor/mentee matching and messaging
│   │   ├── BootcampRegistry/      # Events and bootcamp registration
│   │   ├── ResourcesHub/          # Learning resources and guides
│   │   ├── Community/             # Forums, stories, role models
│   │   └── ImpactDashboard/       # Statistics and alumni tracking
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   ├── Programs.jsx
│   │   ├── Scholarship.jsx
│   │   ├── Mentorship.jsx
│   │   └── Contact.jsx
│   ├── api/                       # Backend API routes
│   ├── hooks/                     # Custom React hooks
│   └── utils/                     # Helper functions
├── public/
│   └── index.html
├── package.json
└── README.md
```

---

## Programs & Initiatives

### 🏆 STEM Bridge Women's Scholarship
A merit and need-based scholarship targeting girls transitioning from Junior Secondary School (JSS3) to Senior Secondary School (SSS1).

**Eligibility criteria:**
- Currently attending JSS3 (Grade 9)
- Planning to enroll in SSS1 (Grade 10) the following academic year
- Demonstrates strong academic performance
- Comes from a disadvantaged socioeconomic background
- Shows passion and interest in STEM subjects

**Application window:** Opens annually in January.

### 🤝 Mentorship Program
Pairs high school girls with women who have similar STEM interests and career goals.

**How it works:**
1. Mentee creates a profile with STEM interests and goals
2. Platform matches her with a compatible mentor
3. Monthly virtual or in-person sessions over one academic year
4. Mentor provides guidance on academics, university applications, and career paths

**Featured mentors have included:** CEOs, software engineers, scientists, doctors, and researchers from across Nigeria and the diaspora.

### 💻 Nationwide Bootcamps
Intensive STEM workshops held across Nigeria covering:
- Coding and software development
- Robotics and hardware
- Mathematics and problem-solving
- Artificial intelligence and machine learning basics
- Leadership and entrepreneurship

**Past impact:** Over 100 girls enrolled as STEM prospects within the first year of programs launching.

### 📣 Awareness & Outreach
- School visits and presentations at public secondary schools
- Social media campaigns highlighting Nigerian women in STEM
- Partnerships with universities to create direct application pathways for graduates
- Annual STEM girls conference bringing together students, mentors, and industry partners

---

## Impact

Since launching in 2022, STEM Bridge Nigeria has:

- 👩‍🎓 Enrolled **100+ girls** as active STEM prospects
- 🏫 Run programs in **multiple states** across Nigeria
- 🤝 Connected girls with **mentors from top companies** including Microsoft, Transcorp, and Afriland Properties
- 🎓 Provided scholarship pathways for girls from **low-income households**
- 🌍 Built a community of girls inspired to pursue **STEM careers** across West Africa

> *"In the subset of countries with standardized science and mathematics test data, there is no systematic advantage for boys — and in some countries, girls are in fact outperforming boys. The gap is not ability. It's access and encouragement."*

---

## Target Audience

| User Type | Role on Platform |
|-----------|-----------------|
| Female students (JSS3–SSS3) | Apply for scholarships, join bootcamps, find mentors |
| Women in STEM careers | Register as mentors, share career stories |
| Parents & guardians | Learn about programs, support applications |
| Educators & school counselors | Refer students, access teaching resources |
| Donors & sponsors | Learn about impact, make financial contributions |
| Program administrators | Review applications, manage scholarship committee |

---

## Roadmap

Planned features for future versions:

- **Mobile app** (iOS & Android) for low-bandwidth environments in rural Nigeria
- **AI career counselor** — personalized guidance on STEM university programs and career paths
- **Alumni network** — connect current students with STEM Bridge graduates now in university or careers
- **Partner university portal** — direct application integration with Nigerian universities
- **Multilingual support** — Yoruba, Hausa, Igbo alongside English
- **Offline resource packs** — downloadable study materials for areas with limited internet access
- **SMS notifications** — bootcamp reminders and scholarship updates via SMS for feature phone users

---

## Contributing

We welcome contributions from developers, educators, STEM professionals, and advocates.

**Priority areas:**
- Scholarship application workflow improvements
- Mentor matching algorithm
- Accessibility for low-bandwidth connections
- Localization into Nigerian languages
- Mobile responsiveness
- Data privacy and security for minor applicants

**Important:** All contributions involving user data for minors (under 18) must follow applicable data protection laws including Nigeria's NDPR (Nigeria Data Protection Regulation).

Please open an issue before submitting a pull request.

---

## Data Privacy & Safeguarding

STEM Bridge Nigeria collects data from minors. All data handling must comply with:

- **Nigeria Data Protection Regulation (NDPR)**
- **Children's Online Privacy Protection** best practices
- Parental/guardian consent required for users under 18
- No personal data shared with third parties without explicit consent
- All mentor-mentee communications logged and reviewable by program administrators for safeguarding purposes

---

## License

MIT License. See `LICENSE` for details.

---

*Bridging the gap, one girl at a time. 🌍*
