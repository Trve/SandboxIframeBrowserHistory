# SandboxIframeBrowserHistory
You can navigate the top frame from inside a sandboxed iframe without proper allow rule.

If you have a nested `<iframe>` with an active sandbox, you still can navigate the top frame via `window.history.back()`.
