# opti-run-log

Every step Opti takes is committed here. Predictive-echo robot run log.

**Policy (enforced every run):**  
When Opti is invoked, each discrete step of the control loop  
`predict echo → decide → PUSH path → do → hear real echo → correct`  
is written as a file under `runs/<ISO-timestamp>/` and committed immediately.

No world map. d always from predicted echo. Path always pushed before move.

## Latest run
`runs/2026-09-26T13-03-18Z/`

## Repo
https://github.com/fitzyracing1/opti-run-log
