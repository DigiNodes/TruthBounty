# 👥 Contributing to TruthBounty Backend

Thank you for your interest in contributing to TruthBounty! Here's how you can help make our decentralized news verification platform better.

## 📸 Screenshot Requirement

**Every pull request must include relevant screenshots** demonstrating:

- The working feature/fix in action
- Any UI changes (before/after when applicable)
- Test results or terminal outputs for backend changes

## 🛠️ Development Setup

### Prerequisites

- Node.js v18+
- PostgreSQL 14+
- Redis 6+
- Git

### Installation

```bash
# Fork and clone the repository
git clone https://github.com/YOUR_USERNAME/TruthBounty_Backend.git
cd TruthBounty_Backend

# Install dependencies
npm install

# Set up environment
cp .env.example .env
# Edit .env with your credentials

# Start in development mode
- npm run start:dev
```

### Database Setup (via pgAdmin)  

1. Open **pgAdmin** and connect to your PostgreSQL server  
2. Right-click **Databases** → **Create** → **Database**  
3. Enter:  
   - **Name**: `truthbounty_dev`  
   - **Owner**: `postgres` (or your admin user)  
4. Update `.env` with your credentials:  

   ```ini
   DB_HOST=localhost
   DB_PORT=5432
   DB_USERNAME=postgres
   DB_PASSWORD=your_password
   DB_DATABASE=truthbounty_dev
   ```

## 🔧 Workflow

### Branch Naming

- `feat/`: New features
- `fix/`: Bug fixes
- `docs/`: Documentation changes
- `chore/`: Maintenance tasks

### Commit Message Format

We follow [Conventional Commits:](https://www.conventionalcommits.org/en/v1.0.0/)

**Examples**

```bash
feat(verification): add reputation scoring system
fix(auth): resolve JWT expiration issue
docs(readme): update installation instructions
```

## 🚀 Submitting Changes

1. Create a new branch for your feature/fix
2. Commit your changes following the commit guidelines
3. Push to your fork
4. Open a Pull Request to our `main` branch

## 📋 Code Review Process

1. Maintainers will review your PR within 3 business days
2. You may be asked to make changes
3. Once approved, your PR will be merged

## 🐛 Reporting Issues

When reporting bugs, please include:

- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots (if applicable)
- Environment details

## 💬 Communication

Join our [Telegram group](https://t.me/+c0_1mfaZyUw2Y2Zk) for real-time discussions.

## 🏷️ Issue Labels

| Label | Purpose |  
|------------|---------|  
| `good_first_issue` | Beginner-friendly tasks |  
| `bug` | Verified defects |  
| `enhancement` | Feature requests |  
| `help_wanted` | Needs community assistance |  

## 🙏 Thank You

We appreciate your contributions to making TruthBounty a more reliable platform for fighting misinformation!
