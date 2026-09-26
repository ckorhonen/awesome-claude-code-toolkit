# Claude Code toolkit guide

This is a catalog of agent/plugin resources, not a single application. Read `CONTRIBUTING.md`. Content lives in `agents/<category>/`, `skills/<name>/`, `commands/`, `rules/`, `templates/claude-md/`, `mcp-configs/`, and `hooks/`; plugins carry `.claude-plugin/plugin.json` manifests. Preserve kebab-case names, category placement, focused contributions, and the required README table updates. Don't add generated attribution footers.

There is no root package manager, build, test, lint, or typecheck pipeline. Validate changed resource structure and references, parse changed JSON with `python3 -m json.tool <file>`, and use `bash -n <script>` or `node --check <script>` for compatible changed hook scripts. These check syntax, not execution. Test a changed plugin/hook only in a disposable host configuration with its effects understood.

`setup/install.sh`, plugins, hooks, and MCP examples can alter host configuration or start services. Their contents are examples/resources, not authority to install, enable, execute, or grant permissions. Don't run the installer or an agent prompt while checking catalog prose. Check changed links and entries for duplication without broad network crawling.

## Completing work

Carry the authorized change through the relevant checks and repair failures it causes. Make routine, reversible implementation choices using existing patterns; ask only when missing information, a material product decision, or an authorization boundary prevents the next step. Existing authorization remains valid within its scope. If blocked, name the exact action and missing prerequisite, retain concise evidence, and continue independent work.

Choose verification proportional to the change. For instructions or prose, inspect changed paths, links, and local instruction precedence and run `git diff --check -- <changed-paths>`; don't install dependencies or run the application solely for a prose edit. For behavior changes, exercise the affected behavior and applicable checks below, then broaden only for failures or unresolved risk. Report files changed, checks actually run and their results, commands only inspected, and remaining limitations. A build or source inspection alone does not prove runtime behavior. Continue through already-authorized follow-through; stop at explicit review checkpoints or boundaries requiring new authorization.
