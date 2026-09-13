# Agent development rules

## Architecture: no God Files

Never add unrelated responsibilities to an existing source module. Keep markup/UI, styling, application logic, data access, networking and configuration separated. Split modules when responsibilities or coupling become unrelated. Prefer explicit interfaces. Do not use a rigid line-count limit as the sole criterion. Generated/binary/vendor assets are exempt.

Before declaring work complete, verify that the change did not increase architectural coupling or create a new God File.
