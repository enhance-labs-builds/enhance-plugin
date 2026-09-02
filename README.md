# Enhance for agents

Enhance gives Claude Code, Codex, Cursor and agents run through Conductor a shared visual canvas for product design, feedback and interactive prototypes.

This repository is the **edge** channel. Its catalogue name is `enhance-edge` and its exact plugin version is `1.0.0-edge.a90c55133fc7`.

Install **Enhance** from your agent's plugin marketplace for your user account. The plugin starts its pinned MCP runtime and opens browser sign-in; it does not need a token, project file, separate CLI install, or terminal setup. If a marketplace listing is not yet available, copy the setup prompt from [Enhance](https://app.enhancelabs.ai/docs) and let the host configure its supported user-level MCP connection.

For a direct catalogue install, Claude Code uses `claude plugin install enhance@enhance-edge --scope user`; Codex uses `codex plugin add enhance@enhance-edge`. Use the host's plugin update action (Claude `plugin update`, Codex marketplace upgrade, or Cursor Customize) to refresh the immutable cached version. Uninstall through that same native plugin surface. If cached bytes are missing or corrupt, uninstall and reinstall the same version; browser credentials are owned by the MCP runtime and remain separate.

After connecting, try one of these:

- Design a product screen on my Enhance canvas.
- Publish and visually verify this prototype.
- Apply the actionable feedback on my canvas.
- Reconcile this canvas design into my prototype source.

Conductor uses the plugin and MCP support of the Claude Code or Codex agent selected for the workspace. Provider setup, recovery and update instructions are maintained at [https://app.enhancelabs.ai/docs](https://app.enhancelabs.ai/docs).

## Trust and support

The generated plugin contains only provider manifests, four workflow skills, launch configuration and brand assets. It stores no credential. Enhance authentication happens in the browser and the local runtime owns its user credential.

- [Documentation](https://app.enhancelabs.ai/docs)
- [Privacy](https://app.enhancelabs.ai/privacy-policy)
- [Terms](https://app.enhancelabs.ai/docs/terms)
- [Support](https://app.enhancelabs.ai/docs/support)
