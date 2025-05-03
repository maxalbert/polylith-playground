# Session 2

## What I did

- Created new component 'trondur'
   - Added a couple of dummy functions: 'double', 'triple'

## Current status

- The polylith workspace contains one component (`trondur`) which can be imported from the development environment.

## Next steps

- Create polylith project which includes the 'trondur' component.
- Build a library using this project.


# Session 1

## What I did

- Initialised uv-managed Python project named "milnir"
- Installed dependencies:
   - polylith-cli
   - ipython (for better repl experience)
- Created a polylith workspace
   - name: fjalnar
   - theme: loose
- Configured hatch/uv settings in pyproject.toml to make them polylith-aware

## Current status

- The repo contains a uv-managed Python virtual environment
   - Activate this via `source .venv/bin/activate`
   - See note below about using direnv to automate this.

## Next steps

- Create a new polylith component named 'trondur'

## Notes

- Explore how to configure direnv to automatically activate the Python virtual environment.
