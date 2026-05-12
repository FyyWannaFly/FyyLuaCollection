# Hook_Https.lua

> Roblox HTTP monitor/debugging utility for inspecting request and response payloads during script development.

<p align="left">
  <img alt="tool" src="https://img.shields.io/badge/tool-HTTP%20Monitor-0E9F6E">
  <img alt="ui" src="https://img.shields.io/badge/ui-Custom%20ScreenGui-6D4CFF">
  <img alt="scope" src="https://img.shields.io/badge/scope-Debugging-1177AA">
</p>

## Overview

`scripts/Hook_Https.lua` creates a compact `HTTP Monitor` GUI and formats captured requests/responses into readable raw HTTP-style text. It is intended for local debugging and inspection, not public runtime documentation of private endpoints.

## Feature Areas

| Area | Features |
|---|---|
| Request Formatting | method, path, host, headers, body, truncation handling |
| Response Formatting | headers, body, long-response protection |
| GUI | compact monitor window, header controls, clear/save/toggle buttons |
| File Output | save captured data when executor file APIs are available |
| Debugging | helps inspect what scripts are sending/receiving at runtime |

## Runtime Model

```text
create HTTP Monitor GUI
  -> hook/observe request functions
  -> format request/response data
  -> display and optionally save output
```

## Best Use Case

Use this locally while debugging scripts or auditing runtime network behavior. Do not publish captured request logs if they contain private domains, tokens, or keys.

## Privacy Notes

This tool can reveal sensitive runtime traffic. Always review saved logs before sharing them.

