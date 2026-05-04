# 🤝 Contributing Guidelines  
### _Authoritative Standards Compliance Required_

Thank you for contributing.  
All contributions must follow the **Authoritative Development Guarantee**.

---

## 🛡️ Mandatory Requirements

### 1. Comment Standards
All modules and routines must include:
- Module header block  
- Routine header block  
- Numbered section headers  
- Line‑item comments  
- Standards section  
- Notes & Function section  

### 2. Naming Conventions
All identifiers must follow:
- Versioned routines (`RoutineName_vXX`)  
- Deterministic, rebuild‑safe naming  
- IntelliSense‑friendly identifiers  
- No ambiguous or ad‑hoc names  

### 3. Logging & Debug Standards
All routines must include:
- Logging toggles  
- Debug toggles  
- Error handling  
- Diagnostics  
- Integration with global logging/debug architecture  

### 4. Rebuild‑Safe Behavior
All routines must:
- Avoid referencing controls before initialization  
- Avoid binding events prematurely  
- Follow rebuild‑safe lifecycle patterns  

### 5. Deterministic Ordering
All routines must:
- Execute in a predictable order  
- Follow the authoritative initialization sequence  

### 6. Removal of Obsolete Routines
When adding a new version:
- Remove old versions  
- Remove deprecated logic  
- Remove dead code  

### 7. Merging Missing Logic
When upgrading routines:
- Merge all missing logic  
- Preserve or improve behavior  
- Avoid regressions  

---

## 🧪 Pull Request Requirements

Every PR must include:

### ✔️ Standards Checklist
- [ ] Comment standards applied  
- [ ] Naming conventions applied  
- [ ] Logging/debug standards applied  
- [ ] Deterministic ordering ensured  
- [ ] Rebuild‑safe behavior ensured  
- [ ] No obsolete routines remain  
- [ ] Missing logic merged  
- [ ] Cross‑routine calls correct  
- [ ] Matches authoritative form  

### ✔️ Technical Checklist
- [ ] Code compiles  
- [ ] No unused variables  
- [ ] No dead code  
- [ ] No silent failures  
- [ ] No UI‑before‑state errors  
- [ ] No state‑before‑UI errors  

---

## 📝 Commit Message Format

