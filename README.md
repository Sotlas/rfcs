# 📜 Sotlas RFCs (Requests for Comments)

This repository contains RFCs (Requests for Comments) for major changes, language syntax evolutions, standard library additions, and tooling architecture for the **Sotlas** programming language.

## 🎯 What is an RFC?

The "RFC" (request for comments) process provides a consistent and controlled path for new features to enter the Sotlas language and standard library.

Many changes, including bug fixes and documentation improvements, can be implemented and reviewed via the normal GitHub pull request workflow in the primary repository ([Sotlas/sotlas](https://github.com/Sotlas/sotlas)).

Some changes, however, are "substantial", and we require that these undergo a design process and produce a consensus among the core team and community before being implemented.

### When to use an RFC:
- A new language feature or syntax change
- Significant modifications to the type system or safety semantics
- Large additions or breaking changes to the standard library (`stdlib/core`, `stdlib/foundation`, `stdlib/system`, `stdlib/graphics`)
- Major changes to the compiler architecture, SIR representation, or CLI commands

---

## 🔄 RFC Life Cycle

1. **Draft**: Fork this repository, copy `0000-template.md` to `text/0000-my-feature.md`, and fill in the design.
2. **Open PR**: Submit a pull request to `Sotlas/rfcs` with the title `RFC: [Feature Name]`.
3. **Discussion & Review**: The community and core maintainers review, ask questions, and propose refinements.
4. **Decision**:
   - **Accepted**: Merged into `text/` with an assigned number (e.g., `text/0001-my-feature.md`).
   - **Postponed**: Kept for future consideration.
   - **Rejected**: Closed with rationale documented.
5. **Implementation**: Once accepted, implementation tracking issues are opened in [Sotlas/sotlas](https://github.com/Sotlas/sotlas).

---

## 📝 Submitting an RFC

1. Copy `0000-template.md` to `text/0000-your-feature-name.md`.
2. Flesh out the template with detailed technical explanations, examples, and trade-offs.
3. Submit a Pull Request.
