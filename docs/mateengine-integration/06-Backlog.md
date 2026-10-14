# Backlog

## MVP

- [ ] ME-001: зафиксировать JSON Schema protocol 0.1 и разделить MVP/P1 events.
- [ ] ME-002: сделать mock SoW WebSocket server.
- [ ] ME-003: выделить Qt-independent headless ChatService из `InterfaceSignals.handle_user_message`.
- [ ] ME-004: определить `SOW_DATA_ROOT` и проверить non-repository CWD.
- [ ] ME-005: сделать Python `IMateEngineBridge` с loopback-only bind и auth/session.
- [ ] ME-006: связать bridge с canonical chat service без Qt widget direct calls.
- [ ] ME-007: добавить serialized single-writer commit для history/memory и request/event IDs.
- [ ] ME-008: добавить event_id/request_id dedupe.
- [ ] ME-009: сделать C# transport abstraction и loopback WebSocket client.
- [ ] ME-010: заменить прямой `LLMCharacter.Chat` в staged ChatBot на SoW request path.
- [ ] ME-011: отключить Unity prompt persistence/live-save и независимые random response paths.
- [ ] ME-012: реализовать stream-to-bubble и safe error bubble.
- [ ] ME-013: реализовать cancel/reconnect/state snapshot.
- [ ] ME-014: null-safe lifecycle для `InputBubble` и caret.
- [ ] ME-015: запретить API key в Unity serialized fields/scene.
- [ ] ME-016: smoke test с mock provider и затем с реальным SoW provider без вывода секрета.
- [ ] ME-017: test chat-open, response, player remains alive.
- [ ] ME-018: test drag, transparency, workspace and edge-hide after chat.
- [ ] ME-019: зафиксировать provenance/hash active Assembly-CSharp и candidate.


## P1

- [ ] ME-101: emotion.changed → configurable animator mapping; сначала реализовать Unity consumer.
- [ ] ME-102: speech lifecycle → talking/lip-sync.
- [ ] ME-103: choose and implement audio ownership mode.
- [ ] ME-104: proactive SoW speech → one and only one bubble.
- [ ] ME-105: protocol approval.request/decision с TTL и default-deny.
- [ ] ME-106: Linux capability adapters: idle, active-window, clipboard, screenshot, media, STT.
- [ ] ME-107: MCP allowlist + unified policy gate + audit.
- [ ] ME-108: persistent reconnect diagnostics and evidence export.

## Explicitly later

- [ ] ME-201: expose SoW tools inside MateEngine UI.
- [ ] ME-202: sync full hormone state.
- [ ] ME-203: multimodal screen image path.
- [ ] ME-204: multi-character/multi-client sessions.
