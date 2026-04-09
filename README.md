# 🌿 LeafSQLite - TwinBasic

**LeafSQLite** is a lightweight **SQLite3 database viewer and editor**, designed for developers who need a fast, portable tool with support for encrypted databases.

It supports the **7 encryption schemes from SQLite3MultipleCiphers**, allowing seamless interaction with both encrypted and non-encrypted databases.

---

## ✨ Features

* Open SQLite databases (encrypted and non-encrypted)
* Table data visualization and editing
* **BLOB** data editing and extraction
* Execute SQL queries
* Database backup support
* Database encryption management

---

## ⚙️ Engine & Architecture

LeafSQLite is built on top of **JSQLiteX**, a custom module that provides a flexible abstraction layer over SQLite.

### JSQLiteX compatibility:

* Static libraries: SQLite3 / SQLite3MultipleCiphers
* Dynamic libraries (DLL): SQLite3 / SQLite3MC

### Included in this project:

* Precompiled static SQLite3MC libraries in `/Miscellaneous/...` (x86 and x64)
* Embedded dynamic libraries in resources (`LIB`), extracted at runtime using `cRuntimeContext`

> ⚠️ **Note:** The x64 static build may be unstable and can crash.
> It is recommended to use the **dynamic DLLs** for better stability.

---

## 🧩 SQL Editor

LeafSQLite uses **Scintilla** for SQL editing with syntax highlighting.

All required libraries are embedded in resources (`LIB`) and extracted at runtime via `cRuntimeContext`.

---

## 📦 About JSQLiteX

**JSQLiteX** is being developed as a standalone component, with plans to be distributed as a **twinBASIC package**.

It is an evolution of the previous library **J3cnn.dll**, originally developed for Visual Basic, now improved with:

* 64-bit compatibility
* Modern SQLite integration
* Enhanced encryption support

---

## 🚧 Project Status

> ⚠️ **Work in Progress**

LeafSQLite is a personal project developed as a hobby and is currently under active development.

Some features may be incomplete, unstable, or subject to change as the project evolves.

---

## 🚀 Roadmap

* Improve x64 static build stability
* Enhance SQL editor features
* Add advanced data analysis tools
* Expand database utilities

---

## 💬 Feedback

Feedback, suggestions, and ideas are welcome.
This project is actively evolving.

---

## 📜 License

 MIT

