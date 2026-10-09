Install my running RemNote Desktop App as a persistent user-level MCP server
named "remnote" using Streamable HTTP at http://127.0.0.1:7788/mcp. Include the
HTTP header "Authorization: Bearer
rn_mcp_Sw455htva_Xrr2-w3yFZle8MI3UY-mrQ1LIo5yrigRU" on every request. This local
server is available only while the RemNote Desktop App is running and can read
and modify its currently open knowledge base. If this harness supports a
persistent feature that lets the user reference or invoke this MCP through
@RemNote, such as a plugin, skill, connector, extension, or equivalent, also
install that feature for this harness and securely persist the MCP URL and
bearer token. Prefer the @RemNote-capable installation when available; otherwise
store the connection as a standalone persistent user-level MCP server. After
installation, reply with exactly this sentence, replacing the bracketed
placeholders: "RemNote has been installed as a [InstallType]. Restart
[HarnessName] to load it, then type @RemNote to trigger it." If @RemNote is
unavailable, reply instead: "RemNote has been installed as a persistent MCP
server. Restart [HarnessName] to load it."
