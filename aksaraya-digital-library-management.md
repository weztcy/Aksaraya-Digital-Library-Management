# Portfolio Project Data — Aksaraya - Digital Library Management

- **Category:** `web-development` (`Web Development`)
- **Accent Color:** `cyan`
- **Target Assets Folder:** `public/images/projects/aksaraya_digital_library_management/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `image16.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "aksaraya-digital-library-management",
  "code": "PRO-58 // WEB-10",
  "title": "Aksaraya - Digital Library Management",
  "category": "web-development",
  "categoryLabel": "Website",
  "year": "2025",
  "status": "Completed",
  "accentColor": "cyan",
  "repoUrl": "https://github.com/weztcy/Aksaraya-Digital-Library-Management",
  "license": "MIT License",
  "banner": "/images/projects/aksaraya_digital_library_management/banner.webp",
  "summary": "Full-stack Laravel library platform unifying browser PDF reading, barcode walk-in circulation, automated fines, and role-based catalog control.",
  "projectDescription": "Aksaraya is a full-stack digital library management system built with Laravel, Blade, Tailwind CSS, and Alpine.js. It unifies an online catalog, watermarked PDF e-reader, barcode-assisted circulation desk, automated overdue fine calculation, and role-based administrative analytics.",
  "architectureSummary": "Full-stack Laravel MVC monolith uniting Blade/Alpine.js portals, role middleware, Eloquent transactional circulation locks, and SQLite persistence.",
  "techStack": [
    "PHP",
    "Laravel",
    "Blade",
    "Tailwind CSS",
    "Alpine.js",
    "SQLite",
    "Eloquent ORM",
    "Vite",
    "PHPUnit",
    "Lucide Icons"
  ],
  "telemetryMatrix": {
    "projectType": "Full-Stack Web Application",
    "targetPlatform": "Responsive Web Browser",
    "primaryDomain": "Digital Library & Circulation",
    "architecturePipeline": "Laravel MVC, Eloquent ORM, SQLite",
    "testingAndAudit": "PHPUnit Passed (11 Tests)",
    "projectStatus": "Completed",
    "projectYear": "2025"
  },
  "projectInfo": {
    "projectType": "Full-Stack Digital Library Management System",
    "developmentStatus": "Completed",
    "developmentYear": "2025",
    "platform": "Web Browser (Desktop & Mobile)",
    "projectCategory": "Web Development"
  },
  "projectBackground": "Traditional community and institutional libraries often rely on disconnected spreadsheets for physical book tracking while lacking integrated digital reading portals. Aksaraya consolidates hybrid physical and e-book collections into a single web platform with real-time stock accuracy and member self-service.",
  "problemStatements": [
    {
      "title": "Fragmented Physical & Digital Catalogs",
      "description": "Libraries managing both physical bookshelves and downloadable PDF materials struggle to present unified discovery, search, and availability visibility to readers.",
      "issueCode": "ISSUE_01"
    },
    {
      "title": "Manual Stock & Overdue Fine Errors",
      "description": "Spreadsheet-based circulation tracking frequently causes stock desynchronization during concurrent checkouts and inconsistent manual late-fine calculations.",
      "issueCode": "ISSUE_02"
    },
    {
      "title": "Slow Front-Desk Circulation Lookups",
      "description": "Walk-in borrowing and return verification slow down when librarians must manually search member directories, ISBNs, and active reservation codes across separate forms.",
      "issueCode": "ISSUE_03"
    },
    {
      "title": "Lack of Member Reading Engagement Tools",
      "description": "Basic library OPAC portals rarely retain reader progress, personal reading shelves, annual literacy targets, or verifiable digital membership credentials.",
      "issueCode": "ISSUE_04"
    }
  ],
  "projectObjectives": [
    {
      "title": "Unify Hybrid Collection Discovery",
      "description": "Deliver multi-facet catalog filtering by keyword, category, e-book or physical format, stock availability, and sorting across all collection types.",
      "targetTag": "TARGET_01"
    },
    {
      "title": "Guarantee Transactional Stock Integrity",
      "description": "Enforce atomic database transactions during loan handovers and returns while automatically computing daily overdue fines from configurable system policies.",
      "targetTag": "TARGET_02"
    },
    {
      "title": "Accelerate Desk & E-Reader Workflows",
      "description": "Provide a JSON barcode/ISBN lookup endpoint for walk-in circulation alongside an in-browser PDF reader with watermark protection and progress auto-save.",
      "targetTag": "TARGET_03"
    },
    {
      "title": "Enforce Strict Role-Based Governance",
      "description": "Isolate member self-service portals, librarian circulation consoles, and administrator system configuration behind session authentication and role middleware.",
      "targetTag": "TARGET_04"
    }
  ],
  "coreFeatures": [
    {
      "title": "Multi-Facet Catalog & Book Detail Portal",
      "description": "Public catalog explorer supporting keyword search across title, author, ISBN, and publisher, format toggles, availability filters, view counters, and community star reviews.",
      "badge": "Discovery"
    },
    {
      "title": "Watermarked Browser PDF E-Reader",
      "description": "Dedicated reading workspace featuring Normal, Sepia, and Dark themes, dynamic user-identity watermarks, fullscreen toggle, and automatic page-progress persistence.",
      "badge": "Digital Reader"
    },
    {
      "title": "Atomic Circulation & Walk-In Barcode Desk",
      "description": "End-to-end loan lifecycle (pending, approved, borrowed, overdue, returned, rejected) with DB transaction stock locking and instant barcode/ISBN lookup for walk-in loans.",
      "badge": "Circulation"
    },
    {
      "title": "Automated Fine Engine & QRIS Simulation",
      "description": "Computes overdue penalties from configurable daily rates upon return and supports both staff cash settlement and simulated member QRIS fine payments with reference codes.",
      "badge": "Billing"
    },
    {
      "title": "Digital Member Card & Personal Shelves",
      "description": "Provides printable holographic barcode membership passes, annual reading challenge trackers, bookmarks, and categorized personal shelves (want to read, reading, completed).",
      "badge": "Member Portal"
    },
    {
      "title": "CSV Batch Sync & Printable Audit Reports",
      "description": "Enables UTF-8 BOM CSV catalog export, batch CSV book import, WhatsApp/Email circulation notification logging, and date-filtered printable circulation reports.",
      "badge": "Administration"
    }
  ],
  "interfaceShowcase": [
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image01.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image02.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image03.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image04.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image05.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image06.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image07.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image08.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image09.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image10.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image11.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image12.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image13.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image14.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image15.webp"
    },
    {
      "imageUrl": "/images/projects/aksaraya_digital_library_management/image16.webp"
    }
  ],
  "userFlow": {
    "summary": "Readers browse and filter hybrid collections in the public catalog, read watermarked PDFs online with saved page progress, or submit physical loan requests. Staff verify reservations, scan member and ISBN barcodes at the desk, process returns, and audit fine settlements in real time.",
    "steps": [
      {
        "step": "01",
        "title": "Catalog Discovery & Format Filtering",
        "description": "Visitors and members search books by title, author, or ISBN, filter by topic or e-book/physical format, and inspect real-time rack availability and reader reviews.",
        "actorOrNode": "Reader / CatalogController"
      },
      {
        "step": "02",
        "title": "Digital Reading or Physical Loan Request",
        "description": "Authenticated members either launch the browser PDF reader with auto-saved page tracking or submit a physical reservation checked against active borrow quotas.",
        "actorOrNode": "Member / LoanController"
      },
      {
        "step": "03",
        "title": "Staff Approval & Barcode Handover",
        "description": "Librarians approve online reservations—dispatching simulated WhatsApp/Email alerts—or scan member/ISBN barcodes at the desk to decrement stock atomically.",
        "actorOrNode": "Staff / LoanManagementController"
      },
      {
        "step": "04",
        "title": "Return Verification & Automated Fine Settlement",
        "description": "Staff process returns to restore available stock, calculate overdue fines from system policy rates, and settle payments via cash verification or simulated QRIS.",
        "actorOrNode": "Staff & Member / Billing"
      },
      {
        "step": "05",
        "title": "Reporting & Policy Governance",
        "description": "Administrators export catalog CSVs, generate printable date-range circulation and fine reports, and adjust loan duration, quota, and daily fine thresholds.",
        "actorOrNode": "Admin / Report & Setting Controllers"
      }
    ]
  },
  "systemArchitecture": {
    "summary": "Aksaraya follows a monolithic full-stack Laravel MVC architecture pairing Blade server-rendered views and Alpine.js reactivity with Eloquent ORM models and SQLite persistence. Role middleware enforces boundary isolation across public, member, staff, and administrator workflows.",
    "layers": [
      {
        "name": "Presentation & Client Interactivity Layer",
        "role": "Renders responsive public, member, e-reader, and admin interfaces with reactive client state and icon rendering.",
        "components": [
          "Blade Templates",
          "Tailwind CSS",
          "Alpine.js",
          "Lucide Icons",
          "Vite Asset Pipeline"
        ]
      },
      {
        "name": "Routing & Security Middleware Layer",
        "role": "Enforces guest, authenticated session, active-account, and multi-role access boundaries across web and JSON routes.",
        "components": [
          "Laravel Web Router",
          "Auth Middleware",
          "CheckRole Middleware",
          "CSRF Protection"
        ]
      },
      {
        "name": "Application Controller & Service Layer",
        "role": "Coordinates catalog queries, reading progress persistence, atomic circulation transitions, CSV streaming, and notification dispatch.",
        "components": [
          "CatalogController",
          "MemberDashboardController",
          "LoanManagementController",
          "BookController",
          "CirculationNotificationService"
        ]
      },
      {
        "name": "Persistence & Storage Layer",
        "role": "Manages relational library records via Eloquent ORM and stores uploaded book covers and e-book PDF assets.",
        "components": [
          "SQLite Database",
          "Eloquent Models",
          "Database Migrations",
          "Public Storage Disk"
        ]
      }
    ]
  },
  "databaseDataFlow": {
    "type": "Database Schema / ERD",
    "summary": "Relational SQLite schema centered on users, categories, books, and loans, extended by reader engagement entities (bookmarks, reviews, reading histories, custom shelves, reading challenges) and operational tables (circulation notifications and dynamic system settings).",
    "entitiesOrPipelines": [
      {
        "name": "users",
        "type": "Table",
        "fields": [
          "id",
          "name",
          "email",
          "password",
          "role",
          "member_number",
          "phone",
          "address",
          "is_active"
        ]
      },
      {
        "name": "categories",
        "type": "Table",
        "fields": [
          "id",
          "name",
          "slug",
          "icon",
          "color",
          "description"
        ]
      },
      {
        "name": "books",
        "type": "Table",
        "fields": [
          "id",
          "category_id",
          "title",
          "slug",
          "author",
          "publisher",
          "publication_year",
          "isbn",
          "shelf_location",
          "stock_total",
          "stock_available",
          "has_ebook",
          "ebook_file",
          "is_featured",
          "views_count"
        ]
      },
      {
        "name": "loans",
        "type": "Table",
        "fields": [
          "id",
          "loan_code",
          "user_id",
          "book_id",
          "loan_date",
          "due_date",
          "return_date",
          "status",
          "fine_amount",
          "fine_paid",
          "payment_method",
          "payment_reference",
          "fine_paid_at",
          "officer_id"
        ]
      },
      {
        "name": "reading_histories",
        "type": "Table",
        "fields": [
          "id",
          "user_id",
          "book_id",
          "last_page",
          "total_pages",
          "is_completed",
          "last_read_at"
        ]
      },
      {
        "name": "user_shelves",
        "type": "Table",
        "fields": [
          "id",
          "user_id",
          "book_id",
          "shelf_type",
          "notes"
        ]
      },
      {
        "name": "reading_challenges",
        "type": "Table",
        "fields": [
          "id",
          "user_id",
          "year",
          "target_books"
        ]
      },
      {
        "name": "reviews",
        "type": "Table",
        "fields": [
          "id",
          "user_id",
          "book_id",
          "rating",
          "comment"
        ]
      },
      {
        "name": "bookmarks",
        "type": "Table",
        "fields": [
          "id",
          "user_id",
          "book_id"
        ]
      },
      {
        "name": "circulation_notifications",
        "type": "Table",
        "fields": [
          "id",
          "loan_id",
          "user_id",
          "channel",
          "type",
          "recipient",
          "message",
          "status"
        ]
      },
      {
        "name": "settings",
        "type": "Table",
        "fields": [
          "id",
          "key",
          "value"
        ]
      }
    ]
  },
  "technicalImplementation": [
    {
      "category": "Concurrency & Integrity",
      "title": "Transactional Stock Synchronization on Circulation",
      "description": "Walk-in checkouts, reservation handovers, and book returns execute inside DB::transaction blocks in LoanManagementController, atomically updating loan statuses and incrementing or decrementing books.stock_available while blocking deletions of books with active loans.",
      "badge": "ACID Safe"
    },
    {
      "category": "Security & Access Control",
      "title": "Multi-Role Middleware & Active Account Enforcement",
      "description": "Custom CheckRole middleware evaluates user role membership (admin, petugas, anggota) alongside real-time is_active status checks, invalidating deactivated sessions and isolating /admin/pengaturan exclusively to administrators.",
      "badge": "RBAC"
    },
    {
      "category": "Digital Reader",
      "title": "Watermarked PDF Viewer & Async Progress Sync",
      "description": "The Blade e-reader overlays dynamic diagonal member-number and email watermarks over embedded PDF iframes, supports Normal/Sepia/Dark CSS filter modes, and syncs page checkpoints to /katalog/{id}/progress via CSRF-protected fetch requests.",
      "badge": "E-Reader"
    },
    {
      "category": "Circulation Automation",
      "title": "Barcode/ISBN Lookup & Dynamic Policy Fine Engine",
      "description": "A unified lookup endpoint resolves ISBNs, book titles, member numbers, and loan codes for walk-in forms, while return workflows dynamically compute overdue fines from database-persisted loan_period_days and daily_fine_rate settings.",
      "badge": "Automation"
    }
  ],
  "primaryTechSpecs": {
    "programmingLanguage": "PHP",
    "framework": "Laravel",
    "database": "SQLite"
  },
  "architectureQuality": {
    "badges": [
      "Role Based Access",
      "Atomic Loan Locks",
      "Integrated E-Reader",
      "Automated Fine Engine"
    ]
  }
}
```
