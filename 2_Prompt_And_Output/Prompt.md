# LLM Prompt and Sample Output

This folder contains:

1. `prompt.txt` — The file prompt_template.txt represents the structured prompt design used in AirWise. Instance-specific identifiers and user details have been anonymized for privacy.
2. `sample_output.json` — A representative LLM response in JSON format, showing recommended appliance settings for a sample indoor/outdoor environment and user profile.

The output JSON strictly follows the schema defined in the prompt:

- `"reason"`: Explanation of the recommendation
- `"AC_MODE"`: AC operating mode
- `"AC_TEMPERATURE"`: Desired AC temperature (null if not applicable)
- `"CEILING_FAN"`: Ceiling fan speed
- `"WINDOW"` / `"DOOR"`: State of windows/doors
- `"RECHECK_AT"`: Minutes until next environment re-evaluation
