# Hilistia SMP

This repository tracks all customizations made to the Hilistia SMP, with the exception of core-mod development which can be found at [hilistia/core-mod](https://github.com/Hilistia/core-mod).

## Issue Tracker

The public bug and suggestion tracker for the SMP project can be found on the [issues](https://github.com/Hilistia/smp/issues) page. Individual issues are tracked to milestones, which are tied to specific planned
releases of the SMP Modpack.

### Issue Labels
We use the following labels to help keep things organized.

**Status Labels**
| Label       | Description                                                                      |
|-------------|----------------------------------------------------------------------------------|
| pending     | This issue has been submitted for review, but no action is planned yet for it.   |
| accepted    | We have reviewed this issue and are either planning to or actively working on it.|
| build-ready | This change is ready but not yet live.                                           |
| wontfix     | We have reviewed this issue but will not be taking action on it.                 |

**Issue Types**
| Label       | Description                                                   |
|-------------|---------------------------------------------------------------|
| bug         | A problem that you encountered with the modpack or the server |
| mods        | A suggested change to the list of mods we are running         |
| enhancement | A suggested improvement to the modpack or server              |

## Component Locations
This repository is set up to track the entire SMP server folder, while ignoring the majority of content. Because of that, we've got a bit of an odd folder structure. Here's where to find specific parts of the SMP.

- **SMP Configuration** is in the `config/` directory
- **SMP Datapack** is in the `world/datapacks/hilistia` directory
- **Player Guide** is in the `patchouli_books/hilistia_guide` directory
- **Server Emotes** are in the `emotes` directory

## Branch Strategy

All changes must be made in feature branches and merged via PR with review and approval. Please keep branch names short, ideally hyphen seperated, and starting with the issue number your branch is related to if any.

For example, if issue \#5 is titled "fix fish spawn rates" the branch name would be `5-fish-spawn-rates`.

## Conventional Commits

Use of the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary) standard is highly recommended, though not required.
