# Fullstack Assignment

Build a simple split-pane web app:

- **Left**: renders a Markdown document  
- **Right**: a chat panel where the user can type natural edit requests  

When the user asks something like *“turn section 2 into a checklist”* or *“fix typos in the highlighted text”*:  
- AI proposes an edit (on the selected section or whole doc)  
- Show a before/after diff preview  
- Let the user **Accept** (apply) or **Discard**  
- Include **Undo/Redo** and local persistence  

Handle unclear or unsafe edits gracefully (show message, don’t break Markdown).

---

## Deliverables

- Working app (**React/Next + TS**)  
- Minimal proxy backend for calling the LLM (with token streaming)  
- **README** with setup, selection model, limitations  

---

## Inputs

- Input file provided in mathpix mardown format `manual.mmd` in the repo.

## What We’re Looking For

- Clean, accessible UI  
- Modular frontend code  
- Safe LLM integration  
