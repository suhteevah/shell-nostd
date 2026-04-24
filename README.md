# shell-nostd

`no_std` AI-native shell with 45+ builtins, pipes, and scripting in Rust.

## Features

- **45+ builtins**: ls, cd, cat, cp, mv, rm, mkdir, rmdir, echo, grep, find, head, tail, wc, sort, uniq, touch, chmod, df, du, env, export, unset, alias, history, clear, help, and more
- **Pipes**: `cmd1 | cmd2 | cmd3` pipeline support
- **Environment variables**: `$VAR` expansion, `export`, `unset`
- **Scripting**: if/else/while/for loops, functions, variables, exit codes
- **Parser**: Quoting, escaping, semicolons, redirections
- **AI integration**: Built-in `ask` and `agent` commands for AI-assisted workflows
- **Customizable prompt**: Working directory display, user-configurable

## Architecture

```text
Shell (shell.rs)             -- REPL loop, command dispatch
    |
Parser (parser.rs)           -- tokenization, quoting, pipes, redirects
    |
Builtins (builtin.rs)        -- 45+ built-in commands
    |
Pipes (pipe.rs)              -- pipeline execution
    |
Environment (env.rs)         -- variable store, expansion
    |
Scripting (script.rs)        -- if/while/for/function execution
    |
AI integration (ai.rs)       -- ask/agent hooks
    |
Prompt (prompt.rs)           -- PS1-like prompt rendering
```

## License

Licensed under either of Apache License 2.0 or MIT License at your option.

---

---

---

---

---

---

---

---

---

---

---

---

---

## Support This Project

If you find this project useful, consider buying me a coffee! Your support helps me keep building and sharing open-source tools.

[![Donate via PayPal](https://img.shields.io/badge/Donate-PayPal-blue.svg?logo=paypal)](https://www.paypal.me/baal_hosting)

**PayPal:** [baal_hosting@live.com](https://paypal.me/baal_hosting)

Every donation, no matter how small, is greatly appreciated and motivates continued development. Thank you!
