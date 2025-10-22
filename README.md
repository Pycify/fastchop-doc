# 📘 FastChop API Documentation

Welcome to the **FastChop API Documentation** — this directory contains automatically generated reference files for all **API routes**, **DTOs**, **interfaces**, and **enums** used across the backend.

---

## 🚀 Quick Links

| Section                       | Description                                                                                                    |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------- |
| [**API Routes**](./routes.md) | Complete list of all backend routes (`GET`, `POST`, `PATCH`, `DELETE`) with their corresponding response DTOs. |
| [**Type Index**](./index.md)  | Entry point to all **DTOs**, **interfaces**, and **enums** used across the application.                        |

---

## 🧩 Structure

```

docs/
┣ 📄 README.md → You are here
┣ 📄 routes.md → API route documentation
┣ 📄 index.md → Global DTO & Interface index
┣ 📁 dtos/ → Generated documentation for Data Transfer Objects
┣ 📁 interfaces/ → Documentation for Interfaces
┗ 📁 enums/ → Enum references

```

---

## 🛠️ Regeneration

These files are auto-generated via scripts in the `/scripts` directory:

```bash
# Generate DTOs, Interfaces, Enums, and Index
pnpm run generate:dto-docs

# Generate Route-to-DTO mapping
pnpm run generate:route-docs
```

> ⚙️ Each script parses TypeScript definitions and AdonisJS route/controller files to keep documentation always in sync with your code.

---

## 🧠 Notes

- Only DTOs, Interfaces, and Enums exported from `app/types/` are documented.
- The routes documentation automatically links `data` fields returned by `sendSuccess()` to their respective DTO files.
- Enums link directly to their respective value lists for clarity.

---

**Maintained by:** [Pycify](https://github.com/Pycify)
_Last updated automatically — do not edit manually._
