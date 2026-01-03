Ah, I see exactly what’s happening 😅

Tum `claude mcp` type kar rahi ho **without a subcommand**, isliye Claude CLI **help message show kar raha hai**.

---

### 🔹 How to correctly **list MCP servers**

Use the **subcommand `list`**:

```bash
claude mcp list
```

Expected output (agar tumne Context7 MCP add kiya hai):

```
✔ context7
```

---

### 🔹 Quick reference: MCP commands

| Command                    | Description                     |
| -------------------------- | ------------------------------- |
| `claude mcp list`          | Show all configured MCP servers |
| `claude mcp add ...`       | Add a new MCP server            |
| `claude mcp remove <name>` | Remove an MCP server            |
| `claude mcp get <name>`    | Show details of a specific MCP  |
| `claude mcp serve`         | Start local MCP server          |
| `claude mcp add-json ...`  | Add MCP using JSON string       |

---

### 🔹 Test inside Claude CLI

Start Claude CLI:

```bash
claude
```

Then type:

```text
/mcp
```

Expected output:

```
1 MCP connected
- context7
```

✅ Ab Context7 MCP **live aur ready** hai.

---

Agar chaho, main tumhare liye **Gemini-style 4 MCP setup commands** ready bana doon, jo ek baar run kar ke **Claude CLI fully Gemini-like MCP setup** ho jaye.

Kya mai ye bana doon?
