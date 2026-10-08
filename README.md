# blog-site

A blogging platform where **writers** publish posts and **readers** discover, follow and subscribe to them.

> **Status: planning / design.** The repository holds the functional design only; no application code exists yet. The design lives in [`Untitled Diagram.drawio`](./Untitled%20Diagram.drawio).

## Viewing the design

Open `Untitled Diagram.drawio` in one of these:

- [diagrams.net / draw.io](https://app.diagrams.net/): *File → Open from → Device* (or *GitHub*)
- The VS Code extension [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)
- The draw.io desktop app

The file has four pages:

| Page | Contents |
| --- | --- |
| **Functional-chart** | Overall user flow and feature map |
| **Landing page** | Wireframe of the home page |
| **POST** | Wireframe of a single blog post page |
| **Page-4** | Navigation from the landing page to login and registration |

## Planned features

### User flow

```
Landing Page
├── Register ──┬── Writer
│              └── Reader
└── Login ─────┬── Writer
               └── Reader
```

### Writers

- **Profile**: personal information, a list of their blogs, reviews and followers
- **Create post**: cover image, post title and body

### Readers

- **View posts**
- **Subscribe** to writers
- **Interests** to tailor content, starting with *Science*, *Technology* and *News*

## Page layouts

### Landing page

- Header with brand/logo, navigation links, and **Log in** / **Register** buttons
- Hero section with a hero image
- **Trending Blogs**: cards showing a cover image, the blog title and a preview

### Post page

- Header with logo/brand and navigation links
- Blog title, cover image and the main post body
- Sidebar with the writer's profile, links, and space for extras or advertisements

### Authentication

- Login page
- Registration page (choose writer or reader)

## Roadmap

- [x] Functional chart and wireframes
- [ ] Choose a tech stack (frontend, backend, database)
- [ ] Registration and login
- [ ] Writer profiles and post creation
- [ ] Landing page with trending blogs
- [ ] Post page
- [ ] Reader subscriptions and interests

## Contributing

Design changes: edit `Untitled Diagram.drawio` in draw.io and commit the updated file. Once code is added, this README should be extended with setup, run and test instructions.
