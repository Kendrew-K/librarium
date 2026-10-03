# Requested visuals

Read this only after the learner explicitly asks for a diagram, illustration, chart, sketch, or other visual. Do not generate a visual merely because it could help.

Choose one focused idea and the simplest supported format that fits the request. For actual architecture, use a component or flow diagram. Inspect the files supporting each node and arrow; label arrows with what moves, such as a request, identifier, event, or result. Keep labels sparse, mark inferred connections, and say what was simplified or omitted. Explain the labels in a short caption. A database or service inferred from a dependency alone is not a verified connection.

For a conceptual metaphor, clearly call it a metaphor and explain its mapping and limits. Never present imagined machinery as actual architecture.

## Optional annotated illustration

The inspected `illustrations` skill specializes in English article-style hand-drawn conceptual images with sparse colored annotations and an Ian/Xiaohei character direction. It is suitable when that direction is explicitly requested or accepted and a conceptual illustration fits the idea. Read the installed skill and its relevant references before invoking it; its availability and tools differ between hosts.

Do not require this character or style for technical diagrams. A generic diagram request is not acceptance of Ian/Xiaohei style. Use an ordinary diagram for literal architecture. For a requested hand-drawn explanation without that style, use an available general image capability or supported diagram rather than forcing the specialized skill. Constrain generation to the learner's requested scope; do not expand one requested visual into an illustration series.

After generation, inspect the output for incorrect arrows, invented components, unreadable labels, and misleading metaphors. Correct errors or disclose them before using the image to teach. Image generation does not establish technical truth.

## Capability fallback

Do not assume a Claude plugin, widget, image generator, or authentication transfers to Codex. If the requested capability is unavailable, briefly state that limitation and use a supported Mermaid diagram, an ASCII diagram, or a labeled text flow as appropriate. If the learner requires a specific unavailable format, explain what can be provided and let them choose; keep answering the underlying teaching question.

Do not save generated assets into the learner's project without a request to save them. Use inline output or the host's permitted artifact area where available. Never claim an image was generated, inspected, or saved unless that action actually happened.
