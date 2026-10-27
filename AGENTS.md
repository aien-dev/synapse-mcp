# AGENTS.md: synapse-mcp

Tools coord_where, coord_tree, coord_check, coord_claim, coord_renew, coord_release, coord_state, coord_who, coord_list, coord_conflicts, coord_verify, coord_pulse, coord_board, coord_lane.

- coord_lane {lane}: execs `synapse-claims --home H list --agent-prefix <lane>`; the result is the scoped recipient list. Message the agents of your lane (parent and children) instead of agent://all.
- Every argument is one argv record; values starting with `-`, empty values and zero bytes are refused (-32602). No shell.
