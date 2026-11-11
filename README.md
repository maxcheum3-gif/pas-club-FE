
```markdown
# pas-club-frontend

React + TypeScript frontend for the President's Award Scheme Club Management System.

## Set-up Instructions

* Clone the repository

```bash
git clone https://github.com/maxcheum3-gif/pas-club-FE.git
cd pas-club-frontend
```

* Install dependencies

```bash
npm ci
```

* Start the development server

```bash
npm run dev
```

The application will be available at `http://localhost:5173`.

## Available Scripts

| Command               | Description                                      |
|-----------------------|--------------------------------------------------|
| `npm ci`              | Clean install of dependencies                    |
| `npm run dev`         | Start development server                         |
| `npm run build`       | Build for production                             |
| `npm run preview`     | Preview the production build                     |
| `npm run lint`        | Run ESLint                                       |
| `npm run lint:fix`   | Automatically fix lint issues                    |
| `npm run format`      | Format code with Prettier                        |
| `npm run format:check`| Check code formatting                            |

## Project Structure

```
src/
├── components/     # Reusable UI components
├── pages/          # Page-level components
├── layouts/        # Layout components
├── hooks/          # Custom React hooks
├── services/       # API services
├── types/          # TypeScript types & interfaces
├── utils/          # Utility functions
├── assets/         # Static assets (images, icons)
└── styles/         # Global styles
```

## Checks Before Making a Pull Request

Before opening a pull request, please run the following:

```bash
npm run lint
```

```bash
npm run lint:fix
```

```bash
npm run format
```

```bash
npm run format:check
```

## Branching Guidelines

- Create a new branch from `main` for every change
- Use clear branch names:
  - `feature/...`
  - `fix/...`
  - `chore/...`
  - `docs/...`
- Open a Pull Request into `main`
- Request at least one review before merging
- Do not push directly to `main`

## Environment Variables

Create a `.env` file in the root of the project:

```env
VITE_API_BASE_URL=http://localhost:8000/api
```

Do not commit the `.env` file.
```

