# B.B.S. GROUP OF EDUCATIONAL INSTITUTES — College Website

## Badges
![React](https://img.shields.io/badge/React-19.2.4-61DAFB?style=flat&logo=react) ![TypeScript](https://img.shields.io/badge/TypeScript-6.0.2-3178C6?style=flat&logo=typescript) ![Vite](https://img.shields.io/badge/Vite-8.0.4-646CFF?style=flat&logo=vite) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)

## Project Description
This is the official website for B.B.S. Group of Educational Institutes, a premier institution offering 16 paramedical diploma courses, 5 counseling programs, and comprehensive educational services. The site showcases courses, faculty, admissions, events, and more, built as a modern React single-page application.

## Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- npm or yarn

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd test2
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the Application
- Development server:
  ```bash
  npm run dev
  ```
- Build for production:
  ```bash
  npm run build
  ```
- Preview production build:
  ```bash
  npm run preview
  ```

### Testing
- Run tests:
  ```bash
  npm test
  ```
- Run tests with coverage:
  ```bash
  npm run test:coverage
  ```

## Usage
Navigate through the website to explore courses, faculty, admissions, and contact information. The site is responsive and optimized for both desktop and mobile devices.

## Contributing
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## License
This project is private and proprietary to B.B.S. Group of Educational Institutes.

## Complete Project Folder Structure
### Tech Stack: React.js · TypeScript · EmailJS · Hardcoded CSS · Google Fonts · Vercel Deployment

---

> **Notes before reading:**
> - No two folders share the same name anywhere in the tree
> - Deployment target: **Vercel** (BrowserRouter used, no HashRouter needed)
> - Fonts loaded via **Google Fonts** link tag in `index.html` (Poppins + Merriweather)
> - All styling via **hardcoded CSS files** — no Tailwind, no CSS-in-JS
> - 16 Paramedical Diploma courses + 5 Counseling courses

---

```
bbs-college-website/
│
├── .github/
│   └── workflows/
│       ├── vercel-deploy.yml              ← auto deploy to Vercel on push to main
│       └── lint-typecheck.yml            ← ESLint + TypeScript check on pull request
│
│
├── public/
│   ├── favicon.ico
│   ├── favicon-32x32.png
│   ├── favicon-16x16.png
│   ├── apple-touch-icon.png
│   ├── site.webmanifest
│   ├── robots.txt
│   ├── sitemap.xml
│   │
│   └── static-assets/
│       │
│       ├── images/
│       │   │
│       │   ├── hero-slides/
│       │   │   ├── slide-main-desktop.webp          (1)
│       │   │   ├── slide-main-mobile.webp           (2)
│       │   │   ├── slide-two-desktop.webp           (3)
│       │   │   ├── slide-three-desktop.webp         (4)
│       │   │   └── slide-four-desktop.webp          (5)
│       │   │
│       │   ├── about-page/
│       │   │   ├── institute-building-front.webp    (6)
│       │   │   ├── institute-building-aerial.webp   (7)
│       │   │   ├── chairman-photo.webp              (8)
│       │   │   ├── director-photo.webp              (9)
│       │   │   ├── principal-photo.webp             (10)
│       │   │   ├── vice-principal-photo.webp        (11)
│       │   │   ├── history-founding-year.webp       (12)
│       │   │   ├── history-growth-phase.webp        (13)
│       │   │   ├── accreditation-certificate.webp   (14)
│       │   │   └── affiliation-document.webp        (15)
│       │   │
│       │   ├── paramedical-courses/
│       │   │   ├── diploma-cms-ed.webp              (16)
│       │   │   ├── diploma-mlt.webp                 (17)
│       │   │   ├── diploma-ophthalmic.webp          (18)
│       │   │   ├── diploma-radiography.webp         (19)
│       │   │   ├── diploma-cath-lab.webp            (20)
│       │   │   ├── diploma-dental-hygiene.webp      (21)
│       │   │   ├── diploma-xray-ecg.webp            (22)
│       │   │   ├── diploma-neuro-tech.webp          (23)
│       │   │   ├── diploma-dialysis.webp            (24)
│       │   │   ├── diploma-mri-tech.webp            (25)
│       │   │   ├── diploma-ct-tech.webp             (26)
│       │   │   ├── diploma-ortho-tech.webp          (27)
│       │   │   ├── diploma-critical-care.webp       (28)
│       │   │   ├── diploma-medical-assistant.webp   (29)
│       │   │   ├── diploma-optometry.webp           (30)
│       │   │   └── diploma-contact-lens.webp        (31)
│       │   │
│       │   ├── counseling-courses/
│       │   │   ├── counseling-d-pharma.webp         (32)
│       │   │   ├── counseling-anm.webp              (33)
│       │   │   ├── counseling-gnm.webp              (34)
│       │   │   ├── counseling-bsc-nursing.webp      (35)
│       │   │   └── counseling-bams.webp             (36)
│       │   │
│       │   ├── faculty-science-dept/
│       │   │   ├── faculty-anatomy-01.webp          (37)
│       │   │   ├── faculty-anatomy-02.webp          (38)
│       │   │   ├── faculty-physiology-01.webp       (39)
│       │   │   ├── faculty-biochem-01.webp          (40)
│       │   │   ├── faculty-pathology-01.webp        (41)
│       │   │   └── faculty-microbiology-01.webp     (42)
│       │   │
│       │   ├── faculty-clinical-dept/
│       │   │   ├── faculty-radiology-01.webp        (43)
│       │   │   ├── faculty-radiology-02.webp        (44)
│       │   │   ├── faculty-cardiology-01.webp       (45)
│       │   │   ├── faculty-neurology-01.webp        (46)
│       │   │   ├── faculty-dialysis-01.webp         (47)
│       │   │   ├── faculty-ophthalmology-01.webp    (48)
│       │   │   ├── faculty-dental-01.webp           (49)
│       │   │   └── faculty-ortho-01.webp            (50)
│       │   │
│       │   ├── faculty-admin-dept/
│       │   │   ├── staff-registrar.webp             (51)
│       │   │   ├── staff-librarian.webp             (52)
│       │   │   ├── staff-accountant.webp            (53)
│       │   │   └── staff-placement-officer.webp     (54)
│       │   │
│       │   ├── photo-gallery/
│       │   │   ├── annual-day-event/
│       │   │   │   ├── annual-day-01.webp           (55)
│       │   │   │   ├── annual-day-02.webp           (56)
│       │   │   │   ├── annual-day-03.webp           (57)
│       │   │   │   └── annual-day-04.webp           (58)
│       │   │   ├── sports-event/
│       │   │   │   ├── sports-day-01.webp           (59)
│       │   │   │   ├── sports-day-02.webp           (60)
│       │   │   │   └── sports-day-03.webp           (61)
│       │   │   ├── cultural-event/
│       │   │   │   ├── cultural-fest-01.webp        (62)
│       │   │   │   ├── cultural-fest-02.webp        (63)
│       │   │   │   └── cultural-fest-03.webp        (64)
│       │   │   ├── convocation-event/
│       │   │   │   ├── convocation-01.webp          (65)
│       │   │   │   └── convocation-02.webp          (66)
│       │   │   └── workshop-event/
│       │   │       ├── workshop-01.webp             (67)
│       │   │       ├── workshop-02.webp             (68)
│       │   │       └── workshop-03.webp             (69)
│       │   │
│       │   ├── campus-infrastructure/
│       │   │   ├── campus-library-interior.webp     (70)
│       │   │   ├── campus-library-exterior.webp     (71)
│       │   │   ├── campus-computer-lab.webp         (72)
│       │   │   ├── campus-science-lab.webp          (73)
│       │   │   ├── campus-anatomy-lab.webp          (74)
│       │   │   ├── campus-radiology-unit.webp       (75)
│       │   │   ├── campus-sports-ground.webp        (76)
│       │   │   ├── campus-canteen.webp              (77)
│       │   │   ├── campus-auditorium.webp           (78)
│       │   │   ├── campus-seminar-hall.webp         (79)
│       │   │   └── campus-garden.webp               (80)
│       │   │
│       │   ├── achievements-section/
│       │   │   ├── achievement-topper-2023.webp     (81)
│       │   │   ├── achievement-topper-2022.webp     (82)
│       │   │   ├── achievement-award-best.webp      (83)
│       │   │   └── achievement-placement.webp       (84)
│       │   │
│       │   ├── alumni-testimonials/
│       │   │   ├── alumnus-photo-01.webp            (85)
│       │   │   ├── alumnus-photo-02.webp            (86)
│       │   │   ├── alumnus-photo-03.webp            (87)
│       │   │   └── alumnus-photo-04.webp            (88)
│       │   │
│       │   └── open-graph/
│       │       └── og-share-default.webp            (89)  ← social share preview image
│       │
│       ├── brand-logos/
│       │   ├── bbs-logo-colored.svg                 (90)
│       │   ├── bbs-logo-white.svg                   (91)
│       │   ├── bbs-logo-dark.svg                    (92)
│       │   ├── affiliated-university-logo.svg       (93)
│       │   ├── ministry-health-logo.svg             (94)
│       │   └── paramedical-council-logo.svg         (95)
│       │
│       ├── pwa-icons/
│       │   ├── pwa-icon-192.png                     (96)
│       │   └── pwa-icon-512.png                     (97)
│       │
│       └── downloadable-docs/
│           ├── bbs-prospectus-2024-25.pdf
│           ├── admission-form-blank.pdf
│           ├── fee-structure-2024-25.pdf
│           └── college-brochure-bbs.pdf
│
│
├── src/
│   │
│   ├── main.tsx                           ← ReactDOM.createRoot entry point
│   ├── App.tsx                            ← BrowserRouter + all route definitions
│   ├── vite-env.d.ts
│   │
│   │
│   ├── pages/
│   │   │
│   │   ├── HomePage/
│   │   │   ├── index.tsx                  ← composes all home sections
│   │   │   ├── HeroSlider.tsx            ← auto-play image slider with CTA
│   │   │   ├── NoticeStrip.tsx           ← scrolling announcement ticker
│   │   │   ├── InstituteStats.tsx        ← animated counters: students/courses/years
│   │   │   ├── FeaturedDiplomas.tsx      ← 6 highlighted diploma course cards
│   │   │   ├── WhyChooseBBS.tsx          ← icon + text feature highlight grid
│   │   │   ├── CampusPreview.tsx         ← 4-image campus glimpse grid
│   │   │   ├── AlumniVoices.tsx          ← alumni testimonial carousel
│   │   │   ├── UpcomingEvents.tsx        ← 3 latest events with date badge
│   │   │   ├── HonorsDisplay.tsx         ← awards, rankings, recognitions
│   │   │   └── AdmissionCallout.tsx      ← full-width apply now CTA banner
│   │   │
│   │   ├── AboutPage/
│   │   │   ├── index.tsx
│   │   │   ├── AboutHeroBanner.tsx       ← page banner with title + breadcrumb
│   │   │   ├── InstituteIntroduction.tsx ← overview paragraph + building image
│   │   │   ├── VisionMissionBlock.tsx    ← two-column vision / mission cards
│   │   │   ├── FoundingHistory.tsx       ← vertical timeline of institute history
│   │   │   ├── ChairmanMessage.tsx       ← chairman photo + message quote card
│   │   │   ├── PrincipalMessage.tsx      ← principal photo + message quote card
│   │   │   ├── GoverningBody.tsx         ← committee member photo cards
│   │   │   ├── RecognitionsBadges.tsx    ← ministry / council / university logos
│   │   │   ├── InfraHighlights.tsx       ← labs, library, auditorium cards
│   │   │   └── UniversityAffiliation.tsx ← affiliated university details block
│   │   │
│   │   ├── CoursesPage/
│   │   │   ├── index.tsx                  ← filter bar + both grids
│   │   │   ├── CoursesHeroBanner.tsx
│   │   │   ├── DiplomaCourseFilter.tsx    ← filter: All / Lab / Imaging / Therapy / Dental
│   │   │   ├── DiplomaCoursesGrid.tsx     ← 16 paramedical diploma cards
│   │   │   ├── CounselingServicesGrid.tsx ← 5 counseling course cards (distinct style)
│   │   │   └── CourseSearchInput.tsx      ← live client-side course search bar
│   │   │
│   │   ├── CourseDetailPage/
│   │   │   ├── index.tsx                  ← /courses/:slug — dynamic route
│   │   │   ├── DiplomaDetailHero.tsx      ← course image, title, duration badge
│   │   │   ├── CourseOverviewPanel.tsx    ← about the diploma + key highlights
│   │   │   ├── SyllabusAccordion.tsx      ← semester/year-wise syllabus breakdown
│   │   │   ├── EligibilityCriteria.tsx    ← qualification requirement block
│   │   │   ├── DurationFeesBlock.tsx      ← duration, seats, fee per semester table
│   │   │   ├── CareerScopeSection.tsx     ← hospitals, clinics, govt jobs scope
│   │   │   ├── RelatedDiplomas.tsx        ← 3 similar diploma course cards
│   │   │   └── DiplomaEnquiryWidget.tsx   ← compact inline EmailJS enquiry form
│   │   │
│   │   ├── AdmissionsPage/
│   │   │   ├── index.tsx
│   │   │   ├── AdmissionsHeroBanner.tsx
│   │   │   ├── HowToApplySteps.tsx        ← numbered step-by-step process
│   │   │   ├── StreamEligibility.tsx      ← per-course eligibility criteria table
│   │   │   ├── KeyDatesCalendar.tsx       ← important dates + deadlines table
│   │   │   ├── DocumentsChecklist.tsx     ← checklist of required documents
│   │   │   ├── FullFeeBreakdown.tsx       ← complete fee structure table
│   │   │   ├── ScholarshipOptions.tsx     ← scholarship types + eligibility
│   │   │   ├── AdmissionsFAQ.tsx          ← accordion FAQ section
│   │   │   └── AdmissionFormSection.tsx   ← EmailJS admission enquiry form + PDF links
│   │   │
│   │   ├── FacultyPage/
│   │   │   ├── index.tsx
│   │   │   ├── FacultyHeroBanner.tsx
│   │   │   ├── FacultyDeptFilter.tsx      ← All / Basic Science / Clinical / Admin
│   │   │   ├── FacultyMembersGrid.tsx     ← responsive card grid of all faculty
│   │   │   ├── FacultyExpandModal.tsx     ← click-open full profile modal
│   │   │   └── DeptHeadSpotlight.tsx      ← HOD highlight row at top of page
│   │   │
│   │   ├── GalleryPage/
│   │   │   ├── index.tsx
│   │   │   ├── GalleryHeroBanner.tsx
│   │   │   ├── GalleryEventFilter.tsx     ← All / Annual Day / Sports / Cultural / Workshop
│   │   │   ├── MasonryPhotoGrid.tsx       ← responsive masonry layout image grid
│   │   │   ├── FullscreenLightbox.tsx     ← lightbox with prev/next/close controls
│   │   │   └── YoutubeVideosBlock.tsx     ← embedded YouTube video section
│   │   │
│   │   ├── ContactPage/
│   │   │   ├── index.tsx
│   │   │   ├── ContactHeroBanner.tsx
│   │   │   ├── ContactInfoCards.tsx       ← address / phone / email / hours cards
│   │   │   ├── MainContactForm.tsx        ← full EmailJS contact + enquiry form
│   │   │   ├── MapEmbedBlock.tsx          ← Google Maps iframe integration
│   │   │   └── SocialChannels.tsx         ← FB / Insta / YouTube / Twitter links
│   │   │
│   │   ├── NotificationsPage/
│   │   │   ├── index.tsx                  ← complete notice board archive
│   │   │   ├── AllNoticesList.tsx
│   │   │   └── SingleNoticeCard.tsx
│   │   │
│   │   ├── ResultsPage/
│   │   │   ├── index.tsx                  ← exam result info + university redirect links
│   │   │   └── ResultLinksBlock.tsx
│   │   │
│   │   ├── AlumniPage/
│   │   │   ├── index.tsx
│   │   │   ├── AlumniHighlightsBlock.tsx
│   │   │   ├── AlumniStoriesSection.tsx
│   │   │   └── AlumniConnectForm.tsx      ← EmailJS powered alumni registration
│   │   │
│   │   └── NotFoundPage/
│   │       └── index.tsx                  ← custom 404 with back-home button
│   │
│   │
│   ├── components/
│   │   │
│   │   ├── layout-shell/
│   │   │   ├── SiteLayout.tsx             ← wraps Navbar + <Outlet> + SiteFooter
│   │   │   │
│   │   │   ├── TopNavbar/
│   │   │   │   ├── index.tsx              ← top-level navbar shell + scroll shadow
│   │   │   │   ├── NavBrand.tsx           ← BBS logo + institute name text
│   │   │   │   ├── DesktopNavLinks.tsx    ← horizontal nav links for desktop
│   │   │   │   ├── NavDropdownMenu.tsx    ← hover dropdown for Courses submenu
│   │   │   │   ├── HamburgerToggle.tsx    ← mobile menu open/close icon button
│   │   │   │   └── MobileSideDrawer.tsx   ← full-height off-canvas mobile nav
│   │   │   │
│   │   │   ├── SiteFooter/
│   │   │   │   ├── index.tsx              ← footer shell grid
│   │   │   │   ├── FooterBrandColumn.tsx  ← logo + institute tagline + brief desc
│   │   │   │   ├── FooterNavColumn.tsx    ← quick navigation links list
│   │   │   │   ├── FooterDiplomasColumn.tsx ← popular diploma course links
│   │   │   │   ├── FooterAddressColumn.tsx  ← address + phone + email + map link
│   │   │   │   └── FooterCopyright.tsx    ← copyright line + social icon row
│   │   │   │
│   │   │   └── PageBreadcrumb.tsx         ← reusable breadcrumb trail component
│   │   │
│   │   │
│   │   ├── card-components/
│   │   │   ├── DiplomaCard.tsx            ← thumbnail + course name + duration + CTA
│   │   │   ├── DiplomaCardSkeleton.tsx    ← loading skeleton placeholder
│   │   │   ├── CounselingCard.tsx         ← distinct style card for counseling courses
│   │   │   ├── FacultyMemberCard.tsx      ← photo + name + designation + dept badge
│   │   │   ├── EventDateCard.tsx          ← date badge + event title + short desc
│   │   │   ├── AlumniQuoteCard.tsx        ← testimonial quote + name + batch year
│   │   │   ├── StatHighlightCard.tsx      ← icon + animated number + label
│   │   │   ├── NoticeBoardCard.tsx        ← date pill + category tag + title + NEW badge
│   │   │   └── FacilityCard.tsx           ← campus facility image + name + description
│   │   │
│   │   │
│   │   ├── button-elements/
│   │   │   ├── PrimaryBtn.tsx             ← solid filled CTA button
│   │   │   ├── OutlineBtn.tsx             ← bordered secondary action button
│   │   │   ├── AnchorLinkBtn.tsx          ← styled anchor rendered as button
│   │   │   └── ScrollTopFAB.tsx           ← floating scroll-to-top action button
│   │   │
│   │   │
│   │   ├── badge-elements/
│   │   │   ├── CourseCategoryBadge.tsx    ← Lab Tech / Imaging / Therapy pill badge
│   │   │   ├── NewAnnounceBadge.tsx       ← blinking "New" indicator badge
│   │   │   └── CounselingTagBadge.tsx     ← distinct badge for counseling entries
│   │   │
│   │   │
│   │   ├── section-blocks/
│   │   │   ├── SectionTitleBlock.tsx      ← reusable heading + subtitle + divider line
│   │   │   ├── InnerPageBanner.tsx        ← full-width page-top banner with title overlay
│   │   │   └── DecorativeDivider.tsx      ← styled section separator with icon/line
│   │   │
│   │   │
│   │   ├── feedback-indicators/
│   │   │   ├── LoadingSpinner.tsx         ← circular CSS spinner
│   │   │   ├── EmptyResultsState.tsx      ← no results illustration + message
│   │   │   ├── GlobalErrorBoundary.tsx    ← React class-based error boundary
│   │   │   └── SuccessToast.tsx           ← form success / error toast notification
│   │   │
│   │   │
│   │   ├── media-elements/
│   │   │   ├── LazyLoadImage.tsx          ← img with blur-up placeholder + observer
│   │   │   ├── LightboxPortal.tsx         ← fullscreen image viewer via React portal
│   │   │   └── YoutubeFrame.tsx           ← responsive 16:9 iframe wrapper
│   │   │
│   │   │
│   │   ├── table-elements/
│   │   │   ├── FeeStructureTable.tsx      ← responsive scrollable fee breakdown table
│   │   │   └── EligibilityTable.tsx       ← per-course eligibility criteria table
│   │   │
│   │   │
│   │   ├── accordion-elements/
│   │   │   ├── CollapsiblePanel.tsx       ← generic expand/collapse component
│   │   │   └── FaqAccordionList.tsx       ← FAQ-specific styled accordion list
│   │   │
│   │   │
│   │   ├── timeline-elements/
│   │   │   └── HistoryTimeline.tsx        ← vertical year-by-year institute timeline
│   │   │
│   │   │
│   │   ├── tab-elements/
│   │   │   ├── PillFilterTabs.tsx         ← pill-shaped filter tab bar
│   │   │   └── ContentPanelTabs.tsx       ← tab switcher for course detail sections
│   │   │
│   │   │
│   │   ├── modal-elements/
│   │   │   ├── ModalWrapper.tsx           ← generic portal modal with backdrop
│   │   │   └── FacultyProfileModal.tsx    ← expanded faculty profile modal content
│   │   │
│   │   │
│   │   ├── counter-elements/
│   │   │   └── ViewportCountUp.tsx        ← number count-up triggered on scroll into view
│   │   │
│   │   │
│   │   ├── utility-elements/
│   │   │   ├── SeoMetaTags.tsx            ← react-helmet-async per-page title + meta
│   │   │   ├── RouteScrollReset.tsx       ← scrolls to top on every route change
│   │   │   ├── MarqueeAnnouncement.tsx    ← CSS marquee scrolling notice bar
│   │   │   └── CookieConsentBar.tsx       ← GDPR-lite consent notification bar
│   │   │
│   │   │
│   │   └── form-fields/
│   │       ├── MainContactForm.tsx        ← full EmailJS contact + enquiry form
│   │       ├── AdmissionEnquiryForm.tsx   ← admission interest form with course select
│   │       ├── DiplomaEnquiryForm.tsx     ← compact inline form on course detail page
│   │       ├── AlumniSignupForm.tsx       ← alumni registration EmailJS form
│   │       └── shared-inputs/
│   │           ├── TextInputField.tsx     ← reusable labeled text input with error
│   │           ├── TextareaField.tsx      ← reusable labeled textarea with error
│   │           ├── SelectDropdown.tsx     ← reusable styled select with options
│   │           ├── CheckboxField.tsx      ← single checkbox with label
│   │           ├── RadioButtonGroup.tsx   ← group of radio inputs with label
│   │           ├── InlineFieldError.tsx   ← validation error message display
│   │           └── FormSubmitButton.tsx   ← submit button with loading/disabled state
│   │
│   │
│   ├── data/
│   │   │
│   │   ├── paramedical-courses/
│   │   │   ├── index.ts                   ← re-exports all 16 diploma objects + helpers
│   │   │   ├── lab-technology.data.ts     ← MLT, Dialysis, CT, MRI, Cath Lab
│   │   │   ├── imaging-courses.data.ts    ← Radiography, X-Ray ECG, MRI Tech
│   │   │   ├── ophthalmic-courses.data.ts ← Ophthalmic Assistant, Optometry, Contact Lens
│   │   │   ├── neuro-cardiac.data.ts      ← Clinical Neuro, Cath Lab Technology
│   │   │   ├── dental-ortho.data.ts       ← Dental Hygiene, Ortho Technician
│   │   │   └── general-clinical.data.ts   ← CMS & ED, Medical Assistant, Critical Care
│   │   │
│   │   ├── counseling-programs/
│   │   │   └── counseling.data.ts         ← D.Pharma, ANM, GNM, BSc Nursing, BAMS
│   │   │
│   │   ├── faculty-members/
│   │   │   ├── index.ts
│   │   │   ├── basic-science.faculty.ts   ← Anatomy, Physiology, Biochemistry faculty
│   │   │   ├── clinical-dept.faculty.ts   ← Radiology, Cardiology, Neuro faculty
│   │   │   └── administrative.staff.ts    ← Registrar, Librarian, Accounts, Placement
│   │   │
│   │   ├── gallery-media/
│   │   │   ├── index.ts
│   │   │   ├── annual-function.gallery.ts
│   │   │   ├── sports-events.gallery.ts
│   │   │   ├── cultural-program.gallery.ts
│   │   │   └── convocation-workshop.gallery.ts
│   │   │
│   │   ├── site-announcements.ts          ← notice board entries with dates + tags
│   │   ├── upcoming-events.ts             ← event name, date, venue, description
│   │   ├── alumni-testimonials.ts         ← quote + name + course + batch + photo
│   │   ├── institute-achievements.ts      ← awards, recognitions, topper records
│   │   ├── admission-deadlines.ts         ← important date entries per session
│   │   ├── faq-content.ts                 ← FAQ question-answer pairs for Admissions
│   │   ├── scholarship-info.ts            ← scholarship name, eligibility, amount
│   │   └── social-media-links.ts          ← FB, Instagram, YouTube, Twitter/X URLs
│   │
│   │
│   ├── services/
│   │   ├── emailjs-service.ts             ← EmailJS init + typed send functions for all forms
│   │   └── analytics-service.ts           ← optional GA4 / Vercel Analytics event helpers
│   │
│   │
│   ├── hooks/
│   │   ├── useRevealOnScroll.ts           ← IntersectionObserver-based element reveal
│   │   ├── useNavbarShadow.ts             ← sticky navbar shadow on scroll trigger
│   │   ├── useDiplomaFilter.ts            ← filter + search state for courses page
│   │   ├── useFacultyFilter.ts            ← department filter state for faculty page
│   │   ├── useGalleryFilter.ts            ← category filter state for gallery page
│   │   ├── useModalControl.ts             ← open/close state + body scroll lock
│   │   ├── useBreakpoint.ts               ← responsive breakpoint detection hook
│   │   ├── useCountUpOnView.ts            ← count-up animation on viewport entry
│   │   └── useEmailSubmit.ts              ← form submit + EmailJS call + toast state
│   │
│   │
│   ├── context/
│   │   ├── NoticeContext.tsx              ← global announcements / notice state
│   │   └── ThemeContext.tsx               ← optional light / dark mode toggle context
│   │
│   │
│   ├── types/
│   │   ├── diploma.types.ts               ← DiplomaData, DiplomaCategory, CourseType
│   │   ├── counseling.types.ts            ← CounselingProgram interface
│   │   ├── faculty.types.ts               ← FacultyMember, Department, Designation
│   │   ├── gallery.types.ts               ← GalleryImage, GalleryEventCategory
│   │   ├── form.types.ts                  ← ContactFormFields, AdmissionFormFields
│   │   ├── announcement.types.ts          ← NoticeEntry, NoticeTag
│   │   ├── event.types.ts                 ← EventItem interface
│   │   └── shared.types.ts                ← NavItem, SocialLink, SeoMetaProps
│   │
│   │
│   ├── constants/
│   │   ├── index.ts                       ← barrel export for all constants
│   │   ├── institute.constants.ts         ← BBS name, address, phone, email, estd year
│   │   ├── route-paths.constants.ts       ← all route path strings as const enum
│   │   ├── emailjs.constants.ts           ← EmailJS service + template IDs from env
│   │   ├── dept-categories.constants.ts   ← department names, codes, color tokens
│   │   └── seo-defaults.constants.ts      ← default title, description, keywords
│   │
│   │
│   ├── utils/
│   │   ├── slugify.ts                     ← "Diploma in MLT" → "diploma-in-mlt"
│   │   ├── date-formatter.ts              ← consistent date display across site
│   │   ├── diploma-filter.ts              ← pure filter + search function for courses
│   │   ├── asset-path-resolver.ts         ← prepends correct base URL to asset paths
│   │   ├── form-validators.ts             ← manual field validation helper functions
│   │   └── classname-merge.ts             ← combines conditional class strings safely
│   │
│   │
│   ├── styles/
│   │   │
│   │   ├── base/
│   │   │   ├── reset.css                  ← browser default reset (box-sizing, margin 0)
│   │   │   ├── root-variables.css         ← :root CSS custom properties: colors, spacing, radius
│   │   │   └── typography-base.css        ← font-family (Google Fonts), sizes, line-heights
│   │   │
│   │   ├── layout/
│   │   │   ├── navbar.css                 ← top navigation bar, sticky, shadow states
│   │   │   ├── footer-layout.css          ← footer grid, columns, padding, bg color
│   │   │   ├── page-wrapper.css           ← main content wrapper, max-width, centering
│   │   │   └── grid-system.css            ← reusable 2/3/4-column responsive grid classes
│   │   │
│   │   ├── pages/
│   │   │   ├── home-page.css              ← all home page specific section styles
│   │   │   ├── about-page.css             ← about page sections: timeline, message, etc.
│   │   │   ├── courses-page.css           ← course grid, filter bar, search input
│   │   │   ├── course-detail-page.css     ← diploma detail tabs, fee table, syllabus
│   │   │   ├── admissions-page.css        ← steps, eligibility table, docs checklist
│   │   │   ├── faculty-page.css           ← faculty grid, modal, HOD spotlight
│   │   │   ├── gallery-page.css           ← masonry grid, lightbox, filter tabs
│   │   │   ├── contact-page.css           ← form layout, info cards, map embed
│   │   │   ├── notifications-page.css     ← notice list, date pill, tags
│   │   │   ├── results-page.css           ← results links, redirect section
│   │   │   ├── alumni-page.css            ← alumni highlights, stories, signup form
│   │   │   └── not-found-page.css         ← 404 page illustration and button styles
│   │   │
│   │   ├── components/
│   │   │   ├── cards.css                  ← DiplomaCard, FacultyCard, EventCard styles
│   │   │   ├── buttons.css                ← PrimaryBtn, OutlineBtn, FAB styles
│   │   │   ├── badges.css                 ← CourseCategoryBadge, NewBadge styles
│   │   │   ├── forms.css                  ← all form field, label, error styles
│   │   │   ├── accordion.css              ← FAQ and syllabus accordion open/close styles
│   │   │   ├── tabs.css                   ← PillFilterTabs, ContentPanelTabs styles
│   │   │   ├── modal.css                  ← backdrop, modal box, close button styles
│   │   │   ├── tables.css                 ← FeeStructureTable, EligibilityTable styles
│   │   │   ├── timeline.css              ← vertical history timeline dot + line styles
│   │   │   ├── lightbox.css              ← fullscreen image viewer overlay styles
│   │   │   ├── toast.css                  ← success / error toast notification styles
│   │   │   ├── spinner.css               ← loading spinner animation
│   │   │   ├── breadcrumb.css            ← page breadcrumb trail styles
│   │   │   ├── marquee-ticker.css        ← scrolling announcement bar styles
│   │   │   ├── counter-display.css       ← stat counter number + label styles
│   │   │   └── cookie-bar.css            ← consent bar bottom fixed styles
│   │   │
│   │   └── animations/
│   │       ├── keyframes.css              ← @keyframes: fadeIn, slideUp, pulse, spin
│   │       ├── reveal-transitions.css     ← scroll-triggered element reveal classes
│   │       └── hover-effects.css          ← card hover lift, button hover states
│   │
│   │
│   └── __tests__/
│       ├── component-tests/
│       │   ├── DiplomaCard.test.tsx
│       │   ├── MainContactForm.test.tsx
│       │   └── TopNavbar.test.tsx
│       ├── hook-tests/
│       │   ├── useDiplomaFilter.test.ts
│       │   └── useEmailSubmit.test.ts
│       ├── util-tests/
│       │   ├── slugify.test.ts
│       │   └── diploma-filter.test.ts
│       └── page-tests/
│           ├── HomePage.test.tsx
│           └── CourseDetailPage.test.tsx
│
│
├── .env                                   ← gitignored — local secrets only
├── .env.example                           ← committed — shows required variable names
├── .eslintrc.cjs
├── .prettierrc
├── .gitignore
├── vercel.json                            ← SPA rewrites: all routes → index.html
├── index.html                             ← Vite entry HTML + Google Fonts <link> tag
├── vite.config.ts                         ← path aliases (@/) + build output config
├── tsconfig.json
├── tsconfig.node.json
├── vitest.config.ts
└── package.json
```

---

## Asset Summary

| Category                      | Count | Format   |
|-------------------------------|-------|----------|
| Hero slider images            | 5     | `.webp`  |
| About page images             | 10    | `.webp`  |
| Paramedical course thumbnails | **16**| `.webp`  |
| Counseling course thumbnails  | **5** | `.webp`  |
| Faculty — Basic Science dept  | 6     | `.webp`  |
| Faculty — Clinical dept       | 8     | `.webp`  |
| Faculty — Admin staff         | 4     | `.webp`  |
| Gallery — Annual Day          | 4     | `.webp`  |
| Gallery — Sports              | 3     | `.webp`  |
| Gallery — Cultural            | 3     | `.webp`  |
| Gallery — Convocation         | 2     | `.webp`  |
| Gallery — Workshops           | 3     | `.webp`  |
| Campus infrastructure         | 11    | `.webp`  |
| Achievements section          | 4     | `.webp`  |
| Alumni testimonials           | 4     | `.webp`  |
| OG share image                | 1     | `.webp`  |
| **Total raster images**       | **89**| `.webp`  |
| Brand logos                   | 6     | `.svg`   |
| PWA icons                     | 2     | `.png`   |
| **Total all image assets**    | **97**|          |
| Downloadable PDFs             | 4     | `.pdf`   |

---

## Google Fonts Setup (in `index.html`)

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&family=Merriweather:wght@400;700&family=Roboto+Condensed:wght@400;700&display=swap" rel="stylesheet">
```

Then in `root-variables.css`:

```css
:root {
  --font-primary: 'Poppins', sans-serif;      /* headings, nav, buttons */
  --font-body: 'Roboto Condensed', sans-serif; /* body text, paragraphs  */
  --font-serif: 'Merriweather', serif;         /* quotes, principal message */
}
```

---

## Vercel Deployment Config (`vercel.json`)

```json
{
  "rewrites": [
    { "source": "/(.*)", "destination": "/index.html" }
  ]
}
```

This single config file is all that is needed — Vercel handles the SPA
routing rewrite automatically. No `HashRouter` required. BrowserRouter works
cleanly with clean URLs like `/courses/diploma-in-mlt`.

---

## Environment Variables (`.env.example`)

```
VITE_EMAILJS_SERVICE_ID=your_service_id
VITE_EMAILJS_TEMPLATE_CONTACT=your_contact_template_id
VITE_EMAILJS_TEMPLATE_ADMISSION=your_admission_template_id
VITE_EMAILJS_TEMPLATE_DIPLOMA_ENQUIRY=your_diploma_enquiry_template_id
VITE_EMAILJS_TEMPLATE_ALUMNI=your_alumni_template_id
VITE_EMAILJS_PUBLIC_KEY=your_public_key
VITE_GOOGLE_MAPS_EMBED_KEY=your_maps_embed_key
VITE_GA4_MEASUREMENT_ID=G-XXXXXXXXXX
```

Add all of these in **Vercel Dashboard → Project → Settings → Environment Variables**
so they are injected at build time on every deployment.

---

## CSS File Count Summary

| Folder                  | Files | Purpose                                      |
|-------------------------|-------|----------------------------------------------|
| `styles/base/`          | 3     | Reset, CSS variables, typography             |
| `styles/layout/`        | 4     | Navbar, footer, wrapper, grid system         |
| `styles/pages/`         | 12    | One CSS file per page                        |
| `styles/components/`    | 16    | One CSS file per component category          |
| `styles/animations/`    | 3     | Keyframes, reveal transitions, hover effects |
| **Total CSS files**     | **38**|                                              |

---

*For: B.B.S. GROUP OF EDUCATIONAL INSTITUTES*
*Stack: React.js · TypeScript · EmailJS · Hardcoded CSS · Google Fonts · Vercel*