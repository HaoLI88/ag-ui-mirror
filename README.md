# ag-ui-mirror

A frozen npm tarball mirror of the AG-UI protocol packages and the CopilotKit packages used by EVEARK. This repo is not a fork and does not track upstream.

| Package | Version | Upstream | License |
|---|---|---|---|
| @ag-ui/core, client, encoder, proto | 1.0.5 | https://github.com/ag-ui-protocol/ag-ui @ `ab01f98214529e64d7857b16617c094afc360ad0` (spec `PROTOCOL_VERSION` 1.0) | MIT |
| @copilotkit/runtime, react-core, react-ui, shared, runtime-client-gql | 1.90.0 | https://github.com/CopilotKit/CopilotKit @ `c1f317e839996dc845b930567210c8d976d6c5b1` | MIT |

The tarballs are attached to the GitHub release exactly as `npm pack` produced them. `INTEGRITY.txt` lists the npm registry integrity hash for each one.

Upgrades: publish a new release. Never rewrite an existing release.

## Releases

| Release | Contents |
|---|---|
| `v1.0.5-cpk1.90.0` | The 9 packages listed above (used by `apps/maos-api`: `@ag-ui/core` only) |
| `v1.0.5-cpk1.90.0-r2` | The same 9 packages, plus every other `@ag-ui/*`, `@copilotkit/*` and `@a2ui/*` package in the dependency tree of the US-53.1 CopilotKit demo client (27 in total). The first release is unchanged. |

Packages added in r2: `@a2ui/web_core@0.15.0`, `@ag-ui/a2ui-middleware@0.0.16`, `@ag-ui/a2ui-toolkit@0.0.5`, `@ag-ui/langgraph@0.0.46`, `@ag-ui/mcp-apps-middleware@0.1.1`, `@ag-ui/mcp-middleware@0.0.2`, `@copilotkit/a2ui-renderer@1.90.0`, `@copilotkit/channels-core@0.12.0`, `@copilotkit/channels-intelligence@0.12.0`, `@copilotkit/channels-slack@0.12.0`, `@copilotkit/channels-teams@0.12.0`, `@copilotkit/channels-ui@0.12.0`, `@copilotkit/core@1.90.0`, `@copilotkit/learning@1.90.0`, `@copilotkit/license-verifier@0.5.0`, `@copilotkit/mcp-apps-renderer@1.90.0`, `@copilotkit/web-components@1.90.0`, `@copilotkit/web-inspector@1.90.0`
