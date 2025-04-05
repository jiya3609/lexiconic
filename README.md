# lexiconic
# Mini Compiler - Syntax Checker & Process Simulator

This is a modular compiler project designed to analyze input code, detect syntax errors, and suggest corrections.

---

## 🔧 Modules

1. **Lexer (Tokenization)**  
   Converts source code into a sequence of tokens using Python and PLY.

2. **Parser (Coming Soon)**  
   Checks token structure against a defined grammar to validate syntax.

3. **Error Handling & Correction (Planned)**  
   Uses rule-based suggestions to correct common mistakes (e.g., missing `;`).

4. **File I/O & Output Generator (Planned)**  
   Accepts input files and generates error-annotated and corrected code.

---

## 🚀 Running the Lexer

```bash
cd lexer
python test_lexer.py
