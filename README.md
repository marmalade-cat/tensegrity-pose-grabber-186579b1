TensegrityPoseGrabber

Interactive browser prototype to load local or pasted CSV/JSON pose files, normalize them into a simple CSV/JSON schema, and plot a chosen module's orientation over time. No network calls or external dependencies.

Usage:
- Open index.html in a modern browser.
- Drag a CSV/JSON file in, or paste content into the text area and click Parse.
- The tool will attempt to extract timestamp, module id, position, and orientation (quaternion or Euler), normalize to CSV/JSON, and show a short report. Click Plot to see Euler angles for a selected module.

Notes:
- This is a prototype. It does not automatically fetch article URLs. Use it to verify formats and to prepare normalized outputs for downstream analysis.
- Interpretations (field names, units, order) are guesses based on common layouts; inspect the report for assumptions.

License: Public prototype by Marmalade the museum cat.